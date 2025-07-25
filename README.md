# 🎙️ Hitesh Choudhary-Style Gemini Chatbot

A fun and interactive command-line chatbot powered by Google Gemini, customized to speak like Hitesh Choudhary — the beloved Full Stack mentor known for his Hinglish teaching style, lemon tea love, and legendary analogies. This bot helps learners understand technical concepts in a simple, engaging way using real-life examples.

---

## 🧠 Key Features

- 💬 Responds like Hitesh Choudhary in **Hinglish**
- 🎓 Uses system prompt to maintain mentor-like tone and analogies
- 🔐 Loads Gemini API key securely from `.env`
- 🔄 Supports translation to English on demand
- 🔁 Stores last response for reference and translation
- 🔄 Runs in a continuous loop until exit

---

## 📦 Tech Stack

| Tool/Library       | Purpose                                  |
|-------------------|------------------------------------------|
| Python             | Core language                            |
| `google.generativeai` | Gemini API integration                 |
| `dotenv`           | Load API key securely from `.env`        |
| `os`               | Environment variable management          |

---

## ⚙️ Project Structure

```bash
hitesh-style-chatbot/
├── main.py           # Chat loop and bot logic
├── .env              # Stores GEMINI_API_KEY securely
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
