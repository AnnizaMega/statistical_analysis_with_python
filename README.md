# 📁 Statistical Analysis with Python

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-brightgreen)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Model-orange)

##  Table of Contents
- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Dataset Overview](#dataset-overview)
- [Analysis Method](#analysis-method)
- [Key Findings and Insights](#key-findings-and-insights)
- [Links to Code](#links-to-code)

---

##  Introduction

This project focuses on applying **Statistical Analysis techniques** to draw actionable insights from different datasets.  
Using Pearson’s Correlation, Chi-Squared Tests, and Linear Regression, we aim to:
- Understand relationships between variables
- Quantify associations
- Develop a regression formula to predict salaries

---

##  Tech Stack

- **Python:** pandas, scikit-learn, numpy
- **Analysis:** Pearson’s, Chi-Squared, Linear Regression
- **Environment:** Google Colab
- **Other:** Kaggle datasets

---

##  Dataset Overview

➥ **Telco Customer Churn:**  
Contains 7043 observations and 21 variables (age, gender, tenure, total charges, etc.).  
➥ **UK Smoking:**  
Survey of 1691 people, 12 variables (age, gender, education, smoking habits).  
➥ **Salary:**  
Simple regression with 30 observations — years of experience vs salaries.

---

##  Analysis Method

### Pearson’s Correlation:
➥ To measure the strength and direction of relationships.  
➥ **Key observation:**  
- Positive strong Pearson's (0.83) between tenure and total charges.  
- Positive weak Pearson's (0.24) between tenure and Monthly Charges.

### Chi-Squared:
➥ To test for independence between two categorical variables.  
➥ Hypotheses:
- H0: There is no association.
- H1: There is a significant association.

➥ **Key observation:**  
- Between gender and smoking: p > 0.05 (Not significant)  
- Between education and smoking: p < 0.05 (Significance)

### Linear Regression:
➥ To predict salaries from years of experience.  
➥ Model formula:
Salary = 9449.96 × YearsExperience + 24848.20

➥ The slope (9449.96) shows salaries increase by about $9,450 for each additional year of experience.

---

##  Key Findings and Insights

 Pearson’s:  
- Customer tenure positively correlates with total charges.  
- Higher experience corresponds to greater salaries.

 Chi-Squared:  
- There is no significant relation between gender and smoking.  
- There is a significant relation between education and smoking habits.

 Linear Regression:  
- The regression formula accurately shows salaries grow with experience.

---

##  Links to Code

➥ [Telco Churn Pearson's and Chi-Squared Analysis (Colab)](https://colab.research.google.com/)  
➥ [UK Smoking Chi-Squared Analysis (Colab)](https://colab.research.google.com/)  
➥ [Salary Linear Regression (Colab)](https://colab.research.google.com/)  

---

 If you'd like more details or a walkthrough, please feel free to [contact me](mailto:annizamegabianalyst@gmail.com).
