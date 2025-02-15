
## Monoalphabetic Cipher
The **Monoalphabetic Cipher** is a type of substitution cipher where each letter in the plaintext is replaced by a letter from a fixed substitution alphabet. The key in this cipher is the mapping between the original alphabet and the cipher alphabet. Unlike the Caesar Cipher, where each letter is shifted by a fixed number, the Monoalphabetic Cipher allows for a random or pre-defined substitution for each letter.

### **Steps to Run the Monoalphabetic Cipher Code on GitHub:**
1. Run code on Colab: [Open in Google Colab](https://colab.research.google.com/drive/1HZXvLp3TbH-yOe4qArm4R1O7vAzmnK4D)

2. **Alternate method to run:**
   
   **Set Up GitHub Codespaces**:
   - Open the repository in **GitHub Codespaces** by clicking on the **Code** button and selecting **Open with Codespaces**.

   **Compile and Run the Code in Codespaces**:
   - Once you're in Codespaces, open the terminal.
   - Compile the code by running:
     ```sh
     gcc monoalphabetic_cipher.c -o monoalphabetic_cipher
     ```
   - Run the compiled code:
     ```sh
     ./monoalphabetic_cipher
     ```
   
   **Enter Inputs**:
   - The program will ask for the **length of the string** and the **string itself** to be encrypted or decrypted. 
   - Example input for encryption:
     ```sh
     Enter the length of string to be encrypted: 5
     Enter the string to encrypt: hello
     ```
     
     **View Output**:
     ```sh
     Encrypted string: qtmmp
     ```

     **Decrypt the string:**
   - You can then enter the encrypted message to decrypt it:
     ```sh
     Enter the length of string to be decrypted: 5
     Enter the string to decrypt: qtmmp
     ```
     ```sh
     The decrypted string: hello
     ```

The Monoalphabetic Cipher is a simple encryption technique that replaces each letter in the plaintext with a corresponding letter from a cipher alphabet. While easy to understand and implement, it is not considered secure due to its vulnerability to frequency analysis. However, it serves as an introductory exercise in cryptography and helps demonstrate how substitution ciphers work.

---

## License
This project is open-source and available under the MIT License.

---

## Contributing
Pull requests and suggestions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes.

---

## Contact
For any issues or queries, feel free to open an issue in the repository.

Happy coding! 🚀

