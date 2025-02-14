**Playfair Cipher**

## Introduction
The Playfair Cipher is a manual symmetric encryption technique that encrypts pairs of letters using a 5x5 matrix. It was invented by Charles Wheatstone in 1854, but it was promoted by Lord Playfair, after whom the cipher is named.

## Encryption Rules
1. If both letters in a pair are the same, or only one letter remains, an 'X' is inserted to separate them.
2. If the letters appear in the same row or column, they are replaced by the letters immediately to their right or below, respectively.
3. If the letters form a rectangle, they are replaced by the letters on the same row but in the other pair of columns.

## Objective
This repository contains a Python implementation of the Playfair Cipher, demonstrating both encryption and decryption processes.

## Steps to Run the Code

### Running in Google Colab
1. Click the link below to open the Playfair Cipher in Google Colab:
   [Google Colab Link](https://colab.research.google.com/drive/1C4neOFxH3RJJwOdWvcProfoOSYz_8kkI)
2. Run the cell by pressing `Shift + Enter`.

### Running in GitHub Codespaces
1. Open your GitHub repository.
2. Click on the **Code** button and select **Open with Codespaces**.
3. In the Codespaces editor, create a new Python file named `playfair_cipher.py`.
4. Copy and paste the Playfair Cipher implementation into the file.
5. Save the file (`Ctrl+S` on Windows or `Cmd+S` on Mac).
6. Open the terminal in Codespaces: **View > Terminal**.
7. Run the script using:
   ```bash
   python playfair_cipher.py
   ```

### Running in VS Code
1. Open **VS Code**.
2. Create a new file and save it as `playfair_cipher.py`.
3. Copy and paste the Playfair Cipher code into the file.
4. Save the file (`Ctrl+S` on Windows or `Cmd+S` on Mac).
5. Open the integrated terminal: **View > Terminal** or press `Ctrl + \`.
6. Run the script using:
   ```bash
   python playfair_cipher.py
   ```

## Example Usage
### Input:
```
Enter the key: PLAYFAIR
Enter the message: HELLO
```

### Output:
```
Encrypted Message: BIPULB
```

The Playfair Cipher is an interesting cryptographic technique that strengthens simple substitution ciphers by encrypting letter pairs, making frequency analysis more challenging. While it is no longer used for secure communication, it remains an important historical encryption method and a great educational tool.

