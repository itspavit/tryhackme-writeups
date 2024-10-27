# TryHackMe - Crack the Hash

This repository contains solutions for the **Crack the Hash** room on TryHackMe, which involves identifying and cracking various hashes using tools like **Hashcat**, **CrackStation**, and **Hashes.com**.

- **Room URL**: [TryHackMe - Crack the Hash](https://tryhackme.com/r/room/crackthehash)

---

## Task 1: Level 1

### Resources Used
- [CrackStation](https://crackstation.net/)
- [Hashcat](https://hashcat.net)
- [Hashes.com](https://hashes.com/en/decrypt/hash)

> **Note:** To find the correct Hashcat mode, refer to [Hashcat’s algorithm list](https://hashcat.net) to determine the appropriate mode for each hash type (e.g., Hashcat mode `110` is for SHA-1 with a salt).

### Hash Solutions

1. **Hash**: `48bb6e862e54f2a795ffc4e541caed4d`
   - **Solution**: Using CrackStation, we find the answer: **"easy"**

2. **Hash**: `CBFDAC6008F9CAB4083784CBD1874F76618D2A97`
   - **Solution**: Using CrackStation, we find the answer: **"password123"**

3. **Hash**: `1C8BFE8F801D79745C4631D09FFF36C82AA37FC4CCE4FC946683D7B336B63032`
   - **Solution**: Using CrackStation, we find the answer: **"letmein"**

4. **Hash**: `$2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom`
   - **Solution**: Use **Hashcat** (or **John the Ripper**) with the following steps:
     - **Step 1**: Install `hashcat` and `hashid`:
       ```bash
       sudo apt update && sudo apt upgrade -y
       sudo apt install hashcat hashid -y
       ```
     - **Step 2**: Install `wordlists` and extract the `rockyou.txt` wordlist:
       ```bash
       sudo apt install wordlists -y
       ```
     - **Step 3**: Identify the hash algorithm:
       ```bash
       hashid -m "$2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom"
       ```
     - **Step 4**: Crack the hash using Hashcat:
       ```bash
       hashcat -m 3200 "$2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom" rockyou.txt
       ```
     - **Answer**: **"bleh"**

5. **Hash**: `279412f945939ba78ce0758d3fd83daa`
   - **Solution**: Using CrackStation, we find the answer: **"Eternity22"**

---

## Task 2: Level 2

This level increases the difficulty. All answers can be found within the **rockyou.txt** password list. 

### Hash Solutions

1. **Hash**: `F09EDCB1FCEFC6DFB23DC3505A882655FF77375ED8AA2D1C13F640FCCC2D0C85`
   - **Solution**: Using CrackStation, we find the answer: **"paule"**

2. **Hash**: `1DFECA0C002AE40B8619ECF94819CC1B`
   - **Solution**: Using CrackStation, we find the answer: **"n63umy8lkf4i"**

3. **Hash**: `$6$aReallyHardSalt$6WKUTqzq.UQQmrm0p/T7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf.hsGpS41BqMhSrHVXgMpdjS6xeKZAs02.`
   - **Salt**: `aReallyHardSalt`
   - **Solution**: Using Hashcat:
     ```bash
     hashcat -m 1800 "$6$aReallyHardSalt$6WKUTqzq.UQQmrm0p/T7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf.hsGpS41BqMhSrHVXgMpdjS6xeKZAs02." rockyou.txt -O
     ```
   - **Answer**: **"waka99"**

4. **Hash**: `e5d8870e5bdd26602cab8dbe07a942c8669e56d6`
   - **Salt**: `tryhackme`
   - **Solution**: Using [Hashes.com](https://hashes.com/en/decrypt/hash), we find the answer: **"481616481616"**

---

This README covers the steps and tools used to crack each hash at different levels of difficulty in the TryHackMe room **Crack the Hash**.
