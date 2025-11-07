🤖 Customer Support Chatbot using Google Gemini API

An intelligent AI-powered Customer Support Chatbot that provides instant, context-aware, and multilingual assistance to users.
This chatbot integrates Google Gemini API, Node.js, and MongoDB to deliver real-time automated responses and enhance the overall support experience.

⸻

🧭 Table of Contents
	•	Overview￼
	•	Features￼
	•	Installation￼
	•	Configuration￼
	•	Sample Interaction￼
	•	Project Structure￼
	•	Future Enhancements￼
	•	License￼

⸻

🚀 Overview

Customer support is a crucial aspect of any modern business, but maintaining a 24/7 human support team can be costly and time-consuming.
This project introduces an AI-driven chatbot capable of handling customer queries such as order tracking, password resets, and contact information retrieval in an intelligent, conversational manner.

The system uses:
	•	Gemini API for Natural Language Understanding (intent detection, language recognition)
	•	Node.js (Express) as the backend framework
	•	MongoDB for storing FAQs and chat history
	•	HTML/CSS/JavaScript for the chat interface

⸻

✨ Features

✅ AI-Powered Responses – Understands and replies intelligently using Gemini API.
✅ Intent Recognition – Detects user’s purpose (e.g., “Track my order”, “Refund status”).
✅ Smart Suggestions – Provides follow-up question buttons for smooth navigation.
✅ Multilingual Support – Responds in multiple languages dynamically.
✅ Memory & Context – Maintains session-based conversation context.
✅ FAQ Integration – Fetches relevant responses from MongoDB when available.
✅ Beautiful Chat UI – Responsive and modern web chat interface.
✅ Error Handling – Handles invalid API responses or connection issues gracefully.

⚙️ Installation

# Clone repo
git clone https://github.com/your-username/Project2025customersupportbot.git
cd Project2025customersupportbot

# Install dependencies
npm install

# Run server
node server.js

Then open http://localhost:5000 in your browser.

🧠 Example

User: Hi
Bot: Hello! How can I help you today?
Intent: Greeting
Language: English

📂 Project Structure

customer-support-chatbot/
│
├── Backend/
│   ├── server.js
│   ├── models/
│   │   ├── Chat.js
│   │   ├── FAQ.js
│   ├── config/
│   │   └── credentials.json
│   ├── routes/
│   └── populateFAQ.js
│
├── Frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md

🔮 Future Enhancements
	•	🗣️ Add voice-to-text interaction (Speech API)
	•	💬 Integrate WhatsApp, Telegram, or Slack bots
	•	📊 Add admin analytics dashboard for chat monitoring
	•	🧩 Implement sentiment analysis
	•	🌐 Deploy using Docker or Google Cloud Run

👨‍💻 Author

Praneeth V
💡 Linux Administrator | AI & Automation Enthusiast
