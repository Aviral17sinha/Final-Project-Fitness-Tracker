Final Project: Fitness Tracker
==============================

📋 Overview
-----------
This Fitness Tracker is a web-based application designed to help users monitor their fitness activities, set goals, and track progress over time.
It offers features like activity logging, goal setting, and progress visualization.

🚀 Features
-----------
- User authentication and profile management
- Activity logging with categories (e.g., running, cycling)
- Goal setting and progress tracking
- Visual dashboards with charts and summaries
- Responsive design for desktop and mobile devices

🛠 Tech Stack
-------------
- Frontend: React.js
- Backend: Node.js with Express.js
- Database: MongoDB
- Styling: CSS3
- Authentication: JWT (JSON Web Tokens)

📦 Prerequisites
----------------
Ensure you have the following installed:
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Git

🔧 Installation
---------------
1. Clone the repository:
   git clone https://github.com/Aviral17sinha/Final-Project-Fitness-Tracker.git
   cd Final-Project-Fitness-Tracker

2. Install backend dependencies:
   cd backend
   npm install

3. Install frontend dependencies:
   cd ../frontend
   npm install

⚙️ Configuration
----------------
1. Backend Configuration:
   Create a .env file in the `backend` directory with:
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key

2. Frontend Configuration:
   Create a .env file in the `frontend` directory with:
   REACT_APP_API_URL=http://localhost:5000/api

🏃‍♂️ Running the Application
----------------------------
1. Start the backend server:
   cd backend
   npm start

2. Start the frontend development server:
   cd frontend
   npm start

The application will run at http://localhost:3000 with the backend at http://localhost:5000/api.

🧪 Testing
----------
- Backend tests:
  cd backend
  npm test

- Frontend tests:
  cd frontend
  npm test

📁 Project Structure
--------------------
Final-Project-Fitness-Tracker/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   ├── .env
│   └── package.json
└── README.md

📚 Resources
------------
- React: https://reactjs.org/docs/getting-started.html
- Express.js: https://expressjs.com/
- MongoDB: https://docs.mongodb.com/
