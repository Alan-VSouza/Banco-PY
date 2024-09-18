# Simple Banking System

This project is a simple banking system implemented in Python that allows users to perform various banking operations such as deposits, withdrawals, and account management. It also includes user registration and account creation functionality. The program simulates basic bank operations for educational purposes.

## Features

1. **User Registration**:
   - Users can register by providing basic details such as name, CPF, and address.
   
2. **Account Creation**:
   - Users can create a bank account linked to their CPF after registration.
   
3. **Banking Operations**:
   - **Deposit**: Users can deposit money into their accounts.
   - **Withdraw**: Users can withdraw money from their accounts with a daily limit and a limit of three withdrawals per day.
   - **Balance Inquiry**: Users can check their account balance and see a list of their recent transactions (deposit and withdrawal history).

4. **Menu Options**:
   - The system presents a menu with different options for the user to interact with, such as viewing balance, making deposits, withdrawing money, or creating new accounts.

## How to Use

1. Run the `Banco.py` file.
2. A menu will appear with the following options:
   - **1. View Account Statement**
   - **2. Deposit**
   - **3. Withdraw**
   - **4. Register User**
   - **5. Create Bank Account**
   - **6. List Bank Accounts**
   - **0. Exit**
3. Follow the on-screen instructions to interact with the banking system.

### Example of Operations

1. **Deposit**: The user inputs the amount they wish to deposit, and the balance is updated.
2. **Withdraw**: Users can withdraw an amount (up to a maximum of 500 per transaction, and up to 3 withdrawals per day).
3. **Account Creation**: Users can create an account linked to their CPF after registering as a customer.

## File Structure

- `Banco.py`: Contains the main banking functionality, including deposits, withdrawals, and balance checks.
- `Banco-com-cadastro.py`: Adds customer registration and account creation features.

## Technologies Used

- **Python**: This project is entirely written in Python.

## Future Improvements

- **Persistent Storage**: Implement functionality to store user and account data permanently using a database or file storage system.
- **User Authentication**: Add password authentication for users.
- **Enhanced Interface**: Improve the user interface for a better experience, possibly by integrating a GUI.

## License

This project is for educational purposes only and is not intended for use in a production environment.
