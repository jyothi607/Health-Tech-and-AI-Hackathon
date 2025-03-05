# AI-Powered Mental Health Tracker

## 📌 Project Overview
The **AI-Powered Mental Health Tracker** is a mobile application designed to analyze user emotions using **Natural Language Processing (NLP)** and **Voice Emotion Analysis**. By utilizing AI-driven sentiment analysis and voice tone detection, the app provides **personalized mental health recommendations**, helping users manage their emotional well-being effectively.

## 🛠️ Tech Stack & Tools Used
### **Backend (Flask + AI Models)**
- **Python** (Flask/FastAPI)
- **Hugging Face Transformers** (BERT for sentiment analysis)
- **Librosa & SpeechRecognition** (Voice emotion analysis)
- **PostgreSQL/MongoDB** (For storing user data)

### **Frontend (React Native)**
- **React Native** (For cross-platform mobile UI)
- **Axios** (API communication)
- **React Navigation** (App navigation)

## 🚀 Installation & Setup
### **1. Clone the Repository**
```sh
 git clone https://github.com/yourusername/mental-health-tracker.git
 cd mental-health-tracker
```

### **2. Backend Setup (Flask API)**
```sh
 cd backend
 python -m venv venv
 source venv/bin/activate  # On Windows use `venv\Scripts\activate`
 pip install -r requirements.txt
 python app.py
```

### **3. Frontend Setup (React Native)**
```sh
 cd frontend
 npm install
 npm start
```

## 🌟 Features
- **Text-Based Sentiment Analysis** (Using BERT/GPT models)
- **Voice Emotion Detection** (Using Librosa & SpeechRecognition)
- **Personalized AI-Based Mental Health Recommendations**
- **Mood Progress Tracking**
- **React Native Mobile Application**

## 🔧 Technical Workflow
```
User Input (Text/Voice)
    ↓
Frontend (React Native)
    ↓
Backend API (Flask)
    ↓
NLP Model (BERT) for Sentiment Analysis
Voice Emotion Detection (Librosa + SpeechRecognition)
    ↓
Personalized AI-Based Recommendations
    ↓
Response Sent Back to Frontend
    ↓
User Receives Mood Analysis & Suggestions
```

## 📌 Future Enhancements
- **Real-Time Chatbot Support** using OpenAI's GPT.
- **Gamification & Rewards** for tracking emotions consistently.
- **Integration with Wearable Devices** for stress level monitoring.
- **Privacy-Focused Edge AI** for local processing.

## 👥 Contributors
- **Jyothi Laxmi** - Lead Developer

For queries, reach out to **jyothilaxmipoosaala@gmail.com**.

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
