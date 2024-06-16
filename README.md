# Account Management Program

## Overview

This Python program implements a simple account management system using the concept of classes. The program allows users to perform basic operations such as debit, credit, and display account balance. Each account is uniquely identified by an account number.

## Features

- **Debit Functionality**: Deducts a specified amount from the account balance.
- **Credit Functionality**: Adds a specified amount to the account balance.
- **Display Balance**: Displays the current account balance.
- **Account Creation**: Each account is created with a unique account number and an initial balance.

## Class Description

### Account

The `Account` class encapsulates the basic operations of an account.

#### Attributes

- `balance`: A float representing the current balance of the account.
- `account_no`: An integer representing the unique account number.

#### Methods

- `__init__(self, bal, acc)`: Constructor to initialize the account with an initial balance and account number.
- `debit(self, amount)`: Method to deduct an amount from the account balance.
- `credit(self, amount)`: Method to add an amount to the account balance.
- `get_balance(self)`: Method to get the current account balance.

## Installation

To run this program, you need to have Python installed on your machine. The program does not require any external libraries.

## Usage

1. Clone the repository or download the program file.
    ```bash
    git clone https://github.com/iprinceyadav/python-learning.git
    ```
2. Navigate to the directory where the program file is located.
    ```bash
    cd python-learning
    ```
3. Run the program using the command:
    ```bash
     account_management.py
    ```



## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
