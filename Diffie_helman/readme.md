### **README for Diffie-Hellman Key Exchange**  

# **🔐 Diffie-Hellman Key Exchange Algorithm**  

This project implements the **Diffie-Hellman Key Exchange**, a cryptographic protocol that allows two parties to establish a **shared secret key** over an insecure channel without directly transmitting the key.  

---

## **📜 Overview**  

The **Diffie-Hellman Key Exchange** enables two users to generate a **common secret key** using modular arithmetic. This key can then be used for **secure communication**.  

---

## **⚙️ How It Works**  

1. **Initial Setup**  
   - A **prime number (q)** is chosen as the base.  
   - A **primitive root (a)** of the prime number is selected.  

2. **Key Generation**  
   - Each user selects a **private key**:  
     - **Xa** (private key of A)  
     - **Xb** (private key of B)  
   - They compute their **public keys**:  
     - **Ya = (a^Xa) mod q** (Public Key of A)  
     - **Yb = (a^Xb) mod q** (Public Key of B)  

3. **Shared Key Calculation**  
   - A computes the **shared key**: **Ka = (Yb^Xa) mod q**  
   - B computes the **shared key**: **Kb = (Ya^Xb) mod q**  
   - Both values **Ka** and **Kb** are the same, forming the **secret shared key**.  

---

## **🚀 How to Run**  

### **1️⃣ Install Python**  
Ensure you have **Python 3** installed. You can download it from:  
[Python Official Website](https://www.python.org/downloads/)  

### **2️⃣ Save the Script**  
Create a new file called **`diffie_hellman.py`** and copy the following code:  

```python
import math

q = int(input("Enter a prime number: "))
a = int(input("Enter a primitive root: "))
Xa = int(input("Enter the private key of A: "))
Xb = int(input("Enter the private key of B: "))

Ya = math.pow(a, Xa) % q
Yb = math.pow(a, Xb) % q

print("Public key of A:", Ya)
print("Public key of B:", Yb)

Ka = math.pow(Yb, Xa) % q
Kb = math.pow(Ya, Xb) % q

print("Shared key for A:", Ka)
print("Shared key for B:", Kb)
```

### **3️⃣ Run the Program**  
Open a terminal or command prompt and navigate to the directory where the script is saved. Then run:  

```bash
python diffie_hellman.py
```

### **4️⃣ Example Input & Output**  

#### 🔹 **Input:**
```
Enter a prime number: 23
Enter a primitive root: 5
Enter the private key of A: 6
Enter the private key of B: 15
```

#### 🔹 **Output:**
```
Public key of A: 8.0
Public key of B: 19.0
Shared key for A: 2.0
Shared key for B: 2.0
```

Now both **A and B have the same shared secret key** (2).  

---

## **🛠 Features**  

✅ Uses **modular exponentiation** to generate secure keys.  
✅ Prevents eavesdropping by never transmitting the **private keys**.  
✅ Public keys are exchanged openly, but the **shared key remains secret**.  
✅ Provides a **foundation for secure communication** in cryptographic protocols.  

---

## **⚠️ Limitations**  

⚠ The security depends on choosing a **large prime number (q)**.  
⚠ Vulnerable to **man-in-the-middle attacks** if public keys are not authenticated.  
⚠ The method only establishes a **shared key**, not direct encryption.  

---

## **📜 License**  

This project is open-source and available under the **MIT License**.  

---

## **🤝 Contributing**  

- Feel free to **fork this repository**, submit **pull requests**, or report issues.  
- If you find any improvements, feel free to contribute!  

---

## **📩 Contact**  

For questions or suggestions, reach out via **GitHub Issues**.  
Happy coding! 🚀
