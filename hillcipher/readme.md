### **README for Hill Cipher**  

# Hill Cipher Encryption & Decryption  

This project implements the **Hill Cipher**, a polygraphic substitution cipher that encrypts and decrypts text using matrix multiplication and modular arithmetic.  

## **Overview**  

The Hill Cipher is a **block cipher** that encrypts messages using a **matrix-based transformation**. It works by dividing plaintext into fixed-size blocks, converting them into numerical values, and performing **matrix multiplication** with a key matrix. The decryption process uses the **modular inverse** of the key matrix to recover the original plaintext.  

## **How It Works**  

1. **Encryption**  
   - The plaintext is divided into blocks of size *n*, based on the key matrix size.  
   - Each block is converted into numerical values (A = 0, B = 1, ..., Z = 25).  
   - The numerical values are arranged into a matrix and multiplied by the key matrix.  
   - The result is taken modulo 26 to obtain the encrypted text.  

2. **Decryption**  
   - The inverse of the key matrix is computed using modular arithmetic.  
   - The ciphertext is converted into numerical values and multiplied by the inverse matrix.  
   - The result is taken modulo 26 to recover the plaintext.  

## **Features**  

✅ Supports both **encryption** and **decryption**.  
✅ Handles **uppercase conversion** and **removes spaces** automatically.  
✅ **Pads** the plaintext if its length is not a multiple of the key size.  
✅ Uses **NumPy** for efficient matrix operations.  

## **Limitations**  

⚠ Requires a **square key matrix** (e.g., 2×2, 3×3).  
⚠ The key matrix **must be invertible** (determinant must not be 0 or have no modular inverse).  
⚠ The plaintext length should be a multiple of the key size; otherwise, padding is added.  

## **License**  

This project is open-source and available under the **MIT License**.  

## **Contributing**  

Feel free to **fork this repository**, submit **pull requests**, or report issues.  

## **Contact**  

For questions or suggestions, reach out via **GitHub Issues**.
