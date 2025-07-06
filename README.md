# 📊 Business Statistics Project – Healthcare & Customer Satisfaction Analytics

This project applies **statistical modeling, data visualization, and predictive analysis** to two real-world datasets in the healthcare and customer satisfaction domains. Using **R and RMarkdown**, we performed hypothesis testing, built classification models, and presented insights through interactive reports.  

---

## Repository Contents

| File                          | Description                                                                               |
|--------------------------------|-------------------------------------------------------------------------------------------|
| `Cardio_Vascular_Disease.csv` | Dataset containing patient health metrics for cardiovascular disease risk prediction.     |
| `cust_satisfaction.csv`       | Customer survey data measuring satisfaction across multiple service parameters.           |
| `5646570.Rmd`                 | RMarkdown file containing data cleaning, analysis, and visualization code.               |
| `5646570.html`                | Rendered HTML report with detailed insights, charts, and model results.                  |

---

## Project Overview

This project aimed to:
- Analyze cardiovascular health and customer satisfaction data.
- Perform **exploratory data analysis (EDA)** to identify patterns and anomalies.  
- Test hypotheses to assess relationships between key variables.  
- Build **predictive models** for cardiovascular risk and customer churn probability.  
- Present results in an **interactive HTML report** for decision-making.

---

## Datasets Used

### Cardio_Vascular_Disease.csv
- **Records**: 70,000+ patient entries  
- **Features**:
  - `age`, `gender`, `cholesterol`, `smoke`, `alco`, `active`, `gluc`, `bp_sys`, `bp_dia`, `cardio` (target variable)  
- **Objective**: Predict whether a patient has cardiovascular disease based on health indicators.

### cust_satisfaction.csv
- **Records**: 1,000+ customer survey responses  
- **Features**:
  - `customer_id`, `age_group`, `gender`, `satisfaction_score`, `service_quality`, `responsiveness`, `recommendation`  
- **Objective**: Understand drivers of customer satisfaction and predict likelihood to recommend the service.

---

## Key Analysis & Insights

### Cardiovascular Dataset
- Performed **hypothesis testing** (chi-square, t-tests) to explore relationships between lifestyle factors and cardiovascular risk.  
- Built a **logistic regression model**:  
  - **Accuracy**: 88%  
  - **Key Predictors**: `age`, `cholesterol`, `smoking`, and `physical activity`.  
- Identified high-risk segments (e.g., older males with high cholesterol and sedentary lifestyle).  

---

### Customer Satisfaction Dataset
- Conducted EDA to visualize satisfaction distribution across demographics.  
- Ran **ANOVA tests** to assess how satisfaction varies by `age_group` and `service_quality`.  
- Developed a classification model:  
  - **Accuracy**: 82%  
  - **Key Drivers**: Service responsiveness and perceived quality strongly impact recommendation likelihood.  

---

## 📊 Results Summary

| Dataset                     | Model Used            | Accuracy | Key Outcomes                                               |
|------------------------------|------------------------|----------|-------------------------------------------------------------|
| Cardiovascular               | Logistic Regression    | 88%      | Identified top predictors of cardiovascular disease risk.   |
| Customer Satisfaction        | Logistic Classification| 82%      | Highlighted key factors driving customer recommendations.   |

- Created **interactive charts** (ggplot2) for stakeholder presentations.  
- Delivered a rendered HTML report summarizing actionable recommendations.

---

## Tools & Technologies
- **Programming**: R  
- **Libraries**: ggplot2, dplyr, tidyr, caret, readr  
- **Visualization**: ggplot2, RMarkdown  
- **Reporting**: HTML reports via `rmarkdown::render()`  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/aarushidhaka/Business-Statistics-Project-2.git
2. Open 5646570.Rmd in RStudio.
3. Knit the RMarkdown file to HTML or PDF to view results.
