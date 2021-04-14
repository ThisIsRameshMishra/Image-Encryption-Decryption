

What is Cryptography?

Cryptography is associated with the process of converting ordinary plain text into unintelligible text and vice-versa.It is a method of storing and transmitting data in a particular form so that only those for whom it is intended can read and process it.

Image Encryption/Decryption

Using the AES algorithim we use to encrypt and decrypt the image.

What is AES Algorithm?
 1) AES is a cryptographic algorithm used to protect Electronic data.
 2) It is a symmetric block cipher that can encrypt and decrypt information.
 3) Encryption converts data to an unreadable form called ciphertext. Decryption converts the data back       into its original form called Plain text.
 4) AES follows a Symmetric-key algorithm. Symmetric is also known as the secret key. Ciphers use the same key for encrypting and decrypting. So, Sender and receiver must know and use the same secret key.
 5) 
Logic of Encryption/Decryption:

First we enter a key which help to encrypt the image.Basically,we will use the XOR operation to encrypt.But,first of all we get the data of the image and convert it into the byte code and store the byte value in an array.Now,we encrypt the each byte by taking the XOR of each byte with the key and store that value in the array at the position of that byte.Now, the combination of byte data is changed so,we can't see the image.For the Decryption,the data at the each index of the array if we again XOR that data with the key we get the original value of the image data which is in the byte form and now the image will decrypt and we can see the image.
