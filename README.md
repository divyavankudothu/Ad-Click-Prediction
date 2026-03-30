# Ad-Click-Prediction
Machine Learning project to predict ad clicks using Logistic Regression, Decision Tree, and Random Forest with data preprocessing and model comparison.
#  Ad Click Prediction using Machine Learning

##  Project Overview

This project aims to predict whether a user will click on an advertisement based on various features such as age, area income, daily internet usage, and time spent on the website. Machine learning models are used to analyze user behavior and make accurate predictions.

---

##  Objectives

* To understand user behavior from the dataset
* To preprocess and clean the data
* To build multiple machine learning models
* To compare model performance and accuracy

---

##  Dataset Description

The dataset contains the following features:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Gender
* Clicked on Ad (Target Variable)

---
##  Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Project Workflow

### 1️⃣ Data Collection

* Loaded dataset from CSV file using Pandas

### 2️⃣ Data Preprocessing

* Removed unnecessary columns (City, Country, Timestamp)
* Handled categorical variables using encoding
* Checked for missing values

### 3️⃣ Feature Selection

* Selected important features affecting ad clicks

### 4️⃣ Train-Test Split

* Split dataset into training and testing sets (80% - 20%)

### 5️⃣ Feature Scaling

* Applied StandardScaler for Logistic Regression

### 6️⃣ Model Building

The following models were implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 7️⃣ Model Evaluation

* Evaluated models using accuracy score
* Compared performance of all models

---

##  Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~65–75%  |
| Decision Tree       | ~64–75%  |
| Random Forest       | ~73–85%  |

---

##  Conclusion

Random Forest performed the best among all models due to its ability to handle complex relationships and reduce overfitting.

---

##  Future Enhancements

* Hyperparameter tuning using GridSearchCV
* Use advanced models like XGBoost
* Deploy the model using Flask or Streamlit
* Improve dataset quality for better accuracy

---


---

## STUDENT DETAILS

NAME:**V.Divya**
COURSE:BTECH-CSE-AIML
PROJECT:Ad-Click-Prediction
---

##  Acknowledgement

This project was developed as part of a capstone project to demonstrate machine learning concepts and model comparison.
