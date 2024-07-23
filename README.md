# Email_EncrypterApp
Email encrpytion application based on python 


This Python application allows you to send and receive encrypted emails using the cryptography library. It features a Tkinter-based GUI for a user-friendly experience, including functionalities to:

Generate and manage encryption keys: Automatically creates and saves an encryption key for secure email communications.
Encrypt and send emails: Encrypts the message body before sending via SMTP, with support for Gmail's SMTP and IMAP servers.
Receive and decrypt emails: Connects to Gmail's IMAP server to fetch and decrypt received emails.
User authentication: Saves email credentials securely using pickle to avoid repeated logins.
Elegant GUI: Implements a visually appealing Tkinter GUI with gradient backgrounds and stylish buttons.
The application uses:

smtplib for sending emails
imaplib for receiving emails
cryptography.fernet for message encryption and decryption
Features:

Secure email transmission
Credential management
Decryption tool integrated into the GUI
Error logging for troubleshooting
Setup:

Ensure secret.key is present or generate one.
Run the script to start the login UI.
Enter Gmail credentials and proceed to use the main application for sending/receiving encrypted emails.
Note: The app currently supports Gmail and requires Python 3.x.

<img src="Screenshot 2024-07-23 134533.png" alt="1">

<img src="Screenshot 2024-07-23 134548.png" alt="2">

<img src="Screenshot 2024-07-23 134601.png" alt="3">


