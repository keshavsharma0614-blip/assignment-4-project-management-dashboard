# Assignment 4 - Project Management Dashboard

A full-stack project management dashboard built using React, Express.js, and MongoDB.

The project is designed to provide a simple platform for managing boards, lists, and task cards with authentication, role-based access, drag-and-drop functionality, and persistent data storage.

## Project Objective

The objective of this project is to demonstrate full-stack development skills by building a production-level project management application using React, Express.js, and MongoDB.

## Technologies Used

- React
- Vite
- Axios
- React Router DOM
- Node.js
- Express.js
- MongoDB
- Mongoose
- bcryptjs
- JSON Web Token (JWT)
- CORS

## Current Features

### User Authentication

- User registration
- User login
- Password hashing using bcryptjs
- JWT-based authentication
- Protected profile route

### User Roles

- User role
- Admin role
- Admin middleware for role-based access control

### Backend

- Express.js REST API
- MongoDB database
- Mongoose models
- Environment variables using `.env`
- CORS configuration

## Project Structure

    assignment-4-project-management-dashboard/
    └── user-api/
        ├── middleware/
        │   ├── admin.js
        │   └── auth.js
        ├── models/
        │   └── User.js
        ├── routes/
        │   ├── auth.js
        │   └── profile.js
        ├── .env
        ├── .gitignore
        ├── package.json
        ├── package-lock.json
        └── server.js

## Authentication Flow

1. User registers with name, email, and password.
2. Password is securely hashed before storing it in MongoDB.
3. User logs in using email and password.
4. Server generates a JWT token.
5. Protected routes verify the JWT token.
6. User role is included in the authentication system.

## Planned Features

### Project Management Dashboard

- Create and manage boards
- Create lists inside boards
- Create task cards
- Edit and delete task cards
- Drag-and-drop task cards
- Move cards between lists
- Persistent MongoDB data

### Role-Based Access

- Admin-specific operations
- User-specific permissions
- Protected management operations

### Frontend

- React dashboard
- React Router navigation
- Authentication UI
- Board and task management interface

## Final Goal

The final application will provide a complete project management dashboard with:

- Authentication
- Role-based access
- Boards
- Lists
- Task cards
- Drag-and-drop functionality
- MongoDB data persistence
- React frontend
- Express.js backend
- Production deployment

## Learning Outcome

This project demonstrates full-stack proficiency by integrating a React frontend with an Express.js backend and MongoDB database while implementing authentication, authorization, CRUD operations, and project management functionality.
