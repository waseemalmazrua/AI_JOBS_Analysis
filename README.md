# 📊 AI Jobs Salary Analysis – 2025

This repository presents an in-depth analysis of over **15,000 AI-related job records** to uncover salary trends, role insights, and predictive modeling outcomes across the AI job market.

---

## 🔍 Key Findings

* **AI Specialist** has the **highest average salary**, though it appears the least in the dataset — suggesting high value and scarcity.
* Most common job roles:

  * Machine Learning Researcher
  * AI Software Engineer
  * Autonomous Systems Engineer
 
    
* **Top-paying industries**:

  * Consulting
  * Manufacturing
  * Media
  * Education
  * Real Estate
    
* Salary data is **right-skewed**, meaning most salaries fall below the average while a few high earners increase the mean.
* Strongest positive correlations with salary were:

  * `experience_level` (**r = 0.76**)
  * `years_experience` (**r = 0.74**)

---

## 🧠 Predictive Modeling

Two regression models were developed to estimate salary based on job features:

* **Linear Regression (log-transformed target)**

  * Train R² Score: **0.9646**
  * Test R² Score: **0.9648**
  * Test MSE: **0.0086**

* **Random Forest Regressor (log-transformed target)**

  * Train R² Score: **0.9999**
  * Test R² Score: **0.9999**
  * Test MSE: **6.83e-08**

> Log-transformation of the salary variable significantly improved model accuracy by correcting skewness and stabilizing variance.

### ✅ Summary:

* Linear Regression is highly interpretable and performed excellently after log transformation.
* Random Forest achieved nearly perfect prediction performance but at the cost of reduced interpretability and higher complexity.

---

## 📂 Data Source & Methodology

Data collected via **ethical web scraping** from leading job platforms:

* LinkedIn Jobs
* Indeed
* Glassdoor
* AngelList
* Stack Overflow Jobs
* Company Career Pages

**Period:** January 2024 – May 2025
**Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)

---

## 📁 Repository Contents

* `AI_jobs.ipynb` — Full notebook with data cleaning, EDA, visualization, and regression modeling
* `README.md` — Overview and summary of the project

---

## 🚀 Author

**Waseem Almazrua**
[LinkedIn Profile](https://www.linkedin.com/in/waseemalmazrua/)
[GitHub Profile](https://github.com/waseemalmazrua)

---

### 📊 Want to Learn More?

Explore the full notebook and try running the model with your own input features to predict AI job salaries based on experience level, skills, and job type!
