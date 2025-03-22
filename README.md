User Authentication System
--------------------------
The User Authentication System is a robust and secure backend service designed to handle user registration, login, and authentication processes. It ensures data security using JWT (JSON Web Token) authentication and password hashing techniques.

Key Features
-------------

1. User Registration & Login – Secure sign-up and sign-in process with email verification.
2. JWT Authentication – Secure token-based authentication for protected routes.
3. Password Hashing – Uses bcrypt.js for encrypting user passwords.
4. Email Verification – Sends verification emails using Nodemailer and Mailtrap SMTP.
5. Forgot Password & Reset – Allows users to reset their passwords securely.

Tech Stack
----------

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Authentication: JWT, bcrypt.js

Email Service: Nodemailer with Mailtrap

Environment Variables: dotenv
