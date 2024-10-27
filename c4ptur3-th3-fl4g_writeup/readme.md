URL - https://tryhackme.com/r/room/c4ptur3th3fl4g

Task 1

Translation & Shifting

Translate, shift and decode the following;

Answers are all case sensitive.

Resources Used - 

https://gchq.github.io/CyberChef/

https://convert.ing-now.com/audio-spectrogram-creator/

https://futureboy.us/stegano/

Note: Please Ignore the first whitepace after question number those are not part of the question. Also ignore the quotation marks " " not part of the solutions.

1) c4n y0u c4p7u23 7h3 f149?

Solution) This is self explanatory if you see carefully some words have been replaced and we can see it says "can you capture the flag"

2) 01101100 01100101 01110100 01110011 00100000 01110100 01110010 01111001 00100000 01110011 01101111 01101101 01100101 00100000 01100010 01101001 01101110 01100001 01110010 01111001 00100000 01101111 01110101 01110100 00100001

solution) Go to website like cyberchef and convert from binary to text

you will get the solution "lets try some binary out!"

3) MJQXGZJTGIQGS4ZAON2XAZLSEBRW63LNN5XCA2LOEBBVIRRHOM======

solution) Again use cybershef and convert the string above from base32 you will get "base32 is super common in CTF's"

4) RWFjaCBCYXNlNjQgZGlnaXQgcmVwcmVzZW50cyBleGFjdGx5IDYgYml0cyBvZiBkYXRhLg==

solution) Follow the same process above but this time convert from base64 you will get "Each Base64 digit represents exactly 6 bits of data."

5) 68 65 78 61 64 65 63 69 6d 61 6c 20 6f 72 20 62 61 73 65 31 36 3f

solution) Again use cyberchef website and convert from hex you will get 

"hexadecimal or base16"

6) Ebgngr zr 13 cynprf!

solution) Use cyberchef and use ROT13 which essentially rotates characters by 13 places hence our answer "Rotate me 13 places!"

7)\*@F DA:? >6 C:89E C@F?5 323J C:89E C@F?5 Wcf E:>6DX

solution) Use cyberchef and use ROT47 this time which means it will rotate characters 47 times. our answer is "You spin me right round baby right round (47 times)"

8) - . .-.. . -.-. --- -- -- ..- -. .. -.-. .- - .. --- -.

. -. -.-. --- -.. .. -. --.

solution) Use cyberchef and convert from morse code your answer is "telecommunication encoding"

9) 85 110 112 97 99 107 32 116 104 105 115 32 66 67 68

solution) Use cyberchef and convert from decimal your answer is "Unpack this BCD"

10) LS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0KLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLS0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi0tLS0KLS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLS0tLS0gLi0tLS0

solution) use cyber chef and convert from base 64 you will get "----- .---- .---- ----- ----- .---- .---- -----

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

\----- .---- .---- ----- ----- .---- ----- .----"

then convert the above from morse code you will get "01100110 01100101 00100000 01100000 01011111 01100000 00100000 01100000 01100000 01100101 00100000 01100010 01101000 00100000 01100000 01100000 01100100 00100000 01100010 01100001 00100000 01100000 01011111 01101000 00100000 01101000 01100110 00100000 01100000 01011111 01100110 00100000 01100000 01011111 01100000 00100000 01100010 01100001 00100000 01100000 01100000 01100101 00100000 01100000 01011111 01100011 00100000 01100000 01011111 01100100 00100000 01100000 01100000 01100100 00100000 01100010 01100001 00100000 01101000 01100110 00100000 01100010 01100001 00100000 01101000 01100111 00100000 01100000 01011111 01100100 00100000 01100000 01100000 01100101 00100000 01100010 01100001 00100000 01100000 01100000 01100101 00100000 01100000 01100000 01100011 00100000 01100000 01011111 01100100 00100000 01101000 01101000 00100000 01100000 01011111 01100110 00100000 01100000 01011111 01100100 00100000 01100000 01011111 01100000 00100000 01100000 01100000 01100011 00100000 01100011 01100101 00100000 01100011 01100101 00100000 01100011 01100101"

now convert the above binary string you will get "fe \`\_\` \`\`e bh \`\`d ba \`\_h hf \`\_f \`\_\` ba \`\`e \`\_c \`\_d \`\`d ba hf ba hg \`\_d \`\`e ba \`\`e \`\`c \`\_d hh \`\_f \`\_d \`\_\` \`\`c ce ce ce"

then again use ROT47 on the above string you will get another decimal string which you have to convert "76 101 116 39 115 32 109 97 107 101 32 116 104 105 115 32 97 32 98 105 116 32 116 114 105 99 107 105 101 114 46 46 46"

finally you will get ur answer "Let's make this a bit trickier..."

Task 2

Spectrograms

Download Task Files

A spectrogram is a visual representation of the spectrum of frequencies of a signal as it varies with time. When applied to an audio signal, spectrograms are sometimes called sonographs, voiceprints, or voicegrams. When the data is represented in a 3D plot they may be called waterfalls.

1) File is provided on tryhackme room find the hidden message

Solution)Download the file in the task and use a spectogram creator and it will display the image with our answer "Super Secret Message"

Task 3

Steganography

Download Task Files

Steganography is the practice of concealing a file, message, image, or video within another file, message, image, or video.

1)Image is give on tryhack room find the hidden message

solution) use a stegnography decoder like https://futureboy.us/stegano/ and provide the image. It will display a message to you in our case the answer "SpaghettiSteg"

Task 4

Security through obscurity

Download Task Files

Security through obscurity is the reliance in security engineering on the secrecy of the design or implementation as the main method of providing security for a system or component of a system.

1) Download and get 'inside' the file. What is the first filename & extension?

solution) open the file in a text editor like neovim or notepad that displays ASCII characters. When you reach the bottom of the text you will see the answer "hackerchat.png"

2) Get inside the archive and inspect the file carefully. Find the hidden text

solution) open the file in a text editor like neovim or notepad that displays ASCII characters. When you reach the bottom of the text you will see the answer "AHH\_YOU\_FOUND\_ME!"