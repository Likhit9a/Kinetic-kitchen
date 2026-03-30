# 🍽️ Kinetic Kitchen

AI-Powered Nutrition & Fitness Tracker

## ✨ Features
- 📊 Dashboard with calorie/protein goal tracking & charts
- 🥗 Meal logging with food search (Open Food Facts) & saved templates
- 💪 Workout logging with 20-exercise library & auto calorie estimation
- 💾 SQLite database — data persists across restarts
- 🌗 Auto dark/light mode (follows system preference)
- 🔔 Toast notifications

## 🚀 How to Run

### Step 1 — Install Dependencies

Open TWO PowerShell windows in the `kk` folder.

**Window 1 (Backend):**
```
cd backend
npm install
```

**Window 2 (Frontend):**
```
cd frontend
npm install
```

### Step 2 — Start the App

**Window 1:**
```
npm run dev
```
→ Backend runs at http://localhost:5000

**Window 2:**
```
npm run dev
```
→ Frontend runs at http://localhost:5173

### Step 3 — Open Browser
Go to: **http://localhost:5173**

## 📁 Structure
```
kk/
├── backend/
│   ├── src/
│   │   ├── server.js    # Express API
│   │   └── db.js        # SQLite setup
│   ├── .env
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── pages/       # Dashboard, Meals, Workouts, Login, Register
│   │   ├── components/  # Layout
│   │   └── context/     # Auth, Toast, Theme
│   ├── .env
│   └── package.json
└── README.md
```
