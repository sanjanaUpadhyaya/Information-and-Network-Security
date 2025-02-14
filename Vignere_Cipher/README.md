# Vigenère Cipher Encryption & Decryption

This is a Python implementation of the Vigenère cipher, which is a method of encrypting and decrypting text using a repeating keyword.

## Features
- Encrypts a message using a keystream
- Decrypts the encrypted message back to plaintext
- Handles lowercase letters and ignores spaces

## How to Use

### Prerequisites
- Python 3 installed on your system
- A terminal or command prompt

### Running the Script Locally
1. Clone this repository or copy the script into a Python file (e.g., `Vigenere_Cipher.py`).
2. Open a terminal and navigate to the script's directory.
3. Run the script using:
   ```bash
   python Vigenere_Cipher.py
   ```
4. Enter a keystream (a keyword) when prompted.
5. Enter a message to encrypt.
6. The script will output the ciphertext and then decrypt it back to plaintext.

## Running in GitHub Codespaces

You can also run this script in GitHub Codespaces, which provides an online development environment.

### Steps to Run in Codespaces:
1. Open this repository in GitHub.
2. Click the **"Code"** button and select **"Codespaces"**.
3. Click **"Create codespace on main"** to launch a new Codespace.
4. Once the Codespace is ready, open a terminal in the Codespace environment.
5. Run the script using:
   ```bash
   python Vigenere_Cipher.py
   ```
6. Follow the prompts to enter a keystream and message.

## Example
```bash
Encrypting....
Enter a keystream : key
Enter a message : hello world
CipherText : ripjvyrgjl
Decrypting
Plain text : helloworld
```

## Notes
- This script only handles lowercase letters.
- Spaces in the input message are removed before encryption.

## License
This project is open-source and free to use.

