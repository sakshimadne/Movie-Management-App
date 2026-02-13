🎬 Movies App – Full Stack (MERN)
🌐 Live Application
Frontend (UI):
👉 https://movies-app-frontend-9cvq.vercel.app/
Backend (API):
👉 https://movies-app-backend-tau.vercel.app/
Base API Endpoint:
👉 https://movies-app-backend-tau.vercel.app/api/movies/

📌 Overview
Movies App is a full-stack Movie Management Application built using the MERN stack.
It provides complete CRUD functionality for managing movies, including search, filtering, and route-based modal editing.
The project follows a clean MVC architecture on the backend and a modern React + Vite setup on the frontend.

🖥 Frontend – React + Vite
🚀 Tech Stack


React 18


Vite


React Router DOM


Axios


Custom CSS


Vercel (Deployment)



🎨 Features


View movies


Search movies


Filter by genre, year, rating


Add new movie


Edit existing movie


Delete movie


Route-based modal editing (/movies/:id/edit)


Responsive UI


Hover action controls


Real-time filtering


Form validation


Error handling


Fallback image handling



📂 Frontend Project Structure
frontend/
│
├── public/
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── main.jsx
│   └── App.css
│
├── index.html
├── package.json
└── vite.config.js


⚙️ Frontend Setup (Local Development)
1️⃣ Clone Repository
git clone <your-new-merged-repo-url>
cd frontend

2️⃣ Install Dependencies
npm install

3️⃣ Start Development Server
npm run dev

App runs at:
http://localhost:5173

4️⃣ Build for Production
npm run build

5️⃣ Preview Production Build
npm run preview


🛠 Backend – Node.js + Express + MongoDB
🧰 Tech Stack


Node.js


Express.js


MongoDB


Mongoose


CORS


dotenv


Vercel (Deployment)



🏗 Backend Project Structure
backend/
│
├── config/
│   └── db.js
│
├── controllers/
│   └── movieController.js
│
├── models/
│   └── Movie.js
│
├── routes/
│   └── movies.js
│
├── .env
├── server.js
└── package.json


🧠 Architecture Pattern
The backend follows MVC architecture:


Model → Mongoose Schema


Controller → Business logic


Routes → API routing


Config → Database connection


Server → Express initialization



⚙️ Backend Setup (Local Development)
1️⃣ Navigate to Backend
cd backend

2️⃣ Install Dependencies
npm install

3️⃣ Create .env File
Create a .env file in the root of backend:
PORT=5000
MONGO_URI=your_mongodb_connection_string

⚠️ Do NOT commit .env to GitHub.
4️⃣ Run Server
npm start

Server runs at:
http://localhost:5000


📡 API Endpoints
🔹 Get All Movies
GET /api/movies

🔹 Get Single Movie
GET /api/movies/:id

🔹 Create Movie
POST /api/movies

Example Body:
{
  "name": "Inception",
  "genre": "Sci-Fi",
  "releaseYear": 2010,
  "rating": 9,
  "imageUrl": "https://image-url.jpg"
}

🔹 Update Movie
PUT /api/movies/:id

🔹 Delete Movie
DELETE /api/movies/:id


🔗 Frontend ↔ Backend Integration
The frontend consumes the deployed backend API:
https://movies-app-backend-tau.vercel.app/api/movies

Ensure API base URL is correctly configured in Axios.

🌍 Deployment
Both frontend and backend are deployed on Vercel.
🚀 Redeploy Process


Push changes to GitHub


Vercel auto-builds and deploys



🧠 Future Improvements


Authentication


Pagination


Toast notifications


Dedicated movie details page


Route-based "Add Movie" modal


Better state management (Redux / Context API)



👩‍💻 Author
Developed by Sakshi Madne

If you'd like, I can now:


Optimize this README for recruiters


Add architecture diagram


Convert it into a professional GitHub-level production README


Add badges (build status, tech stack, deployment, etc.)


Or restructure it for monorepo format


Tell me what direction you want.