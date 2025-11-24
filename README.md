## Bank Management System (Python OOPs)
## Overview
This Bank Management System is built using Object-Oriented Programming (OOP) in Python.
It demonstrates how real-world banking operations can be modeled using classes, objects, inheritance, encapsulation, and polymorphism.

The system allows users to:

Create accounts

Deposit money

Withdraw money

Check balance

View customer details

## OOP Concepts Used
1 Class & Object

Classes like Bank, Account, and Customer represent real-world entities.

2️ Encapsulation

Account balance and customer details are kept private and accessed via getter/setter methods.

3️ Inheritance

A base class Account is extended by derived classes like:

SavingsAccount

CurrentAccount

4️ Polymorphism

Each account type overrides calculate_interest() or similar methods.

5️ Abstraction

An abstract base class enforces required behaviors for all account types.

How to Run the Project

git clone <your-repo-url>
cd bank-management
python main.py

## Features
Create new accounts

Deposit & withdraw money

Display customer details

Interest calculation (optional extension)

Supports multiple account types

Proper OOP structure for scalability

