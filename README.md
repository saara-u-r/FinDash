# FinDash: Full-Stack Stock Trading Simulation Dashboard

**FinDash** is a full-stack mock trading dashboard built using **React**, **Node.js**, and **MongoDB**. It simulates the essential functionalities of a stock trading platform — allowing users to view holdings, manage orders, monitor positions, and visualize their portfolio using charts. It’s a perfect project for those looking to understand how real-time trading UIs and backend systems work.

---

## 🚀 Features

- 📊 Interactive Dashboard to view:
  - Holdings
  - Orders
  - Positions
- 💰 Trade simulation via Buy Action Window
- 📈 Portfolio breakdown using Chart.js (Doughnut chart)
- 🌐 RESTful API backend built with Express
- 🗃️ Persistent storage using MongoDB + Mongoose
- ⚛️ React Context API for global state management

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Chart.js
- Context API
- CSS Modules

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose ODM)

---

## 📁 Project Structure

| Folder/File          | Description                                      |
|----------------------|--------------------------------------------------|
| `backend/`           | Node.js + Express backend                        |
| ├── `.env`           | Environment variables (MongoDB URI, Port)        |
| ├── `index.js`       | Entry point for the backend server               |
| ├── `model/`         | Mongoose models (Holdings, Orders, Positions)    |
| └── `schemas/`       | MongoDB schema definitions                       |
| `dashboard/`         | React frontend for the trading dashboard         |
| ├── `public/`        | Static assets (HTML, logo, robots.txt)           |
| └── `src/`           | React components and global context              |
|     ├── `components/`| Dashboard UI: Holdings, Orders, Charts, etc.     |
|     ├── `index.js`   | React DOM renderer                               |
|     └── `index.css`  | Global styles                                    |

---

## 🧪 How to Run Locally

### 1. Clone the Repository
```bash```
git clone https://github.com/your-username/fin-dash.git
```bash```
cd fin-dash
### 2. Backend setup
```bash```
cd backend
```bash```
npm install
Create a .env file with the following:
MONGODB_URI=your_mongo_connection_string
PORT=5000
```bash```
npm start

### 3. Frontend Setup
```bash```
cd ../dashboard
```bash```
npm install
```bash```
npm start




