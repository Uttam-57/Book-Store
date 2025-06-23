# Book Store RESTful API

This project is a RESTful API for a book store, built with Node.js and MongoDB. It includes user authentication and basic CRUD operations for managing books.

## Features

- **User Registration & Login:**  
    Users can register and log in. Authentication is handled using JWT tokens and passwords are securely hashed with bcrypt.

- **Book Management:**  
    Authenticated users can:
    - Add new books
    - View all books
    - Delete books

- **Book Details:**  
    Each book entry includes:
    - Book name
    - Author name
    - Price

- **Security:**  
    Middleware functions check user credentials (email and password) stored in MongoDB. Passwords are hashed for security.

## Getting Started

Follow these steps to run the application:

1. **Clone the repository:**
     ```bash
     git clone <repository-url>
     ```

2. **Install dependencies:**
     ```bash
     npm install
     ```

3. **Start the backend server:**
     ```bash
     nodemon server.js
     ```

4. **Start the frontend (React app):**
     ```bash
     cd bookstore-react
     npm start
     ```

## Notes

- This project is a demonstration of backend and frontend integration.
- The UI is basic, but all core functionalities are implemented.

---

Feel free to contribute or suggest improvements!
