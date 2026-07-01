# 🏫 Impact of Limited Hall Accommodation on Academic Performance and Wellbeing of Noakhali Science and Technology University (NSTU) Students: A Machine Learning Approach

## 📌 Overview

Limited hall accommodation is one of the major challenges faced by students at Noakhali Science and Technology University (NSTU). Many students are forced to live in rented messes or flats, which may influence their academic performance and overall wellbeing.

This project investigates the relationship between accommodation-related factors and student outcomes using machine learning. The study uses primary survey data collected from NSTU students and applies a complete end-to-end machine learning workflow, from data preprocessing to model evaluation.

---

## 🎯 Objectives

* Analyze the impact of limited hall accommodation on academic performance.
* Analyze the impact of accommodation on student wellbeing.
* Identify the most influential accommodation-related factors.
* Compare the performance of multiple machine learning algorithms.

---

## 📊 Dataset

**Source:** Primary data collected using Google Forms

* 116 student responses
* 36 original features
* Demographic, academic, accommodation, transportation, financial, and wellbeing information

Examples of collected attributes include:

* Gender
* Department
* Academic Year
* Accommodation Type
* Hall Status
* Distance from Campus
* Transportation Method
* Transportation Cost
* Attendance
* Sleep Hours
* Internet Availability
* Safety
* Living Satisfaction
* CGPA

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Data cleaning
* Column renaming
* Missing value handling
* Encoding categorical variables
* Feature engineering
* Feature selection
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Data scaling (where required)

---

## 🤖 Machine Learning Models

The following supervised learning models were implemented and compared:

* Decision Tree
* Random Forest
* XGBoost
* Logistic Regression
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

# 📈 Experiment 1 — Academic Performance Prediction

### Target Variable

CGPA (Multi-class Classification)

### Best Model

**Decision Tree**

**Accuracy:** **66.67%**

---

# 😊 Experiment 2 — Student Wellbeing Prediction

### Original Target

Living Satisfaction (5 Classes)

**Best Model**

Support Vector Machine (SVM)

**Accuracy:** **41.67%**

### Improved Target

The original 5-point Likert scale was grouped into:

* Low Satisfaction
* Medium Satisfaction
* High Satisfaction

This improved class balance and predictive performance.

**Best Model**

Logistic Regression

**Accuracy:** **58.33%**

---

## 📊 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📈 Key Findings

* Attendance was one of the strongest predictors of academic performance.
* Department and academic year significantly influenced prediction results.
* Internet availability and safety contributed to student wellbeing.
* Proper preprocessing and feature engineering improved overall model performance.
* Different machine learning algorithms performed differently depending on the prediction task.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## 📁 Project Workflow

Google Forms Survey

⬇

Data Collection

⬇

Data Cleaning

⬇

Missing Value Handling

⬇

Encoding

⬇

Exploratory Data Analysis (EDA)

⬇

Correlation Analysis

⬇

Feature Engineering

⬇

Train-Test Split

⬇

Model Training

⬇

Model Evaluation

⬇

Feature Importance Analysis

⬇

Results & Conclusions

---

## 📷 Project Visualizations

The repository includes:

* Correlation Heatmap
* Feature Importance Chart
* Model Comparison
* Confusion Matrix
* Exploratory Data Analysis (EDA) Charts

---

## 🚀 Future Improvements

* Collect a larger dataset from multiple universities.
* Perform hyperparameter tuning using GridSearchCV.
* Explore ensemble learning techniques.
* Experiment with deep learning models.
* Deploy the trained model as a web application.

---

## 👩‍💻 Author

**Ishrat Jaman**

Software Engineering Undergraduate

Noakhali Science and Technology University (NSTU)

Interested in Machine Learning, Data Science, Artificial Intelligence, and Software Development.

Feel free to connect with me on LinkedIn or explore my other projects.
