# 📸 InstaClone – MERN Stack Instagram-Style App

Welcome to *InstaClone, a fully functional and responsive **Instagram-style web app* built using the *MERN Stack* — MongoDB, Express.js, React.js, and Node.js. The platform supports *user authentication, **image sharing, **likes, **comments, **profile management, and **Cloudinary-powered uploads*.

---

## 🌐 Live Demo

🚀 [*Click to Visit the Live Website*](https://end-to-end-intagram-clone-website.onrender.com)  

---

## 📸 Preview

> - Login Page
> - ![Screenshot_25-6-2025_18465_end-to-end-intagram-clone-website onrender com](https://github.com/user-attachments/assets/926bcf92-83f5-449b-9c6f-b481fea00c9e)
> - Home Feed
> - ![Screenshot_25-6-2025_184524_end-to-end-intagram-clone-website onrender com](https://github.com/user-attachments/assets/7d2cd6db-fd52-4cd1-a1dd-60d8d0827b2a)
> - Post Creation
> - ![Screenshot_25-6-2025_184749_end-to-end-intagram-clone-website onrender com](https://github.com/user-attachments/assets/983b7416-71bb-4665-ae50-5dda6b2db9cc)
> - Profile Page
> - ![Screenshot_25-6-2025_184552_end-to-end-intagram-clone-website onrender com](https://github.com/user-attachments/assets/ca4d86dd-32ea-43bb-ab1b-5f02d50b97da)
---

## 📚 How It Works – Feature Walkthrough

### 👤 1. *User Authentication*
- Users can *sign up* and *log in* securely
- Passwords are hashed with *bcrypt*
- Authenticated sessions maintained using *JWT tokens* stored in localStorage

---

### 🖼 2. *Image Upload & Posting*
- Users can upload posts with *captions* and *images*
- Images are uploaded directly to *Cloudinary*
- Post appears in the global feed and user profile

> 🔧 Tech: React Form ➜ Cloudinary ➜ MongoDB ➜ Displayed via API

---

### ❤ 3. *Likes & Comments*
- Authenticated users can *like or unlike* posts
- Users can *comment* on posts
- Real-time UI updates without needing to refresh

---

### 🙍‍♂ 4. *User Profile*
- View all your posts, bio, and profile picture
- *Edit your bio or profile image* anytime
- View other users' public profiles too

---

## 🛠 Technologies Used

| Module         | Tools / Libraries                                   |
|----------------|-----------------------------------------------------|
| *Frontend*   | React.js, Axios, React Router, CSS Modules / Tailwind |
| *Backend*    | Node.js, Express.js                                 |
| *Database*   | MongoDB Atlas, Mongoose                             |
| *Authentication* | JWT, bcrypt                                     |
| *Image Upload* | Cloudinary API                                    |

---

## ⚙ Setup & Installation

### 📝 Prerequisites
- Node.js installed (v16+)
- MongoDB Atlas account
- Cloudinary account
- Git installed

- ### 🛠 Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `backend` directory and add:
   ```env
   MONGO_URI=your_mongodb_atlas_connection_string
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   URL=your_deployed_website_link
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### 🌐 Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `frontend` directory and add:
   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   ```
4. Start the frontend development server:
   ```bash
   npm start
   ```

### 🚀 Running the Application
- Ensure MongoDB Atlas and Cloudinary are configured.
- Run both backend and frontend servers.
- Open `http://localhost:3000` in your browser to view the app.

---

## 📂 Project Structure

```
JobPortal-WebD/
├── backend/                # Node.js + Express.js server
│   ├── models/             # Mongoose schemas
│   ├── routes/             # API routes
│   ├── controllers/        # Request handlers
│   ├── middleware/         # Authentication & error handling
│   └── .env                # Environment variables
├── frontend/               # React.js frontend
│   ├── src/                # React components, pages, and assets
│   ├── public/             # Static assets
│   └── .env                # Frontend environment variables
├── README.md               # Project documentation
└── package.json            # Project metadata and scripts
```

---
