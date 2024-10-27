URL - https://tryhackme.com/r/room/crackthehash


Task 1
Level 1


Resouces used - https://crackstation.net/
https://hashcat.net
https://hashes.com/en/decrypt/hash


Note: try to find hashcat modes (algorithms that should be used) by visting hashcat.net and seeing which hash is what. For example hashcat mode 110 is for SHA-1 with a salt


Can you complete the level 1 tasks by cracking the hashes?


Answer the questions below
1) 48bb6e862e54f2a795ffc4e541caed4d
solution) used crackstation and input the above hash there it will convert it to our answer "easy"


2) CBFDAC6008F9CAB4083784CBD1874F76618D2A97 
solution) used crackstation and input the above hash there it will convert it to our answer "password123"


3) 1C8BFE8F801D79745C4631D09FFF36C82AA37FC4CCE4FC946683D7B336B63032
solution)  used crackstation and input the above hash there it will convert it to our answer "letmein"


4) $2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom
solution) For this I will be using a tool called hashcat, you can also use something called John The Ripper. 


Step 1 - Open ur linux terminal and install hashcat and hasid using the following commands
sudo apt update && sudo apt upgrade -y
sudo apt install hashcat -y
sudo apt install hashid -y


Step 2 - sudo apt install wordlists -y and extract it to a location and unzip the wordlists folder


Step 3 - navigate inside wordlists folder and run hashid to find which hashing algorithim is used for the hash
hashid -m "\$2y\$12\$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom"
then run the following 
hashcat -m 3200 "\$2y\$12\$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom" rockyou.txt
It will show you a cracked answer that is "bleh"


5) 279412f945939ba78ce0758d3fd83daa
solution)  used crackstation and input the above hash there it will convert it to our answer "Eternity22"






Task 2
Level 2
This task increases the difficulty. All of the answers will be in the classic rock you password list.


You might have to start using hashcat here and not online tools. It might also be handy to look at some example hashes on hashcats page.


1) F09EDCB1FCEFC6DFB23DC3505A882655FF77375ED8AA2D1C13F640FCCC2D0C85
solution) use crackstation to find the answer "paule"


2) 1DFECA0C002AE40B8619ECF94819CC1B
solution) use crackstation to find the answer "n63umy8lkf4i"


3) $6$aReallyHardSalt$6WKUTqzq.UQQmrm0p/T7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf.hsGpS41BqMhSrHVXgMpdjS6xeKZAs02.


Salt: aReallyHardSalt


solution) use hashcat -m 1800 "\$6\$aReallyHardSalt\$6WKUTqzq.UQQmrm0p/T7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf.hsGpS41BqMhSrHVXgMpdjS6xeKZAs02." rockyou.txt -O
and you will get ur answer "waka99"


4) e5d8870e5bdd26602cab8dbe07a942c8669e56d6


salt: tryhackme


solution) use https://hashes.com/en/decrypt/hash and you will get the answer "481616481616"
