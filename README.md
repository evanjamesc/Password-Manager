# Password Manager

## Introduction
This application allows users to enter their existing password for storage, or randomly generate a secure password for their accounts.
This application is for demo purposes only. Future development will include password hashing.

## Features
- **Simple GUI**: A user-friendly interface that allows for easy interaction.
- **Local Storage**: Login credentials are written to a text file for storage on any of your devices.
- **Database Storage**: Login credentials are written to a MongodDB database.

## Installation
To run the password manager, follow these steps:

- Clone the repository:
- git clone https://github.com/evanjamesc/password-manager.git
- cd password-manager
- Run "main.py" locally on your machine

## How to Use
- Launch the application using the instructions above.
- Enter the website for which you would like to save your login credentials.
- Enter the username/email associated with your account.
- Type your own password, or click the "Generate Password" button. Auto-generated passwords will be copied to your clipboard to easily paste into the application where you are registering an account.
- Click the "Add" button to save your login credentials to a text file and database.

## Technologies Used
- Python 3, including the following libraries:
- Tkinter
- Random
- Pymongo
- Pyperclip

## Contact
For more information, please contact Evan Christianson at evanjameschristianson@gmail.com
