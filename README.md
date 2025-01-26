# Simple-Authentication-App

# Frontend Overview
This is a Flutter application that provides user authentication functionality, including registration and login.

# Features
1. User Registration
2. User Login
3. Secure storage of user credentials

# Setup
1. Ensure you have Flutter and Dart installed on your system.
2. Clone the repository: git clone https://github.com/J33WAKASUPUN/Simple-Authentication-App/tree/main/auth_app_frontend.git
3. Navigate to the project directory: cd auth-app
4. Install dependencies: flutter pub get
5. Run the app: flutter run

# Backend Overview
This backend server provides the authentication functionality for the Flutter Auth App. It includes user registration, login, and secure storage of user credentials.

# Technologies Used
1. Node.js - JavaScript runtime environment for the backend
2. Express.js - Web application framework for Node.js
3. MongoDB - NoSQL database for storing user data
4. Mongoose - Object Data Modeling (ODM) library for MongoDB
6. bcryptjs - Library for hashing passwords
7. jsonwebtoken - Library for generating and verifying JSON Web Tokens

# Setup

1. Install Node.js and MongoDB on your system.
2. Clone the repository: git clone https://github.com/J33WAKASUPUN/Simple-Authentication-App/tree/main/auth_app_backend.git
3. Navigate to the project directory: cd auth-app-backend
4. Install dependencies: npm install
5. Start the server: node server.js

# API Endpoints

POST /api/register

1. Description: Register a new user
2. Request Body: { "username", "email", "password" }
3. Response: { "message": "User created successfully" }


POST /api/login

1. Description: Login an existing user
2. Request Body: { "email", "password" }
3. Response: { "token", "username" }


