# 🎉 EventHub - MERN Stack Event Management Application

EventHub is a full-stack MERN (MongoDB, Express.js, React, Node.js) web application designed to simplify event management. It allows organizers to create and manage events, while attendees can browse, register, and keep track of upcoming events.

The application is built using React with Vite for the frontend and Node.js with Express for the backend. MongoDB Atlas is used as the cloud database, and JWT authentication is implemented to provide secure user access.

---

## 🚀 Live Demo

**Frontend:** https://eventhub-mern-frontend.onrender.com

**Backend API:** https://eventhub-mern-back-end.onrender.com

---

## ✨ Features

- Secure user registration and login using JWT Authentication
- Role-based access for Organizers and Attendees
- Create, update, and delete events
- Browse available events with detailed information
- Upload event cover images and additional images
- Responsive user interface for desktop and mobile devices
- RESTful API built with Express.js
- MongoDB Atlas integration for data storage

---

## 🛠️ Tech Stack

### Frontend

- React 19
- Vite
- React Router DOM
- Axios
- CSS

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- bcryptjs
- Multer
- CORS

---

## 📁 Project Structure

```
EventHub-MERN/
│
├── client-eventhub/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
│
├── README.md
└── render.yaml
```

---

# 💻 Running the Project Locally

## Prerequisites

Before running the project, install:

- Node.js
- Git
- MongoDB Atlas account (or Local MongoDB)

---

## Clone the Repository

```bash
git clone https://github.com/Jveerendragit818/EventHub-MERN.git

cd EventHub-MERN
```

---

## Backend Setup

Navigate to the server folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `server` folder.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FRONTEND_URL=http://localhost:5173
BACKEND_URL=http://localhost:5000
```

Start the backend server:

```bash
npm run dev
```

The backend will run at:

```
http://localhost:5000
```

---

## Frontend Setup

Open another terminal.

Navigate to the frontend folder:

```bash
cd client-eventhub
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside `client-eventhub`.

```env
VITE_API_URL=http://localhost:5000/api
```

Start the frontend:

```bash
npm run dev
```

The application will open at:

```
http://localhost:5173
```

---

# 🌐 Deployment

### Frontend

- Render Static Site

### Backend

- Render Web Service

### Database

- MongoDB Atlas

---

## Environment Variables

### Backend (Render)

```env
NODE_ENV=production
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FRONTEND_URL=https://eventhub-mern-frontend.onrender.com
BACKEND_URL=https://eventhub-mern-back-end.onrender.com
```

### Frontend (Render)

```env
VITE_API_URL=https://eventhub-mern-back-end.onrender.com/api
```

---

## ⚠️ Image Upload Note

The project currently stores uploaded images using **Multer** in the local `uploads` directory.

Since Render's free plan uses an ephemeral filesystem, uploaded files may be removed when the service restarts.

For a production-ready application, cloud storage services such as **Cloudinary** or **AWS S3** are recommended.

---

## 📸 Screenshots

You can add screenshots of the following pages:

- Home Page
- Login Page
- Register Page
- Organizer Dashboard
- Create Event
- Event Details
- My Schedule

---

## Future Improvements

- Email notifications
- PDF ticket generation
- Cloudinary image storage
- Event search and filters
- Event categories
- Payment integration
- Admin analytics dashboard

---

## 👨‍💻 Author

**Jaya Veerendra Kadiyala**

GitHub: https://github.com/Jveerendragit818

---

## 📄 License

This project is developed for learning, portfolio, and educational purposes.
