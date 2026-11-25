# Supermarket Billing System

A Python-based supermarket billing application that generates customer bills, applies discounts and stores transaction records using Pickle file handling.

## Project Overview

This project simulates a basic supermarket billing system. It allows users to enter multiple products, calculates item-wise discounts and additional bill discounts, generates a formatted receipt and saves transaction records for future retrieval.

## Features

- Multiple items per transaction
- Category-based discounts
- Additional bill discount
- Input validation for price, quantity and category
- Formatted customer receipts
- Transaction storage using Pickle
- Retrieval of previously saved transactions

## Discount Rules

| Category / Condition | Discount |
|---|---:|
| Dairy | 5% |
| Fruits | 10% |
| Other | 0% |
| Bill subtotal above ₹1,000 | Additional 5% |

## Technologies Used

- Python
- Jupyter Notebook
- Pickle (File Handling)

## Project Files

- `billing_system.ipynb` – Generates bills and saves transaction records.
- `retrieve_transactions.ipynb` – Retrieves and displays saved transaction records.

## How to Run

1. Download or clone this repository.
2. Open the project folder in Jupyter Notebook.
3. Run `billing_system.ipynb` to generate customer bills.
4. Transaction records are saved in `transactions.pkl`.
5. Run `retrieve_transactions.ipynb` to view saved transactions.

**Note:** The `transactions.pkl` file is generated when the billing system is run for the first time. Keep it in the same folder as the notebooks when retrieving records.

## Learning Outcomes

Through this project, I practised:

- Python fundamentals and loops
- Conditional statements
- Dictionaries and lists
- Input validation and exception handling
- File handling and data persistence using Pickle

---

**Project:** Supermarket Billing System