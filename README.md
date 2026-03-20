# 🚦 Indore Route Pathfinder – Optimized Travel Route Adviser

A full-stack navigation web application to plan optimal routes between transit stations in Indore using Dijkstra's Algorithm — optimized for both shortest distance and minimum cost.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## 🚀 Live Demo

🔗 [https://indore-metro.vercel.app](https://indore-metro.vercel.app)

---

## ✨ What It Does

- 📍 **Add Stations:** Create new stations/locations across the city
- 🔗 **Connect Stations:** Link stations with distance (km) and cost (₹)
- 🧭 **Find Routes:** Calculate shortest path by distance OR cheapest path by cost
- 📊 **View All:** See all stations and connections in one place
- ↔️ **Bidirectional Connectivity:** All connections work in both directions

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js, Vite, React Flow |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Algorithm | Dijkstra's Shortest Path |

---

## ⚡ Performance Highlights

- Implements **Dijkstra's algorithm** across **25+ transit stations**
- **10+ RESTful API endpoints** with **350ms average response time**
- **20+ automated deployments** with modular backend architecture
- Supports both **distance** and **cost** optimization in a single system

---

## 🧩 System Architecture

- Graph-based station and connection model stored in MongoDB
- Dijkstra's algorithm runs server-side for accurate route computation
- Modular backend with separate routes, controllers, and utility functions
- React Flow used for interactive visual graph representation

---

## 📂 Project Structure

```
indore-route-pathfinder/
├── frontend/           # React + Vite app
│   ├── src/
│   │   └── App.jsx     # Main component
│   └── package.json
├── backend/            # Express API
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API routes
│   ├── controllers/    # Business logic
│   ├── utils/          # Dijkstra algorithm
│   └── server.js       # Main server
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/pariharsakshi10/indore-route-pathfinder.git
cd indore-route-pathfinder
```

### 2️⃣ Install dependencies
```bash
# Backend
cd backend && npm install

# Frontend
cd ../frontend && npm install
```

### 3️⃣ Setup environment variables
Create a `.env` file in the backend folder:
```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4️⃣ Run the application
```bash
# Start backend (Terminal 1)
cd backend && npm run dev

# Start frontend (Terminal 2)
cd frontend && npm run dev
```

Open `http://localhost:3000` 🎉

---

## 🎯 How to Use

1. **Add Stations:** Enter station name and click "Add Station"
2. **Connect Stations:** Select two stations, enter distance (km) and cost (₹), click "Add Connection"
3. **Find Route:** Choose start/end stations, select "Distance" or "Cost" optimization, click "Find Route"
4. **View Results:** See the optimal path with total distance and cost

---

## 🔌 API Endpoints

```
GET    /api/stations       # Get all stations
POST   /api/stations       # Add new station
GET    /api/connections    # Get all connections
POST   /api/connections    # Add new connection
POST   /api/route          # Calculate optimal route
```

---

## 🧮 Algorithm

Uses **Dijkstra's Algorithm** to find:
- 📏 **Shortest Distance:** Minimum total kilometers between stations
- 💰 **Cheapest Cost:** Minimum total fare in rupees

---

## 🚀 Deployment

- **Frontend:** Vercel → [https://indore-metro.vercel.app](https://indore-metro.vercel.app)
- **Backend:** Render → [https://indore-metro.onrender.com](https://indore-metro.onrender.com)
- Set environment variables in respective deployment platforms

---

## 🤝 Contributing

1. Fork the repository
2. Create feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push branch: `git push origin feature-name`
5. Open Pull Request

---

## 📬 Contact

**Sakshi Parihar**
- 📧 Email: pariharsakshi10@gmail.com
- 💻 GitHub: [@pariharsakshi10](https://github.com/pariharsakshi)
- 🔗 LinkedIn: [Sakshi Parihar](https://www.linkedin.com/in/sakshi-parihar-ba377a279/)

---

## 📄 License

MIT License — feel free to use this project!
