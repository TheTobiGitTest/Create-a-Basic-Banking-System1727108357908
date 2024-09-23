Objective:

  
To create a simple banking application that allows users to deposit money, withdraw money, and check their balance.

  
Requirements:

  
 • Write a Java program that simulates a basic banking system.

 • The system should allow the user to:

 1\. Create an account with an initial balance.

 2\. Deposit money into the account.

 3\. Withdraw money from the account, ensuring the account does not go into a negative balance.

 4\. Check account balance.

  
Specifications:

  
 1\. Class Design:

 • Create a class called BankAccount.

 • The BankAccount class should have the following attributes:

 • accountNumber (String)

 • accountHolderName (String)

 • balance (double)

 • The class should also have the following methods:

 1\. deposit(double amount) – Adds money to the balance.

 2\. withdraw(double amount) – Subtracts money from the balance, ensuring no overdrafts.

 3\. getBalance() – Returns the current balance.

 4\. getAccountInfo() – Returns account number, holder name, and balance.

 2\. Main Program:

 • In the main method, create a menu that allows the user to:

 1\. Create a new account.

 2\. Deposit money.

 3\. Withdraw money.

 4\. Check balance.

 5\. Exit the program.

  
Sample Output:

  
Welcome to Simple Bank!


1. Create a new account
2. Deposit money
3. Withdraw money
4. Check balance
5. Exit


Enter your choice: 1
Enter account number: 12345
Enter account holder name: John Doe
Account created with initial balance: $0.0


Enter your choice: 2
Enter deposit amount: 1000
Deposit successful! Current balance: $1000.0


Enter your choice: 4
Your current balance is: $1000.0


Enter your choice: 3
Enter withdrawal amount: 500
Withdrawal successful! Current balance: $500.0


Enter your choice: 5
Goodbye!