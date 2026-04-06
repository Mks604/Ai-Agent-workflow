# 🤖 Telegram AI Agent Assistant (n8n)

## 🚀 Overview

This project is an AI-powered Telegram chatbot built using n8n. It can understand user messages, respond intelligently, remember conversations, perform web searches, and send emails using integrated tools.

---

## ✨ Features

* 🤖 AI-powered conversational bot
* 🧠 Context-aware memory (chat history)
* 🌐 Real-time web search (SerpAPI)
* 📧 Email automation (Gmail integration)
* ⚡ Event-driven workflow automation
* 🔄 Scalable and modular architecture

---

## 🏗️ Workflow Architecture

```
Telegram Trigger → AI Agent → Telegram Response
                         ↘
               (Memory + AI Model + Tools)
```

---

## 🧩 Nodes Used

### 1. Telegram Trigger

* Captures incoming user messages

### 2. AI Agent

* Core logic for processing user input
* Decides whether to respond or use tools

### 3. OpenAI Chat Model

* Generates intelligent responses using GPT model

### 4. Simple Memory

* Maintains conversation context using session ID

### 5. SerpAPI Tool

* Enables real-time web search

### 6. Gmail Tool

* Sends emails dynamically based on user request

### 7. Telegram Send Message

* Sends AI response back to user

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```
git clone <your-repo-link>
cd <your-project>
```

### 2. Import Workflow

* Open n8n
* Click "Import from JSON"
* Upload the provided workflow file

### 3. Configure Credentials

* Telegram Bot API
* OpenAI API
* SerpAPI
* Gmail OAuth

### 4. Activate Workflow

* Click "Publish" or "Activate"

---

## 🧠 How It Works

1. User sends message via Telegram
2. Trigger captures message
3. AI Agent processes input
4. Uses memory + AI model
5. Calls tools if required (search/email)
6. Sends response back to user

---

## 💻 Tech Stack

* n8n (Workflow Automation)
* OpenAI API (AI Responses)
* Telegram Bot API (Messaging)
* SerpAPI (Web Search)
* Gmail API (Email Automation)

---

## 🎯 Use Cases

* AI Chatbot
* Customer Support Bot
* Personal Assistant
* Email Automation Bot
* Real-time Info Bot

---

## ⚠️ Notes

* Ensure all API credentials are valid
* Tool nodes must be connected and enabled
* Workflow must be activated to run automatically

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Author

Kumar K

---



