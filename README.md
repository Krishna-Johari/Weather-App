🌦️ Weather App

A full-stack weather application built with React and Express that displays real-time temperature, humidity, and wind data using the OpenWeather API.

## 📸 Preview

![Weather App](./assets/preview.png)

⚙️ Tech Stack
Frontend: React (Vite)
Backend: Node.js + Express
API: OpenWeather API

🚀 How to Run the Project
🔹 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/weather-app.git
cd weather-app

🔹 2. Backend Setup
cd backend
npm install
npm run start

👉 Backend runs on:
http://localhost:5000

🔹 3. Frontend Setup
Open new terminal:
cd frontend
npm install
npm run dev

👉 Frontend runs on:
http://localhost:5173

🔐 Environment Variables
Create a .env file inside the backend folder:
OPENWEATHER_API_KEY=YOUR_API_KEY
PORT=5000

📁 Project Structure
weather-app/
 ├── backend/
 ├── frontend/
 ├── README.md

⚠️ Note
.env file is not included in the repository
Replace YOUR_API_KEY with your OpenWeather API key
Country-level search may not always return accurate results

✨ Features
Search weather by city
Displays temperature, humidity, and wind speed
Clean UI with weather icons