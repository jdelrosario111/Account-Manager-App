# Account-Manager-App
Keeps and manages your account information on your own computer.

🔐 Account Manager App

A simple Account Manager (Password Manager) App built with Python that helps you securely generate passwords, store account details, and quickly search for saved accounts.

🚀 Features

🔑 Generate Strong Passwords
Automatically creates secure, random passwords to protect your accounts.

🔍 Search Account
Quickly find saved account details by website or service name.

💾 Save Accounts to JSON File
Stores website, email/username, and password in a local .json file for easy access and persistence.

✉️ Email Input Validation
Ensures the email format is valid before saving account information.

⚠️ Empty Input Validation
Prevents saving data when required fields are left empty.

🛠️ Built With

Python

Tkinter (GUI)

JSON (data storage)

📂 How It Works

Enter the website, email/username, and password.

Use the Generate Password button to create a strong password automatically.

Click Add to save the account details to a JSON file.

Use Search to retrieve stored account information instantly.

The app validates:

Email format

Empty input fields

📌 Example Data Structure (JSON)
{
  "example.com": {
    "email": "user@example.com",
    "password": "A9$kLm#12"
  }
}

📈 Future Improvements

Encrypt stored passwords

Copy password to clipboard

Delete or update existing accounts

Cloud or database storage

📄 License

This project is for learning and personal use. Feel free to modify and improve it.

✨ Simple. Secure. Practical.
