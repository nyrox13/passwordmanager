# Password Manager

This is a simple command-line password manager written in Python. The password manager allows users to register, log in, add passwords for different websites, retrieve passwords, and view the list of saved websites.

## Features
- **Registration:** Users can register by providing a unique username and a master password.
- **Login:** After registration, users can log in using their username and master password.
- **Password Management:**
  - **Add Password:** Users can add passwords for different websites, and the passwords are encrypted for security.
  - **Get Password:** Users can retrieve passwords for specific websites, and the decrypted password is copied to the clipboard.
- **View Saved Websites:** Users can view the list of websites for which passwords are saved.
- **Encryption:** Passwords are encrypted using the Fernet symmetric encryption algorithm.

## How to Use
1. Clone the repository to your local machine.
2. Run the script in your terminal or command prompt.
3. Follow the on-screen instructions to register or log in.
4. After logging in, choose options to manage passwords.


## Files
- `password_manager.py`: The main script containing the password manager functionality.
- `user_data.json`: JSON file to store user registration data.
- `passwords.json`: JSON file to store encrypted passwords.
- `encryption_key.key`: File containing the encryption key.

## Security
- User passwords are hashed using SHA-256 for storage in the `user_data.json` file.
- Passwords for websites are encrypted using the Fernet symmetric encryption algorithm.

## Disclaimer
This password manager is a simple project created for my purpose. It is recommended to use well-established password management tools for sensitive information.
