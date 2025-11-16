## AI in Mental Health
Detecting Early Signs of Mental Health Instability Using Machine Learning & GUI-Based Dashboard
📌 Project Overview

Mental health issues such as stress, anxiety, and depression are rapidly increasing due to academic pressure, workload, lifestyle imbalance, and digital dependency.
This project “AI in Mental Health” aims to detect early signs of mental instability using AI techniques and provide a simple, interactive dashboard for users to check their stress level and related mental health indicators.

The project includes:

Machine learning–based prediction models

Stress level detection

GUI (web-based) dashboard

User-friendly visualization

Real-time mental health assessment

🎯 Objective

The main objectives of this project are:

Identify stress, work pressure, anxiety, and mental instability indicators.

Build a prediction model using machine learning.

Create an interactive front-end dashboard for users.

Provide actionable suggestions based on predicted stress levels.

Support early mental health monitoring using AI.

🧩 Problem Statement

Mental health issues are often ignored until they become severe.
Early detection is difficult without continuous monitoring and expert supervision.

Key challenges include:

Lack of awareness of early symptoms

No easy monitoring tools

Difficulty in identifying stress patterns

Limited availability of mental health professionals

This project proposes an AI-powered solution to solve these challenges.

🧬 Proposed Solution

The project integrates:

Machine Learning Model

Trained on mental health–related datasets

Predicts Stress Level, Work Pressure, Anxiety, and Burnout

Web-based GUI Dashboard

User inputs behavioral & physiological parameters

System predicts stress level in real time

Displays results through charts & progress bars

Result Interpretation

Normal

Mild Stress

Moderate Stress

High Stress

Critical (Needs attention)

Suggestions

Lifestyle changes

Work-life balance recommendations

Mindfulness & relaxation techniques

🏗️ Architecture / Flow of the System
User Input
     ↓
Pre-processing
     ↓
ML Model Prediction
     ↓
Stress/Anxiety/Burnout Classification
     ↓
Visualization in Dashboard
     ↓
Suggestions for Improvement

🔍 Features

✔ AI/ML-based predictions
✔ Stress Level Detector
✔ Work Pressure Analyzer
✔ Anxiety Detection
✔ Real-time prediction
✔ Interactive GUI Dashboard
✔ Graphs & visualization
✔ Lightweight & accessible online

📂 Project Structure
AI-in-Mental-Health/
│
├── data/
│   └── dataset.csv
│
├── model/
│   └── stress_model.pkl
│
├── web/
│   └── index.html
│   └── style.css
│   └── script.js
│
├── backend/
│   └── prediction.ipynb
│   └── flask_app.py (if API used)
│
├── README.md
│
└── assets/
    └── screenshots/

🛠️ Technologies Used
Frontend

HTML

CSS

JavaScript

Tailwind CSS

Backend / ML

Python

NumPy

Pandas

Scikit-Learn

Flask (optional, if API connected)

Jupyter Notebook

Visualization

Matplotlib

Seaborn

JavaScript Charts

📊 Machine Learning Model Details
Algorithms Explored

Logistic Regression

Random Forest

Support Vector Machine

Decision Tree

Gradient Boosting

Selected Best Model

Random Forest Classifier (Based on accuracy metrics)

Performance Metrics

Accuracy: ~92%

Precision: High

Recall: Good for stress categories

💻 How to Run the Project
1. Clone the repository
git clone https://github.com/your-repo/AI-in-Mental-Health.git

2. Install dependencies
pip install -r requirements.txt

3. Run ML Notebook

Open:

prediction.ipynb

4. Run Frontend

Simply open:

web/index.html

5. If using backend API

Start Flask backend:

python flask_app.py

🌐 Live Demo (GUI)

If your webpage is hosted on Netlify:

🔗 https://courageous-phoenix-30d309.netlify.app/

📈 Results

The system accurately predicts:

Stress level

Pressure indicators

Burnout

Emotional fluctuations

Graphs, prediction values, and interpretation are displayed on the dashboard.




Mobile app version
