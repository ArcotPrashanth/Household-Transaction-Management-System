# Household Transaction Management System

A simple application to record and track everyday household money matters in one place. Built with **Python**, using **Flask** and **Tkinter**.

## What It Does

- Shows a **home dashboard** with an overview of your household finances
- Records **transactions** such as income and expenses
- Manages the **people** involved, such as family members or contacts you lend to and borrow from
- Keeps a **passbook** so you can view the full history of entries
- Helps you stay on top of who paid what and where the money went

## Project Structure

| File | Purpose |
|---|---|
| `main.py` | Entry point that starts the application |
| `dashboard.py` | Home dashboard |
| `transactions.py` | Add, view and manage transactions |
| `people.py` | Add and manage people |
| `passbook.py` | Transaction history and passbook view |
| `helper.py` | Shared helper functions used across the project |

## Tech Stack

- Python
- Flask
- Tkinter

## Getting Started

1. Make sure Python 3 is installed.
2. Install the required package:
   ```
   pip install flask
   ```
   Tkinter comes bundled with most Python installations.
3. Run the application:
   ```
   python main.py
   ```
