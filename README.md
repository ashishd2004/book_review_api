Book Review API
This is a RESTful API built with Node.js, Express, and MongoDB for managing books and their reviews. The API supports user registration and login with JWT-based authentication, enabling secure access to protected routes. Authenticated users can create, update, and delete books as well as reviews, while public users can browse and search for books.

Key features include CRUD operations for books and reviews, ensuring each user can submit only one review per book. The API supports pagination and filtering on both books and reviews for efficient data retrieval. It also includes a search endpoint to find books by title or author with partial and case-insensitive matching.

Password hashing with bcrypt secures user credentials, and JWT tokens are issued upon successful login or registration to maintain stateless authentication. Middleware protects sensitive routes to ensure only authorized actions are permitted.

The API endpoints cover user authentication (register and login), book management (add, list with filters, detail view), review management (add, update, delete, list by book), and search functionality. The database schemas include User, Book, and Review models with proper relationships.

Environment variables manage sensitive data such as the MongoDB connection string, JWT secret, and server port. The project emphasizes error handling and validation to provide meaningful responses.

Overall, this Book Review API is designed as a scalable backend service for any book-related application that needs secure user interactions, reliable review management, and flexible book searching.
