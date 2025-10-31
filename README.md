# 🌴 LagawTaDi

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)

---

**LagawTaDi** (Hiligaynon for *“Let’s Go Travel!”*) is a **MERN stack web app** that helps locals and tourists explore the best of **Bacolod City** — from famous landmarks and hidden gems to local cuisine and cultural experiences.

---

## 🚀 Mission
To make exploring Bacolod City easier, smarter, and more enjoyable by providing tourists and locals with a digital guide to discover top attractions, hidden gems, and cultural experiences — all in one interactive platform.

---

## 🧩 Features
- 🗺️ Explore top-rated tourist spots and attractions  
- 🔍 Smart search and category filters  
- ⭐ User reviews and ratings  
- ❤️ Save favorite destinations  
- 📱 Mobile-responsive interface  
- ⚡ Built with the MERN stack (MongoDB, Express, React, Node.js)

---

## 🏗️ Tech Stack
| Layer | Technology |
|-------|-------------|
| Frontend | React, TailwindCSS, Vite |
| Backend | Node.js, Express |
| Database | MongoDB Atlas |
| Hosting | Vercel / Render / Netlify |
| Version Control | GitHub |

---

## 🧱 Database Schema Overview
```text
User
 ├─ name, email, password, favorites[]
 └─ hasMany → Reviews

TouristSpot
 ├─ name, description, category, location, images[]
 └─ hasMany → Reviews

Review
 ├─ userId, spotId, rating, comment
```

---

## 🛠️ Installation
```bash
# Clone repository
<<<<<<< HEAD
<<<<<<< HEAD
git clone https://github.com/Mooyi07/LagawTaDi.git
=======
git clone https://github.com/<your-username>/LagawTaDi.git
>>>>>>> ad09344 (Update README.md)
=======
git clone https://github.com/Mooyi07/LagawTaDi.git
>>>>>>> fa8fae5 (Update README.md)

# Go into project folder
cd LagawTaDi/frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

---

## 🤝 Contributing
1. Fork the project  
2. Create your feature branch (`git checkout -b feature/your-feature`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to the branch (`git push origin feature/your-feature`)  
5. Open a Pull Request  

---

## 📍 Project Status
🚧 *In Development* — LagawTaDi is currently under active development. Stay tuned for updates!

---

## 📜 License
This project is licensed under the **MIT License**.

---

### ❤️ Built with pride in Bacolod City
> “LagawTaDi — Explore. Discover. Experience Bacolod.”