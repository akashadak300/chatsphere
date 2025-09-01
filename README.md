# 💬 Chatsphere

Chatsphere is a **real-time chat application** built with the **MERN stack** (MongoDB, Express.js, React, Node.js) and **Socket.IO** for instant messaging.  
It supports **user authentication, persistent sessions, and live communication** with a clean modern UI powered by **TailwindCSS + DaisyUI**.

---

## ✨ Features
- 🔐 **User Authentication** (JWT + bcrypt.js)
- 💬 **Real-time messaging** using Socket.IO
- 🗂️ **Persistent Redux Store** with Redux Toolkit + Redux Persist
- 🎨 **Responsive UI** with TailwindCSS & DaisyUI
- 📌 **Toast notifications** for user feedback
- 🌐 **REST API backend** with Express & MongoDB
- ⚡ **Optimized for production** build and deployment

---

## 🛠️ Tech Stack

**Frontend**
- React 18, React Router DOM
- Redux Toolkit + Redux Persist
- Axios, React Hot Toast, React Icons
- TailwindCSS, DaisyUI

**Backend**
- Node.js + Express.js
- MongoDB + Mongoose
- Socket.IO
- JWT Authentication + bcrypt.js
- CORS, dotenv, cookie-parser

---

## 📂 Project Structure

```
Chatsphere/
├── frontend/       # React client
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/        # Express + MongoDB server
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── index.js
│   └── package.json
│
├── README.md
└── ...
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/akashadak300/chatsphere.git
cd Chatsphere
```

### 2️⃣ Setup Backend
```bash
cd backend
npm install
```

Create a `.env` file in the **backend** folder:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Run the backend:
```bash
npm run dev
```

### 3️⃣ Setup Frontend
```bash
cd ../frontend
npm install
```

Start the frontend:
```bash
npm start
```

Now the app runs on:
- Frontend → `http://localhost:3000`
- Backend → `http://localhost:5000`

---

## 🚀 Deployment

### 🔹 Frontend (Vercel/Netlify)
1. Build the React app:
   ```bash
   npm run build
   ```
2. Deploy the `build/` folder to Vercel/Netlify.

### 🔹 Backend (Render/Heroku)
1. Push backend code to GitHub.
2. Connect repository to **Render** or **Heroku**.
3. Add environment variables (`MONGO_URI`, `JWT_SECRET`, `PORT`).
4. Deploy and get a live API URL.

### 🔹 Update Frontend
Change Axios base URL in frontend to point to deployed backend.

---

## 📜 Scripts

**Frontend**
- `npm start` → Run development server  
- `npm run build` → Build production bundle  
- `npm test` → Run tests  

**Backend**
- `npm run dev` → Run with Nodemon  
- `npm start` → Start server normally  
- `npm run build` → Install dependencies  

---

## 🤝 Contributing
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Added feature"`)  
4. Push branch (`git push origin feature-name`)  
5. Create a Pull Request 🎉  

---


## 👨‍💻 Author
Developed with ❤️ by **Akash Adak**
