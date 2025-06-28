# Locked In – Personal Fitness Companion

Locked In is a full-stack MERN (MongoDB, Express, React, Node.js) fitness web application designed to help users track workouts, calculate BMR, analyze nutrition, and more through an intuitive interface.

## 🚀 Features

- 🧠 AI-powered nutrition checker and workout database
- 📊 BMR Calculator to determine your Basal Metabolic Rate
- 🔐 Authentication using JWT and secure cookies
- 🏋️ Workout Planner and meal plan management
- 📱 Responsive design with React + Bootstrap
- 📈 Redux Toolkit for state management

## 📂 Project Structure

```
.
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── config
├── frontend
│   ├── components
│   ├── pages
│   └── assets
├── .env
└── package.json
```

## ⚙️ Installation & Setup

### Backend

```bash
cd backend
npm install
npm run server
```

### Frontend

```bash
cd frontend
npm install
npm start
```

> Ensure MongoDB is running locally or update your MONGO_URI in `.env`.

## 🌐 Deployment

To deploy in production:

```bash
cd backend
npm run build
```

Then host using platforms like Render, Vercel, Netlify, etc.

## 🔐 Environment Variables

Create a `.env` file in the backend root with:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

## 👨‍💻 Author

Made with ❤️ by [Your Name]

## 📜 License

This project is licensed under the MIT License.
