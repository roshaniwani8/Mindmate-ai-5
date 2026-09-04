# 🧠 MindMate

**AI-powered wellness companion for everyday mental well-being.**

MindMate is a web-based AI wellness companion designed to help users understand their mood, reflect through journaling, and build healthier daily habits in a simple and supportive environment.

> 💚 **Disclaimer:** MindMate is an AI wellness companion, not a doctor or therapist. For serious concerns, please reach out to a qualified professional or someone you trust.

## ✨ Features

* 🤖 **AI Wellness Chat** — Have supportive conversations with an AI companion.
* 💭 **Mood Tracker** — Track your mood and view your mood history.
* 📔 **Digital Journal** — Write and manage personal journal entries.
* 🌿 **Wellness Toolkit** — Access simple activities and wellness suggestions.
* 🎙️ **Voice Interaction** — Supports speech recognition and voice output.
* 💬 **Conversation Memory** — Maintains context during conversations.
* 🔍 **Conversation Search** — Easily find previous conversations.
* 📊 **Wellness Dashboard** — View your mood and wellness activity.
* 🌙 **User-Friendly Interface** — Clean, responsive interface designed for everyday use.
* 🔒 **Local Data Storage** — Mood and journal data can be stored locally in the browser.

## 🛠️ Built With

### Frontend

* HTML5
* CSS3
* JavaScript
* DOM API
* LocalStorage
* Web Speech API

### Backend

* Python
* Flask
* REST API

### AI

* Ollama
* Qwen 2.5 3B

## 🏗️ Architecture

```text
MindMate
│
├── Frontend
│   ├── HTML
│   ├── CSS
│   └── JavaScript
│
├── Flask Backend
│   ├── API Routes
│   └── AI Integration
│
├── Local AI
│   └── Ollama + Qwen 2.5 3B
│
└── Browser Storage
    ├── Mood History
    └── Journal Entries
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/MindMate.git
cd MindMate
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Install and run Ollama

Make sure Ollama is installed and the required model is available locally.

```bash
ollama pull qwen2.5:3b
```

Then start Ollama.

### 5. Run the Flask application

```bash
python app.py
```

Open the local address shown by Flask in your browser.

## 📁 Project Structure

```text
MindMate/
│
├── static/
│   ├── css/
│   ├── js/
│   └── assets/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

## 💡 Inspiration

Mental well-being is an important part of everyday life, but people may not always have someone available to talk to or a simple way to reflect on how they are feeling.

We built MindMate to create a friendly digital space where users can check in with their mood, journal their thoughts, explore wellness activities, and have supportive AI-powered conversations.

## 🧩 Challenges We Ran Into

* Integrating an AI model with the Flask backend.
* Handling streaming AI responses.
* Managing conversation context.
* Building mood tracking and persistent browser storage.
* Creating a responsive and intuitive user interface.
* Working with local AI through Ollama.
* Handling API and server-side errors gracefully.

## 🏆 Accomplishments We're Proud Of

* Built a complete AI wellness web application.
* Integrated a local AI model using Ollama.
* Added real-time AI response streaming.
* Implemented mood tracking and history.
* Added journaling and wellness tools.
* Created an interactive dashboard.
* Built the project using a lightweight and accessible technology stack.

## 📚 What We Learned

Through MindMate, we learned how to:

* Build a full-stack application with Flask.
* Connect frontend JavaScript with backend REST APIs.
* Integrate and communicate with local AI models.
* Handle streaming responses.
* Work with browser LocalStorage.
* Design a user-focused wellness interface.
* Debug frontend and backend integration issues.

## 🔮 What's Next for MindMate

Future improvements could include:

* 📱 Mobile application
* ☁️ Secure cloud synchronization
* 📈 Advanced wellness insights
* 🧠 More AI-powered wellness tools
* 🎯 Personalized wellness recommendations
* 🔔 Daily wellness reminders
* 🌍 Multi-language support
* 🔐 Enhanced privacy and security

## ❤️ Responsible AI

MindMate is designed as a supportive wellness companion rather than a replacement for professional healthcare.

The application should not be used for diagnosis, treatment, or emergency situations. Users experiencing serious concerns should seek help from a qualified professional or a trusted person.

## 👩‍💻 Built For

**Hack for Humanity – Summer 2026**

### Project

**MindMate — AI Wellness Companion**

---

Made with 💚 for better everyday well-being.
