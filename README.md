# 🎬 Movie Mate — AI Movie Recommender Web App

**Movie Mate** is a full-stack movie recommendation platform that allows users to explore, save, and curate personalized movie playlists based on their mood or favorite genres. Built using **React.js**, **Node.js**, **MySQL**, and powered by the **TMDB API**, the app delivers real-time, dynamic movie suggestions with an intuitive user experience.

---

## 🚀 Features

✅ **Explore by Genre** — Get real-time recommendations across genres (Action, Comedy, Drama, etc.)  
✅ **Curate Playlists by Mood** — Create and save playlists like "Feel-Good", "Thriller Night", or "Weekend Watch"  
✅ **Add to Favorites** — Save your favorite movies for quick access  
✅ **Delete from Favorites** — Easily remove items from your saved list  
✅ **Login & Singup** — user friendly and password protected  
✅ **TMDB Integrated** — Fetches rich metadata, posters, and movie details via [The Movie Database (TMDB)](https://www.themoviedb.org/documentation/api)

---

## 🛠️ Tech Stack

| Layer        | Tech Used             |
|--------------|------------------------|
| 🌐 Frontend  | React.js, Axios, Tailwind CSS / CSS Modules |
| ⚙️ Backend   | Node.js, Express.js    |
| 💾 Database  | MySQL (with Sequelize or raw queries) |
| 🔌 API       | TMDB API               |
| ☁️ Deployment| netlify (frontend) + Render/Railway (backend & DB)

---

## 🔑 TMDB API Setup

1. Go to [https://www.themoviedb.org/settings/api](https://www.themoviedb.org/settings/api)
2. Create an account and get your **API Key (v3 auth)**
3. Add it to your backend `.env` file:

## 📁 Folder Structure

```
movie-mate/
├── client/               # React frontend
│   ├── public/
│   └── src/
│       ├── Home.js
│       ├── Playlists.js
│       ├── Favourites.js
│       ├── Signup.js
│       ├── Login.js
│       └── App.js
│       └── index.js
├── server/               # Node.js backend
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── config/
│   └── server.js
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Installation

### ✅ 1. Clone the Repository

git clone https://github.com/yourusername/movie-mate.git
cd movie-mate

---

### ✅ 2. Setup Backend (Node.js + MySQL)

cd server
npm install
```

Create a `.env` file in `server/`


> ⚠️ Make sure MySQL is running and the database `movie_mate_db` is created.

Start the backend:
npm start

### ✅ 3. Setup Frontend (React)

cd client
npm install
npm start

🧑‍💻 Author- Nandini Singh 
🔗 [GitHub](https://github.com/nandinis898)  
🧠 Passionate about full-stack dev, GenAI, and building useful tools for real users

---
📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with credit.

