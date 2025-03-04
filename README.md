# Authentication Service

## Overview
The Authentication Service is a simple and secure authentication system built using **Go**. It provides user registration, login, JWT-based authentication, and role-based access control.

## Features
- **User Registration**: Allows users to sign up with email and password.
- **User Login**: Authenticates users and issues JWT tokens.
- **JWT Authentication**: Secure token-based authentication.
- **Role-Based Access Control (RBAC)**: Restricts access based on user roles.
- **Password Hashing**: Uses bcrypt for secure password storage.

## Tech Stack
- **Backend**: Go (Gin/Fiber/Chi)
- **Database**: PostgreSQL / MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Docker**: Containerized deployment

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/auth-service.git
   cd auth-service

