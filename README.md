# Banking System Console Application

This simple console application in C implements a basic banking system, allowing users to perform tasks such as login, signup, account type selection, and basic banking operations like checking balances and making transactions. The program is designed to showcase fundamental concepts in C programming and user interaction.

## How to Use

1. Compile the program using a C compiler.

    ```bash
    gcc banking_system.c -o banking_system
    ```

2. Run the executable.

    ```bash
    ./banking_system
    ```

3. Follow the on-screen prompts to either log in or sign up.

## Features

- User authentication and signup functionality.
- Account type selection for either Loan or Savings.
- Loan eligibility checks based on user details.
- Basic Savings account functionalities such as checking balance and making transactions.

## Code Structure

- `main`: Entry point of the program, prompts user for login or signup.
- `login`: Takes user input for login credentials, checks if the user exists, and redirects to the account type selection.
- `signup`: Takes user input for signup details, records the information, and redirects to login.
- `accounttype`: Takes user input for account type (Loan or Savings) and redirects accordingly.
- `Loan`: Handles loan-related functionalities, checks eligibility, and provides information or redirects to Savings account.
- `Savings`: Handles Savings account functionalities, such as checking balance and making transactions.
- `logout`: Logs the user out of the system.

## Notes

- This code is intended for educational purposes to demonstrate basic C programming concepts.
- It lacks security measures and should not be used for actual banking transactions.
- Feel free to explore and modify the code for learning purposes.
