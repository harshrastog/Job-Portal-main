Job Portal - MERN Stack Application
A full-stack Job Portal application built using the MERN stack, where users can register either as students (job seekers) or recruiters (job providers). The platform enables smooth interaction between job applicants and recruiters with role-based dashboards and secure authentication.

🔍 Overview
👨‍🎓 Student Functionality
Register and login using JWT-based authentication
Update profile: bio, profile picture, skills, resume upload
View and apply to job postings
Dashboard to track applied job status and edit personal details

🧑‍💼 Recruiter Functionality
Register and login securely
Register companies
Post jobs under registered companies
View applications for posted jobs
Accept or reject applicants

🧰 Tech Stack
Frontend: React.js, Redux, Tailwind CSS, ShadCN UI
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT (JSON Web Tokens)
File Storage: Cloudinary (for profile pictures, resumes)
API Testing: Postman

🚀 Getting Started
Prerequisites
Node.js & npm
MongoDB (local or hosted)
A .env file (see below)
Installation
Clone the repository

git clone : //github.com/harshrastog/Job-Portal-main.git
cd Job-Portal
Install Dependencies (Backend)

cd backend
npm install
Install Dependencies (Frontend)

cd ../frontend
npm install
Create a .env file in the backend directory and add the following:

 PORT=8000
 MONGODB_URI=your_mongo_connection_string
 JWT_SECRET=your_jwt_secret
 CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
 CLOUDINARY_API_KEY=your_cloudinary_api_key
 CLOUDINARY_API_SECRET=your_cloudinary_api_secret
Run the App

Start both the backend and frontend servers in separate terminals:

Start Backend

cd backend
npm run dev
Start Frontend

cd frontend
npm run dev
