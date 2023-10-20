# Bankist App

This project is part of Jonas Schmedtmann's JavaScript course. It's a simple web application for managing bank accounts and transactions.

## Introduction

The Bankist App is a web-based banking application that allows users to perform various banking operations such as deposits, withdrawals, transferring money, requesting loans, and closing accounts. It includes features like a balance overview, transaction history, and a summary of the user's financial activities.

## Features

- User login and authentication
- View account balance
- Record and display transaction history
- Request loans
- Transfer money between accounts
- Close accounts
- Automatic logout timer

## Technologies

- JavaScript
- HTML
- CSS

## Accounts Credentials:
>>**1. js 1111**

>>**2. jd 2222**

>>**3. stw 3333**

>>**4. ss 4444**

## Implementation Details

### Data

The app stores account information and transaction data in JavaScript objects. Sample account data and transactions are included. Each account object has the following properties:

- `owner`: The account owner's name.
- `movements`: An array of transactions (positive for deposits and negative for withdrawals).
- `interestRate`: The interest rate for the account.
- `pin`: The PIN for the account.
- `movementsDates`: An array of dates corresponding to each transaction.
- `currency`: The currency used for the account.
- `locale`: The locale for formatting dates and numbers.

### User Authentication

To log in, the user must provide a valid username and PIN. Upon successful login, the user is greeted with a welcome message and their account details are displayed. An automatic logout timer is activated to log the user out after a period of inactivity.

### Formatting Dates and Currency

The app utilizes the `Intl` object for formatting dates and currency according to the account's specified locale and currency. It includes functions like `formatMovementDate` and `formatCur` to display dates and currency amounts appropriately.

### Transaction History and Sorting

The app displays the transaction history for the logged-in user's account. Users can sort the transactions by clicking the "SORT" button. The sorted transactions are displayed based on the specified locale and currency.

### Banking Operations

- **Deposit**: Users can make deposits to their account.
- **Withdrawal**: Users can make withdrawals from their account.
- **Transfer**: Users can transfer money to other accounts.
- **Request Loan**: Users can request loans if they meet specific criteria.
- **Close Account**: Users can close their accounts.

### Automatic Logout

The app includes an automatic logout feature. If the user is inactive for a certain period, they are automatically logged out, and the welcome message is displayed again.

Feel free to explore and test various banking operations using the provided accounts.
