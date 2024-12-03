# User Authentication Application

## Description

This is a simple web application built using **Flask** for user authentication. It allows users to register, login, and manage their accounts with basic session management and password encryption.

### Features:
- User Registration: Users can create a new account with their name, email, and password.
- User Login: Registered users can log in to their account using their email and password.
- Session Management: After logging in, users can view their profile and log out securely.
- Password Encryption: Passwords are securely hashed and stored in a MySQL database.

## Technologies Used:
- **Flask**: A lightweight Python web framework used for building web applications.
- **Flask-MySQLdb**: A Flask extension that provides MySQL database integration.
- **Flask-Bcrypt**: A library for hashing passwords securely.
- **MySQL**: A relational database to store user information.
- **HTML, CSS**: For front-end design and layout.

## Installation

1. Clone the repository:

git clone -

arduino

2. Create a virtual environment:

python3 -m venv venv source venv/bin/activate # On Windows: venv\Scripts\activate

3. Install the required dependencies:

pip install -r requirements.txt

4. Set up the MySQL database:

- Ensure that MySQL is installed and running on your system.
- Create a database named `user_table`.

5. Run the application:

python app.py

csharp

6. Access the application in your web browser at `http://127.0.0.1:5000/`.

## Usage

- Visit the homepage to navigate to the login or registration pages.
- Register a new account or log in with your existing credentials.
- Once logged in, you will be directed to the user profile page where you can log out.

