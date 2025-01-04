# Bank-System-IIT-M-Project

**Project Description**

This project is a Python-based console application that simulates the core functionalities of a basic banking system. It is designed to manage user accounts, perform transactions, and maintain transaction logs, all while ensuring data is persistently stored in text files. The system includes two main access modes: Admin Mode and User Mode. Admins have the authority to create new user accounts and delete existing ones, providing flexibility for account management. On the other hand, users can securely log in to their accounts using a unique account number and password. Once logged in, users can view their current account balance, deposit funds, withdraw money, or transfer funds to another user. Every transaction is logged with details such as transaction type, amount, and date for better traceability.
The project efficiently handles data using two primary files: accounts.txt for storing account information, including account number, user name, password, and balance, and transactions.txt for recording all transactions performed by the users. The system is designed to ensure data integrity by automatically creating these files if they do not exist, thus allowing seamless initialization. For enhanced usability, the project supports preloaded data, making it easier to demonstrate the application without requiring users to input all the data manually. 


**Features Implemented**

1. Admin Mode:

   Create new user accounts with unique account numbers to avoid duplication.

   Delete existing accounts securely, ensuring proper data management.
   
3. User Mode:

    Secure login using a unique account number and password.

   View current account balance to track financial status.

   Perform key banking operations:

     a. Deposit Funds: Add money to the account and update the balance.

     b. Withdraw Funds: Withdraw money, with checks for sufficient funds.

     c. Transfer Funds: Transfer money to another user, with validation for account existence and balance sufficiency.

5. Transaction Logging:

   Maintain a detailed record of all transactions in transactions.txt.

   Log includes transaction type, amount, and date for complete traceability.

7. File Handling:

   Automatically create required files (accounts.txt and transactions.txt) if they do not exist.

   Pre-load data into files for ease of testing and demonstrations.

9. Data Management:

   Ensure accurate updates to account balances after every transaction.

   Validate transactions to prevent errors such as overdrafts or invalid transfers.

11. User Experience:

    Intuitive console-based interface with clear options for both admins and users.

    Modular design for smooth integration of new features or updates.





**How to Run the Project**

To run the banking system project, ensure you have Python (version 3.7 or later) installed on your system. While the project can be executed using any Python interpreter, using an Anaconda Notebook is recommended for a smoother experience. Begin by navigating to the project directory in your terminal or Python environment. If you have pre-existing accounts.txt and transactions.txt files containing sample data, place them in the same directory as the script. This will allow you to use preloaded data for testing and demonstration purposes.

If these files are not available, the script will automatically create them upon execution. However, the newly generated files will be empty, requiring you to populate them manually by creating user accounts through the admin interface. Once the setup is ready, execute the Python script by running the command python banking_system.py in the terminal, or load the script in Anaconda Notebook and run it cell by cell. The application will launch a console-based interface where you can log in as an admin or a user and perform various banking operations. It is advisable to use pre-stored data in the files for efficient testing, as manually inputting all account details may be time-consuming.
