# Module 2 challenge: Pelcgbybtl (Cryptology)


1. **Question 1**: The logic used to convert plaintext into ciphertext is called a(n) ______.  
   **Answer**: encryption algorithm

2. **Question 2**: DES, RC4, and AES are examples of ______ encryption algorithms.  
   **Answer**: symmetric

3. **Question 3**: Using an asymmetric cryptosystem provides which of the following benefits? Select all that apply.  
   **Answer**:  
   - Authenticity  
   - Non-repudiation  

4. **Question 4**: In which of the following scenarios is symmetric encryption better than asymmetric encryption? Select all that apply.  
   **Answer**:  
   - All communications will take place over a trusted network, like a company’s internal servers.  
   - You need to encrypt and decrypt a large amount of data.

5. **Question 5**: Of the following options, which are true of an ideal hash function? Select all that apply.  
   **Answer**:  
   - They are deterministic.  
   - It maps any amount of data to an output of fixed size.  
   - A change in input is not correlated with the resulting change in the output.  

6. **Question 6**: Which of the following strategies can make passwords and password hashes stronger and more difficult for hackers to use?  
   **Answer**:  
   - Running passwords through the hashing function multiple times.  
   - Using randomly chosen and large password salts.  

7. **Question 7**: In the TLS protocol, a client validates a server’s digital certificate by checking that the certificate:  
   **Answer**:  
   - is for the correct host name.  
   - is trusted.  

8. **Question 8**: ____ is a system that defines the creation, storage, and distribution of digital certificates.  
   **Answer**: PKI

9. **Question 9**: You’re a consultant whose clients send you documents encrypted with your public key. You use your private key to decrypt these documents. What would happen if the client uses the wrong public key to encrypt the file before sending it to you?  
   **Answer**: You would not be able to decrypt the file, so when you open it you will see garbled, nonsensical output.

10. **Question 10**: Your colleague sent you a text file, a hash digest of the text file, and their public key so that you can verify a file they sent you hasn’t been modified. You run the command to determine whether the file has been modified. What output would you expect to see if the file has not been modified?  
   **Answer**: file.txt OK
