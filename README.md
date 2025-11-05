# Wellness-Chatbot
This is a streamlit based chatbot which is built on a knowledge base allowing flexiblity to query using Hindi and English. Also there is availabilty for user and admin access 
# 🩺 Multilingual Health Chatbot (Milestone 3)

An intelligent **multilingual health assistant** built with **Streamlit**, providing quick general health guidance in **English** and **Hindi**.  
It features user authentication, profile-based responses, translation using MarianMT models, and an **Admin Dashboard** for analytics, feedback visualization, and knowledge base management.

---

## 🚀 Features

### 👤 User Module
- **User Registration & Login** (stored in `users.json`)
- **Profile Management**: Age, gender, height, weight, blood group
- **BMI Calculation** with categorized health feedback
- **Multilingual Chatbot**: English, Hindi, and Hinglish queries supported
- **Translation Models**: MarianMT for Hindi ↔ English
- **Feedback System**: Like 👍 / Dislike 👎 responses with analytics tracking
- **Persistent Logging**: All queries and feedback stored in `metrics.json`

### 👑 Admin Dashboard
- Real-time **User Statistics** (total users, queries, top topics)
- **Feedback Charts** (positive vs. negative)
- **Knowledge Base Management** (add/delete topics dynamically)
- **Unanswered Query Tracker** to identify content gaps
- **User Activity View** with per-user metrics and logs

---

## ⚙️ Technologies Used

| Component | Technology |
|------------|-------------|
| Frontend / UI | Streamlit |
| Backend Logic | Python |
| Translation | MarianMT (Helsinki-NLP) |
| Visualization | Altair |
| Data Storage | JSON Files (`users.json`, `metrics.json`) |
| Security | SHA-256 Password Hashing |

---



