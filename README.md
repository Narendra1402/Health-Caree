# 🏥 Healthcare Diabetes Prediction Dashboard – Python & Tableau Project

A data science capstone project leveraging Python and Tableau to predict diabetes outcomes using medical diagnostic data, with insights visualized through interactive dashboards.


![Healthcare](https://user-images.githubusercontent.com/122566558/212751550-1a726966-f0c3-41fd-a999-c617bf8db082.png)


## 🧠 Problem Overview

Chronic diseases like diabetes are on the rise globally. NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) provides crucial datasets to support research in this domain. The goal of this project is to predict whether a patient is diabetic based on various medical attributes. The dataset contains features such as glucose levels, BMI, age, insulin, and more. 

This project covers the end-to-end pipeline from data exploration and preprocessing in Python to visual storytelling in Tableau.


## 📁 Dataset Summary

| Feature                  | Description                                                    |
|--------------------------|----------------------------------------------------------------|
| Pregnancies              | Number of times pregnant                                       |
| Glucose                  | Plasma glucose concentration in an oral glucose tolerance test |
| BloodPressure            | Diastolic blood pressure (mm Hg)                              |
| SkinThickness            | Triceps skinfold thickness (mm)                               |
| Insulin                  | Two-hour serum insulin (mu U/ml)                              |
| BMI                      | Body Mass Index                                               |
| DiabetesPedigreeFunction| Diabetes pedigree function (family history)                   |
| Age                      | Patient age                                                   |
| Outcome                  | 1 for diabetic, 0 for non-diabetic                            |



## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Sklearn)
- Tableau (for dashboarding and reporting)
- Jupyter Notebook



## 🚶‍♂️ Implementation Steps

### 🔹 Week 1 – Data Exploration
- Loaded the dataset and explored basic statistics.
- Identified variables with zero values that indicate missing data.
- Replaced or imputed missing values (Glucose, BloodPressure, SkinThickness, Insulin, BMI).
- Used histograms to visualize distributions.

### 🔹 Week 2 – Visual Analysis
- Created count plots for the outcome variable.
- Analyzed data balance between diabetic and non-diabetic classes.
- Created scatter plots between variables to study relationships.
- Generated correlation heatmap to detect strong and weak correlations.

### 🔹 Week 3 – Modeling
- Applied K-Nearest Neighbors (KNN) as a baseline model.
- Tried other classifiers (Logistic Regression, Decision Tree, SVM).
- Evaluated models using accuracy, precision, recall, and F1-score.

### 🔹 Week 4 – Evaluation & Dashboarding
- Analyzed AUC, sensitivity, specificity.
- Created multiple dashboards in Tableau using the final dataset and insights.



## 📊 Dashboard Components (Tableau)

### ✅ Diabetic vs Non-Diabetic Population (Pie Chart)
Clearly shows the distribution between diabetic and non-diabetic patients in the dataset.

### 🔍 Variable Relationships (Scatter Plots)
Shows how different variables like BMI vs Glucose or Age vs Insulin behave for each class.

### 📈 Histogram Distribution
Histograms show the frequency of values across different medical attributes like BMI, Glucose, and Age.

### 🌡️ Correlation Heatmap
A heatmap showing correlations among variables — useful to detect multicollinearity and key indicators.

### 🔘 Bubble Chart: Age Bins
Age is binned (20-25, 25-30, etc.), and bubble chart displays average glucose/BMI levels per age bracket.



## 📁 Folder Structure
```
├── README.md
├── notebooks/
│   └── diabetes_analysis.ipynb
├── tableau/
│   └── final_dashboard.twb
├── data/
│   └── diabetes.csv
├── images/
│   └── dashboard_snapshots.png
```



## 🔮 Future Enhancements
- Deploy model with a Flask web app for real-time prediction
- Add more demographic variables (gender, lifestyle)
- Connect Tableau to a real-time database





## 🔗 Connect With Me  
Feel free to explore more of my projects and reach out:  
- [LinkedIn](https://www.linkedin.com/in/narendrasingh1402)
- [YouTube](https://www.youtube.com/@Analyst_Hive)  
- [Portfolio](https://narendra1402.github.io/)


> 🧬 Bridging medical data with predictive intelligence to enhance healthcare outcomes.

![Main dashboard](https://user-images.githubusercontent.com/122566558/212751619-706e6beb-4ed4-4a01-8041-b7d058f4e61d.png)

