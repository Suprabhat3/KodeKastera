# 🔥 KodeKshetra

**KodeKshetra** is a DSA (Data Structures & Algorithms) problem-solving platform that helps developers improve their coding skills through structured challenges, real-time progress tracking, and collaborative learning. Built with a powerful tech stack and a bold mission — to make DSA fun, focused, and effective.

---

## 🧠 About the Project

KodeKshetra provides a focused environment to:
- 🧩 Solve DSA problems categorized by topic and difficulty
- 📈 Track your progress and performance over time
- 💬 Collaborate and discuss problems with peers
- 🏆 Join challenges and climb the leaderboard *(coming soon)*

---

## ⚙️ Tech Stack

| Layer      | Tech        |
|------------|-------------|
| Frontend   | React.js, Tailwind CSS |
| Backend    | Node.js, Express.js    |
| Database   | PostgreSQL             |
| ORM        | Prisma ORM             |
| Auth       | JWT / Auth0 *(optional)* |
| Hosting    | Not diside yet |

---

## 📦 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/Suprabhat3/kodekshetra.git
cd kodekshetra
```

### 2. Install dependencies

**Backend**
```bash
cd server
npm install
```

**Frontend**
```bash
cd ../client
npm install
```

### 3. Set up the database

Make sure PostgreSQL is running.

Create a `.env` file inside the `server` folder and add:

```env
DATABASE_URL="postgresql://username:password@localhost:5432/kodekshetra"
PORT=5000
JWT_SECRET=your_jwt_secret
```

Run Prisma migrations:

```bash
npx prisma migrate dev --name init
npx prisma generate
```

---

## ▶️ Running the App

**Backend:**
```bash
cd server
npm run dev
```

**Frontend:**
```bash
cd client
npm start
```

App should now be live at `http://localhost:5000`

---

## 📸 Preview

> ![KodeKshetra Logo](./assets/logo.png)  
> *"Solve DSA, Build Skills."*

---

## 🚧 Folder Structure

```
kodekshetra/
├── frontend/         # React Frontend
│   └── assets/
│   └── src/
├── backend/  
│   ├── prisma/ 
│   └── src/
│   ├── .env/ 
│   └── nodemodule/
└── README.md
```

## 📜 License

MIT License  
© 2025 [Suprabhat / Team KodeKshetra]

---

## ❤️ Credits

- Prisma & PostgreSQL for the robust backend
- React + Tailwind for sleek UI
- OpenAI for idea shaping
- Judge0 for Code execution
- DSA communities for inspiration

---

**KodeKshetra – Solve DSA, Build Skills.**
