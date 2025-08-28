# Medical Clinic Management System

A comprehensive Medical Clinic Management System built with Node.js, Express.js, and MongoDB to streamline administrative processes and enhance patient care.

## Introduction

This project is designed to facilitate the management of medical clinics by providing a robust backend system that handles patient records, doctor information, and appointment scheduling. It includes secure authentication and authorization mechanisms to ensure data privacy and integrity.

## Features

- **User Authentication & Authorization**: Secure login and registration with JWT-based authentication.
- **Role-Based Access Control**: Different levels of access for Admin, Doctor, and Patient roles.
- **CRUD Operations**: Create, Read, Update, and Delete functionalities for patients, doctors, and appointments.
- **Responsive Views**: Dynamic and responsive views built with EJS for managing records and appointments.
- **Data Validation & Security**: Integrated security features and data validation to ensure safe and reliable operations.

## Technologies

- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT, bcrypt
- **Frontend**: EJS (Embedded JavaScript)
- **Security**: Helmet, CORS
- **Tools**: Git, npm, Postman, Swagger

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/medical-clinic-management-system.git
    cd medical-clinic-management-system
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and add the following:

    ```plaintext
    PORT=5000
    MONGO_URI="your_mongo_connection_string"
    JWT_SECRET="your_jwt_secret_key"
    SESSION_SECRET="your_session_secret_key"
    ```

4. **Start the server:**

    ```bash
    npm start
    ```

    The server will start on `http://localhost:5000`.

## Usage

1. **Register a new user:**

    Navigate to `http://localhost:5000/api/auth/register` and create a new account.

2. **Login:**

    Navigate to `http://localhost:5000/api/auth/login` and log in with your credentials.

3. **Accessing Features:**

    Depending on your role (Admin, Doctor, Patient), you can access different features such as managing patients, doctors, and appointments.

## API Documentation

The API is documented using Swagger. To view the API documentation:

1. Start the server.
2. Navigate to `http://localhost:5000/api-docs` in your browser.
