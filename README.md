# HabitTrack — Daily Habit Tracker

A full-featured personal habit tracking web application built 
with HTML, CSS, JavaScript, and Firebase. HabitTrack helps 
users build consistent daily habits by tracking completion, 
visualizing progress, and providing weekly and monthly 
performance insights.

---

## 🌐 Live Demo

> Coming soon

---

## 📸 Screenshots

### Login Page
![Login](screenshots/login.png)

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Daily Habits Table
![Daily Habits](screenshots/daily-habits.png)

### Monthly Heatmap
![Heatmap](screenshots/heatmap.png)

---

## ✨ Features

### 🔐 Authentication
- **Google OAuth** — one-click sign in with Google account
- **GitHub OAuth** — sign in with GitHub account
- **Email/Password** — traditional login and registration
- **Remember Me** — persistent session across browser closes
- **Forgot Password** — Firebase password reset via email
- **Create Account** — new user registration tab
- User email displayed on dashboard after login

### 📋 Habit Management
- Add custom habits with name and emoji icon
- Manage and delete existing habits
- Supports 15+ simultaneous habits
- Each habit has unique color coding

### ✅ Daily Tracking
- Interactive checkbox grid for every day of the month
- Click any day to mark habit complete or incomplete
- Add personal notes for each day
- Notes are auto-saved locally

### 📊 Progress Visualization
- **Monthly Completion Chart** — line graph showing daily 
  completion percentage across full month
- **Weekly Overview** — breakdown by WK1 to WK5 showing:
  - DONE count
  - GOAL target  
  - LEFT remaining
  - PCT percentage completed
- **Habit Progress Sidebar** — individual progress bar 
  for every habit
- **Weekly Completion % Chart** — comparing week by week
- **Overview Progress** — donut chart showing Done vs Left

### 📅 Monthly Heatmap
- Visual calendar showing activity intensity
- Color coded days based on completion percentage
- Quick overview of best and worst performing days

### 🏆 Top Habits Ranking
- Ranks habits by completion rate
- Highlights most consistent habits

### 📤 Export and Reset
- **CSV Export** — download full month data as CSV file
- **Reset** — clear all data for fresh start
- **Dark Mode** — toggle between light and dark themes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling and responsive design |
| JavaScript | All logic and interactivity |
| Firebase Authentication | Google, GitHub, Email login |
| Firebase Firestore | Real-time habit data storage |
| Chart.js | Line graph and bar charts |
| localStorage | Auto-save daily notes |

---

## 🚀 How to Run Locally

### Prerequisites
- Modern web browser (Chrome recommended)
- Firebase account (free)
- VS Code with Live Server extension

### Steps

**1. Clone the repository**"# habit-tracker" 
