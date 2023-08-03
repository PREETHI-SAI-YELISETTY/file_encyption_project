# file_encyption_project

# INTRODUCTION: 
We always aim to maintain availability, integrity and confidentiality of file transfer which gives us more reliance. So, in order to achieve it, we are using the random encryption algorithm. The random encryption algorithm makes use of cryptographic algorithms to secure the file transfer, where randomness is vital for file security, making possible secure encryption that allows us to maintain secrecy. Experiments show that the algorithm has many characteristics: encrypting faster, increasing the difficulty of deciphering. We take an input file, which will be divided into chunks, and each chunk will be encrypted randomly, and stored in a secured file. In the same way, the decryption will be done for each chunk by referring to the secured file in order to know the encryption algorithm to decrypt. We are using TDES, RSA and AES for file encryption.

# PROJECT WORK PROPOSED:
This project mainly focuses on improving security of data by implementing random multiple encryptions. The encryption algorithms used in the projects are individually not very feasible and strong but when used collectively it can give us a very powerful encryption. Moreover, by randomizing the algorithms for each file chunk we get an extra layer of unpredictability on the right algorithm used. The entire process can be broken down into 4 important steps. 
● Development of an User Interface (UI) that accepts an input file from the User 
● Segmentation of the file into defined chunks. 
● Applying random encryption algorithms to each chunk. 
● Provide a Decryptor that decrypts each chunk and merges them to get the original file. The Algorithms that are to be used for encryption are Advanced Encryption Standard(AES), Triple Data Encryption standard (TDES), and RSA algorithm. 
In order to achieve this we intend to use the following tech stack 1) Python - To build the encryptors and decryptors. 2) Tkinter GUI - to design and implement the user experience of the project. 3) 0auth - To facilitate secure authentication. 4) pyCryptodome- To facilitate fast and secure encryption and decryption.

# LIST OF MODULES: 
● User Interface and Experience 
● Authentication 
● File Preprocessing
● File Encryption and Decryption using AES
● File Encryption and Decryption using TDES
● Key Encryption and Decryption using RSA
