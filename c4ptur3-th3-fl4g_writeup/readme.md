# TryHackMe - Capture The Flag

This repository contains solutions for the **Capture The Flag** room on TryHackMe, covering techniques such as translation, encoding, steganography, and more.

- **Room URL**: [TryHackMe - Capture The Flag](https://tryhackme.com/r/room/c4ptur3th3fl4g)

---

## Task 1: Translation & Shifting

Translate, shift, and decode the following strings using various online tools. Answers are case-sensitive.

### Resources Used
- [CyberChef](https://gchq.github.io/CyberChef/)
- [Spectrogram Creator](https://convert.ing-now.com/audio-spectrogram-creator/)
- [Steganography Tool](https://futureboy.us/stegano/)

> **Note**: Ignore the initial whitespace after the question number and any surrounding quotation marks `" "` in the solutions.

### Challenges and Solutions

1. **`c4n y0u c4p7u23 7h3 f149?`**
   - **Solution**: Observing the text reveals it says: **"can you capture the flag"**

2. **`01101100 01100101 01110100 01110011 00100000 01110100 01110010 01111001 00100000 01110011 01101111 01101101 01100101 00100000 01100010 01101001 01101110 01100001 01110010 01111001 00100000 01101111 01110101 01110100 00100001`**
   - **Solution**: Convert binary to text using CyberChef to get: **"lets try some binary out!"**

3. **`MJQXGZJTGIQGS4ZAON2XAZLSEBRW63LNN5XCA2LOEBBVIRRHOM======`**
   - **Solution**: Convert from Base32 using CyberChef to get: **"base32 is super common in CTF's"**

4. **`RWFjaCBCYXNlNjQgZGlnaXQgcmVwcmVzZW50cyBleGFjdGx5IDYgYml0cyBvZiBkYXRhLg==`**
   - **Solution**: Convert from Base64 using CyberChef to get: **"Each Base64 digit represents exactly 6 bits of data."**

5. **`68 65 78 61 64 65 63 69 6d 61 6c 20 6f 72 20 62 61 73 65 31 36 3f`**
   - **Solution**: Convert hex to text using CyberChef to get: **"hexadecimal or base16?"**

6. **`Ebgngr zr 13 cynprf!`**
   - **Solution**: Use ROT13 in CyberChef to get: **"Rotate me 13 places!"**

7. **`*@F DA:? >6 C:89E C@F?5 323J C:89E C@F?5 Wcf E:>6DX`**
   - **Solution**: Use ROT47 in CyberChef to get: **"You spin me right round baby right round (47 times)"**

8. **`- . .-.. . -.-. --- -- -- ..- -. .. -.-. .- - .. --- -. . -. -.-. --- -.. .. -. --.`**
   - **Solution**: Convert from Morse code using CyberChef to get: **"telecommunication encoding"**

9. **`85 110 112 97 99 107 32 116 104 105 115 32 66 67 68`**
   - **Solution**: Convert from decimal to text using CyberChef to get: **"Unpack this BCD"**

10) **`LS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0`**

- **Solution**: use cyber chef and convert from base 64 you will get 

**`----- .---- .---- ----- ----- .---- .---- -----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- ----- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- -----

\----- .---- .---- ----- .---- ----- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- .---- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- -----

\----- .---- .---- ----- ----- ----- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- .---- ----- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- .---- ----- ----- -----

\----- .---- .---- ----- ----- .---- .---- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- .---- .---- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- ----- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- -----

\----- .---- .---- ----- ----- ----- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- ----- .---- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- .---- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- .---- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- -----

\----- .---- .---- ----- ----- ----- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- .---- ----- ----- -----

\----- .---- .---- ----- ----- .---- .---- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- -----

\----- .---- .---- ----- ----- ----- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- .---- ----- ----- -----

\----- .---- .---- ----- ----- .---- .---- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- .---- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- -----

\----- .---- .---- ----- ----- ----- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- .---- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- .---- ----- ----- -----

\----- .---- .---- ----- .---- ----- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- .---- .---- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- .---- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- ----- .---- .---- .---- .---- .----

\----- .---- .---- ----- ----- ----- ----- -----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- .----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- .----

\----- .---- .---- ----- ----- .---- ----- .----

\----- ----- .---- ----- ----- ----- ----- -----

\----- .---- .---- ----- ----- ----- .---- .----

\----- .---- .---- ----- ----- .---- ----- .----`**

then convert the above from morse code you will get **`01100110 01100101 00100000 01100000 01011111 01100000 00100000 01100000 01100000 01100101 00100000 01100010 01101000 00100000 01100000 01100000 01100100 00100000 01100010 01100001 00100000 01100000 01011111 01101000 00100000 01101000 01100110 00100000 01100000 01011111 01100110 00100000 01100000 01011111 01100000 00100000 01100010 01100001 00100000 01100000 01100000 01100101 00100000 01100000 01011111 01100011 00100000 01100000 01011111 01100100 00100000 01100000 01100000 01100100 00100000 01100010 01100001 00100000 01101000 01100110 00100000 01100010 01100001 00100000 01101000 01100111 00100000 01100000 01011111 01100100 00100000 01100000 01100000 01100101 00100000 01100010 01100001 00100000 01100000 01100000 01100101 00100000 01100000 01100000 01100011 00100000 01100000 01011111 01100100 00100000 01101000 01101000 00100000 01100000 01011111 01100110 00100000 01100000 01011111 01100100 00100000 01100000 01011111 01100000 00100000 01100000 01100000 01100011 00100000 01100011 01100101 00100000 01100011 01100101 00100000 01100011 01100101`**

now convert the above binary string you will get **`fe \`\_\` \`\`e bh \`\`d ba \`\_h hf \`\_f \`\_\` ba \`\`e \`\_c \`\_d \`\`d ba hf ba hg \`\_d \`\`e ba \`\`e \`\`c \`\_d hh \`\_f \`\_d \`\_\` \`\`c ce ce ce`**

then again use ROT47 on the above string you will get another decimal string which you have to convert **`76 101 116 39 115 32 109 97 107 101 32 116 104 105 115 32 97 32 98 105 116 32 116 114 105 99 107 105 101 114 46 46 46`**

finally you will get ur answer **`Let's make this a bit trickier...`**

## Task 2: Spectrograms

A **spectrogram** is a visual representation of the spectrum of frequencies in a signal over time. When applied to audio, spectrograms are sometimes called sonographs, voiceprints, or voicegrams. In 3D plots, they are referred to as waterfalls.

1. **Hidden Message in File**  
   - **Challenge**: Download the provided file from TryHackMe and locate the hidden message.
   - **Solution**: Use a spectrogram creator (e.g., [Spectrogram Creator](https://convert.ing-now.com/audio-spectrogram-creator/)) to analyze the file. This reveals the message: **"Super Secret Message"**

---

## Task 3: Steganography

**Steganography** is the practice of hiding information within another file, such as an image or video.

1. **Hidden Message in Image**  
   - **Challenge**: Use the provided image file to locate the hidden message.
   - **Solution**: Use a steganography decoder like [FutureBoy Steganography Decoder](https://futureboy.us/stegano/) and upload the image. This reveals the message: **"SpaghettiSteg"**

---

## Task 4: Security Through Obscurity

**Security through obscurity** relies on concealing the design or implementation details as the primary method of securing a system.

1. **Identifying First File in Archive**  
   - **Challenge**: Download the file and examine its contents to identify the first filename and extension.
   - **Solution**: Open the file in a text editor (such as Neovim or Notepad) that displays ASCII characters. At the bottom of the text, you’ll find the answer: **"hackerchat.png"**

2. **Extracting Hidden Text**  
   - **Challenge**: Further inspect the archive for hidden text.
   - **Solution**: Continue examining the file in a text editor to locate the hidden message at the bottom: **"AHH_YOU_FOUND_ME!"**

---

This README summarizes the solutions and methods used to solve the **Capture The Flag** challenges on TryHackMe.
