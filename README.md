# Payment-system
Payment system will enable user to make payments with debit and credit cards in just a touch. Instead of paying with physical card, using PayUp makes it easier and secure to make payments. 
User may simply register and make transfers using to recipient by using their username or email id. While doing so unique transaction number is generated linked to particular username. Transaction completes when recipient verifies it, and let sender know of accepted transaction. User may view past transactions and available balance. Instead of accessing payment cards each time, user may load his/her account with credits which can later be used to make transfers. Another part of payment system is Forex trading. This allows user to buy/sell different currencies at market rate. 
Admin may view overall transaction log and operate on currencies. 
Package
Class Name
Description
Model
Databaseperations.java
This class contains all generic CRUD methods. This class is implemented in controller package by all the classes.

Connector.java
To establish connection with database server
View
Login.java
To provide login view

CreateAccountConsole.java
To provide account creation view

AccountHolderConsole.java
This class provides view to perform transactions
Controllers
LoginController.java
This class acts as connector between model and view for login.



