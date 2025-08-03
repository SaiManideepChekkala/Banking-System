# 💳 Bank Management System

## 📌 Description:
This is a mini project developed in **C language** as part of coursework. It simulates a **simple banking system**, allowing operations such as:

- Creating accounts
- Depositing and withdrawing money
- Viewing account details and transaction history
- Transferring money between accounts
- Saving and retrieving account data from a file

The project uses **structures**, **structure pointers**, **single linked lists (SLL)**, and **file handling** to manage account data efficiently.

---

## 🧑‍💻 Features:

- 📁 **Create Account**  
- 💰 **Deposit Money**  
- 💸 **Withdraw Money**  
- 🔄 **Transfer Money**  
- 📊 **Check Balance**  
- 🧾 **Transaction History (Last 5)**  
- 🔍 **Search Account**  
- 📂 **Display All Accounts**  
- 💾 **Save Data to File**  
- 🧠 **Load Existing Data on Startup**

---

## 🛠 Technologies Used:

- Programming Language: **C**
- Concepts: **Structures, Linked List, File Handling**
- Tools: **GCC**, **Makefile**

---

## ⚙️ How to Run:

### 🔧 Step 1: Compile the project using make
```bash
make
```

### ▶️ Step 2: Run the executable
```bash
./bank
```

---

## 📘 Menu Options:
```text
------------------MENU---------------------------
C/c : Create account
H/h : View transaction history
W/w : Withdraw amount
D/d : Deposit amount
B/b : Balance enquiry
T/t : Transfer money
E/e : Display all account details
S/s : Save account info to file
F/f : Find specific account
Q/q : Quit application
```

---

## 📂 Project Structure:

```
C_Mini/
├── src/                # C source files (create.c, withdraw.c, etc.)
├── include/            # Header files
├── makefile            # Build file
├── readme.txt          # Usage instructions
└── bank_data.txt       # File storing persistent account info
```

---

## 📎 Notes:

- Every function like `create_account()`, `withdraw()`, etc. is implemented in a separate source file.
- Transaction info is stored in a nested structure containing:
  - Transaction ID
  - Transaction type (withdraw/deposit)
- Duplicate account numbers are not allowed.
- File-based storage ensures **data is persistent** across runs.

---

## 📑 Authors:
- Sai Manideep
