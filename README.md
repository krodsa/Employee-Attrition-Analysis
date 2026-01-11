# 📊 Employee Attrition Analysis  
[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)
[![Tableau](https://img.shields.io/badge/Visualization-Tableau-blue.svg)](https://public.tableau.com/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-black.svg)](https://github.com/krodsa/Employee-Attrition-Analysis)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

An end-to-end workforce analytics project combining Python-based statistical analysis, predictive modeling, and an interactive Tableau dashboard to uncover drivers of employee turnover and support strategic HR decision-making.

---

## 📚 Table of Contents
- [Background](#-background)
- [Project Overview](#-project-overview)
- [Executive Summary](#-executive-summary)
- [Methodology](#-methodology)
  - [Data Preparation](#1-data-preparation)
  - [Exploratory Data Analysis (Python)](#2-exploratory-data-analysis-python)
  - [Predictive Modeling](#3-predictive-modeling)
  - [Visualization & Storytelling (Tableau)](#4-visualization--storytelling-tableau)
- [Notebooks & Dashboards](#-notebooks--dashboards)
- [Dataset](#-dataset)
- [Limitations](#-limitations)
- [Future Enhancements](#-future-enhancements)
- [Contact](#-contact)

---

## 📌 Background  
Employee turnover poses a significant challenge for organizations, influencing productivity, talent continuity, and long-term business stability. This project analyzes an anonymized employee dataset containing demographic information, compensation tiers, domain experience, bench-status indicators, and employment history. The goal is to explore workforce patterns that contribute to attrition and to generate predictive insights that support proactive workforce planning and retention strategies.

---

## 🎯 Project Overview  
The analysis examines employee attributes across demographic, financial, and job-history dimensions, including:

- **Payment Tier** (compensation band)  
- **Experience in Current Domain**  
- **EverBenched** (periods without project assignment)  
- **Education Level**  
- **City / Work Location**  
- **Joining Year & Employment Tenure**  
- **Age and Gender**  
- **LeaveOrNot** (attrition label)

Core objectives of this project include:

- Identifying key drivers associated with employee turnover  
- Detecting attrition trends and patterns over time  
- Building a predictive model to estimate the likelihood of attrition  
- Visualizing insights in an interactive Tableau dashboard for business stakeholders  

---

## 🧠 Executive Summary  

### 🔹 Key Drivers of Attrition  
Analysis and machine learning model outputs reveal:

- **Lower Payment Tiers** strongly correlate with higher attrition  
- Employees who have been **benched (EverBenched = Yes)** show higher turnover likelihood  
- **Lower domain experience** is associated with higher mobility  
- **Younger employees** tend to exhibit higher attrition levels  
- Certain **locations (City)** show consistently higher turnover rates  

These factors create meaningful opportunities for targeted retention strategies.

### 🔹 Workforce Trends  
- Attrition counts varied substantially year over year from 2012–2018  
- Some cities appear to experience higher exit rates  
- Employees in lower compensation tiers or with limited experience show higher risk  

### 🔹 Predictive Modeling  
A classification model was developed using Python to identify employees with elevated attrition risk. The model provides likelihood scores that can be applied for proactive HR intervention.

### 🔹 Forecasted Attrition (2019–2021)  
Using the trained model, predicted attrition counts were estimated for future years:

- **2019:** 239  
- **2020:** 262  
- **2021:** 286  

These predictions are visualized alongside historical attrition to illustrate potential future trends.

---

## 🛠️ Methodology  

### 1. Data Preparation  
- Cleaned, standardized, and validated employee data  
- Handled missing values and normalized categorical fields  
- Created derived features such as tenure and domain experience groups  

### 2. Exploratory Data Analysis (Python)  
- Summary statistics and distribution assessments  
- Visual analysis of attrition by PaymentTier, City, Domain Experience, Age, Bench Status  
- Trend analysis of yearly attrition counts (2012–2018)  

### 3. Predictive Modeling  
- Trained classification models (e.g., logistic regression, tree-based models)  
- Evaluated accuracy, precision, recall, and feature importance  
- Generated future attrition predictions (2019–2021)  
- Exported predictions to Tableau for visualization  

### 4. Visualization & Storytelling (Tableau)  
- Built a dashboard showing:  
  - Attrition by demographics  
  - Attrition by compensation tier  
  - Attrition by city  
  - **Actual (2012–2018) vs. Predicted (2019–2021) Attrition Trend**  
- Designed interactive filters for exploratory insight generation  

---

## 📓 Notebooks & Dashboards  

### 📘 Python Notebook  
Full analysis, modeling, and prediction workflow:  
➡️ https://nbviewer.org/github/krodsa/Employee-Analysis/blob/main/Employee%20Attrition%20Analysis.ipynb  

### 📊 Tableau Dashboard  
Interactive visual summary and attrition trend forecast:  
➡️ [https://public.tableau.com/app/profile/krodsa/viz/EmployeeAttritionDashboard_17344953568520/AttritionDashboard](https://public.tableau.com/views/EmployeeAttritionDashboard_17344953568520/HREmployeeAttritionDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

---

## 📂 Dataset  
The dataset includes the following fields:

- **Employee_ID** (anonymous identifier)  
- **Gender, Age, Education Level, Marital Status**  
- **City** (work location)  
- **PaymentTier** (compensation level)  
- **Joining Year**  
- **EverBenched** (Yes/No project bench periods)  
- **ExperienceInCurrentDomain**  
- **LeaveOrNot** (0 = stayed, 1 = left)

This structure enables both exploratory analysis and predictive modeling of employee attrition.

---

## ⚠️ Limitations  
- Dataset is anonymized and may not capture all nuances of real-world HRIS systems  
- Does not include satisfaction or engagement metrics  
- Some variables are simplified compared to enterprise HR datasets  
- Predictions should be interpreted directionally  

---

## 🚀 Future Enhancements  
- Incorporate additional behavioral or performance variables  
- Deploy the predictive model via an API or lightweight web app  
- Add retention strategy simulations based on model outputs  
- Expand Tableau dashboard with department-level analytics  

---

## 📬 Contact  
Feel free to reach out with questions or collaboration ideas related to workforce analytics, predictive modeling, or dashboard design.

