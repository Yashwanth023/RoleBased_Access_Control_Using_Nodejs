# Role BasedAccess Control(RBAC) Management System

  ### A Role-Based Access Control (RBAC) management system built using the MERN Stack (MongoDB, Express.js, React, Node.js). 
  ### This project provides a secure and efficient way to manage roles, permissions, and user access for modern web applications.

## Features
 - User Authentication: Secure login and signup functionality for users.
 - Role Management: Create, update, and delete roles.
 - Permission Assignment: Assign and manage permissions for specific roles.
 - User Role Assignment: Associate users with one or more roles.
 - Access Control: Enforce access restrictions based on assigned roles and permissions.
 - Admin Panel: Manage all users, roles, and permissions through an intuitive interface.
 - Email Functionality:
   -  Email verification during user registration.
   -  Reset password and forgot password workflows via SMTP.

## Technologies Used

  ## Frontend
     - React.js: Component-based library for building the user interface.
     - CSS : Tailored styles for responsive design and usability.

  ## Backend
     - Node.js: JavaScript runtime for the server-side.
     - Express.js: Lightweight and flexible web application framework.
     - MongoDB: NoSQL database for managing users, roles, and permissions.

## Setup Instructions
### Prerequisites

### Ensure the following are installed on your machine:

- Node.js (v16 or later)
- MongoDB (local or hosted, e.g., MongoDB Atlas)
- Git (optional, for cloning the repository)

## Installation
  ### Clone the repository:

  ```bash
  git clone https://github.com/Yashwanth023/RoleBased_Access_Control_Using_Nodejs.git
  ```

  ## Install dependencies:
  - Frontend
  ```bash
  cd frontend
  npm install
  ``` 
## Configure environment variables: Create a .env file in the root directory of frontend and add the following:

### .env
  ```bash
  REACT_APP_BACKEND_URL=http://localhost:5000
  REACT_APP_CLOUD_NAME=
  REACT_APP_UPLOAD_PRESET=
  ```

 ```bash
  npm start
  ```

## Access the app: Open your browser and navigate to http://localhost:3000.

## Navigate to the backend folder:
  ```bash
  cd backend
  npm install
  npm start
  ```
## Configure environment variables: Create a .env file in the root directory of backend and add the following:

### .env
  ```bash
    MONGO_URI="your mongodb uri"
    NODE_ENV=development
    JWT_SECRET="secretkey"

    EMAIL_HOST="yoursmtpemail"
    EMAIL_USER="idname"
    EMAIL_PASS="password"

    FRONTEND_URL=http://localhost:3000
  ```
