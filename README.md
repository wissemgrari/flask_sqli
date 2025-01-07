# Flask SQL Injection Project

This project is a Flask web application that demonstrates SQL injection vulnerabilities and their prevention.

## Screenshots

### Registration Page
This page allows users to register by providing a username, email, and password.
![register](screenshots/register.png)

### Database View
This view shows the database content, which can be manipulated through SQL injection.
![db](screenshots/db.png)

### Login Page
Users can log in using their credentials. This page is vulnerable to SQL injection attacks.
![login](screenshots/login.png)

### Server Logs
The server logs show the running SQL script that gets injected by the attacker.
![logs](screenshots/logs.png)

### Admin Dashboard
The hacker gains access to the admin dashboard through SQL injection.
![welcome](screenshots/welcome.png)

## Requirements

To install the required packages, run:

```sh
flask run
```

## Project Structure

- `app.py`: Main application file containing the Flask app and database functions.
- `utils.py`: Utility functions such as password hashing and key generation.
- `templates/`: HTML templates for rendering web pages.
- `static/`: Static files such as CSS and images.
- `requirements.txt`: Project dependencies.
- `README.md`: Project documentation.
- `screenshots/`: Folder containing screenshots used in the README.