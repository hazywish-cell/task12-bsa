# 🩺 Healthcare Diabetes Analysis & Interactive Tableau Dashboard

An end-to-end exploratory data analysis (EDA) and interactive dashboard built using **Tableau Public** on a healthcare dataset of 768 patient records to analyze key risk factors associated with diabetes.

---

## 🔗 Project Links

* **Live Interactive Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/priya.sree4870/viz/task12_17915357167170/Dashboard1#1) 👈 *(Replace with your link)*

---

## 📌 Project Overview & Objectives

The primary objective of this task was to analyze health metrics—including Glucose levels, BMI, Age, and Pregnancy count—to uncover significant patterns, trends, and correlations related to diabetes diagnosis.

### Requirements Fulfilled:
* **Visualizations:** Minimum of 4 distinct chart types (Line Chart, Scatter Plot, Treemap, and Heatmap).
* **Interactivity:** At least 2 dynamic filters (`Glucose Group` and `Diabetes Status`) applied across all dashboard worksheets.
* **Dashboard:** 1 unified, interactive Tableau dashboard layout.
* **Analytical Deliverables:** Key findings, strategic suggestions, actionable recommendations, and an overall conclusion.

---

## 📊 Dataset Summary

* **Source File:** `health care diabetes.xlsx`
* **Total Records:** 768 Patients
* **Target Outcome:** Binary classification (`0`: Non-Diabetic, `1`: Diabetic)
* **Prevalence:** 500 Non-Diabetic (65.1%) vs. 268 Diabetic (34.9%)
* **Key Fields Analyzed:** `Glucose`, `BMI`, `Age`, `Pregnancies`, `BloodPressure`, `Insulin`, `DiabetesPedigreeFunction`

---

## 📈 Visualizations Built

1. **Line Chart (Pregnancies vs. Diabetes Risk):** Demonstrates the upward trend of diabetes rate relative to pregnancy count.
2. **Treemap (Glucose Category Breakdown):** Visualizes the proportion of patients across Normal ($<100\text{ mg/dL}$), Prediabetes ($100–140\text{ mg/dL}$), and High ($>140\text{ mg/dL}$) glucose ranges.
3. **Risk Heatmap (Age Group vs. BMI Group):** Identifies critical high-density risk hotspots combining body mass index and age brackets.
4. **Scatter Plot (BMI vs. Glucose):** Highlights clustering and correlations between elevated glucose levels and BMI across diabetes outcomes.

---

## 💡 Key Findings

1. **Glucose as the Primary Indicator:** Fasting glucose displays the strongest linear correlation ($r = 0.47$) with diabetes outcomes. Patients with glucose levels exceeding $140\text{ mg/dL}$ exhibit a **68.8%** prevalence rate compared to **8.1%** for normal glucose levels ($<100\text{ mg/dL}$).
2. **Age-Related Risk Elevation:** Diabetes prevalence jumps significantly past age 30. Only **21.6%** of patients aged 21–30 tested positive, whereas the prevalence rate increases to **48.4%** for ages 31–40 and peaks at **57.4%** for ages 51–60.
3. **Compounding Obesity Impact:** Patients in normal BMI ranges ($18.5–24.9$) present a low diabetes rate of **6.9%**, while those classified as Obese Class I ($30–34.9$) and Obese Class II+ ($\ge 35$) face prevalence rates of **45.1%** and **47.6%** respectively.

---

## 🎯 Suggestions & Recommendations

* **Targeted Clinical Screening (Suggestion):** Implement routine, automated diabetes testing for all patients over 30 years old whose BMI exceeds $30\text{ kg/m}^2$, regardless of initial symptoms.
* **Early Preventive Intervention (Recommendation):** Launch public health nutritional and weight management programs aimed at younger demographics (ages 20–30) to curb BMI escalation prior to age-related metabolic decline.

---

## 📝 Overall Conclusion

Analysis of the dataset confirms that glucose level, age, and BMI are the three primary determinants of diabetes diagnosis. Managing body mass index prior to age 30 and maintaining fasting glucose levels below $100\text{ mg/dL}$ represent the most effective preventative strategies against diabetes progression.
