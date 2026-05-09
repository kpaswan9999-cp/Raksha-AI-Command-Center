# 🛡️ Raksha AI — National Emergency Command Center
# Live link: https://raksha-ai-command-center.vercel.app
## Protecting Every Citizen, Speaking Every Language.
## Because in an emergency, every second—and every word—matters.
<img width="1330" height="742" alt="Screenshot 2026-05-08 042616" src="https://github.com/user-attachments/assets/cbb71832-b868-43b1-a244-c7c61679f36f" />

### Raksha AI is an intelligent, multilingual emergency response ecosystem designed to bridge the gap between distress and dispatch. It transforms standard voice calls into real-time tactical data using advanced Neural Speech Processing and Sentiment Analysis.

##  Key Features
- **Multilingual Neural Engine:** Real-time transcription and translation for Hindi, Kannada, Marathi, and Hinglish.
- **Sentiment & Panic Analysis:** AI-driven emotion detection to quantify caller distress and prioritize high-risk cases.
- **Tactical Command Dashboard:** High-fidelity HUD featuring live geolocation tracking and mission alerts.
- **Telephony Integration:** Seamless voice-to-data pipeline built on Twilio infrastructure.
- **Human-in-the-Loop:** Designed to empower agents with AI-generated summaries and actionable insights.

##  Technology Stack
- **Frontend:** React, Tailwind CSS, Framer Motion (Strategic HUD UI)
- **Backend:** FastAPI, Python (Neural Processing Layer)
- **Voice AI:** Deepgram / Whisper (Multilingual STT)
- **Communications:** Twilio Programmable Voice & Webhooks
- **Database:** SQLite / PostgreSQL (Mission Persistence)


##  Our Mission
### In a diverse nation like India, reaching for help should never be a struggle of language or technology. Raksha AI is more than just a dashboard; it’s a smart bridge between women in distress and the help they need. We’ve built a system that listens, understands, and acts instantly—no matter which language you speak or how much panic is in your voic

##  How We’re Changing the Game
### We Speak Your Language: From the heart of North India to the streets of Bangalore, our system instantly understands Hindi, Kannada, Marathi, and 'Hinglish'. No more translation delays when lives are on the line.
### We Hear the Unspoken: Our AI doesn't just read words; it senses the urgency. By analyzing the emotional tone and panic levels of a caller, we help responders prioritize those in the most immediate danger.
### The Tactical Edge: We’ve given emergency agents a "Command Center" view. Within seconds, they see the caller’s exact location, a live transcription, and an AI-generated summary of the situation.

##  The Tech Behind the Shield
###  We chose our tools to ensure speed, stability, and a premium experience:

### The Interface: Crafted with React and Framer Motion to create a high-stakes, "National Command Center" feel that keeps agents focused and calm.
### The Brain: A Python (FastAPI) backend that handles the heavy lifting of speech processing and intent analysis.
### The Voice: Powered by Deepgram and Whisper for world-class multilingual accuracy.
### The Connection: Twilio’s robust telephony infrastructure handles the real-world voice calls.
### Built for Reality: We integrated our system with Twilio, ensuring that any woman with a simple mobile phone can reach our AI shield just by dialing a number.


## Instructions to Run & Test Raksha AI
###  1. Prerequisites
### Before running the project locally, ensure you have the following installed on your system:

### Node.js (v18 or higher)
### Python (v3.10 or higher)
### Git

## 2. Local Setup & Installation

### A. Start the Backend Server (FastAPI)

### Open a terminal and navigate to the backend folder: cd backend
### Create and activate a virtual environment:
### Windows: python -m venv venv and then .\venv\Scripts\activate
### Mac/Linux: python3 -m venv venv and then source venv/bin/activate
### Install dependencies: pip install -r requirements.txt
### Run the server: python main.py (The server will start on http://localhost:8000)

### B. Start the Frontend Application (React/Vite)

### Open a new terminal window and navigate to the frontend folder: cd frontend
### Install dependencies: npm install
### Run the development server: npm run dev
### Open your browser and go to: http://localhost:3000

### 3. How to Use & Test the Platform

### Step 1: Authentication
### When you open the application, you will see the Strategic Command Login screen.
### Use the provided Demo Credentials to log in:
### Email: agent@raksha.gov.in
### Password: Raksha@1092

### Step 2: The Command Dashboard
### Upon logging in, you will be directed to the main dashboard. Here you can see live system statistics, the tactical map tracking active incidents in Karnataka, and a real-time feed of emergency cases.

### Step 3: Triggering Live Emergency Simulations To test the AI capabilities without making a real phone call, we have built a Demo Controls Module:
### Look for the orange "DEMO" button floating at the bottom right of the screen.
### Click it to open the control panel.
### Click "Random Emergency Call".
### What to watch for: Our backend will instantly generate a simulated emergency call. You will hear an audio alert (ensure your volume is on), and the AI will read the translated transcript aloud in the detected language (Hindi/Marathi/Kannada/English).
### The new case will instantly appear on the live map and in the "Active Cases" list on the left side of the screen.
### Click "🔴 CRITICAL Alert".
### This triggers a high-priority SOS situation (like domestic violence or kidnapping). Notice how the UI highlights the case in red and triggers a specific emergency siren.

### Step 4: Deep Dive into AI Analysis (Case Details)
### Click on any "Case ID" (e.g., RK202405...) in the active cases list.
### This opens the Case Details Interface.
### What to look at here:
### AI Assessment: See how the NLP model extracted the primary intent (e.g., "Medical Emergency") and calculated the caller's emotion level.
### Call Transcript: Read the real-time transcription of the caller's plea.
### Location Intelligence: View the precise extracted location data mapped to specific districts in Bangalore/Karnataka.

### Step 5: Analytics & Reporting
### Navigate to the Reports tab (using the sidebar menu).
### Here, you can view the aggregated data of all calls, broken down by intent, emotion, and regional language usage. This demonstrates how authorities can use Raksha AI for long-term strategic planning.


# 🤝 Meet the Team
## This project was built with passion and a vision for a safer India by:
### Pratik Pisal – Lead Developer & Visionary (Senior Agent)
### Krishna Paswan – Strategic Lead & Systems Architect (Supervisor)
### Krishna Paswan - System design & UI/UX
### Bharat Rathod - API integreation & database 

## To Check Our Project Demo click on this link : https://youtu.be/rR-PRN-iztU

# Thank You.. 
