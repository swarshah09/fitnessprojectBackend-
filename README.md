# Fitness Freak Web-App Backend

Welcome to the backend of Fitness Freak, a comprehensive MERN stack application designed to help users track their fitness journey effectively. This backend handles the essential functionalities such as user authentication, workout tracking, calorie intake monitoring, sleep analysis, step count recording, water intake monitoring, weight management, and BMI calculation.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Configuration](#configuration)
- [API Endpoints](#api-endpoints)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication:** Secure registration and login functionality.
- **Workout Tracking:** Log and monitor various workouts.
- **Calorie Intake Monitoring:** Track daily calorie consumption.
- **Sleep Analysis:** Record and analyze sleep patterns.
- **Step Count Recording:** Keep track of daily steps.
- **Water Intake Monitoring:** Monitor daily water intake.
- **Weight Management:** Log and track weight changes.
- **BMI Calculation:** Calculate and monitor Body Mass Index (BMI).

## Technologies

- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
- **JWT (JSON Web Tokens)** for authentication
- **Bcrypt** for password hashing

## Installation

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Clone the Repository

```bash
git clone https://github.com/your-username/fitness-freak-backend.git
cd fitness-freak-backend
```

Install Dependencies
```bash
npm install
```

Configuration
Create a .env file in the root of the project with the following environment variables:
plaintext
Copy code
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
API Endpoints
User Authentication
POST /api/auth/register: Register a new user
POST /api/auth/login: Login an existing user
Workout
GET /api/workouts: Get all workouts for the authenticated user
POST /api/workouts: Add a new workout
PUT /api/workouts/
: Update a workout
DELETE /api/workouts/
: Delete a workout
Calorie Intake
GET /api/calories: Get all calorie entries for the authenticated user
POST /api/calories: Add a new calorie entry
PUT /api/calories/
: Update a calorie entry
DELETE /api/calories/
: Delete a calorie entry
Sleep Analysis
GET /api/sleep: Get all sleep records for the authenticated user
POST /api/sleep: Add a new sleep record
PUT /api/sleep/
: Update a sleep record
DELETE /api/sleep/
: Delete a sleep record
Step Count
GET /api/steps: Get all step records for the authenticated user
POST /api/steps: Add a new step record
PUT /api/steps/
: Update a step record
DELETE /api/steps/
: Delete a step record
Water Intake
GET /api/water: Get all water intake records for the authenticated user
POST /api/water: Add a new water intake record
PUT /api/water/
: Update a water intake record
DELETE /api/water/
: Delete a water intake record
Weight Management
GET /api/weight: Get all weight records for the authenticated user
POST /api/weight: Add a new weight record
PUT /api/weight/
: Update a weight record
DELETE /api/weight/
: Delete a weight record
BMI Calculation
GET /api/bmi: Calculate BMI for the authenticated user based on the latest weight and height
Usage
To start the server, run:

bash
Copy code
npm start
The backend will be running on the port specified in the .env file (default is 5000).

Contributing
We welcome contributions! Please read our Contributing Guidelines before submitting a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for using Fitness Freak! We hope this app helps you maintain a healthy and active lifestyle. If you have any questions or feedback, feel free to contact us.

javascript
Copy code

Feel free to replace placeholders like `your-username` with your actual GitHub username 
