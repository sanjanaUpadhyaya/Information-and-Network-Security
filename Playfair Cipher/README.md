Playfair Cipher Report
1. Introduction
The Playfair Cipher is a manual symmetric encryption technique that encrypts pairs of letters using a 5x5 matrix. It was invented by Charles Wheatstone in 1854, but it was promoted by Lord Playfair, after whom the cipher is named. The Playfair Cipher encrypts a digraph (pair of letters) by applying the following rules:

If both letters are the same, or only one letter remains, an 'X' is inserted to separate them.
If the letters appear in the same row or column, they are replaced by the letters immediately to their right or below, respectively.
If the letters form a rectangle, they are replaced by the letters on the same row but in the other pair of columns.
2. Objective
The purpose of this report is to explain the Playfair Cipher encryption and decryption mechanism through a Python implementation. The report will provide step-by-step instructions for running the code, explaining the input, output, and flow of the program.

Steps to Run the Code:
1. Open GitHub Codespaces

2. Navigate to your GitHub repository.
   Click on the Code button and select Open with Codespaces.
   Create a New File

3. Once in the Codespaces editor, create a new Python file named playfair_cipher.py.
   Paste the Code

4. Copy and paste the above Playfair Cipher implementation into the new file.
   Save the File

5. Press Ctrl+S (Windows) or Cmd+S (Mac) to save the file.
   Open Terminal

6. In Codespaces, open the terminal by going to View > Terminal.
   Run the Code

7. In the terminal, type the following command to execute the Python script:
   python playfair_cipher.py

   OR


1. Open VS Code.
2. Create a new file and save it as playfair_cipher.py.
3. Copy and paste the Playfair Cipher code into the playfair_cipher.py file.
4. Save the File: Press Ctrl+S (Windows) or Cmd+S (Mac) to save the file.
5. Open Integrated Terminal: Go to View > Terminal or press Ctrl+` to open the terminal in VS Code.
6. Run the Python Script: bash: python playfair_cipher.py


Input:

Enter the key and message when prompted:
Enter the key: PLAYFAIR
Enter the message: HELLO

Output:
Encrypted Message: BIPULB

   
   Key: PLAYFAIR
   Message: HELLO
Steps:

Enter the key: PLAYFAIR
Enter the message: HELLO
