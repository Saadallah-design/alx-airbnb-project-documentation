# 📂 Backend Requirements Specifications

This directory contains **detailed backend requirements** for the Airbnb-like booking system. The specifications include API endpoints, input/output formats, validation rules, and performance criteria for key features.

## 1. User Authentication

**Description:** Handles user registration, login, and profile management.

### API Endpoints

| Method | Endpoint       | Description                       |
|--------|---------------|-----------------------------------|
| POST   | /api/register  | Register a new user               |
| POST   | /api/login     | Authenticate user and return token|
| GET    | /api/profile   | Get user profile (auth required) |
| PUT    | /api/profile   | Update user profile (auth required)|

### Input/Output

**Register**
```json
Input:
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "P@ssw0rd123"
}

Output:
{
  "message": "User registered successfully",
  "userId": "12345"
}
