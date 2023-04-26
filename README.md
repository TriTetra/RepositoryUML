# What is UML
- Class Diagram: A class diagram is a static structure diagram that represents the classes, interfaces, and their relationships in a system. It shows the attributes and methods of each class and how they are related to each other. Here's an example of a class diagram for a simple banking system:

### Class Diagram Example:
#### Bank<br>
Attributes: name, address, phone<br>
Methods: openAccount(customer), closeAccount(account)<br>
Relationships:<br>
One Bank has many Customers (1 to many)<br>
One Customer has many Accounts (1 to many)

#### Customer<br>
Attributes: name, address, phone<br>
Methods: deposit(account, amount), withdraw(account, amount)<br>
Relationships:<br>
One Customer belongs to one Bank (1 to 1)<br>
One Customer has many Accounts (1 to many)

#### Account<br>
Attributes: accountNumber, balance<br>
Methods: deposit(amount), withdraw(amount)<br>
Relationships:<br>
One Account belongs to one Customer (1 to 1)

- In this diagram, the Bank class has a relationship with the Customer class, as each Bank has many Customers. The Customer class has a relationship with the Account class, as each Customer has many Accounts.
