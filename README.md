# Banking-System
Here is my JAVA coding about control a banking system.
# Simple Banking Programme in Java

A lightweight, console-based banking application written in Java. This project demonstrates core programming concepts such as loops, conditional statements (`switch` expressions), user input handling, and modular method structures.

---

## 🚀 Features

* **Check Balance:** Displays the current balance formatted to two decimal places.
* **Deposit Money:** Allows users to add funds, with built-in validation to prevent negative deposits.
* **Withdraw Money:** Enables users to withdraw funds, featuring checks for both negative amounts and insufficient balances.
* **User-Friendly Interface:** A continuous command-line menu interface that runs until the user explicitly chooses to exit.

---

## 🛠️ How It Works

The program uses a `while` loop to keep the application running. Based on the user's input, a `switch` statement routes the program logic to specific helper methods:

| Method | Description |
| :--- | :--- |
| `showBalance(double balance)` | Prints the current account balance. |
| `deposit()` | Prompts for an amount, validates it, and returns the value to be added to the balance. |
| `withdraw(double balance)` | Prompts for an amount, ensures it's valid and within the current balance, and returns the value to be deducted. |

---

## 📋 Prerequisites

To run this program, you will need:
* **Java Development Kit (JDK)** 14 or higher (due to the use of enhanced `->` switch expressions).


SAMPLE OUTPUT:

=================
BANKING PROGRAMME
=================
1. Show Balance
2. Deposit
3. Withdraw
4. Exit

=================

Enter your choice: 2

Enter deposit amount: 50.50

Deposit Successful!


=================
BANKING PROGRAMME
=================
1. Show Balance
2. Deposit
3. Withdraw
4. Exit
=================
Enter your choice: 1
$60.50
