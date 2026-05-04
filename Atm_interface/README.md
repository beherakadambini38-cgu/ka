##  ATM Interface (Java Project)

##  Project Description

This project is a simple **ATM Interface simulation** developed using Java.
It allows users to perform basic banking operations like **checking balance, depositing money, and withdrawing money** using a menu-driven system.

The program is designed using **Object-Oriented Programming (OOP)** concepts such as classes and methods.

---

##  Features

* Check account balance
* Deposit money
* Withdraw money
* Input validation (no negative values, sufficient balance required)
* Simple menu-driven interface
* Displays success and failure messages

---

##  Technologies Used

* Java
* OOP Concepts
* Programiz Online Java Compiler

---

##  How to Run the Project

1. Open the project link:
    https://www.programiz.com/online-compiler/3gyzS3Ucwuwka

2. Click on **Run ** to execute the program

3. Enter your choice from the menu

4. Perform operations like deposit, withdraw, or check balance

Programiz provides an online environment where you can write, compile, and run Java code directly in your browser without installing software. ([Programiz][1])

---

## 📷 Sample Output

```id="s92kd8"
ATM Menu
1. Check Balance
2. Deposit
3. Withdraw
4. Exit

Enter choice: 1
Current balance: 2000.0

Enter choice: 3
Enter amount: 2500
Insufficient balance

Enter choice: 2
Enter amount: 1000
Deposit successful
```

---

##  Project Structure

```id="k2md93"
Main Class
│
├── BankAccount Class
│     ├── deposit()
│     ├── withdraw()
│     └── checkBalance()
│
└── ATM Class
      ├── menu()
      └── user interaction
```

---

##  Validation Rules

* Withdrawal allowed only if balance is sufficient
* Deposit amount must be greater than zero
* Invalid inputs are handled properly

---

##  Learning Outcomes

* Understanding of Java classes and objects
* Implementation of real-life ATM logic
* Use of conditional statements and loops
* Handling user input

---

##  Author

Kadambini Behera

---



[1]: https://www.programiz.com/java-programming/online-compiler?utm_source=chatgpt.com "Online Java Compiler - Programiz"
