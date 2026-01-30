🏦 Bank Management System (Python)
📌 Project Overview

The Bank Management System is a Python-based application that simulates core banking operations such as account creation, secure transactions, and user data management. The project focuses on backend logic, data persistence, and input validation using file-based storage.

🚀 Features

Create a new bank account with auto-generated account number

Secure PIN-based authentication for user operations

Deposit and withdraw money with transaction limits

Persistent storage of user data using JSON

View complete account details securely

Input validation and error handling for reliable operations

🛠️ Tech Stack

Programming Language: Python

Data Storage: JSON (File-based persistence)

Core Concepts Used:

Object-Oriented Programming (OOP)

File Handling

Data Validation

Conditional Logic

Error Handling

⚙️ How the System Works

User creates a bank account by providing personal details and a PIN.

The system generates a unique account number automatically.

User data is stored securely in a JSON file.

Users can authenticate using account number and PIN to:

Deposit money

Withdraw money

View account details

All transactions update the stored data in real time.

📂 Project Structure
Bank-Management-System/
│
├── data.json        # Stores user account data
├── bank.py          # Main application logic
└── README.md        # Project documentation

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/rohan02-tech/Bank-Management-System.git


Navigate to the project directory:

cd Bank-Management-System


Run the application:

python bank.py

🔒 Validation & Security Logic

Age validation for account creation

PIN length and phone number validation

Transaction limits enforced for deposits and withdrawals

Balance checks to prevent insufficient fund withdrawals

📈 Learning Outcomes

Strengthened understanding of Python backend development

Hands-on experience with data persistence using JSON

Improved logic building and problem-solving skills

Practical exposure to secure data handling concepts

📌 Future Improvements

Database integration (MySQL / MongoDB)

Password hashing for improved security

Transaction history tracking

REST API version for web or mobile integration
