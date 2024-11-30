# BANKING_API_SYSTEM

## Overview
The Banking API System is a simple RESTful API built using Python and Flask.  
It enables users to interact with a banking system to perform key actions such as creating accounts, updating information, making transactions, and viewing account balances and transaction histories.  
The API is backed by an SQL database to securely store user data and transaction records.

## What the API Allows the User to Do

### Create Bank Accounts:
Users can create a new bank account by providing details such as name, email, and initial balance.

### Update Account Information:
Users can update their account details, including personal information like name, email, and contact details.

### Delete Accounts:
Users can delete their bank account if they no longer need it.

### Perform Transactions:
- **Deposits:** Users can deposit money into their bank account.  
- **Withdrawals:** Users can withdraw funds from their account.

### View Account Details and Balance:
Users can check their account balance and view their transaction history.

## Features

### Account Management:
- Create, update, and delete bank accounts.  
- Account details are stored securely with user-specific information.

### Transaction Support:
- Deposit and withdrawal operations for users to manage their finances.  
- Secure transaction handling ensures balance consistency.

### Balance and Transaction History:
- Users can view their real-time account balance.  
- Transaction history can be accessed for tracking deposits and withdrawals.

### Error Handling:
- Proper validation for actions like withdrawal to prevent going into a negative balance.  
- Prevents accidental deletions with confirmation steps.
