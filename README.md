# 🚀 Zorvyn Fintech Dashboard

A modern, responsive financial dashboard built using **React + Material UI**, featuring role-based UI, interactive charts, and clean UI/UX.

---
## ✅ Live link
Zorvyn Fintech Dashboard Project live link- https://zorvyn-dashboard-ruddy.vercel.app/

---

## 📌 Overview

Zorvyn Dashboard is a fully responsive admin dashboard designed to manage financial data such as transactions, insights, and analytics.

It focuses on:
- Clean UI/UX
- Responsive design (mobile + desktop)
- Role-based access (Admin / Viewer)
- Modular architecture
- Light/Dark theme support

---

## ✨ Features

### 🎨 1. Modern UI Design
- Clean dark & light themes
- Gradient + glow effects (charts)
- Card-based layout

### 📱 2. Fully Responsive
- Works across:
  - Mobile 📱
  - Tablet 💻
  - Desktop 🖥️
- Sidebar auto-collapses on small screens

### 🔐 3. Role-Based UI (RBAC)
- Admin:
  - Can add transactions
  - Full access
- Viewer:
  - Read-only access

### 📊 4. Dashboard Analytics
- Summary Cards:
  - Total Balance
  - Income
  - Expenses
  - Transactions
- Revenue Line Chart (glow effect)
- Expense Pie Chart
- Insights Section

### 📋 5. Transactions Table
- Search functionality
- Filter (Income / Expense)
- Pagination
- Status color coding:
  - Completed ✅
  - Pending ⏳

### 🌙 6. Theme Toggle
- Dark mode 🌑
- Light mode ☀️
- Dynamic UI adaptation

---

## 🧠 State Management

Used **React Context API** for centralized state:

### Managed States:
- User Role (Admin / Viewer)
- Transactions Data
- Filter Type (Income / Expense)
- Derived Filtered Data

### Why Context?
- Lightweight
- No extra dependencies
- Scalable for mid-size apps

---

## 🗂️ Project Structure

src/
│
├── Dashboard/
│ ├── TopBar.jsx
│ ├── SideBar.jsx
│ ├── Header.jsx
│ ├── SummaryCards.jsx
│ ├── Charts.jsx
│ ├── Insights.jsx
│ ├── Transactions.jsx
│
├── Data/
│ └── mockData.js
│
├── context/
│ └── AppContext.jsx
│
├── Theme.js
├── App.js
└── index.js

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repo

```bash
git clone https://github.com/AswinM7-byte/financial-dashboard.git
cd zorvyn-dashboard

### 2️⃣ Install dependencies

npm install
npm start

🧩 Tech Stack
React.js ⚛️
Material UI (MUI) 🎨
Recharts 📊
Context API 🧠

🧩 Tech Stack
React.js ⚛️
Material UI (MUI) 🎨
Nivo 📊
Context API 🧠

🔍 Attention to Detail
Light mode text visibility fixed
Hover states for charts
Sidebar responsiveness
Button access control (RBAC)
Smooth spacing & alignment
Export CSV functionality
Clean typography

🚀 Future Improvements
API integration (replace mock data)
Authentication system
Advanced filters
Animations (Framer Motion)

