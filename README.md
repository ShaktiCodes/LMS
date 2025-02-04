Full-Stack LMS App with MERN Stack | React + Node

🚀 Project Overview

This is a Full-Stack Learning Management System (LMS) built using MERN Stack (MongoDB, Express.js, React.js, and Node.js). It allows users to register, purchase courses, track progress, and manage courses with an intuitive UI/UX.

🌟 Features

Frontend (React + Redux + Shadcn UI)

Shadcn UI Setup for consistent design

Light/Dark Mode Toggle

Login/Signup Page with Google Authentication

User Dashboard

Navbar & Hero Section

Course Listing Page with Search & Filters

Course Details Page

Purchase Course (Stripe Payment Integration & Webhooks)

Track Course Progress

Protected Routes Implementation

Backend (Node.js + Express + MongoDB)

User Authentication (JWT & Google OAuth)

Multer & Cloudinary Setup for File Uploads

Course Model & Controllers

Admin Dashboard for Course Management

CRUD Operations: Add, Edit, Publish, Unpublish, and Delete Courses

Lecture Management: Add, Get, Upload, Edit, Remove Lectures

Purchase & Payment Handling (Stripe API)

🛠️ Tech Stack

Frontend:

React.js

Redux Toolkit (RTK Query)

React Router DOM

Tailwind CSS & Shadcn UI

Axios

Backend:

Node.js

Express.js

MongoDB (Mongoose)

Multer (File Uploads)

Cloudinary (Image & Video Hosting)

Stripe API (Payments)

JWT (Authentication)

🚀 Getting Started

1️⃣ Clone the Repository

git clone https://github.com/your-username/lms-app.git
cd lms-app

2️⃣ Install Dependencies

Backend:

cd backend
npm install

Frontend:

cd frontend
npm install

3️⃣ Setup Environment Variables

Create a .env file in both frontend and backend directories and add the required environment variables:

Backend .env

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

Frontend .env

REACT_APP_API_URL=http://localhost:5000
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key

4️⃣ Start the Development Servers

Backend:

cd backend
npm run dev

Frontend:

cd frontend
npm start

🛠️ API Endpoints

Method

Endpoint

Description

POST

/api/auth/register

Register a new user

POST

/api/auth/login

Login user

GET

/api/courses

Get all courses

POST

/api/courses

Add a new course (Admin)

GET

/api/courses/:id

Get course by ID

PUT

/api/courses/:id

Edit course details (Admin)

DELETE

/api/courses/:id

Delete a course (Admin)

POST

/api/payment/checkout

Process Stripe Payment

🎉 Deployment

To deploy the app:

Frontend: Deploy on Vercel/Netlify

Backend: Deploy on Render/Vercel

Database: Use MongoDB Atlas

🤝 Contributing

Feel free to fork this repo, submit issues, and contribute enhancements. Pull requests are welcome!

🚀 Happy Coding!

