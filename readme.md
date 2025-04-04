# 🚀 AstroHunt - Space Treasure Hunt

**An immersive space-themed treasure hunt created by [Antriksh Club](https://www.linkedin.com/company/antrikshnitkkr/) for Techspardha '24 at NIT Kurukshetra.**

[🔗 Live Demo](https://frontend-antariksh.vercel.app/)

---

## 🌟 Features

- 🎮 **Multi-level puzzle-based gameplay**
- 🤝 **Team-based competition system**
- 🔐 **Progressive level unlocking**
- 💡 **Strategic hint system**
- 📊 **Real-time leaderboard**
- 👑 **Admin dashboard for game management**
- 🎨 **Space-themed interactive UI**
- 🔒 **Secure authentication system**

---

## 🛠️ Tech Stack

### 🚀 Frontend
- React.js
- TailwindCSS
- Framer Motion
- Axios
- React Router DOM

### 🛰️ Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Cloudinary (for image storage)

---

## ⚙️ Getting Started

### 📋 Prerequisites

- Node.js (v14+)
- MongoDB
- npm or yarn

---

### 🧩 Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/ShivamPratap16/AstronhuntGame.git
cd astrohunt
```

#### 2. Install Backend Dependencies

```bash
cd Backend
npm install
```

#### 3. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

#### 4. Setup Environment Variables

Create `.env` files in both `frontend` and `Backend` directories with the necessary configuration keys:

<details>
<summary>Sample <code>.env</code> entries (click to expand)</summary>

```env
# Backend (.env)
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

# Frontend (.env)
VITE_API_BASE_URL=http://localhost:5000
```

</details>

---

### 🚀 Run the Application

#### Start Backend

```bash
cd Backend
npm start
```

#### Start Frontend

```bash
cd ../frontend
npm start
```

---

## 🎮 Game Rules

1. Form a team or play solo.
2. Start at **Level 1**.
3. Solve space-themed **riddles and puzzles** to progress.
4. Use **hints** wisely — point deductions apply!
5. Climb the **leaderboard** by completing levels fastest.

---

## 👥 Contributing

We welcome contributions!

- Fork the repo
- Create a new branch (`git checkout -b feature-name`)
- Commit your changes
- Push to the branch (`git push origin feature-name`)
- Open a Pull Request

> For major changes, please open an issue to discuss the proposal first.

---



