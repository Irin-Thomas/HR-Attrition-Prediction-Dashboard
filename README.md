# 📊 HR Attrition Analysis using Power BI & Logistic Regression

## 🔍 Overview

This project investigates employee attrition within an organization by analyzing an HR dataset. The goal is to identify key factors that influence employee turnover and provide actionable insights for HR strategy and employee retention. The project uses **Power BI for data visualization** and **Binary Logistic Regression** for predictive modeling.

---

## 📂 Project Structure
- dashboard/ → Power BI .pbix file [https://github.com/Irin-Thomas/HR-Attrition-Prediction-Dashboard/blob/main/dashboard/powerbi%20hr%20attrition%20trail.pbix] 
- data/ → Dataset used in the model [https://github.com/Irin-Thomas/HR-Attrition-Prediction-Dashboard/blob/main/data/hr%20attrition%20dataset.csv]
- docs/ → Final project report (PDF) [https://github.com/Irin-Thomas/HR-Attrition-Prediction-Dashboard/blob/main/docs/HR%20ARTITION.pdf]
- figures/ → Screenshots of the dashboard  [https://github.com/Irin-Thomas/HR-Attrition-Prediction-Dashboard/blob/main/figures/HR%20Attrition%20Dataset.png]

---

## 📌 Key Objectives

- Understand and explore HR attrition trends
- Identify the most significant features affecting attrition
- Build and evaluate a **Binary Logistic Regression model**
- Use **Power BI** to present insightful visualizations

---
## 💡 Key Features
- Interactive filtering by department, gender, satisfaction levels
- Predictive modeling using Power BI's Key Influencers visual
- Visualization of attrition breakdown, KPI cards, and summary tables

  
## 📚 Dataset Details

- **Source**: [data.world](https://data.world/juhipathak7/hr-attrition-data)
- **Size**: 1470 employees
- **Attrition Rate**: 16.1% (237 employees left)

---

## 🧪 Methodology

### 1. **Data Preparation**
- Removed irrelevant columns (e.g., BusinessTravel, MaritalStatus, JobRole)
- Converted categorical variables (Yes/No → 1/0)
- Pivoted and normalized categorical values
- Created `Initial Dataset` and `Final Dataset` for comparison

### 2. **Exploratory Data Analysis**
- Visualized attrition trends with:
  - Donut Chart (Overtime impact)
  - Scatter Plot (Distance vs Age)
  - Bar/Line Charts (Job Role, Years at Company)
  - Matrix Cards (Accuracy, Count)

### 3. **Model Selection**
- Chose **Binary Logistic Regression** due to binary nature of target variable (Attrition: Yes/No)
- Compared with alternative models (KNN, Regularized LR) — Logistic Regression selected for interpretability

### 4. **Model Evaluation**
- Accuracy: **85%**
- F1 Score: **0.34**
- Key Influencers:
  - Overtime (Odds Ratio: 2.28)
  - Distance From Home (1.23)
  - Year Since Last Promotion (1.73)

---

## 📊 Power BI Visuals

- Line Chart: Attrition vs Years at Company
- Donut Chart: Overtime distribution
- Scatter Plot: Age vs Distance from Home
- Stacked Bar Chart: Attrition by Age Group
- Matrix: Job Satisfaction across Departments
- Dashboard link: [Power BI Report](https://app.powerbi.com/groups/me/reports/5da343c9-ac1c-466c-8f49-ee28f1fd20e0)

---

## 📈 Results

| Metric        | Value     |
|---------------|-----------|
| Model Accuracy| 85%       |
| F1 Score      | 0.34      |
| Top Feature   | Overtime  |
| Evaluation    | Confusion Matrix, ROC Curve, Coefficients |

---

## ✅ Recommendations

- Focus retention efforts on employees:
  - Who frequently work overtime
  - With long commute distances
  - Who haven’t been promoted recently
- Introduce wellness & flexibility programs to mitigate turnover risks
- Tailor strategies for high-risk job roles (e.g., Research Scientists, Lab Technicians)

---

## 📚 References

Citations and source materials are listed in the final report PDF [`HR_ATTRITION_IRIN.pdf`](report/HR_ATTRITION_IRIN.pdf).

---

## 📬 Contact

**Author**: Irin Mary Thomas  
**Email**: irinthomas0@gmail.com  





