# Caesar Cipher

The **Caesar Cipher** is a simple encryption method where each letter in the message is shifted by a certain number of places in the alphabet. For example, with a shift of `3`, the letter **'A'** becomes **'D'**, **'B'** becomes **'E'**, and so on. This is a substitution cipher that replaces each letter with another based on the key (the number of positions to shift).

The Caesar Cipher was historically used by Julius Caesar to protect confidential messages. While it is not secure by modern cryptographic standards, it serves as an excellent introduction to the concept of encryption and data obfuscation.

---

## How to Run

### Running in Google Colab
1. Click the link below to open the Caesar Cipher in Google Colab:
   [Open in Google Colab](https://colab.research.google.com/drive/1lY-b7Ylzd5Zvt-4ZrEZi5kWtUsVA_Hzg)
2. Run the cell by pressing **Shift + Enter**.

### Running Locally
1. Save the script as **`caesar_cipher.py`**.
2. Open the command prompt (`cmd`) and navigate to the file location using:
   ```sh
   cd path/to/file
   ```
3. Run the script using:
   ```sh
   python caesar_cipher.py
   ```
4. Enter the text and shift key when prompted.
5. Get the encrypted or decrypted output.

---

## Example Usage

### Encryption
#### Input:
```sh
Enter text: Hello
Enter shift key: 3
```
#### Output:
```sh
Encrypted text: Khoor
```

### Decryption
#### Input:
```sh
Enter text: Khoor
Enter shift key: 3
```
#### Output:
```sh
Decrypted text: Hello
```

---

## Features
- Encrypts and decrypts messages using the Caesar Cipher technique.
- Allows user input for text and shift key.
- Works in Google Colab and local Python environments.

---

## Limitations
- Only works with alphabetic characters (A-Z, a-z).
- Does not support numbers or special characters.
- Not secure for modern encryption purposes.

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

