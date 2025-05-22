# Investigate a Dataset: No-show Medical Appointments

---

## 📝 Project Overview  
This project analyzes a dataset containing 100,000 medical appointments in Brazil to understand why patients miss their medical appointments. The focus is on uncovering key factors like age, gender, socioeconomic status, health conditions, and SMS reminders that may influence no-show behavior.

The goal is to provide data-driven insights that healthcare providers can use to improve patient engagement and reduce appointment absenteeism.

---

## 📂 Dataset Description  
The dataset includes:

- **Patient demographics:** age, gender  
- **Medical conditions:** diabetes, hypertension, alcoholism, handicap  
- **Appointment details:** date, neighborhood, SMS reminders  
- **Financial aid status:** participation in Bolsa Família program  
- **Outcome:** whether the patient showed up (No-show column)

This rich set of features enables a multi-dimensional analysis of attendance patterns.

---

## 🎯 Key Research Questions  
This analysis aims to answer:

- **Does age affect appointment attendance?**  
  → Are younger or older patients more likely to miss appointments?

- **What is the impact of socioeconomic factors?**  
  → Do patients under Bolsa Família aid show higher no-show rates?

- **Do SMS reminders improve attendance?**  
  → Does sending reminders help reduce no-shows?

- **Are there geographic patterns?**  
  → Do certain neighborhoods have consistently high no-show rates?

- **Does gender play a role?**  
  → Are there attendance differences between male and female patients?

---

## 🛠 Tools and Libraries  

- **Python** 
- `Pandas` for data manipulation  
- `NumPy` for numerical operations  
- `Matplotlib` & `Seaborn` for visualizations

---

## 🔍 Project Workflow  

### 1️⃣ Data Wrangling  
- Load dataset using Pandas  
- Inspect for missing or inconsistent values  
- Clean data by:  
  - Removing invalid ages (negative values)  
  - Converting date fields to datetime objects  
  - Standardizing categorical values  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Generate summary statistics  
- Use bar charts for categorical features (e.g., gender, scholarship, SMS received)  
- Apply scatter plots to explore age vs. no-show trends  
- Draw box plots to compare distributions across groups  
- Create histograms for age distributions  
- Run correlation analysis to understand relationships  

---

## 3️⃣ Key Findings  
- Summarize which factors have the strongest impact on no-shows  
- Highlight surprising or notable trends (e.g., age group patterns, SMS effectiveness)  
- Provide potential recommendations based on insights  

---

## 📊 Example Visualizations  
- **Bar charts:** Showed no-show rates by gender and scholarship  
- **Scatter plots:** Age vs. attendance status  
- **Box plots:** Age distributions for no-show vs. show-up groups  
- **Heatmaps:** Correlation matrix to spot inter-feature relationships  

---

## 💡 Conclusions  
Based on the analysis:

- Identify high-risk groups for no-shows  
- Assess whether SMS reminders effectively reduce absenteeism  
- Recommend focused interventions (e.g., extra follow-ups for certain neighborhoods or age groups)


---
## 👨‍💻 Authors
This project was developed by:
- **Yazeed Hamdan**
  
---

## 📫 Contact
For any questions or discussions, feel free to reach out:

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yazedyazedl2020@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/yazeed-hamdan-59b83b281/)  
