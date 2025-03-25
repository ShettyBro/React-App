# Auth Main Project

This repository contains a full-stack authentication system built using **Node.js, Express.js, MongoDB, and React**.

## 📂 Project Structure
```
/auth-main
│── backend/                 # Node.js & Express backend
│   ├── Config/              # Database configuration
│   ├── controllers/         # Authentication controllers
│   ├── middlewares/         # Middleware for authentication
│   ├── models/              # Mongoose models
│   ├── routes/              # API routes
│   ├── server.js            # Main server file
│   ├── .env                 # Environment variables (Not committed)
│── frontend/                # React frontend
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── pages/           # Application pages
│   │   ├── App.js           # Main React app
│   │   ├── index.js         # Entry point
│   ├── public/              # Static files
│   ├── package.json         # Frontend dependencies
│── README.md                # Project documentation
│── .gitignore               # Files to ignore in Git
```

## 🚀 Setup Instructions
### Backend Setup (Node.js & Express)
1. Navigate to the `backend/` folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up the `.env` file with necessary configurations.
4. Start the backend server:
   ```sh
   npm start
   ```
   Or using **nodemon**:
   ```sh
   npm run dev
   ```

### Frontend Setup (React)
1. Navigate to the `frontend/` folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm start
   ```
   Or, if using **Vite**:
   ```sh
   npm run dev
   ```

## 📌 Features
✅ User Authentication (Login, Register, Logout)  
✅ JWT-based authentication  
✅ Protected Routes  
✅ Responsive UI with React  

## 🔧 Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT (JSON Web Tokens)

---
🚀 Happy Coding! 🎉
