📝 Student Task Manager (MERN)

A full-stack Task Management Web Application built using the MERN stack.
Users can create, view, update, delete, filter, and search tasks with priority and status management.

🚀 Live Demo

Frontend: https://student-task-manager-frontend.onrender.com

Backend API: https://student-task-manager-backend-rb9u.onrender.com

🛠️ Tech Stack
Frontend

React (Vite)

Axios

CSS Modules

Responsive UI (Desktop + Mobile)

Backend

Node.js

Express.js

MongoDB Atlas

Mongoose

RESTful APIs

Deployment

Frontend: Render (Static Site)

Backend: Render (Web Service)

Database: MongoDB Atlas

✨ Features

➕ Add tasks with title, description, priority & due date

✏️ Update task status (Pending / Completed)

🗑️ Delete tasks

🔍 Search tasks by title or description

🎯 Filter tasks (All / Pending / Completed)

📊 Sort tasks by priority or due date

📱 Fully responsive layout

🌐 Deployed with environment-based configuration

📂 Project Structure
Backend
backend/
├── src/
│   ├── controllers/
│   │   └── taskController.js
│   ├── models/
│   │   └── task.js
│   ├── routes/
│   │   └── taskRoutes.js
│   ├── config/
│   │   └── db.js
│   ├── app.js
│   └── server.js
├── package.json

Frontend
frontend/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── api/
│   │   └── axios.js
│   ├── App.jsx
│   └── main.jsx
├── .env
├── vite.config.js
├── package.json

🔗 API Endpoints

Base URL:

/api/tasks

Method	Endpoint	Description
GET	/	Get all tasks
GET	/:id	Get task by ID
POST	/	Create a new task
PUT	/:id	Update a task
DELETE	/:id	Delete a task
⚙️ Environment Variables
Backend (Render)
MONGODB_URI = your_mongodb_atlas_connection_string
PORT = 10000

Frontend (Render)
VITE_API_URL = https://student-task-manager-backend-rb9u.onrender.com/api

🧪 Running Locally
Backend
cd backend
npm install
npm run dev

Frontend
cd frontend
npm install
npm run dev

📌 Learning Outcomes

Built a complete MERN stack application

Implemented RESTful API architecture

Used environment variables correctly for production

Deployed full-stack app using Render

Integrated MongoDB Atlas cloud database

Followed clean project structure and best practices

👤 Author

Swaroop Mane
📧 Email: your email
🔗 GitHub: https://github.com/SANNINelite

💼 Role: Full-Stack Developer (MERN)

⭐ Future Improvements

User authentication (JWT)

Task categories & labels

Drag-and-drop task ordering

Dark mode

Role-based access

