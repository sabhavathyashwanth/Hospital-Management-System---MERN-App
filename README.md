# Hospital Management System - MERN Stack Application

A comprehensive Hospital Management System built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application provides a robust platform for managing hospital operations, patient records, and administrative tasks.

## 🚀 Features

- User Authentication & Authorization
- Patient Management
- Appointment Scheduling
- Medical Records Management
- Staff Management
- Dashboard Analytics
- Responsive Design

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM for routing
- React Icons for UI elements
- React Multi Carousel for sliders
- React Toastify for notifications
- Axios for API requests
- Vite as build tool

### Backend
- Node.js & Express.js
- MongoDB with Mongoose ODM
- JWT for authentication
- Bcrypt for password hashing
- Cloudinary for image uploads
- Express Session for session management
- Express FileUpload for file handling
- Validator for data validation

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/sabhavathyashwanth/Hospital-Management-System---MERN-App.git
cd Hospital-Management-System-MERN-App
```

2. Install Backend Dependencies
```bash
cd backend
npm install
```

3. Install Frontend Dependencies
```bash
cd frontend
npm install
```

4. Environment Variables Setup (Required)
Create a new `.env` file in the backend directory and configure the following required environment variables:

```
# Required Environment Variables - Add these to your .env file
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Note: You'll need to set up these environment variables with your own values before running the application.

5. Run the Application

Backend:
```bash
cd backend
npm run dev
```

Frontend:
```bash
cd frontend
npm run dev
```

## 🌐 Project Structure

```
├── backend/
│   ├── controller/     # Route controllers
│   ├── database/      # Database configuration
│   ├── middlewares/   # Custom middlewares
│   ├── models/        # Database models
│   ├── router/        # API routes
│   ├── utils/         # Utility functions
│   ├── app.js         # Express app configuration
│   └── server.js      # Server entry point
│
├── frontend/
│   ├── public/        # Static files
│   ├── src/          # React source files
│   └── index.html    # HTML entry point
│
├── dashboard/         # Admin Dashboard Interface
```

## 🔒 Security Features

- JWT Authentication
- Password Hashing
- Protected Routes
- Session Management
- Input Validation
- File Upload Security

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the ISC License.

## 🙏 Acknowledgments

- MERN Stack Community
- Open Source Contributors 
