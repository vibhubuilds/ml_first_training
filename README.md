# Placement Prediction Using Linear Regression

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Linear%20Regression-brightgreen.svg)]()

An end-to-end Machine Learning project that predicts a student's likelihood of placement based on their academic performance (CGPA) and the number of internships they have completed. 

## 📌 Project Overview
Getting a campus placement is a crucial milestone for every engineering and undergraduate student. This project aims to analyze how key factors like cumulative grades and practical experience impact placement outcomes. Using a dataset of 10,000 student records, a Linear Regression model was built to quantify and predict these placement chances.

## 📊 Dataset Description
The dataset used in this project was sourced from Kaggle and converted into a standard structured CSV format. 
* **Total Records:** 10,000 student profiles
* **Key Features:**
  * `CGPA` (Continuous numerical value representing academic performance)
  * `Internships` (Count of professional internships completed)
* **Target Variable:** * `Placement Chance / Status` (The probability or likelihood of being placed)

## 🛠️ Project Pipeline
1. **Data Ingestion:** Loaded the converted Kaggle CSV dataset into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** Analyzed the correlation between a student's CGPA, their internships, and how they linearly scale with placement success.
3. **Data Splitting:** Divided the 10,000 data points into Training and Testing sets to evaluate the model accurately.
4. **Model Training:** Fitted a **Linear Regression** model using Scikit-Learn to map the mathematical relationship between the independent features and placement outcomes.
5. **Evaluation:** Evaluated the model using standard regression metrics.

## 📈 Model Performance
The Linear Regression baseline model achieved an score of approximately 75%**. 

Given the massive dataset size of 10,000 rows, a 75% variance explanation shows a strong, clear linear relationship between maintaining a solid CGPA, securing internships, and getting successfully placed.

## 💻 Repository Structure
* `*.ipynb` : The Jupyter Notebook containing the full step-by-step EDA, data preprocessing, and model training logic.
* `*.py` : The executable Python script version of the model pipeline.
* `requirements.txt` : List of necessary libraries to replicate the environment.

