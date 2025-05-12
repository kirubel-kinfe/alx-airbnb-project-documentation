# Backend Feature Requirements

## 1. User Authentication

### Functional Requirements
- Users must be able to register with email and password.
- Users must be able to log in and receive a JWT token.
- The system must support token-based authentication for protected routes.

### API Endpoints
- `POST /api/auth/register`  
  Registers a new user.

  **Input:**
  ```json
  {
    "email": "user@example.com",
    "password": "P@ssw0rd"
  }
