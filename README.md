### CSC7 Final Project - READ ME (Program Explanation)

Team Hard Stuck College: Vigenere Cipher Decryption Final Project

Team Members: Hector Avina, Janelle Hamoy, Michael Hareu

Date of Publish: June 4, 2023

Due Date: June 8, 2023

For the CSC7 Final Project, Team Hard Stuck College decided to tackle the Vigenere Cipher Decryption implementation. The Vigenere Cipher is a type of encryption and decryption program that will encrypt/decrypt on user input. This cipher can only encrpyt/decrypt messages that has alphabetic characters. In order to decrypt or encrypt, this program needs to recieve both a message and a key from the user (all in alphabetic characters). Non-alphabetic characters cannot be encrypted/decrypted. The message will either be encrypted or decrypted based on the key the user decides to input. 
The basic mathematical implementation of encryption with a key is as follows (using 0 as 'A' and 25 as 'Z'): (message[at index i] + key [at index i]) modulo 26. By modding the sum of the indexes at i for both message and key, the new encrpyed letter is produced. The basic mathematical implementeation of decryption is similar and is as follows: (message[at index i] - key [at index i] +26) modulo 26. Instead of the sum of the indexes at i for both message and key, it is the difference. To ensure that the correct decrypted letter is produced by the modulus, the difference is added by 26. This is done so that the modulus will correctly adjust the decrypted value.

To use Team Hard Stuck College's Vigenere Cipher Decryption implementation, the program will prompt you with a menu of 3 choices. The choices allow the user to decide to encrypt, decrypt, or terminate the program. If the user decides to encrypt, the user is prompted with providing a key and a message for the program to encrypt. However, if anywhere in the key an invalid character is detected, the user will have to replace the invalid character. The same occurs if the user decideds to decrypt. The program loops until the user decides to terminate the program.
