# 🌍 Living Itinerary

A *real-time interactive travel itinerary planner* that helps users create, update, and share travel plans dynamically. It integrates live data from APIs (Weather, Google Maps, Eventbrite, etc.) and allows collaborative planning with friends.

## ✨ Features
- 🗺 Interactive trip planning with live updates
- 🌦 Real-time weather integration
- 📍 Google Maps for navigation & places
- 🎉 Eventbrite API for discovering local events
- 👥 Multi-user collaboration with Socket.IO
- 🚀 Live deployment support (Heroku / Vercel / AWS)

## 🛠 Tech Stack
- *Frontend:* HTML, CSS, JavaScript
- *Backend:* Node.js + Express
- *Realtime:* Socket.IO
- *Database (optional):* Firebase / MongoDB
- *APIs Integrated:*
    - OpenWeather API (Weather data)
    - Google Maps API (Maps & directions)
    - Eventbrite API (Events)

## 📂 Project Structure
    Living-Itinerary/
    ├── public/              # Frontend files (HTML, CSS, JS)
    ├── server.js            # Express + Socket.IO backend
    ├── package.json         # Dependencies & scripts
    ├── .env                 # API keys & environment variables (ignored in git)
    └── README.md            # Documentation

## ⚡ Getting Started

### 1️⃣ Clone the repo
    git clone https://github.com/your-username/living-itinerary.git
    cd living-itinerary

### 2️⃣ Install dependencies
    npm install

### 3️⃣ Setup environment variables
Create a `.env` file in the project root and add:

    PORT=3000
    OPENWEATHER_API=your_api_key
    GOOGLE_MAPS_API=your_api_key
    EVENTBRITE_API=your_api_key

> ⚠️ Do NOT commit your `.env` file. Add it to `.gitignore`.

### 4️⃣ Run the server
    npm start

App will run at: http://localhost:3000 🚀

## 🌐 Deployment
You can deploy this project to:
- Heroku
- Vercel
- AWS (Elastic Beanstalk / EC2 / Amplify)

> Tip: For production, set your environment variables in the hosting platform's settings and enable HTTPS.

## 🧩 Notes & Tips
- Use Socket.IO rooms to separate different trip sessions for collaboration.
- Cache API responses where appropriate to avoid hitting rate limits (especially Google Maps / Eventbrite).
- Secure API keys: restrict keys to your domains and restrict quotas in the provider console.
- Consider using MongoDB/Firebase for persisting itineraries, users, and comments.

## 👥 Contributors
- **Jayesh Khandelwal** – Full Stack Development  
- **Srushti Panara** – API Integrations  
- **Mugdha Phalak** – Frontend Design  
- **Tanmay Pokale** – Backend & Database

## ✅ License
This project is licensed under the **MIT License**. Feel free to use, modify, and distribute.

---
