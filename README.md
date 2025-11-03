# 🔒 Secure User Profile App

A simple console app for managing user accounts securely with class encapsulation, password validation, and email updates.

---

## ✨ Features

- **Create user profiles** (username, email, password)
- **View all stored profiles**
- **Update email address** securely (validates format)
- **Password setter** with minimum length requirement (at least 6 characters)
- **Menu interface** for easy use

---

## 🚀 How to Run

1. Make sure Python is installed.
2. Save the script as `secure.py`.
3. Open your terminal or command prompt.
4. Run: `python secure.py`

---

## 💡 Example Session

--- Secure User Profile App ---

1. Create User

2. View All Profiles

3. Update Email

4. Exit
Enter your choice(1-4): 1
Enter username: lorik
Enter email: lorik@email.com
Enter password: 123456
Password set successfully
User created successfully

Create User

View All Profiles

Update Email

Exit
Enter your choice(1-4): 2

--- User Profile ---
Username: lorik
Email: lorik@email.com
Password: 123456

---

## 🛡️ Security Design

- **Email** is protected with getter/setter; must be in valid format (`@` and `.`).
- **Password** has a setter; not less than 6 characters.
- **Encapsulation**: email is protected, password is private.

---

## 📄 License

MIT License — use and modify freely.

---

A simple tool for understanding Python encapsulation and basic user data security!
