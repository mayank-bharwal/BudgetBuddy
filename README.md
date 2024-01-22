# BudgetBuddy - Accounting Ledger Web Application

http://budgetbuddy.pythonanywhere.com

![Screenshot 2024-01-21 at 11 36 09 PM](https://github.com/mayank-bharwal/MindScape/assets/119955673/07f690c9-b651-4795-ba08-d256e9490078)

BudgetBuddy is a simple accounting ledger web application built using Flask, SQLAlchemy, and Flask-Login. It allows users to register, login, add transactions, and view their transaction history.

## Features

- User registration and authentication.
- Secure password storage using hashing.
- Adding transactions with date, description, and amount.
- Viewing the list of transactions.
- User logout functionality.

## Technologies Used

- Flask: A micro web framework for Python.
- SQLAlchemy: An ORM (Object-Relational Mapping) library for working with databases.
- Flask-Login: An extension for handling user authentication.
- SQLite: A lightweight relational database management system.
- HTML and CSS: For the front-end interface.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/mayank-bharwal/BudgetBuddy.git
   ```

2. Create a virtual environment and activate it:

   ```
   python -m venv venv
   source venv/bin/activate
   ```

3. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

4. Set the Flask secret key and database URI in the `app.py` file:

   ```python
   app.config['SECRET_KEY'] = 'your-secret-key'  # Change this to a random secret key
   app.config['SQLALCHEMY_DATABASE_URI'] = 'sqlite:///site.db'
   ```

5. Create the SQLite database:

   ```
   flask db create
   ```

6. Run the application:

   ```
   flask run
   ```

7. Access the web application in your browser at `http://localhost:5000`.

## Usage

1. Register a new user account by clicking on the "Register" link.
2. Log in with your registered credentials.
3. Add transactions with a date, description, and amount using the "Add Transaction" form.
4. View your transaction history on the main page.
5. Logout using the "Logout" link.

## Screenshots

![Screenshot 2024-01-21 at 11 35 08 PM](https://github.com/mayank-bharwal/MindScape/assets/119955673/81319cd1-40ef-4e77-b3a5-f85b21244f3d)

## Contributions

Contributions to this project are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.
