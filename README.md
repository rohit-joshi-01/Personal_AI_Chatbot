# 🤖 Personal AI Chatbot (Streamlit + OpenAI)

A simple, interactive **AI-powered chatbot** built using **Streamlit** and **OpenAI’s Chat Completions API**.  
This project demonstrates how to create a conversational web app with persistent chat history using session state.

---

## ✨ Features

- 💬 Real-time chat interface using Streamlit’s `chat_input`
- 🧠 AI responses powered by OpenAI (`gpt-4o-mini`)
- 🗂️ Conversation memory using Streamlit session state
- 🔐 Secure API key handling with `.env` and `python-dotenv`
- ⚡ Lightweight, fast, and easy to extend

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – UI and web app framework
- **OpenAI Python SDK**
- **python-dotenv** – Environment variable management

---

## 📁 Project Structure

- ├── app.py                # Main Streamlit application
- ├── .env                  # Environment variables (API key)
- ├── requirements.txt      # Python dependencies
- └── README.md             # Project documentation

---

## 🧠 How It Works

- User inputs a message via the Streamlit chat UI
- Messages are stored in st.session_state to preserve chat history
- The full conversation is sent to the OpenAI API
- The AI generates a response based on context
- The response is displayed and saved for future turns

---

## 📌 Future Improvements

- 🔄 Streaming responses
- 🧑‍🎨 Custom avatars or themes
- 🧾 Chat export / download
- 🗑️ Clear chat button
- 🧠 System prompt customization


--- 

Author : "Rohit Joshi"

---
