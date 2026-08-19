# 🚛 FleetPulse – Smart Fleet Performance Analytics

![FleetPulse](https://img.shields.io/badge/Project-FleetPulse-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Prediction-green)

## 📌 Project Overview

**FleetPulse – Smart Fleet Performance Analytics** is an end-to-end Data Analytics and Machine Learning project designed to analyze fleet operations, identify performance inefficiencies, and predict potential fleet risks.

The project combines **Excel, MySQL, Python, Machine Learning, and Power BI** to convert raw fleet data into meaningful insights and predictive results.

The system helps fleet managers understand vehicle performance, fuel consumption, maintenance costs, trip efficiency, and operational risks to support **data-driven decision-making**.

---

## 🎯 Objectives

* Analyze overall fleet performance.
* Monitor vehicle and trip efficiency.
* Analyze fuel consumption and fuel efficiency.
* Identify high-performing and under-performing vehicles.
* Analyze maintenance and operational costs.
* Identify factors affecting fleet performance.
* Predict potential vehicle/fleet risks using Machine Learning.
* Create an interactive Power BI dashboard.
* Provide actionable business insights for fleet management.

---

## 🛠️ Technologies Used

| Technology          | Purpose                                 |
| ------------------- | --------------------------------------- |
| **Microsoft Excel** | Data cleaning and preprocessing         |
| **MySQL**           | Data storage and SQL analysis           |
| **Python**          | Data analysis and Machine Learning      |
| **Pandas**          | Data manipulation                       |
| **NumPy**           | Numerical analysis                      |
| **Matplotlib**      | Data visualization                      |
| **Seaborn**         | Exploratory data visualization          |
| **Scikit-learn**    | Machine Learning                        |
| **XGBoost**         | Advanced prediction                     |
| **Power BI**        | Interactive dashboard and visualization |

---

## 🔄 Project Workflow

```text
Raw Fleet Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Excel
        ↓
MySQL Database
        ↓
SQL Queries & Analysis
        ↓
Python EDA
        ↓
Feature Engineering
        ↓
Machine Learning Model
        ↓
Prediction
        ↓
Power BI Dashboard
        ↓
Business Insights
```

---

# 📊 Data Analysis

FleetPulse performs exploratory and business analysis to understand fleet operations.

### Key Analysis Areas

* Vehicle performance
* Trip performance
* Fuel consumption
* Fuel efficiency
* Distance travelled
* Maintenance cost
* Operational cost
* Vehicle utilization
* Driver performance
* Route performance
* Monthly performance trends

### Important KPIs

#### 🚗 Total Vehicles

Measures the total number of vehicles available in the fleet.

#### 🛣️ Total Distance

Measures the total distance travelled by the fleet.

#### ⛽ Fuel Consumption

Analyzes the amount of fuel consumed by individual vehicles and the overall fleet.

#### 📈 Fuel Efficiency

```text
Fuel Efficiency = Distance Travelled / Fuel Consumed
```

Higher fuel efficiency indicates better vehicle performance.

#### 💰 Cost per Kilometer

```text
Cost per KM = Total Cost / Distance Travelled
```

This helps identify expensive vehicles and routes.

#### 🔧 Maintenance Cost

Analyzes maintenance expenses by vehicle and helps identify vehicles requiring frequent maintenance.

---

# 🗄️ SQL Analysis

MySQL is used to store and analyze the fleet dataset.

The project includes SQL operations such as:

* `SELECT`
* `WHERE`
* `ORDER BY`
* `GROUP BY`
* `HAVING`
* Aggregate functions
* `INNER JOIN`
* `LEFT JOIN`
* Subqueries
* Conditional filtering
* Ranking and performance analysis

### Example Business Questions

* Which vehicles have the highest fuel consumption?
* Which vehicles have the lowest fuel efficiency?
* Which routes generate the highest cost?
* Which vehicles have the highest maintenance expenses?
* What is the average distance travelled by vehicle?
* Which vehicles are performing below the fleet average?

---

# 🐍 Python Data Analysis

Python is used for data preprocessing, exploratory data analysis, feature engineering, and Machine Learning.

### Main Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

Python is used to:

* Handle missing values
* Remove duplicate records
* Detect outliers
* Analyze numerical variables
* Analyze categorical variables
* Generate visualizations
* Create features for Machine Learning
* Train and evaluate prediction models

---

# 🤖 Machine Learning Prediction

The prediction component of FleetPulse uses Machine Learning to identify potential fleet risks and performance issues.

## Algorithms Used

### 🌳 Decision Tree

Decision Tree provides an easy-to-understand rule-based approach for predicting fleet outcomes.

It can be used to identify conditions associated with:

* High fuel consumption
* Poor vehicle performance
* Maintenance requirements
* Fleet risk

### 🌲 Random Forest

Random Forest combines multiple decision trees to improve prediction performance and reduce overfitting.

It can be used for:

* Vehicle risk classification
* Maintenance prediction
* Performance prediction
* Fuel efficiency classification

### ⚡ XGBoost

XGBoost is an advanced gradient boosting algorithm used to improve prediction accuracy and capture complex relationships within the fleet data.

It can be used for:

* Fleet risk prediction
* Vehicle performance prediction
* Maintenance prediction
* Classification and regression problems

---

# 🔮 Prediction Output

Based on the selected target variable, vehicles can be categorized into different risk levels.

```text
Low Risk
Medium Risk
High Risk
```

### Example

```text
High Fuel Consumption
        +
Low Fuel Efficiency
        +
High Maintenance Cost
        ↓
High Fleet Risk
```

The prediction helps fleet managers identify vehicles that may require attention before they become major operational problems.

---

# 📈 Model Evaluation

The Machine Learning model is evaluated using suitable performance metrics.

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC

### Regression Metrics

* MAE
* MSE
* RMSE
* R² Score

The appropriate model is selected based on its performance and business requirements.

---

#  Power BI Dashboard

The Power BI dashboard provides an interactive overview of fleet performance.

## Dashboard Sections

### Fleet Overview

Displays:

* Total Vehicles
* Total Trips
* Total Distance
* Total Fuel Consumption
* Average Fuel Efficiency
* Total Maintenance Cost

### Vehicle Performance

Analyzes:

* Vehicle-wise performance
* Fuel efficiency
* Distance travelled
* Maintenance cost
* Vehicle utilization

### Fuel Analysis

Displays:

* Fuel consumption trends
* Fuel efficiency by vehicle
* Fuel consumption by route
* High fuel-consuming vehicles

### Maintenance Analysis

Displays:

* Maintenance cost by vehicle
* Maintenance frequency
* Vehicles requiring attention

### Prediction Analysis

Displays:

* Predicted risk category
* High-risk vehicles
* Medium-risk vehicles
* Low-risk vehicles
* Factors affecting prediction

---

# 💡 Key Insights

FleetPulse can answer important business questions such as:

* Which vehicles consume the most fuel?
* Which vehicles have the best fuel efficiency?
* Which vehicles have high maintenance costs?
* Which vehicles are underperforming?
* Which routes are more expensive?
* Which vehicles are underutilized?
* What factors influence fleet performance?
* Which vehicles are predicted to have higher risk?
* Where can operational costs be reduced?

---

# 📌 Business Benefits

FleetPulse helps organizations to:

* ⛽ Reduce fuel consumption
* 💰 Reduce operational costs
* 🔧 Improve preventive maintenance
* 🚗 Improve vehicle utilization
* 📊 Monitor fleet KPIs
* ⚠️ Identify high-risk vehicles
* 📈 Improve fleet productivity
* 🧠 Make data-driven decisions
* 🔮 Take proactive action using predictions

---

# 📁 Project Structure

```text
FleetPulse/
│
├── dataset/
│   └── fleet_data.xlsx
│
├── sql/
│   └── fleet_queries.sql
│
├── notebooks/
│   └── fleet_analysis.ipynb
│
├── model/
│   └── fleet_prediction_model.pkl
│
├── dashboard/
│   └── FleetPulse.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── requirements.txt
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/FleetPulse.git
```

## 2. Navigate to the Project

```bash
cd FleetPulse
```
## 3. Collect and Clean the Database
```Excel
csv
```
## 4. Upload to MySql Workbench
```
SQL queries
```

## 5. MySQL

Import the fleet dataset into MySQL and execute the SQL queries available in:

```text
sql/fleet_queries.sql
```

## 6. Power BI

Open:

```text
dashboard/FleetPulse.pbix
```

and refresh the data connection if required.

---

# 🚀 Future Enhancements

Future versions of FleetPulse can include:

* Finding Load Capacity
* fuel monitoring
* Automated maintenance alerts
* Route Analysis
* Weather Pedicition
* Delayed Delivery
* Predictive Score
* Downtime maintenance
* Failure History
* Vehicle and thier production model year and performance.

---

# Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Excel
* SQL
* MySQL
* Data Visualization
* Power BI
* Dashboard Development
* KPI Analysis
  

---

# Author

**Navyaa Sri**

**Data Analyst | Python | SQL | Excel | Power BI | Machine Learning**

---

#  Project Summary

**FleetPulse – Smart Fleet Performance Analytics** is an end-to-end analytics project that combines **Data Analytics, Business Intelligence, and Machine Learning**.

The project follows:

```text
Data Cleaning
      ↓
SQL Analysis
      ↓
Python EDA
      ↓
Machine Learning
      ↓
Prediction
      ↓
Power BI Dashboard
      ↓
Business Insights
```

FleetPulse transforms raw fleet data into **actionable insights and predictive intelligence**, helping organizations improve fleet efficiency, reduce costs, and make better operational decisions.
