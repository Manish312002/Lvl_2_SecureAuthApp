# Lvl_2_secureAuthApp

## Description
Lvl_2_secureAuthApp is a secure authentication application built with Express.js. It provides user registration and login functionalities, with passwords hashed using bcrypt for added security. The application uses a PostgreSQL database to store user credentials and renders views with EJS.

## Features
- User registration with email and password
- Password hashing for secure storage
- User login with password verification
- Environment variables for configuration
- EJS templating for dynamic views

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Manish312002/Lvl_2_secureAuthApp.git
   cd Lvl_2_secureAuthApp


2. Install dependencies:

   ```bash
   npm i express ejs pg body-parser bcrypt

3. Set up your PostgreSQL database:

   - Create a database named Web Dev or update the db configuration in app.js to match your database name.
   - Create a table named userauth with columns email (VARCHAR) and password (VARCHAR).

4. Start the server:

   ```bash
   node index.js

## Usage

   - Home Page: GET / - Displays the home page.
   - Login Page: GET /login - Displays the login form.
   - Register Page: GET /register - Displays the registration form.
   - Register User: POST /register - Submits user registration data.
   - Login User: POST /login - Submits user login data.
