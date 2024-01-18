# OIBSIP_Task_3

TASK 3:- ATM INHERITANCE BY SHRUTI_GODSE

We have all come across ATMs in our cities and it is built on Java. This complex project consists of five different classes and is a console-based application. When the system starts the user is
prompted with user id and user pin. On entering the details successfully, then ATM functionalities are unlocked. The project allows to perform following operations:

Transactions History

Withdraw

Deposit

Transfer

Quit

Explaintion of Code:

This Java program represents a simple ATM (Automated Teller Machine) interface with basic banking functionalities. Let's go through the code to understand its functionality:

BankAccount Class:

The BankAccount class represents a bank account with properties like name, username, password, account number, balance, transaction count, and transaction history.
It has methods for account registration (register), login (login), withdrawal (withdraw), deposit (deposit), transfer (transfer), checking balance (checkBalance), and viewing transaction history (transHistory).

AtmInterface Class:

The AtmInterface class contains the main method where the ATM interface is implemented.
The takeIntegerInput method is a utility method to safely take integer input from the user, handling exceptions and ensuring the input is within specified limits.

In the main method:
It begins by prompting the user to register or exit.
If the user chooses to register, it creates a new BankAccount object, registers the user, and then enters a loop for login or exit.
Inside the login loop, the user is prompted for login credentials. If successful, the user is presented with a menu for deposit, withdrawal, transfer, balance check, transaction history, or exit.
The user can perform these operations until choosing to exit.

Explanation of Banking Operations:

register: 
Collects user information and registers the account.

login: 
Authenticates the user based on username and password.

withdraw:
Allows the user to withdraw a specified amount, updating the balance and transaction history.

deposit: 
Allows the user to deposit a specified amount, updating the balance and transaction history.

transfer:
Enables the user to transfer money to another account, with a limit of 50000.00, updating the balance and transaction history.

checkBalance: Displays the current account balance.

transHistory: Displays the transaction history.
User Interface:

The program provides a simple text-based interface, guiding the user through registration, login, and various banking operations.

Note:
The code includes some exception handling with try-catch blocks, although the catch blocks are empty, which is not ideal. It would be better to handle exceptions appropriately (e.g., printing error messages).
The use of floating-point numbers (float) for representing monetary values may not be ideal due to precision issues. Using BigDecimal or double could be a better choice for financial calculations.
Overall, the code represents a basic ATM system with user registration, login, and simple banking operations.







