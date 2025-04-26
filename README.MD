# Task Management App

## Description

This is a task management application that allows users to create, manage, and track their tasks efficiently. It uses the MERN stack (MongoDB, Express, React, Node.js) to provide a full-stack solution for task management.

## Features

- User authentication (Sign up, Log in)
- CRUD operations for tasks (Create, Read, Update, Delete)
- Task categorization and prioritization
- Responsive design for seamless use on mobile and desktop

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Installation

### Prerequisites

- Node.js
- MongoDB (local or cloud)

### Steps to Run the Project

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   ```

2. **Install dependencies**:

   - For the backend:
     ```bash
     cd backend
     npm install
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```

3. **Set up environment variables**:

   - Create a `.env` file in the `backend` folder and add the following variables:
     ```
     MONGO_URI=<your-mongodb-uri>
     JWT_SECRET=<your-jwt-secret>
     PORT=5000
     ```

4. **Run the backend server**:

   ```bash
   cd backend
   npm start
   ```

5. **Run the frontend server**:

   ```bash
   cd frontend
   npm start
   ```

6. **Open your browser and go to**:  
   `http://localhost:3000` (Frontend)  
   `http://localhost:5000` (Backend)

## Usage

- **Sign Up**: Create a new user account.
- **Login**: Log in to access your tasks.
- **Add Task**: Create a new task by filling in the details.
- **Manage Tasks**: Edit or delete tasks as needed.

## Author

Developed by **Assinat**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
