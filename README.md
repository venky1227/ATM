This project simulates an Automated Teller Machine (ATM) system where users can access their checking and saving accounts to perform various banking transactions such as checking balance, withdrawing funds, and depositing funds. The ATM system requires users to input their customer number and PIN number for authentication.

Features:
Login Authentication: Users are required to input their customer number and PIN number to access their accounts. The system authenticates the provided credentials against a pre-defined set of customer numbers and PIN numbers stored in a HashMap.

Account Selection: After successful authentication, users can select the type of account they want to access (checking or saving) from the main menu.

Checking Account Operations: Users can perform the following operations on their checking account:

View balance
Withdraw funds
Deposit funds
Saving Account Operations: Users can perform similar operations on their saving account:

View balance
Withdraw funds
Deposit funds
Balance Checking: The system ensures that users cannot withdraw more funds than their account balance, preventing the balance from becoming negative.

Implementation Details:
The Account class defines the basic structure and operations for both checking and saving accounts, including methods for setting and getting customer numbers, PIN numbers, and account balances.

The OptionMenu class extends the Account class and implements the main functionalities of the ATM system. It includes methods for login authentication, account selection, and account operations.

Input/output operations are handled using Scanner for user input and formatted output using DecimalFormat for displaying currency values.

Usage:
1. Clone the repository to your local machine:

    git clone <repository-url>

2. Compile the Java files:

    javac Account.java OptionMenu.java

3. Run the main program:

    java OptionMenu

4. Follow the prompts to login and perform banking transactions.

Dependencies:
    Java Development Kit (JDK)
    Git (optional, for cloning the repository)
