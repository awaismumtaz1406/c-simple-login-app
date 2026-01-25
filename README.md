# C Simple Login App

A **console-based user authentication system** in C++ that supports user login, sign-up, and password recovery.

## 🧠 Overview

This project demonstrates a basic **authentication system** using file storage. It allows users to:

- Create an account (username, email, password)
- Log in with saved credentials
- Recover forgotten passwords  
User data is stored in a structured text file (`loginData.txt`). :contentReference[oaicite:1]{index=1}

## 🚀 Features

- ✅ New user registration  
- ✅ Login with credentials  
- ✅ Password recovery by username + email  
- 📄 Simple text file storage (`loginData.txt`)  
- 🧩 Easy to understand and extend :contentReference[oaicite:2]{index=2}

## 🛠️ How It Works

- User entries are appended to `loginData.txt`  
- Login checks username and password from the file  
- Forgot password retrieves the stored password if matched :contentReference[oaicite:3]{index=3}

⚠ **Note:** Passwords are stored in plain text — this is **not secure for real applications**. Use hashing in production. :contentReference[oaicite:4]{index=4}

## 💻 How to Compile

Use any standard C++ compiler:

```bash
g++ login.cpp -o login-app
