# 🤖 Generative AI Chatbot Deployment

**Tech Stack:** Python · SQL · Streamlit · Docker  
**Live Demo:** https://sjd-llm.onrender.com/

---

## 📌 Project Overview

This project demonstrates the end-to-end design, development, deployment, and monitoring of a production-grade Generative AI chatbot with real-time inference and analytics. The system is built to not only serve AI responses, but also track, analyze, and report user interactions for performance optimization and operational insights.

It showcases strong skills in LLM integration, backend engineering, data logging, analytics, and cloud deployment workflows.

---

## Key Features

- Real-time AI chat interface using Streamlit  
- Usage analytics & interaction tracking stored in SQL database  
- Structured logging system for model inputs, outputs, latency, and errors  
- Containerized with Docker for reproducible deployment  
- Deployed to cloud with public live access  
- Performance monitoring for model behavior and system reliability  
- Scalable architecture ready for production workloads  

---
## 🛠️ Tech Stack

- Gradio – Web UI  
- OpenAI SDK – API integration  
- Ollama – Local model inference  
- Qwen2.5-Coder – Code-specialized LLM  
- Python – Backend logic  

---

### 📦 Prerequisites

Make sure the following are installed:

- Git  
- Python 3.8+  

---

### ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/coding-chatbot/coding-chatbot.git

```
### 2. Navigate to the Project Directory
``` 
cd coding-chatbot
```


### 3. Run the Startup Script
```
chmod +x on_start.sh
./on_start.sh
```
### 4. Run the Gradio App
```
python gradio_app.py
```




## 📁 Project Structure

```
coding-chatbot/
│── gradio_app.py
│── on_start.sh
│── requirements.txt
│── models/
│── utils/
└── README.md
```












