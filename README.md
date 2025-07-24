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
FinDash/
├── backend/
│ ├── .env
│ ├── index.js
│ ├── package.json
│ ├── model/
│ │ ├── HoldingsModel.js
│ │ ├── OrdersModel.js
│ │ └── PositionsModel.js
│ └── schemas/
│ ├── HoldingsSchema.js
│ ├── OrdersSchema.js
│ └── PositionsSchema.js
├── dashboard/
│ ├── package.json
│ ├── public/
│ │ ├── index.html
│ │ ├── logo.png
│ │ └── robots.txt
│ └── src/
│ ├── index.js
│ ├── index.css
│ └── components/
│ ├── Apps.js
│ ├── BuyActionWindow.js
│ ├── BuyActionWindow.css
│ ├── Dashboard.js
│ ├── DoughnutChart.js
│ ├── Funds.js
│ ├── GeneralContext.js
│ ├── Holdings.js
│ ├── Home.js
│ ├── Menu.js
│ ├── Orders.js
│ └── Positions.js


---

## 🧪 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/fin-dash.git
cd fin-dash

### 2. Backend setup
cd backend
npm install
# Create a .env file with:
# MONGODB_URI=your_mongo_connection_string
# PORT=5000
npm start

### 3. Frontend Setup
cd ../dashboard
npm install
npm start

##✨ Future Improvements
🔒 User authentication (login/signup)

📡 Real-time stock price updates using WebSockets or third-party APIs

📈 Integration with live market data (e.g., Yahoo Finance or NSE APIs)

📊 More advanced analytics and trade history


