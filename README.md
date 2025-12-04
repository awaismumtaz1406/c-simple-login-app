C++ Login, Sign Up, and Forgot Password System

This project is a console-based user authentication system written in C++. It provides three main features: user login, new account creation (sign up), and password recovery. User data is stored in a text file in a structured format.

Features

Create a new account with username, email, and password

Login using stored credentials

Recover forgotten passwords using username and email

Data stored in a simple text file (loginData.txt)

Easy to modify and understand

How Data Is Stored

Each record is saved in this format:

username*email*password


The asterisk separates each field for easy reading and searching.

How It Works

Sign Up

User enters username, email, and password

Details are saved inside loginData.txt

Login

Program reads each record from the file

It checks if the username and password match any saved record

Displays a success message if both match

Forgot Password

User enters username and email

Program searches records

If a match is found, the saved password is shown

How to Compile

Use any C++ compiler:

g++ main.cpp -o auth

How to Run
./auth

File Structure
/project-folder
   main.cpp
   loginData.txt
   README.md

Notes

Passwords are stored in plain text. This is not secure for real applications.

Only for practice and demonstration.

Improve by adding encryption or hashing for passwords if needed.
