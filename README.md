# EXCEPTION-HANDLING-ATM-Banking-System

## Introduction
This repository contains a Python implementation of a simple Banking ATM System, developed as part of an Object-Oriented Programming (OOP) case study assignment. The project demonstrates the use of classes, methods, and robust exception handling to simulate core ATM operations.

## Task Summary
The task required building a `BankAccount` class with the following methods:
- `deposit()` — adds funds to the account
- `withdraw()` — removes funds from the account
- `check_balance()` — displays the current account balance

The program handles the following exceptions:
- **Negative deposit** — raised as a `ValueError` when a deposit amount is less than zero
- **Invalid withdrawal amount** — raised as a `ValueError` when a withdrawal amount is zero or negative
- **Insufficient funds** — raised as a custom exception, `InsufficientFundsError`, when a withdrawal exceeds the available balance
