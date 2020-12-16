# WinjaCTF
Forensics, Web, Cryptography based challenges

Imp patient Data

Author : Arun and Rohan

# Description: 
Steganography and bruteforce.

# Requirements:
FlexHex

john (the ripper)

# Sources:
imp_data.zip

# Hint:
I wanted to send this file to Clinical Staff but I did not want anyone else to see what's inside it, so I protected it with a pin.


# Exploit:
You need to bruteforce 4 lettered pin (2611) using a tool like john (the ripper) to access the zipped file. Then, unzip the file to see two images, one of them distorted. then use flexhex and any other tool to compare two image files and get the flag.
