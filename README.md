# SecureLogin
A simple Flask web application with user registration, login, and logout functionality.  
Passwords are securely stored using hashing (`werkzeug.security`).  
The app uses **SQLite** as the database and includes a minimal HTML/CSS frontend.

## Features
- User Registration with password hashing
- Secure Login with session management
- Logout functionality
- Parameterized SQL queries to prevent SQL injection
- Basic HTML/CSS styling
- SQLite database (auto-initialized on first run)

## Requirements
- Python 3.x
- Flask
- Werkzeug

## How to Run
1. Clone the repository
```bash
git clone https://github.com/soyaaabean/SecureLogin.git
cd SecureLogin
```
2. Create a virtual environment and activate it
```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
```
3. Install dependencies
```bash
pip install flask werkzeug
```
4. Run :)
```bash
python app.py   # Should be running on https://127.0.0.1:5000
```

<img width="902" height="640" alt="Screenshot 2025-08-15 at 10 51 58 PM" src="https://github.com/user-attachments/assets/f80ef528-b6a7-4b10-8bf3-31d9382ae97a" />
<img width="902" height="640" alt="Screenshot 2025-08-15 at 10 53 26 PM" src="https://github.com/user-attachments/assets/77995204-14f1-4bea-8f1e-3a695b70e77c" />
<img width="902" height="640" alt="Screenshot 2025-08-15 at 10 52 50 PM" src="https://github.com/user-attachments/assets/af6a1ed4-bd99-4242-b6fc-4c99ef46b26e" />

## Author

This project was developed as part of personal projects

## License

This code is provided for educational purposes. You are free to modify and reuse it for non-commercial use.
