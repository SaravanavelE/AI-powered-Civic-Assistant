# AI Civic & Scholarship Assistant

An AI-powered, voice-ready civic assistant that helps users understand eligibility and access public schemes such as scholarships through simple conversational interaction.

Built as a full-stack prototype using FastAPI, Google Gemini API, and AWS-ready frontend deployment.

---

## 🚀 Problem Statement

Access to government schemes and scholarships is often limited by:
- Complex eligibility rules
- Language barriers
- Low digital literacy
- Fragmented information sources

This solution provides a conversational AI assistant that:
- Understands user queries
- Asks clarifying questions
- Evaluates eligibility
- Explains results clearly
- Provides step-by-step application guidance

---

## 🧠 Key Features

- Conversational AI interface
- Scholarship eligibility evaluation
- Step-by-step guidance
- Explainable AI responses
- Backend-controlled prompt logic
- AWS S3–ready frontend hosting
- Scalable architecture for future expansion

---

## 🏗️ System Architecture
User (Browser)

↓

Frontend (HTML/CSS/JS)
↓

Backend API (FastAPI)
↓

Google Gemini LLM
↓

Structured Response


---

## 📂 Project Structure
ai-civic-fullstack/

│

├── backend/

│ ├── main.py

│ ├── requirements.txt

│ └── .env

│

└── frontend/

├── index.html

├── style.css

└── script.js

---

## ⚙️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- FastAPI
- Uvicorn

### AI
- Google Gemini API
- Prompt Engineering

### Cloud
- AWS S3 (Static Hosting Ready)

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/SaravanavelE/AI-powered-Civic-Assistant
cd ai-civic-fullstack
```
### 2️⃣ Backend Setup
cd backend
```
pip install -r requirements.txt
```

Create .env file:

GEMINI_API_KEY=your_api_key_here

Run the server:
```
uvicorn main:app --reload
```
Server runs at:
```
http://127.0.0.1:8000
```
### 3️⃣ Frontend Setup

Open:

frontend/index.html

in your browser.

Make sure backend is running.

🧪 Example Usage

User Input:

Am I eligible for PMSS scholarship?

System:

Asks age

Asks income

Evaluates eligibility

Provides required documents

Provides application steps

## 📈 Future Enhancements
- Multi-language support
- Voice input integration
- Real government scheme database integration
- Cloud backend deployment (AWS EC2 / Render)
- Role-based user personalization
- NGO / Public Service dashboard
