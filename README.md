# Healthcare Analytics for Doctor Visits

## 📌 Project Overview

This project focuses on analyzing healthcare data to understand the factors associated with doctor visits. The analysis explores patient characteristics such as age, gender, illness, health condition, income, chronic conditions, and insurance status.

The main goal is to identify meaningful patterns in healthcare utilization through Exploratory Data Analysis (EDA) and data visualization.

---

## 🎯 Problem Statement

Understanding the factors that influence doctor visits can be challenging because healthcare utilization depends on multiple patient characteristics.

This project analyzes healthcare data to identify patterns and relationships between doctor visits and factors such as demographic characteristics, illness, health conditions, income, chronic conditions, and insurance status.

---

## 🎯 Objectives

* Analyze the healthcare dataset and understand its structure.
* Clean and prepare the data for analysis.
* Explore individual variables using univariate analysis.
* Analyze relationships between variables using bivariate analysis.
* Perform multivariate analysis to understand multiple factors together.
* Identify relationships between numerical variables using correlation analysis.
* Use visualizations to identify important healthcare utilization patterns.
* Generate meaningful insights from the analysis.

---

## 📊 Dataset

The dataset contains information related to patients and doctor visits.

### Important Features

| Feature     | Description                        |
| ----------- | ---------------------------------- |
| `visits`    | Number of doctor visits            |
| `gender`    | Gender of the patient              |
| `age`       | Age group/index                    |
| `income`    | Income level                       |
| `illness`   | Illness level                      |
| `reduced`   | Reduced activity due to health     |
| `health`    | General health condition           |
| `private`   | Private insurance status           |
| `freepoor`  | Free/poor insurance status         |
| `freerepat` | Free/repatriation insurance status |
| `nchronic`  | Number of non-chronic conditions   |
| `lchronic`  | Long-term chronic condition        |

---

## 🔍 Analysis Performed

### 1. Data Understanding

* Dataset shape
* Data types
* Statistical summary
* Unique values
* Numerical and categorical variables

### 2. Data Cleaning

* Checked for missing values
* Checked for duplicate records
* Removed unnecessary columns
* Verified data consistency

### 3. Univariate Analysis

Individual variables were analyzed using:

* Histograms
* Count plots
* Bar charts
* Box plots

### 4. Bivariate Analysis

Relationships between two variables were explored using:

* Bar plots
* Box plots
* Grouped analysis
* Cross-tabulation

### 5. Multivariate Analysis

Multiple factors were analyzed together to understand their combined relationship with doctor visits.

Examples include:

* Illness + Gender + Doctor Visits
* Age + Gender + Doctor Visits
* Income + Chronic Condition + Doctor Visits

### 6. Correlation Analysis

A correlation heatmap was used to identify relationships between numerical variables.

### 7. Pair Plot

A pair plot was used to visualize relationships and distributions among selected numerical variables.

### 8. Distribution and Outlier Analysis

Histograms and box plots were used to understand the distribution of doctor visits and identify unusually high values.

---

## 💡 Key Insights

* Doctor visits vary across different illness levels.
* Different age groups show different patterns in doctor visits.
* Doctor visit patterns differ between male and female patients.
* Chronic health conditions are associated with differences in doctor visits.
* Health status provides useful information about healthcare utilization.
* Income levels show differences in healthcare utilization patterns.
* Insurance-related factors provide additional information about doctor visits.
* Considering multiple patient characteristics together provides a broader understanding of healthcare utilization.
* Correlation analysis helps identify relationships among numerical variables.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* **CSV Dataset**

---

## 📂 Project Structure

```text
Healthcare-Analytics-Doctor-Visits/
│
├── Healthcare_Analytics_Doctor_Visits.ipynb
├── healthcare_doctor_visits.csv
└── README.md
```

---

## ▶️ How to Run the Project

### Using Google Colab

1. Open the Jupyter Notebook in Google Colab.
2. Upload the healthcare CSV dataset.
3. Run the notebook cells sequentially.
4. The notebook performs data cleaning, analysis, visualization, and generates insights.

### Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📈 Project Outcome

The project provides an exploratory analysis of doctor visit patterns and highlights how demographic, health, income, chronic-condition, and insurance-related factors are associated with healthcare utilization.

The analysis demonstrates how Python-based data analysis and visualization can be used to extract meaningful insights from healthcare data.

---

## 👤 End Users

* Healthcare organizations
* Hospitals and healthcare professionals
* Healthcare analysts
* Data analysts
* Insurance companies
* Healthcare researchers
* Students and researchers

---

## 🚀 Future Scope

The project can be further extended by:

* Building a predictive model for doctor visits.
* Developing an interactive dashboard using Power BI.
* Performing advanced statistical analysis.
* Applying machine learning techniques to healthcare data.
* Creating a healthcare utilization prediction system.

---

## 🙏 Conclusion

This project demonstrates the use of Exploratory Data Analysis to understand doctor visit patterns. By analyzing multiple patient-related factors and visualizing their relationships, the project provides useful insights into healthcare utilization and demonstrates the practical application of Python in healthcare analytics.
