﻿# DemoProject
# DemoProject

## Project Overview
AlgoWise Technologies is a web platform for browsing job listings and trending courses. It includes a ReactJS frontend and a Node.js backend with MongoDB for storing data.

## Setup Instructions

### Prerequisites
- Node.js (v14+)
- MongoDB (local or cloud instance)
- Git

### Steps to Set Up the Project Locally
1. **Clone the repository**:
   ```bash
   git clone https://github.com/manasakancharla1/DemoProject.git
   cd DemoProject
   
2.  **Install dependencies**:
       For the frontend:
             cd frontend
             npm install
       For the backend:
             cd ../backend
             npm install
3.**Set up environment variables**: In the backend folder, create a .env file or place it in server.js file with the following content:
        MONGO_URI=mongodb://localhost:27017/jobCoursesDB
PORT=5000
  **Running the Project**
    *Start the Backend*
      1.Navigate to the backend folder:
           cd backend
      2.Run the server:
           npm start
    The backend will run at http://localhost:5000.
    *Start the Frontend*
       1.In a new terminal, navigate to the frontend folder:
            cd frontend
       2.Start the React app:
             npm start
    The frontend will run at http://localhost:3000.
**API Documentation**
      Endpoint	 Method 	Description
      /api/jobs	  GET	    Get all jobs
   /api/courses	  GET	    Get all courses
/api/auth/signup	POST	  Register a new user
/api/auth/signin	POST	  Log in a user
**Dependencies**
  *Frontend*
     React
     Axios
     Bootstrap
  *Backend*
     Express
     MongoDB & Mongoose
     JWT
     CORS
**Troubleshooting**
*MongoDB connection issue*: Ensure MongoDB is running and the URI (mongodb://localhost:27017/jobCoursesDB) is correct.
*CORS issue*: Check the CORS configuration in the backend.
*API not responding*: Verify that the backend is running on http://localhost:5000.
arduino



