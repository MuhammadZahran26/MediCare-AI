# 🧠 MediCare-AI  
**Multimodal Alzheimer’s Disease Detection and Assistance System**

MediCare-AI is a Flask-based web application designed for early-stage Alzheimer’s Disease analysis and patient assistance.  
The system combines **medical image processing**, **deep learning models**, and an **AI-powered medical chatbot** to support patients and doctors in understanding Alzheimer’s progression.

This project is developed as a **Final Year Project (FYP)** with a strong focus on **realistic constraints**, **medical AI pipelines**, and **explainable system design**.

---

## 🎯 Project Objectives

- Detect Alzheimer’s Disease stages using medical imaging data
- Assist patients through an AI-based medical chatbot
- Maintain patient scan history and preprocessing pipelines
- Provide a clean, extensible backend architecture suitable for research
- Demonstrate real-world challenges such as limited data and compute

---

## ✨ Core Features

- 🔐 **User Authentication**
  - Patient and Doctor login system
  - Secure session handling with Flask

- 🧠 **Medical Image Analysis**
  - MRI / PET scan ingestion
  - Image preprocessing pipeline
  - Deep learning model inference (CNN / multimodal-ready)

- 🤖 **MediBot (Medical Chatbot)**
  - Alzheimer-related guidance
  - Prevention tips, exercises, and disease awareness
  - Knowledge-based responses (non-diagnostic)

- 📂 **Patient History Management**
  - Uploaded scans stored securely
  - Future-ready for disease progression tracking

- 🏗 **Modular Architecture**
  - Clear separation of ingestion, preprocessing, models, and UI
  - Easy to extend for research experiments

---

## 🛠 Tech Stack

### Backend
- Flask
- Python 3.10+
- Jinja2 Templates
- SQLAlchemy (lightweight usage)
- Session-based authentication

### AI / ML
- CNN-based models
- Multimodal design (MRI + PET ready)
- Custom preprocessing pipelines
- Vector store for chatbot context

### Storage
- Local filesystem (uploads, vectorstore)
- SQLite (current)
- Designed to migrate to PostgreSQL / Neon

---


## 🚀 Setup & Installation

### 1️⃣ Create Virtual Environment
```bash
python -m venv .venv
source .venv/bin/activate     # Linux / macOS
.venv\Scripts\activate        # Windows
```
---
## ⚠ Disclaimer

MediCare-AI is a research and educational system only.
It does not provide medical diagnosis and must not be used as a substitute for professional medical advice.


## 📁 Actual Project Structure

