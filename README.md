# Login and SignUp System with User Authentication

This repository contains a simple and secure login and signup system built using Node.js, Express.js, and MongoDB. The system provides essential features like user registration, login, and session management, making it a reliable solution for any web application that requires user authentication.

## Features

- **User Registration**: Allows new users to create an account by providing a username, email, and password. Passwords are securely hashed using bcrypt before storage.
  
- **User Login**: Authenticates users by verifying their credentials. Successful login initiates a session for the user.
  
- **Session Management**: Utilizes Express-session to manage user sessions, maintaining user login states across different routes.
  
- **Password Security**: Implements bcrypt for hashing passwords, ensuring that user credentials are securely stored.
  
- **MongoDB Integration**: Stores user information in a MongoDB database, offering scalability and reliability.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing user data.
- **Mongoose**: ODM for MongoDB, enabling schema-based data management.
- **bcrypt**: Library for hashing passwords securely.

## Getting Started

To set up this project locally, follow these instructions:

### Prerequisites

- Node.js installed on your machine.
- MongoDB installed and running, or a MongoDB Atlas account.
