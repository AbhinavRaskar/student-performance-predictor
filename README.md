# 🎓 Student Performance Predictor


## 🚀 Live Demo

[Open Student Performance Predictor](https://student-performance-predictor-680k.onrender.com)


A Machine Learning web application that predicts a student's **Math Score** based on academic and demographic information and provides an interactive analytics dashboard.

## 📌 Project Overview

The Student Performance Predictor uses a trained Machine Learning regression model to estimate a student's math performance.

The application combines:

- Machine Learning
- Python
- Flask
- Pandas
- Scikit-learn
- CatBoost
- SQLite
- HTML/CSS
- Chart.js

The user enters student information through a web form. The application preprocesses the input, sends it to the trained ML model, displays the predicted Math Score, and stores the prediction in a SQLite database.

---

## 🚀 Features

### 🧠 Student Performance Prediction

The application predicts a student's Math Score using:

- Gender
- Race / Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

### 📊 Analytics Dashboard

The dashboard provides:

- Average predicted score
- Highest predicted score
- Lowest predicted score
- Prediction Trend
- Score Distribution
- Performance Breakdown
- Prediction History

### 💡 Performance Insights

Based on the predicted score, the application provides an automatic performance message:

- **Above 75** → Excellent Performance 🎉
- **51–75** → Average Performance 👍
- **50 or below** → Needs Improvement ⚠️

### 🗄️ Prediction History

Every prediction is stored in a SQLite database.

The application also provides an option to clear the prediction history.

---

## 🏗️ Machine Learning Workflow

```text
Student Input
      │
      ▼
Flask Web Application
      │
      ▼
CustomData
      │
      ▼
Pandas DataFrame
      │
      ▼
Preprocessor
(preprocessor.pkl)
      │
      ▼
Trained ML Model
(model.pkl)
      │
      ▼
Predicted Math Score
      │
      ▼
SQLite Database
(students.db)
      │
      ▼
Analytics Dashboard