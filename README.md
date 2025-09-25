# Employee Performance Insights: A Data-Driven Approach

This project analyzes **employee performance drivers** to help organizations improve productivity, optimize hiring, and reduce turnover. Using statistical and machine learning models, we identified the factors most strongly linked to performance and provided actionable recommendations for workforce management.

## Project Overview

* **Business Problem:** Organizations often lack data-driven insights into what drives high employee performance. This limits effective hiring, training, and retention strategies.
* **Approach:** Built predictive models to identify key performance drivers and compared different modeling techniques.
* **Outcome:** Age, experience, and work hours per week emerged as the strongest predictors of performance.

## Skills Demonstrated

* **Exploratory Data Analysis (EDA):** Cleaning, transforming, and visualizing employee data.
* **Statistical Modeling:** Built Multiple Linear Regression (MLR), Random Forest, and XGBoost models.
* **Model Evaluation:** Compared models using MAE, MSE, and MAPE. MLR performed best, balancing accuracy and interpretability.
* **Feature Selection:** Applied stepwise AIC and Group LASSO to identify top predictors.
* **Business Translation:** Converted technical findings into clear recommendations for HR and leadership.

## Tools & Technologies

* **R / RStudio**
* R packages: `caret`, `glmnet`, `randomForest`, `xgboost`
* Dataset: `employee_performance.csv` (demographic and work-related attributes)

## Repository Contents

* **`MGT6203_project.html`** – HTML notebook with code, analysis, and outputs.
* **`annotated-Final_Presentation_Team115.pptx.pdf`** – Final presentation slides summarizing findings and business implications.
* **`employee_performance.csv`** – Dataset used for analysis.

## Key Findings

* **Predictors:** Age, experience, and weekly work hours are the strongest drivers of performance.
* **Model Results:** MLR (reduced version) outperformed Random Forest and XGBoost on predictive accuracy.
* **Insights:**

  * Hire and assign tasks based on **experience and skills**.
  * **Reward additional work hours** with incentives.
  * Develop **age- and experience-specific training programs** to boost performance and retention.

## Business Impact

* Refined recruitment processes by focusing on traits tied to high performance.
* Tailored development programs and mentoring for younger/less experienced employees.
* Optimized resource allocation to align workforce strengths with organizational needs.

## Lessons Learned

* Simpler, interpretable models can outperform complex ones when explaining employee performance.
* Data quality and feature selection are critical for effective workforce analytics.
* Bridging technical analysis with actionable business recommendations is key for impact.

## Credits

Project completed for Data Analytics for Business (MGT 6203) at **Georgia Tech** by my teammates and myself:

* Diane Egret
* Arya Kalappurayil
* Ivory Peng
* Xinfeng Feng
