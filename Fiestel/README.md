# Feistel Cipher Implementation

This repository contains a simple implementation of the **Feistel Cipher** in Python. The Feistel Cipher is a symmetric structure used in many encryption algorithms, including DES (Data Encryption Standard).

## Features
- Converts input text into an 8-bit binary format.
- Implements a simple Feistel encryption scheme.
- Allows user to input a key for encryption.
- Displays both binary and character representations of the cipher text.

## How It Works
1. The input string is converted into an 8-bit binary representation.
2. The binary string is split into two equal halves (Left and Right).
3. A simple round function is applied using the provided key:
   - The right half is modified using the key and XOR operation.
   - The halves are swapped and another round is performed.
4. The final encrypted binary output is converted back to text.

## Prerequisites
- Python 3.x

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/feistel-cipher.git](https://github.com/sanjanaUpadhyaya/Information-and-Network-Security/new/main/Fiestel
   cd Feistel
   ```
2. Run the script:
   ```sh
   python Feistel.py
   ```
3. Enter a string and a key when prompted.
4. The script will output the encrypted binary and character-based cipher text.

## Example Output
```
Enter a string: Hello
Result: 0100100001100101011011000110110001101111
Enter a key: key
Cipher Text (Binary): 1101100000110111010101101000100110011101
Cipher Text: Ø7VO
```

## License
This project is open-source and available under the MIT License.

## Contribution
Feel free to fork this repository and submit pull requests to improve the implementation.

## Author
Sanjana - GitHub: https://github.com/sanjanaUpadhyaya/

