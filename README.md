# NEXUS - AI Digital Twin (Frontend)

The official interactive web interface for **NEXUS**, the AI Digital Twin and career 
assistant representing **Manas Ranjan Sahoo**. This frontend is built with **React** 
and **Vite**, featuring real-time markdown rendering, session history management, 
and a clean, responsive chat experience communicating with the FastAPI backend.

---

## 🚀 Tech Stack

* **Framework:** React (Vite)
* **Styling:** Custom CSS
* **Markdown Rendering:** `react-markdown`
* **Communication:** REST API via Fetch

---

## 📁 Project Structure

```text
chat-with-nexus/
├── public/              # Static assets & icons
├── src/
│   ├── assets/          # Images and vector graphics
│   ├── App.jsx          # Core chat interface and state management logic
│   ├── App.css          # Styling for container, bubbles, and typing indicators
│   ├── index.css        # Global styles
│   └── main.jsx         # React application entry point
├── .env                 # Environment variables configuration
├── index.html           # HTML root template
├── package.json         # Dependencies and scripts
└── vite.config.js       # Vite configuration
```

## ⚙️ Getting Started
* **Prerequisites**
Make sure you have Node.js (v18+) and npm installed on your machine.

1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/chat-with-nexus.git](https://github.com/YOUR_USERNAME/chat-with-nexus.git)
cd chat-with-nexus
```
2. Install Dependencies
```bash
npm install
```

3. Configure Environment Variables
Create a .env file in the root directory of the project and define your backend API base URL:
```Code snippet
VITE_API_URL=http://localhost:8000
```

4. Run the Development Server
```Bash
npm run dev
```
Open your browser and navigate to the local development URL provided by Vite (typically http://localhost:5173).

## 🔗 Backend Integration
This frontend acts as a headless client interface. It requires the accompanying ChatWithManas FastAPI backend service (powered by LangGraph, Pinecone, and Google Gemini RAG) to be running concurrently.

- Ensure your backend CORS configuration permits requests from your frontend origin (http://localhost:5173).

## 📄 License
This project is open-source and created for professional portfolio demonstration purposes.
