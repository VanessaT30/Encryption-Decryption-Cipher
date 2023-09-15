# ADFGVX-Cipher
Program takes in file input and encrypts it using columnar transposition
File Encryption/Decryption
Vanessa Tolentino
Version JavaSE 17

Description:
The following programme is a simple ADFGVX encryption and decryption application tool for files chosen by the user. It includes the substitution of each character in a text with 2 of the letters of the ADFGVX matrix, this cypher also moves around columns; effectively causing more ambiguity for the encryption. It also employs the use of a keyword – provided by the user to encode/decode the files.
To Run
The programme is run from console when deployed from the ie.atu.sw.Runner class . A menu will be displayed showing 8 options the user can choose. The user must choose a valid file directory to be encrypted, a keyword and to name the file the texts will be outputted to. If any inputs are invalid, you will have to choose the option again and then set it, else the programme will shut down. It’s also important to note that encrypt /decrypt will only continue when the input/output and key word are all set; if not set, it will run the options in order of not set. Additionally, the user will be prompted to input 2 output file names; 1 for encrypt and one for decrypt. The user shouldn’t worry about the validity of their key as it will be formatted for them before encryption/decryption. Specifying input file to be encoded/decoded: when naming file directory, you do not need to be specific with upper or lowercase characters. 

Features:
•	A save and load option which can save and load data from an already existing saved file is also included.
o	For the save option, you will need to choose a file to save and another file to save this file to
o	For load, this saved file can be chosen to load it.
