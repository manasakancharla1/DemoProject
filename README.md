# DemoProject
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
   
2.  Install Dependencies:
 
 *For the backend*:
 
   # cd backend
   
   # npm install

 *For the frontend*:
 
   # cd ../frontend
   
   # npm install

**Create a .env File**:

In the backend directory, create a .env file to store your environment variables.

*Add the following content to .env*:

  ** MONGO_URI=your mongo db database url **
  PORT=5000
  
**Create a .gitignore File**:

Ensure that .env and other sensitive or unnecessary files are excluded by adding them to your .gitignore file in the root of the project:

  # Node modules directory
    node_modules/

  # Environment variable files
    .env

  # Build output directories
    dist/
    build/

   # Logs
     *.log

   # OS-specific files
    Thumbs.db
    .DS_Store

    # IDE/Editor settings
      .vscode/
       .idea/
**Running the Project**

**Backend**

*Navigate to the backend directory*:

# cd backend

*Start the Backend Server*:

# npm start

The backend server will run on port 5000 by default.

**Frontend**

*Navigate to the frontend directory*:

# cd ../frontend

*Start the Frontend Server*:

# npm start

The frontend application will run on port 3000 by default.

**API Documentation**

Endpoints

GET /api/jobs: Fetches a list of job listings.

GET /api/courses: Fetches a list of trending courses.

POST /api/users/signup: Registers a new user.

POST /api/users/signin: Authenticates a user and returns a token.


**Dependencies**

**Backend**:

express: Fast web framework for Node.js

mongoose: MongoDB object modeling tool

dotenv: Loads environment variables from a .env file

**Frontend**:

react: JavaScript library for building user interfaces

react-router-dom: Routing library for React

bootstrap: CSS framework for responsive design


**Troubleshooting**

Issue: "Module not found" error

Ensure all dependencies are installed by running npm install in both frontend and backend directories.

Issue: "Failed to connect to MongoDB"

Verify that MongoDB is running and the connection URI in the .env file is correct.
Issue: Port conflict

Ensure that ports 3000 and 5000 are not being used by other applications. You can change the port in the .env file if needed.

