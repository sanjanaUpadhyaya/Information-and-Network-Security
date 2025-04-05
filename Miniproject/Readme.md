# 🛡️ Digital Signature Algorithm (DSA) Implementation in Python

This project demonstrates a secure and transparent implementation of the **Digital Signature Algorithm (DSA)** in Python without relying on external cryptographic libraries. It involves generating large prime numbers, hashing the message using SHA-256, signing it, and verifying the signature to ensure data integrity, authenticity, and non-repudiation.

---

## 📌 Features

- Manual implementation of DSA using basic Python operations
- Prime number generation using the **Miller-Rabin** primality test
- SHA-256 based message hashing using `hashlib`
- Signature generation and verification
- Demonstration of tamper detection by verifying both original and altered messages

---

## 🔧 Requirements

- Python 3.7 or above  
- No additional libraries required (uses only `hashlib`, `random`, and `time`)

---

## 🚀 How to Run

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/DSA-python-implementation.git
   cd DSA-python-implementation
   ```

2. **Run the program**:

   ```bash
   python dsa_demo.py
   ```

   > Make sure the file is named `dsa_demo.py` or change the filename accordingly.

3. **Output Explanation**:
   - Displays generation of `q`, `p`, and generator `g`
   - Shows private/public key creation
   - Displays signature values for a sample message
   - Validates signature for both original and altered message

---

## 🧪 Sample Output

```bash
=== DIGITAL SIGNATURE STANDARD DEMO ===

Generating q (128-bit prime)...
q generated in 0.65s

Generating p (512-bit prime where p-1 divisible by q)...
p generated in 1.34s

Finding generator g...
g found in 0.01s

Generating private and public key...
Keys generated.

Signing message: 'Hi I am sanjana '
SHA-256 hash: 84ef4a3...f9ad

Signature:
r = 213123...
s = 843094...

Verifying original message...
Signature valid: True

Verifying altered message: 'Hi I am sanjana'
Signature valid for altered: False
```

---

## 📘 Educational Use

This project is ideal for students or enthusiasts looking to understand:

- The internal working of DSA
- How secure keys and digital signatures are generated manually
- The importance of cryptographic integrity in digital communication

---

## 📄 License

This project is open-source and free to use under the MIT License.
