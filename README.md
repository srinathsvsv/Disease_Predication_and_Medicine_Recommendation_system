# 🩺 Disease Prediction and Medicine Recommendation System

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Framework-lightgrey?logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-green?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Active-success)
![Made with ❤️ in Python](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)

---

## 📘 Overview
The **Disease Prediction and Medicine Recommendation System** is a machine learning–based web application built using **Python** and **Flask**.  
It predicts potential diseases from user-provided symptoms and recommends suitable medicines or treatments.  
This project aims to support early disease detection and assist users in making informed health decisions.

---

## 🎯 Features
✅ Predicts diseases based on user symptoms.  
✅ Suggests relevant medicines and precautions.  
✅ Simple, responsive, and user-friendly web interface.  
✅ Flask-based backend integrated with ML models.  
✅ Lightweight design for fast local or cloud deployment.

---

## 🧠 Machine Learning Model
The system leverages **supervised learning algorithms** trained on a symptom–disease dataset.  
Models used:
- **Random Forest Classifier**
- **Naive Bayes**
- **Decision Tree**
- **Support Vector Machine (SVM)**

The trained model is serialized using **pickle** and integrated into Flask for real-time predictions.

---

## 🧩 Tech Stack

| Component | Technology Used |
|------------|-----------------|
| Frontend | HTML, CSS, Bootstrap |
| Backend | Flask (Python) |
| Machine Learning | scikit-learn, pandas, numpy |
| Database | CSV / SQLite (optional) |
| Version Control | Git & GitHub |

---

## 🚀 How to Run Locally

### 1️⃣ Clone this repository
    git clone https://github.com/srinathsvsv/Disease_Predication_and_Medicine_Recommendation_system.git

### 2️⃣ Navigate to the project directory
    cd Disease_Predication_and_Medicine_Recommendation_system

### 3️⃣ Create and activate a virtual environment
    python -m venv venv
    venv\Scripts\activate      # For Windows
    source venv/bin/activate   # For Linux/Mac
### 4️⃣ Install dependencies
    pip install -r requirements.txt
### 5️⃣ Run the Flask application
    python app.py
### 6️⃣ Open your browser
    Visit 👉 http://127.0.0.1:5000/
---
## 📊 Example Use Case
1. User enters symptoms such as headache, fever, sore throat.
2. The model processes the input and predicts a possible disease (e.g., **Common Cold**).
3. The system displays:
   - 🩺 Disease Name
   - 💊 Recommended Medicines
   - ⚠️ Precautions
   - 🧾 Disease Description
---
## 📁 Folder Structure
```
  Disease_Predication_and_Medicine_Recommendation_system/
  │
    ├── app.py # Main Flask application
    ├── model.pkl # Trained Machine Learning model
    ├── static/ # CSS, JS, and images for the web interface
    ├── templates/ # HTML templates for Flask routes
    ├── dataset.csv # Dataset used for training the ML model
    ├── requirements.txt # Project dependencies
    └── README.md # Project documentation
```
## 💡 Future Enhancements
  - 🚀 Integrate user login and health record management.
  - 📱 Add voice-based symptom input.
  - 🌐 Deploy on AWS, Render, or Heroku.
  - 🧬 Improve dataset and model accuracy.
  - 💬 Add chatbot integration for symptom assistance.

## 🧑‍💻 Author
  **Srinath S V**
  - 📍 GitHub: @srinathsvsv
  - 💼 Project Repository: Disease Prediction and Medicine Recommendation System





