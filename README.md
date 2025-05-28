# Banking-Management-System-Project-with-GUI-With-Changes
# 💳 Java Banking System Project

A simple GUI-based banking system developed in Java using OOP principles like **Encapsulation, Inheritance, Abstraction, and Polymorphism**. The project supports **Admin & User login**, file-based account management, and includes an **OTP-based secure login system**.

---

## 📌 Features

- Admin and User Login System
- OTP-based secure login
- File-based account storage using Serialization
- Account creation, update, delete (Admin)
- Deposit and Withdraw with validation (User)
- Balance Inquiry & Transaction History
- GUI-based user interface using `JOptionPane`
- Input validation for security (username/password rules)

---

## 🎯 Project Aim

The main objective of this project is to demonstrate the use of **Object-Oriented Programming (OOP)** in a real-world banking system scenario with GUI interaction and file handling.

---

## 💻 Technologies Used

- Java
- Swing (JOptionPane)
- Java IO (FileInputStream, FileOutputStream)
- Object Serialization

---

## 🧱 OOP Principles Used

| OOP Principle    | Description |
|------------------|-------------|
| **Encapsulation** | Data hiding using `private` variables and `get/set` methods. |
| **Inheritance**   | `CurrentAccount` inherits from `BankAccount`. |
| **Abstraction**   | `BankAccount` is an abstract class. |
| **Polymorphism**  | `withdraw()` method is overridden in child class. |

---

## 🧾 Class Structure (UML Overview)

- **BankAccount** (abstract)
  - `CurrentAccount` (extends BankAccount)
- `BankigAccount` (main UI + logic)

---

## 📁 Packages & Libraries

- `javax.swing.*` for GUI
- `java.util.*` for collections and random
- `java.io.*` for file handling
- `java.util.regex.*` for input validation

---

## 🔐 Login Credentials Validation

- Username must start with a capital letter and contain only alphabets (max 8 characters).
- Password must:
  - Be 8 to 32 characters long
  - Include letters, numbers, and a symbol
- OTP: 6-digit random code shown via simulation dialog

---

## 📂 File Handling

- Accounts stored in a file named `accounts.ser` using Java Serialization.
- Data is automatically saved/loaded during login/logout.

---

## 🔮 Future Updates

- Support for multiple account types (Savings, Fixed)
- Email-based OTP verification using SMTP
- Export transaction history as PDF
- Responsive GUI with Swing layouts
- Full authentication and authorization system

---

## ▶️ How to Run

1. Compile:  
   ```bash
   javac BankigAccount.java
