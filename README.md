# Express Middleware Task

This project is a full-stack JavaScript application demonstrating the use of middleware in an Express server with a React front end.

The backend handles authentication, input validation, and access control using custom middleware functions.  
The frontend provides a simple interface for users to register, log in, and manage a list of personal to-do items.

## Key Features
- User registration and login restricted to Gmail addresses.
- Middleware that:
  - Enforces JSON request format.
  - Limits to-do text to 140 characters.
  - Validates JWT tokens for secure routes.
- CRUD operations for user-specific to-do items.
- React interface for adding, editing, completing, and deleting tasks.
