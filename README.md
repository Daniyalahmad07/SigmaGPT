# 🤖 SigmaGPT

SigmaGPT is a full-stack AI chat application inspired by ChatGPT.  
It supports multi-threaded conversations, persistent chat history, and real-time AI responses using a modern MERN-based architecture.

---

## 🚀 Live Demo

**Frontend (User Interface):**  
🔗 https://sigmagpt-frontend-mxuw.onrender.com

> ⚠️ Note: On the free hosting tier, the backend may take 30–50 seconds to respond on the first request due to cold starts.

---

## 🧠 Features

- 💬 AI-powered chat interface
- 🧵 Multiple conversation threads
- 💾 Persistent chat history using MongoDB
- ⚡ Real-time responses
- 🌐 Fully deployed (Frontend + Backend)
- 🔐 Secure environment variable handling
- 📱 Clean and responsive UI

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- JavaScript (ES6+)
- CSS
- React Context API
- Fetch API

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- REST APIs
- OpenAI API

### Deployment
- Frontend: Render (Static Site)
- Backend: Render (Web Service)
- Database: MongoDB Atlas

---

## 📂 Project Structure

SigmaGPT/
│
├── Frontend/
│ ├── src/
│ ├── public/
│ ├── .env
│ └── package.json
│
├── Backend/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── server.js
│ └── package.json
│
└── README.md

yaml
Copy code

---

## ⚙️ Environment Variables

### Backend (`Backend/.env`)
MONGODB_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key

shell
Copy code

### Frontend (`Frontend/.env`)
VITE_API_URL=http://localhost:8080

yaml
Copy code

> In production, environment variables are securely managed via Render.

---

## ▶️ Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Daniyalahmad07/SigmaGPT.git
cd SigmaGPT
2️⃣ Start Backend
bash
Copy code
cd Backend
npm install
node server.js
Backend runs at:

arduino
Copy code
http://localhost:8080
3️⃣ Start Frontend
Open a new terminal:

bash
Copy code
cd Frontend
npm install
npm run dev
Frontend runs at:

arduino
Copy code
http://localhost:5173
🌍 Deployment Workflow
Push code to GitHub

Render automatically builds & deploys

Frontend and backend are deployed independently

Environment variables are managed via Render Dashboard

🔐 Security Notes
.env files containing secrets are never exposed in production

API keys are securely stored using Render Environment Variables

MongoDB access is restricted via Atlas configuration

📈 Future Improvements
User authentication (Login / Signup)

Chat export feature

Rate limiting & usage analytics

UI enhancements & animations

Dark / Light mode toggle

👨‍💻 Author
Daniyal Ahmad
Built with ❤️ as a full-stack learning project.

⭐ Acknowledgements
OpenAI for the AI API

Render for deployment

MongoDB Atlas for database hosting

📜 License
This project is for educational and learning purposes.
