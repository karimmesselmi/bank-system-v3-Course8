 Bank System V2 (C++) 🏦

A console-based banking application built in C++, featuring a complete login system with user management and role-based access control. This is an upgraded version of my previous bank system, adding multi-user support, permissions management, and a secure login screen.

This is my fourth practical programming project in C++, built to apply more advanced concepts like file handling, vectors, and access control systems.

---

## 🎓 Learning and Programming Foundation

This project was built as part of the practical applications in the **"Algorithms and Problem Solving - Level 3 (Course 7)"** course on [programmingadvices.com](https://programmingadvices.com), under the supervision of engineer **Mohammed Abu Hadhoud** 👑 ([LinkedIn](https://www.linkedin.com/in/abuhadhoud)).

---

## 🆚 V2 vs Previous Version

| Feature | Bank System V1 | Bank System V2 |
|---------|---------------|----------------|
| Login System | ❌ | ✅ |
| User Management | ❌ | ✅ |
| Access Permissions | ❌ | ✅ |
| Client Management | ✅ | ✅ |
| Transactions | ✅ | ✅ |

---

## 🏧 How the System Works

- The program starts with a **Login Screen** — username and password required
- Each user has specific **permissions** that control what they can access
- The **Admin** account has full access and cannot be deleted
- All data is saved to local text files and persists between runs

---

## ✨ Key Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | **Login System** | Secure login with username and password |
| 2 | **View Client List** | Display all registered accounts |
| 3 | **Add New Client** | Create a new bank account |
| 4 | **Delete Client** | Safely remove an account |
| 5 | **Update Client Info** | Modify customer details or balance |
| 6 | **Find Client** | Search by account number |
| 7 | **Transactions** | Deposit, withdraw, and view total balances |
| 8 | **Manage Users** | Add, delete, update, and find system users |
| 9 | **Access Control** | Each user has specific permissions per feature |
| 10 | **Logout** | Switch between users securely |

---

## 🔐 Permissions System

Each user can be granted or denied access to specific features:

| Permission | Value |
|-----------|-------|
| Show Client List | 1 |
| Add New Client | 2 |
| Delete Client | 4 |
| Update Client | 8 |
| Find Client | 16 |
| Transactions | 32 |
| Manage Users | 64 |
| Full Access | -1 |

---

## 🧠 Programming Concepts Applied

- **Structures** (`struct`) — to group client and user data
- **Enums** (`enum`) — for menu options and permission flags
- **Vectors** — to manage client and user lists dynamically
- **File Handling** (`fstream`) — to store data in text files
- **Bitwise Operations** — to manage permissions efficiently
- **Functions** — clean separation of every task
- **Data Validation** — account number uniqueness, balance checks, admin protection

---

## 📈 My Progress: My Attempt vs. Final Solution

### 1. `Bank_System_MyAttempt.cpp` — My First Try
- My independent approach before watching the solution
- Core logic works but structure could be improved

### 2. `Bank_System_FinalSolution.cpp` — The Improved Version
- Cleaner and more structured code
- Better separation of responsibilities between functions

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `Bank_System_FinalSolution.cpp` | The improved and structured version |
| `Bank_System_MyAttempt.cpp` | My first independent attempt |
| `Clients.txt` | Auto-generated file storing client records |
| `Users.txt` | Auto-generated file storing user accounts |
| `README.md` | This file, explaining the project |

---

## 🛠 How to Run the Project

### Prerequisites
You need a C++ compiler installed (like **GCC** on Linux/Mac or **MinGW** on Windows).

### Steps

1. Clone this project:
```bash
git clone https://github.com/karimmesselmi/bank-system-v2.git
```

2. Go to the project folder:
```bash
cd bank-system-v2
```

3. Compile the final version:
```bash
g++ Bank_System_FinalSolution.cpp -o BankSystemV2
```

4. Run the program:

On Windows:
```bash
BankSystemV2
```
On Linux/Mac:
```bash
./BankSystemV2
```

> **Note:** On first run, make sure a `Users.txt` file exists with at least one admin account in the format: `Admin#//#1234#//#-1`

---

## 👤 About Me

**Karim Messelmi** — Computer Science student, building my foundation one project at a time.

🔗 [LinkedIn](https://www.linkedin.com/in/karim-messelmi-34a02a379)

> *"Every project I build teaches me something new. This is just the beginning."* 🚀
