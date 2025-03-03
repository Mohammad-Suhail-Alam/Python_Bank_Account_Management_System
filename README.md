# Python_Bank_Account_Management_System
This project is a Python-based Bank Account Management System
🏦 Python Bank Account Management System
📌 Project Overview
This project is a Python-based Bank Account Management System that allows users to create and manage accounts, perform transactions, and view account details and transaction history. It incorporates key Python concepts such as file handling, data structures, functions, and error handling to ensure a seamless user experience.

🎯 Features
🔹 Account Management
Create new bank accounts with auto-generated account numbers.
Store account holder’s name, account type (Savings/Current), and initial balance.
Retrieve and display account details.
🔹 Transactions
Deposit: Users can deposit money into their accounts.
Withdrawal: Ensures users do not withdraw more than the available balance.
Transfer: Transfer funds between accounts securely.
🔹 File Handling
Account details and transactions are stored in files using pickle for persistence.
Account data is loaded at the start and saved upon exit.
Transaction history is appended without overwriting previous data.
🔹 Reports & Analysis
View transaction history (date, type, amount).
Generate summary statistics (e.g., total deposits, withdrawals, and average transaction amount) using NumPy.
🔹 User Interaction
Interactive menu for users to navigate different operations.
Loop-based system for smooth and efficient transactions.
🔹 Error Handling
Input validation to ensure positive deposit/withdrawal amounts.
Prevention of overdraft (ensuring withdrawal doesn’t exceed the balance).
Error handling for missing accounts in transactions.
🔹 Bonus (Optional Enhancements)
User login system for secure access to accounts.
Use of lambda functions for optimized calculations.
🛠️ Technologies Used
Python (Core Logic)
Pickle (File Handling for Data Storage)
NumPy (Statistical Analysis & Reporting)
🚀 How to Run the Project
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/bank-account-management.git
cd bank-account-management
Install Dependencies (if needed)

bash
Copy
Edit
pip install numpy
Run the Python Script

bash
Copy
Edit
python bank_management.py
📊 Sample Menu Output
pgsql
Copy
Edit
Welcome to the Bank Account Management System!

1. Open a New Account
2. View Account Details
3. Deposit Money
4. Withdraw Money
5. Transfer Funds
6. View Transaction History
7. Exit

Enter your choice: _
