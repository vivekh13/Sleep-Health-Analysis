# 🌙 Decoding Sleep Health
### An Exploratory Data Analysis of Sleep Health & Sleep Disorder Factors

[[https://img.shields.io/badge/Python-3.10%2B-blue?logo=python]](https://www.python.org/)
[[https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter]](https://jupyter.org/)
[[https://img.shields.io/badge/License-MIT-yellow.svg]](LICENSE)

---

## 📌 Project Overview
This project is an Exploratory Data Analysis (EDA) investigating how daily lifestyle habits, professional occupations, and physiological vital signs correlate with sleep quality and sleep disorders (**Insomnia** and **Sleep Apnea**).

Using Python, Pandas, and Matplotlib/Seaborn, we cleaned raw sleep health data, removed repeated medical records, analyzed key patterns across demographics, and evaluated the relationship between stress and sleep quality.

---

## 👥 Project Team
- **Ganesh**
- **Neha**
- **Vivek**
- **Anushka**
- **Mahima**
- **Mohd Fuzail**

---

## 📊 Dataset & Data Cleaning
- **Original Dataset**: 374 patient entries across 13 health and demographic features.
- **De-duplication**: Identified and removed 242 repeated patient records, narrowing the data down to **132 unique individuals**.
- **Categorical Cleaning**: Standardized labels (e.g., `Normal Weight` → `Normal`, `Sales Representative` → `Salesperson`).
- **Blood Pressure Parsing**: Transformed text strings (`120/80`) into numeric `Higher_BP` (systolic) and `Lower_BP` (diastolic) columns.
- **Comparison Sample**: Filtered out healthy individuals ("None") to form a balanced comparative group of **59 disorder cases** (29 Insomnia vs. 30 Sleep Apnea).

---

## 🔍 Key Insights & Findings

1. **Sleep Duration & Quality**:
   - **Insomnia**: Average sleep duration of **6.68 hours** and sleep quality of **6.52 / 10**.
   - **Sleep Apnea**: Slightly higher averages of **6.94 hours** and **6.87 / 10** quality.

2. **Stress vs. Sleep Quality Correlation**:
   - A strong negative correlation (**r = -0.884**) shows that higher stress strongly aligns with declining sleep quality. Between stress levels 3 and 8, average sleep quality drops from 9.0 to 5.6.

3. **Occupational Trends**:
   - **High Sleep Apnea**: Nurses (85%) and Scientists (100%).
   - **High Insomnia**: Teachers (72.7%), Salespeople (75%), Accountants (100%), and Software Engineers (100%).

4. **Age, Gender & BMI Patterns**:
   - **Age**: Participants aged 50+ showed the highest proportion of Sleep Apnea (73.3%), whereas ages 40–49 showed more Insomnia (66.7%).
   - **Gender**: In this dataset, 61.8% of female disorder records were Sleep Apnea, while 64.0% of male disorder records were Insomnia.
   - **BMI & Vitals**: Obese individuals had a higher incidence of Sleep Apnea (57.1%) alongside higher average systolic (134.87) and diastolic (90.00) blood pressure.

*Note: These observations represent statistical patterns within the sample and do not establish direct clinical causation.*

---

