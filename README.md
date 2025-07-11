# 🏦 Bank Management System (C++)

A CLI-based banking system built in C++ to simulate essential banking operations with a blend of OOP and database integration.



## ⚙️ Features

- **Create New Account** (`new_acc`)
- **Account Types**: Supports both **Current** and **Savings** accounts
- **Balance Inquiry**
- **Loan Management**
- **Fixed Deposit (FD)**

## 🧠 Tech Stack

- **Language**: C++
- **Data Handling**:
  - `struct` for temporary in-memory operations (private scope)
  - **MySQL** for persistent storage
- **Design Paradigm**: Object-Oriented Programming (OOP) using classes
- **Interface**: CLI (Graphical User Interface planned)

## 🚀 Getting Started

1. Clone the repo  
   `git clone https://github.com/SparshKhanna0001/bankmgmtcpp`

2. Compile  
   `g++ main.cpp account.cpp dbManager.cpp -o bankmgmt`

3. Run  
   `./bankmgmt`

## 🛠️ Future Scope

- GUI using Qt or GTK
- ATM simulation module
- Admin dashboard for account oversight
- **Multithreading** for concurrent banking operations (e.g. multiple users accessing accounts simultaneously)

