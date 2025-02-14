# INS Lab - Cryptography

## Introduction
INS (Information and Network Security) is a crucial subject that deals with cryptographic techniques and network security mechanisms. This repository contains implementations of various cryptographic algorithms and security protocols used in the INS Lab.

## Features
- Implementation of classical and modern cryptographic algorithms
- Cipher implementations including Hill, Playfair, Vigenère, and Hybrid ciphers
- Encryption and decryption scripts
- Hashing techniques
- Digital signatures and authentication mechanisms
- Secure communication protocols

## Prerequisites
Before setting up the project, ensure you have the following installed:
- Python 3.x
- OpenSSL (for some cryptographic operations)
- Necessary Python libraries (listed in `requirements.txt`)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/ins-lab.git
   cd ins-lab
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Navigate to the respective algorithm folder.
2. Run the script using Python. Example:
   ```sh
   python hill_cipher.py
   ```
3. Provide input as required (plaintext, keys, etc.).
4. View the encrypted/decrypted output in the console.

## Running Tests
To test all implementations, run:
```sh
pytest
```

## Contents
- `classical_ciphers/` - Classical ciphers (Hill, Playfair, Vigenère, etc.)
- `hybrid_ciphers/` - Hybrid encryption techniques
- `symmetric/` - Symmetric encryption algorithms (AES, DES, etc.)
- `asymmetric/` - Asymmetric encryption algorithms (RSA, ECC, etc.)


## Contributing
Feel free to contribute by submitting issues or pull requests. Follow the guidelines in `CONTRIBUTING.md`.

## License
This project is licensed under the MIT License.

## Contact
For any queries, reach out to `your-email@example.com` or create an issue in the repository.

---
Happy Coding! 🚀

