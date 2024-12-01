# Swire Coca-Cola Capstone Modeling

This portfolio highlights the **Swire Coca-Cola Capstone Project**, focusing on the use of a **Random Forest Regressor** to impute missing values and predict machine failures. The goal of the project is to reduce downtime and improve operational efficiency through predictive modeling. Click the links below to view the code and analysis on my GitHub page.

## [EDA Notebook: Exploratory Data Analysis](https://github.com/SamRobinson123/GroupProjectRepo/blob/main/EDA.ipynb)
## [Modeling Assignment Notebook: Predictive Modeling](https://github.com/SamRobinson123/GroupProjectRepo/blob/main/ModelingAssignment.ipynb)
![Project Status](https://img.shields.io/badge/status-complete-green.svg)

### Business Problem
Swire Coca-Cola incurs an annual loss of approximately **$60 million** due to unplanned machine downtimes. Current maintenance practices are reactive, causing delays in repairs and productivity losses. The project aims to analyze machine data, identify key patterns, and build predictive models to forecast failures, enabling proactive maintenance.

### 🎯 Objective
The key objectives of this project are:
- Develop a **Random Forest Regressor** to impute missing values and predict machine failures.
- Utilize the model's predictions to transition maintenance workflows from reactive to proactive.
- Evaluate the model's performance using metrics such as **Root Mean Squared Error (RMSE)** and **R-squared**.

### 📊 Project Details

#### **EDA Highlights**
- **Dataset**: Contains operational metrics from Swire Coca-Cola's machines, including `FUNCTIONAL_LOC` (machine IDs) and `EQUIPMENT_ID` (component IDs).
- **Findings**:
  - Identified high-risk components and trends in unplanned machine downtimes.
  - Provided a foundation for feature engineering and predictive modeling.

#### **Random Forest Regressor Highlights**
- **Purpose**: Impute missing values and predict machine failure times.
- **Features Used**:
  - `SEGMENT_1` to `SEGMENT_6` (categorical variables).
  - Cumulative metrics such as `Cumulative_Equipment_Replacements` and `Unplanned_Rolling_12M`.
  - Time-based features like `Days_Since_Planned_Maintenance` and `Planned_Rolling_12M`.
- **Performance Metrics**:
  - **Root Mean Squared Error (RMSE)**: [Insert Value]
  - **R-squared**: [Insert Value]

---

### Takeaways
- The **Random Forest Regressor** is effective for imputing missing values and predicting machine failures.
- Feature engineering (e.g., categorical encoding) plays a critical role in improving model performance.
- The model provides actionable insights for transitioning from reactive to proactive maintenance workflows.
