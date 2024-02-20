## Bookstore Management System

This repository contains a Python script for a simple Bookstore Management System. The system utilizes Python along with SQL to store user login credentials and manage books in the inventory.

### Features

- **User Authentication**: Users can sign up with a username and password and log in to the system.
- **Book Inventory Management**: Users can add new books to the inventory, delete books, and search for books based on various criteria such as name, genre, and author.
- **Staff Management**: Staff details can be added, removed, and viewed within the system.
- **Sales Records**: The system keeps track of sales records including customer name, phone number, purchased books, quantity, and price.
- **Total Income Calculation**: The system can calculate the total income from sales records.

### Setup

1. **Database Setup**: Ensure that you have MySQL installed. Create a database named `store` and execute the SQL commands provided in the script to create the necessary tables (`signup`, `Available_Books`, `Sell_rec`, `Staff_details`).
   
2. **Python Environment**: Make sure you have Python installed on your system. Install the `mysql-connector-python` module using pip:
   
    ```
    pip install mysql-connector-python
    ```

### Usage

1. Run the Python script `bookstore_management.py`.
   
2. Choose between signing up for a new account or logging in with existing credentials.
   
3. Use the menu options to perform various tasks such as adding books, managing staff, viewing sales records, etc.

### Troubleshooting

- If you encounter any issues with MySQL connection, ensure that your MySQL server is running and the credentials in the script are correct.
- Check for any firewall rules blocking connections to the MySQL server.

### Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or pull request.

