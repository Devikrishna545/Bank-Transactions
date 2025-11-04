# Bank Account Mini Project 🏦

A simple bank account management system built with Python as part of the Entri Data Science and Machine Learning course assignment. This project demonstrates fundamental Python programming concepts including object-oriented programming, user authentication, and basic banking operations.

## 📋 Project Overview

This mini project implements a basic banking system with static user authentication and core banking functionalities. It serves as a learning exercise to understand fundamental Python concepts and application development.

## ✨ Features

- **User Authentication**: Static username and password-based login system
- **Deposit**: Add funds to the bank account
- **Withdrawal**: Withdraw funds from the account (with balance validation)
- **Check Balance**: View current account balance
- **Simple Console Interface**: Easy-to-use command-line interface

## 🛠️ Technologies Used

- Python 3.x
- Basic Python concepts:
  - Functions
  - Conditional statements
  - Loops
  - Variables and data types
  - User input handling

## 📁 Project Structure

```
BankAccount_MiniProject/
│
├── README.md           # Project documentation
└── bank_account.py     # Main application file (or your actual filename)
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- Basic understanding of command-line operations

### Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Devikrishna545/BankAccount_MiniProject.git
   ```

2. Navigate to the project directory:
   ```bash
   cd BankAccount_MiniProject
   ```

### Running the Application

1. Run the Python script:
   ```bash
   python bank_account.py
   ```

2. Enter the static username and password when prompted

3. Choose from the available banking operations:
   - Deposit money
   - Withdraw money
   - Check balance
   - Exit

## 💡 Usage Example

```
Welcome to the Bank Account System!

Enter Username: [your_username]
Enter Password: [your_password]

Login Successful!

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit

Enter your choice: 1
Enter amount to deposit: 1000
Deposit successful! Your new balance is: ₹1000

```

## 🎯 Learning Objectives

This project helped me understand:

- ✅ Basic Python syntax and structure
- ✅ Function definition and calling
- ✅ User input handling and validation
- ✅ Conditional statements (if-else)
- ✅ While loops for menu-driven programs
- ✅ Variable scope and management
- ✅ Basic error handling
- ✅ Object-oriented programming concepts (if applicable)

## 🔒 Security Note

**Important**: This project uses static username and password for educational purposes only. In real-world applications, never hardcode credentials or store passwords in plain text. Use proper authentication mechanisms, encryption, and secure storage methods.

## 🎓 Course Information

- **Course**: Entri Data Science and Machine Learning
- **Project Type**: Assignment - Mini Project
- **Focus**: Basic Python Programming Fundamentals

## 📝 Features Breakdown

### 1. Login System
- Static username and password validation
- Access control to banking operations

### 2. Deposit Function
- Accepts positive amount inputs
- Updates account balance
- Provides confirmation message

### 3. Withdrawal Function
- Validates withdrawal amount against available balance
- Prevents overdrafts
- Updates account balance accordingly

### 4. Balance Inquiry
- Displays current account balance
- Real-time balance updates after transactions

## 🔮 Future Enhancements

Potential improvements for learning:

- [ ] Multiple user account support
- [ ] Database integration for persistent storage
- [ ] Transaction history tracking
- [ ] Password encryption
- [ ] GUI interface using Tkinter
- [ ] Interest calculation
- [ ] Account types (Savings, Current)
- [ ] Transfer between accounts
- [ ] Input validation and error handling improvements

## 👨‍💻 Author

**Devikrishna545**
- GitHub: [@Devikrishna545](https://github.com/Devikrishna545)
- Course: Entri Data Science and Machine Learning

## 📄 License

This project is created for educational purposes as part of a course assignment.

## 🙏 Acknowledgments

- Entri for providing the learning platform and course structure
- Course instructors and mentors for guidance
- Fellow learners for support and feedback

---

**Note**: This is a beginner-level project designed to demonstrate basic Python programming concepts. It is not intended for production use.
