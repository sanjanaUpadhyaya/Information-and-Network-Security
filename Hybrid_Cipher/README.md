 Hybrid Encryption Using Playfair and Columnar Transposition Cipher

 Overview
This project implements a hybrid encryption technique that combines the Playfair cipher and the Columnar Transposition cipher to enhance security. The Playfair cipher is a substitution cipher that encrypts pairs of letters, while the Columnar Transposition cipher is a permutation cipher that rearranges characters based on a given key.

 Features
- Encrypts plaintext using a hybrid approach.
- Decrypts ciphertext back to the original plaintext.
- Implements Playfair cipher for substitution-based encryption.
- Implements Columnar Transposition cipher for permutation-based encryption.
- Handles key-based encryption and decryption.

 Prerequisites
- Python 3.x
- NumPy library (for matrix operations)

 Installation
1. Clone this repository:
   sh
   git clone https://github.com/yourusername/hybrid-encryption.git
   cd hybrid-encryption
   
2. Install dependencies:
   sh
   pip install numpy
   

 Usage
 Running the script
Execute the script in a terminal:
sh
python encrypt_decrypt.py


 Inputs
The program will prompt the user for:
- Playfair key (A keyword used to generate the Playfair matrix)
- Transposition key (A word used to define the column order for transposition cipher)
- Plaintext (Message to be encrypted)

 Encryption Process
1. The Playfair cipher encrypts the plaintext into an intermediate ciphertext.
2. The Columnar Transposition cipher further encrypts the intermediate text to produce the final ciphertext.

 Decryption Process
1. The Columnar Transposition cipher is reversed to retrieve the intermediate text.
2. The Playfair cipher is reversed to retrieve the original plaintext.

 Example

Enter Playfair key: KEYWORD
Enter Transposition key: SECRET
Enter Plaintext: HELLO WORLD
Encrypted Text: WXYZ...
Decrypted Text: HELXLOWORLD

Note: The letter 'X' may be used for padding in Playfair cipher.



