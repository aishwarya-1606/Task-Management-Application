# Task Management Application

A full-stack task management web application developed for creating, updating, organizing, and tracking daily tasks efficiently.

---

## Features

* User authentication and authorization
* Create, update, and delete tasks
* Mark tasks as completed or pending
* Real-time task updates
* Responsive design for desktop and mobile
* REST API integration
* Dynamic task management
* Secure user login system

---

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* React.js

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT Authentication
* bcrypt.js

### Deployment

* Vercel
* Render
* Netlify

---

## Project Structure

```bash id="ehfkkq"
task-management-app/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## Installation

### Clone Repository

```bash id="5dvb1s"
git clone <repository-link>
```

### Frontend Setup

```bash id="mhsu40"
cd client
npm install
npm start
```

### Backend Setup

```bash id="2jck9s"
cd server
npm install
node server.js
```

---

## Required Packages

```bash id="7b1d9z"
npm install express mongoose cors dotenv bcryptjs jsonwebtoken
npm install nodemon --save-dev
```

---

## Database Setup

Connect MongoDB using:

```javascript id="1t8n4k"
mongoose.connect('YOUR_MONGODB_URL')
```

---

## API Endpoints

| Method | Endpoint           | Description   |
| ------ | ------------------ | ------------- |
| POST   | /api/auth/register | Register user |
| POST   | /api/auth/login    | Login user    |
| GET    | /api/tasks         | Fetch tasks   |
| POST   | /api/tasks         | Create task   |
| PUT    | /api/tasks/:id     | Update task   |
| DELETE | /api/tasks/:id     | Delete task   |

---

## Deployment

### Frontend

* Vercel
* Netlify

### Backend

* Render
* Railway

### Database

* MongoDB Atlas

---

## Expected Outcome

* Learn full-stack application structure
* Understand authentication systems
* Gain experience with REST APIs
* Learn database integration
* Handle dynamic data efficiently
* Deploy full-stack applications

---

## Future Enhancements

* Task reminders
* Notifications
* Drag and drop tasks
* Dark mode
* Team collaboration
* Priority labels
* Due date calendar

---

## Author

Aishwarya
AIML Student | Full Stack Developer
