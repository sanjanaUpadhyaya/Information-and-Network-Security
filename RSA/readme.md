# Diffie-Hellman Key Exchange 🔐

This is a simple Python implementation of the **Diffie-Hellman Key Exchange Algorithm**.  
It allows two parties (A and B) to securely generate a **shared secret key** using modular exponentiation.  

---

## 🚀 How It Works
1. The user inputs:
   - A **prime number (q)**.
   - A **primitive root (a)** of q.
   - **Private keys** for A (`Xa`) and B (`Xb`).
2. The script computes:
   - **Public keys** for A (`Ya`) and B (`Yb`).
   - The **shared secret key** using modular exponentiation.

---

## 🛠 Installation & Usage
### **1️⃣ Run the Script**
Make sure you have **Python 3** installed.  
Run the script using:
```bash
python diffie_hellman.py

Input:
Enter a prime number : 23
Enter a primitive root : 5
Enter the private key of A : 6
Enter the private key of B : 15

Output:
Public key of A : 8.0
Public key of B : 19.0
Shared key for A : 2.0
Shared key for B : 2.0

