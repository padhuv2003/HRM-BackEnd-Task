 HRM Backend API (Employee Management & Attendance)
 This is a robust backend API built using Node.js and Express. It's designed to manage employee registration, authentication, and location-based attendance tracking (Check-in/Check-out). The API is connected to a MongoDB database for persistent data storage.
 To ensure maintainability and scalability, the project follows the MVC (Model-View-Controller) pattern:
 routes/  Defines the API endpoints and delegates requests to the correct controller. It acts as the API map.
 controllers/  Handles the core business logic (registration, authentication, attendance calculation). These are the action takers.
 models/   Defines the Mongoose Schemas for the MongoDB database (e.g., User, Attendance). This is the database blueprint.
 middlewares/ Handles security functions like JWT token verification and error handling. These are the security guards.
 utils/  Contains small, reusable functions for tasks like password hashing and token generation. These are the utility tools.


Live Link
Deployed Backend (Base URL)=https://hrm-backend-task.onrender.com
The base address for the live API server.

Swagger API Documentation
https://hrm-backend-task.onrender.com/api-docs
The interactive testing playground for testing all authentication and attendance endpoints.
