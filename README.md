
# 🚀 IBM Data Science Capstone Project – SpaceX Launch Analysis

This repository contains my capstone project for the **IBM Data Science Professional Certificate**.  
The project demonstrates a complete, end-to-end data science workflow — from data collection and wrangling to interactive dashboards and machine learning model development.

---

## 📘 Project Overview

The objective of this project is to **analyze SpaceX launch data** and predict the success of first-stage rocket landings.  
Through this analysis, we aim to identify factors influencing launch success and build predictive models for future launches.

### Key Steps
1. **Data Collection**  
   - Extracted launch records via REST APIs and web scraping (Wikipedia).  
   - Parsed and structured JSON and HTML data using `requests` and `BeautifulSoup`.

2. **Data Wrangling & Preparation**  
   - Cleaned and transformed datasets using `Pandas` and `NumPy`.  
   - Engineered new features such as success labels and payload categories.  
   - Addressed missing data and standardized column formats.

3. **Exploratory Data Analysis (EDA)**  
   - Visualized relationships between payload, booster version, and orbit type using `Matplotlib` and `Seaborn`.  
   - Performed SQL queries to analyze launch frequencies and success patterns.  

4. **Interactive Visualization & Dashboards**  
   - Built **interactive maps** with `Folium` to show global launch sites and outcomes.  
   - Created **dynamic dashboards** using `Plotly Dash` for real-time data exploration.

5. **Machine Learning Model Development**  
   - Framed a binary classification problem to predict landing success.  
   - Applied multiple models: Logistic Regression, SVM, Decision Tree, and KNN.  
   - Tuned hyperparameters using `GridSearchCV` and evaluated with accuracy, confusion matrix, and F1-score metrics.

---

## 🧠 Skills & Tools Demonstrated

| Category | Tools / Techniques |
|-----------|--------------------|
| **Programming & Data Handling** | Python, Jupyter Notebooks, Pandas, NumPy |
| **Data Collection** | REST APIs, Web Scraping (BeautifulSoup) |
| **Visualization** | Matplotlib, Seaborn, Folium, Plotly Dash |
| **Data Querying** | SQL (SQLite), DataFrames |
| **Machine Learning** | Scikit-learn (Logistic Regression, SVM, Decision Tree, KNN) |
| **Model Evaluation** | Accuracy, F1-Score, Confusion Matrix, GridSearchCV |
| **Reporting** | Dashboards, Presentation, Documentation |

---

## 📊 Results Summary

- Achieved classification accuracy of ~**83%** (Decision Tree model).  
- Identified payload mass and orbit type as key determinants of landing success.  
- Delivered a fully functional dashboard for visual exploration of launch outcomes.


