# SessionAuthSystem 🔒💻

## Overview
**SessionAuthSystem** is a secure authentication system built with **Node.js**, **Express**, and **MongoDB**. It allows users to sign up, log in, and manage their sessions using cookies. The project demonstrates session-based authentication with **JWT** (JSON Web Tokens) for maintaining a user's session across different requests.

---

## Features 🚀
- **Sign Up** 📝: Users can create an account with their name, email, and password.
- **Login** 🔑: Registered users can log in securely using their credentials.
- **Session Management** 🗂️: User sessions are managed via cookies for persistent login states.
- **Middleware Authentication** 🔐: Only logged-in users can access certain routes.
- **User Data Display** 🧑‍💻: After logging in, users can view their data securely.

---

## Tech Stack 🛠️
- **Node.js** 🟩
- **Express.js** ⚡
- **MongoDB** 🗄️
- **Cookie-Parser** 🍪
- **JWT** 🔑
- **bcrypt** 🔒

---

## Installation 🔧

1. Clone the repository:
    ```bash
    git clone https://github.com/ANKITKUMARBARIK/SessionAuthSystem.git
    ```

2. Install dependencies:
    ```bash
    cd SessionAuthSystem
    npm install
    ```

3. Set up MongoDB and update the connection string in `connection.js`.

4. Start the server:
    ```bash
    npm run start
    ```

5. Open your browser and go to `http://localhost:8000/` to use the app!

---

## Endpoints 📡

- **POST /userauth**: User sign up.
- **POST /userauth/login**: User login.
- **GET /user**: View user data (requires authentication).

---

## Example Usage 💻

- **Sign Up**: Register a new user by providing their full name, email, and password.
- **Login**: After signing up, use the login page to access the system.
- **User Dashboard**: Once logged in, users can access their profile and data.

---

## License 📜
This project is licensed under the GNU License.

---

## Acknowledgements 🎉
- Thanks to **Express.js** for simplifying the server-side logic.
- MongoDB for the database storage.
- **bcrypt** for securely hashing passwords.
- **cookie-parser** for managing cookies easily.

---

## Author 👨‍💻
Created by **ankit**

