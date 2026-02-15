🎓 Exam Score Prediction using Linear Regression

This project predicts student exam scores using Linear Regression with a full machine learning pipeline built using Scikit-Learn.

The model is deployed as a simple and interactive Streamlit web application.

📌 Project Overview

The goal of this project is to predict a student's exam score based on various academic and personal factors such as:

Age

Study Hours

Sleep Hours

Class Attendance

Gender

Course

Internet Access

Sleep Quality

Study Method

Facility Rating

Exam Difficulty

The project demonstrates:

Data preprocessing

Feature encoding

Model training

Pipeline creation

Model serialization

Web app deployment

📂 Project Structure
Linear_Regression/
│
├── app.py                         # Streamlit web app
├── Exam_Score_Prediction.csv      # Dataset
├── Exam_Score_Prediction.ipynb    # Model training notebook
├── exam_score_model.pkl           # Trained model
├── exam_score_pipeline.pkl        # Full preprocessing + model pipeline
├── feature_selector.pkl           # Feature selection object
├── requirements.txt               # Project dependencies
└── README.md                      # Project documentation

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Joblib

Matplotlib

Seaborn

Streamlit

🧠 Machine Learning Workflow

Data Collection

Data Cleaning

Feature Engineering

Encoding Categorical Variables

Train/Test Split

Linear Regression Model Training

Pipeline Creation using ColumnTransformer

Model Saving using joblib

Deployment with Streamlit

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/vinayagamvarshini65-create/Linear_Regression.git
cd Linear_Regression

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run app.py


The app will open in your browser.

🖥️ Streamlit Application Features

User-friendly interface

Real-time prediction

Handles categorical inputs automatically

Uses full preprocessing pipeline

Displays predicted exam score instantly

📊 Dataset

The dataset contains student-related academic and behavioral features used to train the model.

Target Variable:

Exam Score

📈 Model Used

Linear Regression

Implemented using Scikit-Learn

Integrated with preprocessing pipeline

🔮 Future Improvements

Add model evaluation metrics display

Add data visualization dashboard

Try advanced regression models

Deploy to cloud (Streamlit Cloud / Render / AWS)

Add model performance comparison

👩‍💻 Author

Vinayagam Varshini

⭐ If you like this project

Give it a ⭐ on GitHub!

If you want, I can also:

Make this README more professional for placement

Add screenshots section

Add badges (Python, Streamlit, License, etc.)

Add model evaluation results

Make it resume-ready

Just tell me 😊

live demo link:https://linearregression-gafzgkvebcz6vhjfm5tcaq.streamlit.app/
Make this README more professional for placement

Here is your professional, placement-ready README.md with your live demo included.
You can directly copy and paste this into your repository on GitHub.

🎓 Exam Score Prediction | Machine Learning Web App

🔗 Live Demo:
👉 https://linearregression-gafzgkvebcz6vhjfm5tcaq.streamlit.app/

📌 Project Overview

This project is an end-to-end Machine Learning Regression Application that predicts student exam scores based on academic, behavioral, and environmental factors.

The solution demonstrates the complete ML lifecycle:

Data preprocessing

Feature engineering

Model building using Linear Regression

Pipeline creation with Scikit-Learn

Model serialization

Deployment as an interactive web app using Streamlit

This project showcases practical implementation skills required for real-world ML deployment.

🧠 Problem Statement

Predict a student’s exam score using features such as:

Age

Study Hours

Sleep Hours

Class Attendance (%)

Gender

Course

Internet Access

Sleep Quality

Study Method

Facility Rating

Exam Difficulty

🏗️ Project Architecture
User Input (Streamlit UI)
        ↓
Preprocessing Pipeline (ColumnTransformer + Encoding)
        ↓
Linear Regression Model
        ↓
Prediction Output (Exam Score)

📂 Project Structure
Linear_Regression/
│
├── app.py                         # Streamlit Web Application
├── Exam_Score_Prediction.csv      # Dataset
├── Exam_Score_Prediction.ipynb    # Model Development Notebook
├── exam_score_model.pkl           # Trained Model
├── exam_score_pipeline.pkl        # Complete ML Pipeline
├── feature_selector.pkl           # Feature Selection Object
├── requirements.txt               # Dependencies
└── README.md                      # Documentation

⚙️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Joblib

Visualization: Matplotlib, Seaborn

Deployment: Streamlit

🔬 Machine Learning Workflow

Data Loading & Cleaning

Exploratory Data Analysis

Feature Encoding (Categorical Variables)

Train-Test Split

Model Training (Linear Regression)

Pipeline Creation using ColumnTransformer

Model Serialization using joblib

Deployment using Streamlit

🚀 How to Run Locally
1️⃣ Clone Repository
git clone https://github.com/vinayagamvarshini65-create/Linear_Regression.git
cd Linear_Regression

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Application
streamlit run app.py

💻 Live Application Features

✔ Interactive user interface
✔ Real-time predictions
✔ Automated preprocessing via pipeline
✔ Handles categorical & numerical features
✔ Clean and responsive design

📊 Model Details

Algorithm Used: Linear Regression

Type: Supervised Learning (Regression)

Target Variable: Exam Score

Preprocessing: OneHotEncoding + ColumnTransformer

Pipeline Integration: Yes

📈 Key Highlights (For Recruiters)

Built complete ML pipeline from scratch

Implemented proper preprocessing workflow

Deployed ML model as production-ready web app

Used model serialization for scalable deployment

Demonstrates understanding of real-world ML architecture

🔮 Future Enhancements

Add performance metrics display (R², MAE, RMSE)

Add model comparison (Ridge, Lasso, Random Forest)

Deploy using Docker

Add CI/CD integration

Add authentication layer

👩‍💻 Author

Vinayagam Varshini
Aspiring Data Scientist | Machine Learning Enthusiast

⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
