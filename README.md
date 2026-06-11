# X Clone (Twitter Clone)

A full-stack social media application inspired by X (formerly Twitter), built using the MERN stack. Users can create accounts, log in securely, create posts with images, view profiles, receive notifications, and interact through a modern responsive interface.

## Live Demo

Frontend: https://twitter-clone-sonu.vercel.app/

## Tech Stack

### Frontend

- React.js
- React Router
- React Query
- Tailwind CSS
- JavaScript (ES6+)

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose

### Authentication & Security

- JWT Authentication
- HTTP-Only Cookies
- Protected Routes
- Password Hashing

### Cloud & Deployment

- Cloudinary (Image Storage)
- Vercel (Frontend Deployment)
- Render (Backend Deployment)

## Features

### Authentication

- User Signup
- User Login
- User Logout
- JWT-Based Authentication
- Protected Routes

### User Profile

- View User Profiles
- Update Profile Information
- Upload Profile Picture
- Upload Cover Image

### Posts

- Create Posts
- Upload Images with Posts
- View Feed
- Delete Posts
- Like Posts

### Social Features

- Follow Users
- Unfollow Users
- Suggested Users to Follow
- Notifications

### UI/UX

- Responsive Design
- Mobile Friendly Layout
- Modern Social Media Interface
- Loading States
- Toast Notifications

## Challenges Solved

During development and deployment, several real-world engineering challenges were addressed:

- Cross-Origin Resource Sharing (CORS) configuration
- JWT Authentication using HTTP-only cookies
- Cookie handling across browsers
- Vercel and Render deployment setup
- React Router routing issues after deployment
- Cloudinary image upload integration
- MongoDB schema and database management

## Project Structure

frontend/
├── src/
├── components/
├── pages/
├── hooks/
└── services/

backend/
├── controllers/
├── routes/
├── middleware/
├── models/
├── database/
└── utils/

## Installation

### Clone Repository

git clone <repository-url>

### Backend Setup

cd backend

npm install

Create a .env file and add:

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

Run backend:

npm start

### Frontend Setup

cd frontend

npm install

Create a .env file and add:

VITE_API_URL=http://localhost:5000

Run frontend:

npm run dev

## Future Improvements

- Real-time messaging
- Real-time notifications
- Post comments
- Search functionality
- Bookmark posts
- User verification badges
- Infinite scrolling
- Dark/Light theme toggle

## Author

Sonu S

Built as a full-stack MERN project to strengthen practical skills in authentication, database management, API development, deployment, and modern frontend development.
