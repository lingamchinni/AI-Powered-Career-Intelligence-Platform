# AI-Powered Career Intelligence Platform

### Milestone 1 – Resume Parsing and Career Prediction

An AI-powered resume analysis platform that extracts important information from resumes and predicts suitable career areas using Machine Learning.

---

## 📌 Project Overview

The **AI-Powered Career Intelligence Platform** is a machine learning-based web application that analyzes a user's resume and predicts the most suitable career area.

The system automatically extracts important information such as education, skills, experience, email, and phone number from uploaded resumes and uses a trained machine learning model to recommend an appropriate career path.

This milestone focuses on building the core resume analysis and career-area prediction pipeline using Python, Flask, and Machine Learning.

---

## 🎯 Objectives

- Build a web-based resume analysis system.
- Extract structured information from uploaded resumes.
- Predict the most suitable career area using a trained machine learning model.
- Display extracted information and prediction results through a user-friendly interface.

---

## ✨ Features Implemented (Milestone 1)

- Resume upload through a Flask web application.
- PDF resume text extraction.
- Automatic extraction of:
  - Name
  - Email
  - Phone Number
  - Education
  - Skills
  - Years of Experience
- Resume preprocessing using TF-IDF Vectorization.
- Career-area prediction using a trained Logistic Regression model.
- Display of parsed resume details and predicted career.

---

## 🛠️ Technologies Used

### Programming Language
- Python 3.x

### Machine Learning
- Scikit-learn
- Logistic Regression
- TF-IDF Vectorizer

### Backend
- Flask

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

### Libraries
- Pandas
- NumPy
- Joblib
- PDFPlumber
- SciPy

---

## 📂 Project Structure

```text
AI-Powered-Career-Intelligence-Platform/
│
├── backend/
│   ├── __init__.py
│   ├── parser.py
│   ├── feature_extractor.py
│   └── predictor.py
│
├── frontend/
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── prediction.html
│   │   └── upload.html
│   └── static/
│       ├── css/
│       │   └── style.css
│       └── js/
│           └── script.js
│
├── models/
│   ├── logistic_regression_model.pkl
│   ├── tfidf_vectorizer.pkl
│   ├── education_onehot_encoder.pkl
│   └── job_role_label_encoder.pkl
│
├── uploads/
│
├── datasets/
│   └── clean_training_data.csv
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🤖 Machine Learning Workflow

1. Load the training dataset.
2. Clean and preprocess resume text.
3. Extract relevant features.
4. Convert resume text into TF-IDF vectors.
5. Encode education using One-Hot Encoding.
6. Include years of experience as a numerical feature.
7. Train a Logistic Regression classifier.
8. Save the trained model and preprocessing objects.
9. Load the saved model in the Flask application.
10. Predict the most suitable career area for uploaded resumes.

---

## ⚙️ How It Works

1. User uploads a PDF resume.
2. The system extracts the resume text.
3. Important information is identified:
   - Education
   - Skills
   - Experience
   - Email
   - Phone Number
4. The extracted data is converted into machine learning features.
5. The trained Logistic Regression model predicts the most suitable career area.
6. The predicted role and extracted resume details are displayed on the web page.

---

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/udaykiranreddy-vennapusa/AI-POWERED-CAREER-INTELLIGENCE-PLATFORM.git
```

### 2. Move into the Project Directory

```bash
cd AI-POWERED-CAREER-INTELLIGENCE-PLATFORM
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

### 5. Open in Browser

Visit the following URL:

```text
http://127.0.0.1:5000
```

---

## 📊 Current Model Status

| Model | Status |
|---|---|
| Logistic Regression | Implemented |
| TF-IDF Vectorizer | Implemented |
| Education One-Hot Encoder | Implemented |
| Job
