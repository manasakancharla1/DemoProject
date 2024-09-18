# DemoProject
# DemoProject

## Overview

AlgoWise Technologies is a web application designed to help users explore job opportunities and trending courses. This project features a ReactJS frontend and a Node.js backend, providing a seamless experience for users to browse and filter job listings and courses.

## Project Structure

The project is organized into two main parts:

- **Frontend**: Built with ReactJS, this part handles the user interface and user interactions.
- **Backend**: Developed using Node.js and Express, this part manages API endpoints and interacts with the MongoDB database.

## Features

- **Job Listings**: Browse and filter available job opportunities.
- **Trending Courses**: Explore courses to enhance skills and advance careers.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **User Authentication**: Sign up and sign in functionalities.

## Installation

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)

### Frontend

1. Clone the repository:

   ```bash
   git clone https://github.com/manasakancharla1/DemoProject.git
   cd DemoProject/frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

   The frontend will be available at `http://localhost:3000`.

### Backend

1. Navigate to the backend directory:

   ```bash
   cd ../backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the backend server:

   ```bash
   npm start
   ```

   The backend API will be available at `http://localhost:5000`.

4. Make sure MongoDB is running locally or configure the `MONGODB_URI` in the `.env` file to connect to your MongoDB instance.

## API Endpoints

- **GET** `/api/jobs` - Fetch all job listings.
- **GET** `/api/jobs/:id` - Fetch a specific job by ID.
- **GET** `/api/courses` - Fetch all courses.
- **GET** `/api/courses/:id` - Fetch a specific course by ID.
- **POST** `/api/signup` - Register a new user.
- **POST** `/api/signin` - Authenticate a user.

## Configuration

Create a `.env` file in the `backend` directory with the following content:

```dotenv
MONGODB_URI= your data base url
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

---

Thank you for using AlgoWise Technologies!
