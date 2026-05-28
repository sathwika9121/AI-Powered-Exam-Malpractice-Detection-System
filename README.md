# 🎓 AI-Powered Exam Malpractice Detection System

An AI-powered full-stack web application that detects exam malpractice using Machine Learning and real-time proctoring features like face monitoring, phone detection, warning generation, evidence capture, and admin analytics.

## 🚀 Live Demo

### 🌐 Frontend

https://ai-powered-exam-malpractice-detecti.vercel.app/

### ⚡ Backend API

https://exam-malpractice-backend-roky.onrender.com

## 📌 Project Overview

This project helps institutions conduct secure online MCQ examinations by automatically detecting suspicious student activities during exams.

The system provides:

* Student Registration and Login
* Admin Login
* MCQ Test Creation
* Student Test Selection
* Real-time AI Monitoring
* Malpractice Warning System
* Screenshot Evidence Capture
* Video Recording Evidence
* Admin Analytics Dashboard
* CSV Report Download
* Machine Learning Model Training and Evaluation

## 🧠 Machine Learning Workflow

### ✅ Data Preprocessing

The dataset undergoes:

* Missing Value Handling
* Duplicate Removal
* Outlier Detection using IQR
* Feature Engineering
* Label Encoding
* Feature Scaling
* Train-Test Split

### ✅ Feature Engineering

Additional features created:

* Total_Violations
* Movement_Score
* Device_Issues

## 🤖 Machine Learning Models Used

### Base Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine
* K-Nearest Neighbors

### Final Ensemble Model

* Stacking Classifier

## ❓ Why Stacking Classifier?

Exam malpractice data contains:

* Linear behavior patterns
* Nonlinear suspicious activities
* Movement-based features
* Device usage indicators
* Noise and tab-switching behavior

Using one model may not capture all patterns properly.

### ✅ Stacking Advantages

* Combines multiple ML models
* Improves prediction accuracy
* Reduces overfitting
* Handles complex feature relationships
* Gives more reliable final prediction

## 📊 Model Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

## 🔐 Authentication System

### Admin Credentials

Username: admin
Password: admin123

## 📈 Features

### 🎯 AI Proctoring Features

* Multiple face detection
* Phone/object detection
* Head movement detection
* Tab switch detection
* Copy/paste attempt detection
* Student inactivity detection
* Warning generation
* Auto-submit after warning limit

### ⚡ Backend Features

* FastAPI REST APIs
* Student registration
* Student login
* Admin login
* Exam creation API
* Report submission API
* Evidence storage
* Admin summary APIs
* CSV export API

### 🎨 Frontend Features

* Modern React UI
* Student dashboard
* Admin dashboard
* MCQ exam interface
* Real-time warning display
* Analytics charts
* Evidence viewer
* Responsive layout

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Recharts
* TensorFlow.js
* CSS3

### Backend

* FastAPI
* Python
* Pydantic
* JSON file storage

### Machine Learning

* Pandas
* NumPy
* Scikit-Learn
* Logistic Regression
* Decision Tree
* Random Forest
* SVM
* KNN
* Stacking Classifier

### Deployment

* Vercel for frontend
* Render for backend
* GitHub for version control

## 📂 Project Structure

AI-Powered-Exam-Malpractice-Detection-System

├── backend
│   ├── main.py
│   ├── requirements.txt
│   ├── students.json
│   ├── exams.json
│   ├── exam_reports.json

├── frontend
│   ├── src
│   │   ├── main.jsx
│   │   ├── style.css
│   ├── package.json
│   ├── index.html

├── ml
│   ├── preprocess.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   ├── feature_engineering.py
│   ├── model_comparison.py

├── data
│   ├── exam_malpractice_dataset.csv

├── models
│   ├── malpractice_model.pkl
│   ├── scaler.pkl
│   ├── features.pkl

├── screenshots
├── recordings
├── requirements.txt
├── README.md

## ⚙️ Installation Guide

### 1️⃣ Clone Repository

git clone https://github.com/sathwika9121/AI-Powered-Exam-Malpractice-Detection-System.git

### 2️⃣ Install Python Dependencies

pip install -r requirements.txt

### 3️⃣ Run ML Files

python ml/preprocess.py
python ml/train_model.py
python ml/evaluate_model.py

### 4️⃣ Backend Setup

cd backend
python -m uvicorn main:app --reload

Backend runs on:

http://127.0.0.1:8000

### 5️⃣ Frontend Setup

cd frontend
npm install
npm run dev

Frontend runs on:

http://localhost:5173

## 🔗 API Endpoints

### 🔐 Authentication

POST /register
POST /login

### 📝 Exam APIs

GET /exams
POST /admin/exams

### 📊 Report APIs

POST /submit-report
GET /admin/reports
GET /admin/summary
GET /admin/export-csv

## 📉 Admin Analytics

The admin dashboard provides:

* Total reports
* Normal students count
* Suspicious students count
* Evidence count
* Detection count charts
* Normal vs suspicious chart
* Warning timeline
* Screenshot evidence
* Video evidence
* CSV report export

## 🌍 Deployment

### Frontend Deployment

Platform: Vercel
Live Link: https://ai-powered-exam-malpractice-detecti.vercel.app/

### Backend Deployment

Platform: Render
Live Link: https://exam-malpractice-backend-roky.onrender.com

## 🔥 Future Enhancements

* Database integration
* JWT authentication
* PDF report generation
* Email notifications
* Live webcam review for admin
* Better face recognition
* Cloud evidence storage
* Role-based access control
* Docker deployment

## ⭐ GitHub Repository

https://github.com/sathwika9121/AI-Powered-Exam-Malpractice-Detection-System
## 👨‍💻 Author

### Sathwika Samudrala

B.Tech Data Science Student
Machine Learning & Full Stack Development Enthusiast

### 🔗 GitHub

https://github.com/sathwika9121

### 🌐 Project Repository

https://github.com/sathwika9121/AI-Powered-Exam-Malpractice-Detection-System

