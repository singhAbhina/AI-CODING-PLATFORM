# AI-CODING-PLATFORM


A full-featured online coding platform inspired by LeetCode, designed to help users practice coding, execute code, and receive AI-assisted guidance. This platform also provides administrative capabilities to manage the coding environment efficiently.

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [APIs](#apis)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features

### For Users:
- **Solve Coding Problems**: Choose from a variety of coding challenges.  
- **Submit & Execute Code**: Run code in multiple languages using [Judge0](https://judge0.com/).  
- **AI Assistance Chatbot**: Get guidance and hints from an AI-powered chatbot (powered by Gemini).  
- **View Results**: Receive immediate feedback on code execution and output.  

### For Admins:
- **Manage Code Base**: Create, update, and delete coding problems.  
- **User Management**: Manage registered users and their progress.  
- **Content Deployment**: Upload instructional videos through Cloudinary.  

### Additional Features:
- **JWT Authentication & Authorization**: Secure login and role-based access.  
- **Caching**: Redis used for fast retrieval of frequently accessed data.  
- **Database**: MongoDB for storing users, problems, and submission history.  

---

## Tech Stack

| Layer                     | Technology / Tool |
|----------------------------|-----------------|
| Frontend                   | React, Redux    |
| Backend                    | Node.js, Express|
| Database                   | MongoDB         |
| Caching                    | Redis           |
| Code Execution             | Judge0 API      |
| Authentication & Security  | JWT             |
| Media Deployment           | Cloudinary      |
| AI Chatbot                 | Gemini          |

---
##Architecture
![Alt Text](https://github.com/singhAbhina/AI-CODING-PLATFORM/blob/main/leetcode%20_system_architecture.png)

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/singhAbhina/AI-CODING-PLATFORM.git
cd AI-CODING-PLATFORM
Install backend dependencies

bash
Copy code
cd backend
npm install
Install frontend dependencies

bash
Copy code
cd ../frontend
npm install
Setup environment variables
Create a .env file in the backend directory and add:

ini
Copy code
MONGO_URI=your_mongodb_connection_string
REDIS_URL=your_redis_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JUDGE0_API_URL=your_judge0_endpoint
GEMINI_API_KEY=your_gemini_api_key
Run the backend

bash
Copy code
cd ../backend
npm run dev
Run the frontend

bash
Copy code
cd ../frontend
npm start
Your app should now be running locally at http://localhost:3000.

Usage
User Workflow:

Sign up / Login

Browse coding problems

Write and execute code in the editor

Submit code for evaluation

Use AI chatbot for hints and guidance

Admin Workflow:

Login as Admin

Create, Update, Delete coding problems

Upload video tutorials or resources

Manage users and monitor submissions

Project Structure
bash
Copy code
AI-CODING-PLATFORM/
├── backend/            # Node.js backend (API, auth, DB models)
├── frontend/           # React frontend (UI, Redux store)
├── README.md
└── package.json
APIs
User APIs: Register, Login, Fetch Problems, Submit Code

Admin APIs: Manage Problems, Upload Videos

Judge0 API: Execute user-submitted code

Gemini API: AI Chatbot integration

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create a new branch (git checkout -b feature/your-feature)

Make changes and commit (git commit -m "Add new feature")

Push to the branch (git push origin feature/your-feature)

Open a Pull Request

#RESULT
![Alt Text](https://github.com/singhAbhina/AI-CODING-PLATFORM/blob/main/Screenshot%202025-09-08%20222351.png)

