# CGPA Prediction using Multiple Linear Regression

A data analysis project using **Multiple Linear Regression Model (MLRM)** to study how student habits such as high school GPA, sleep hours, and study time affect current academic performance (CGPA). Implemented in **RStudio** as part of a **Probability and Statistics** course project.

---

## 📌 Project Overview

This project aims to analyze the relationship between students’ habits and their university academic performance using a Multiple Linear Regression Model (MLRM). The focus is on predicting CGPA based on:

- High School GPA
- Average Sleep Hours
- Weekly Study Time
- Mean Attendance

Data was collected through **Google Forms** and **in-person surveys** from a diverse group of students.

---

## 🔍 Objective

To quantify the effect of different independent variables on CGPA and determine which factors significantly influence academic performance.

---

## 🧮 Independent Variables

- **High School GPA** – Reflects previous academic capability.
- **Sleep Time** – Average daily hours of sleep.
- **Study Time** – Hours spent studying per week.
- **Mean Attendance** – Attendance percentage throughout the semester.

---

## 🎯 Dependent Variable

- **University GPA (CGPA)** – Represents current academic performance.

---

## 📊 Summary of Data

- **CGPA Range**: 2.000 – 3.880 (Mean: 2.980)
- **High School %**: 61.00 – 97.00 (Mean: 74.93)
- **Study Time**: 6 – 11 hrs/week (Mean: 8.44)
- **Sleep Time**: 3 – 10 hrs/day (Mean: 6.11)
- **Attendance**: 75% – 100% (Mean: 87.85%)

---

## 📈 Visualizations & Insights

### 📦 Box & Whisker Plots

- **CGPA, Sleep Time, Study Time**: Symmetric and consistent distribution.
- **High School %**: Slight positive skew; greater variability.
- **Attendance**: Symmetric and tightly clustered around 87%.

### ⚪ Scatter Plots

- **CGPA**: Tightly grouped, indicating consistent performance.
- **High School %**: Broad variability across students.
- **Study & Sleep Time**: Clustered patterns, consistent habits.

---

## 📉 MLRM Diagnostic Plots

- **Residuals vs Fitted**: Slight non-linearity observed.
- **Q-Q Plot**: Mostly normal residuals with heavier tails.
- **Scale-Location**: Mild heteroscedasticity for higher values.
- **Residuals vs Leverage**: Influential points (Obs 65 & 66) detected.

---

## 📊 Model Performance

- **R-squared**: 0.998 — model explains 99.8% of variance.
- **Adjusted R-squared**: Nearly identical — model is not overfitted.
- **Error terms**: Small residuals, no major outliers.

### 📌 Key Takeaways

- **Important Predictors**: Study Time and Attendance.
- **Less Impactful Predictors**: High School GPA, Sleep Time.
- **Next Steps**: Model optimization by removing insignificant predictors or applying transformations for non-linear behavior.

---

## 🧠 Tools Used

- **RStudio** – for statistical modeling and visualization.
- **Google Forms** – for data collection.
- **ggplot2**, **base R plots** – for graphs and diagnostic visuals.
