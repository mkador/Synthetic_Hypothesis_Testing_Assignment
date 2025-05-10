# 📊 Statistical Hypothesis Testing with Sample Size Calculation

This repository contains a comprehensive Python notebook focused on performing statistical hypothesis tests and sample size calculations using synthetic datasets. It follows the standard statistical workflow from data generation and assumption checking to hypothesis testing and result interpretation.

---

## 🧪 Project Objectives

- Apply different statistical hypothesis tests.
- Define and test statistical hypotheses (null and alternative).
- Check assumptions for each test:
  - **Normality** (Shapiro-Wilk test, visual inspection)
  - **Homogeneity of Variance** (Levene’s test)
- Choose appropriate statistical tests (parametric or non-parametric).
- Interpret statistical test results.
- Calculate required sample size using power analysis.

---

## 📁 Files Included

- `Synthetic_Hypothesis_Testing_Assignment.ipynb`: Main Jupyter Notebook containing:
  - Data generation and visualization
  - Assumption checks
  - Hypothesis test selection and execution
  - Test output interpretation
  - Sample size calculation using `statsmodels`

---

## 🧬 Statistical Tests Used

- **Shapiro-Wilk Test** for normality
- **Levene’s Test** for equal variances
- **Independent t-test** (parametric)
- **Mann-Whitney U Test** (non-parametric)
- **Sample Size Calculation** using power analysis (`TTestIndPower`)

---


## 📝 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/mkador/hypothesis-testing-assignment.git
   cd hypothesis-testing-assignment
pip install -r requirements.txt
jupyter notebook Synthetic_Hypothesis_Testing_Assignment.ipynb

## 🔍 Example Hypothesis
Null Hypothesis (H₀): There is no significant difference in conversion rates between Group A and Group B.

Alternative Hypothesis (H₁): There is a significant difference in conversion rates between Group A and Group B.

## 📈 Sample Size Calculation
Using power analysis to calculate the minimum required sample size to detect a given effect size with sufficient power (typically 80%) and significance level (α = 0.05).

## 📚 Libraries Used
numpy

pandas

matplotlib

seaborn

scipy.stats

statsmodels

## 🧑‍💻 Author
Md. Musa Kalimulla
Data Science & Machine Learning Engineer
Email: mkador169@gmail.com
