# Titanic Survival Analysis - Exploratory Data Analysis (EDA)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github.com/javeriaathar/TITANIC-SURVIVAL-ANALYSIS-USING-PYTHON-EDA-Project-/blob/main/Titanic%20Project.ipynb
)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Titanic Survival Dataset containing 1,000 passenger records. The dataset was generated using Python and analyzed to identify patterns, trends, and factors that influenced passenger survival.

The main objective of this project is to demonstrate data cleaning, visualization, feature engineering, and insight generation using Python data analysis libraries.

---

## 🎯 Objectives

* Understand the structure of the dataset
* Perform data cleaning and preprocessing
* Explore survival patterns among passengers
* Visualize relationships between features
* Generate meaningful insights from the data

---

## 📂 Dataset Features

| Feature     | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique Passenger Identifier       |
| Pclass      | Passenger Class (1, 2, 3)         |
| Sex         | Gender of Passenger               |
| Age         | Age of Passenger                  |
| SibSp       | Number of Siblings/Spouses Aboard |
| Parch       | Number of Parents/Children Aboard |
| Fare        | Ticket Fare                       |
| Embarked    | Port of Embarkation (S, C, Q)     |
| Survived    | Survival Status (0 = No, 1 = Yes) |

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Exploratory Data Analysis Performed

### Data Inspection

* Displayed dataset head and tail
* Checked column information
* Generated statistical summaries

### Data Cleaning

* Checked missing values
* Identified duplicate records
* Removed duplicates

### Survival Analysis

* Overall survival distribution
* Survival rate calculation
* Survival comparison by gender
* Survival comparison by passenger class

### Feature Analysis

* Age distribution
* Fare distribution
* Embarkation analysis
* Family size analysis

### Feature Engineering

Created a new feature:

```python
df["FamilySize"] = df["SibSp"] + df["Parch"]
```

---

## 📊 Visualizations Created

* Survival Distribution Bar Chart
* Survival by Gender Count Plot
* Survival by Passenger Class Count Plot
* Age Distribution Histogram
* Fare vs Survival Box Plot
* Survival by Embarkation Port Plot
* Family Size vs Survival Box Plot
* Correlation Heatmap

---

## 💡 Key Insights

* Female passengers had a higher survival rate than male passengers.
* First-class passengers showed better survival chances.
* Children were more likely to survive.
* Higher ticket fares were generally associated with increased survival rates.
* Family size influenced survival outcomes.
* Passenger class and fare showed a noticeable relationship with survival.

---
## 🚀 How to Run This Project

### 1. Clone Repository
```bash
https://github.com/javeriaathar/TITANIC-SURVIVAL-ANALYSIS-USING-PYTHON-EDA-Project-.git
```

### 2. Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run Python Script / Notebook
```bash
python titanic_analysis.py
---
## 📁 Output Files

* `titanic_1000.csv` – Generated dataset
* `cleaned_titanic_1000.csv` – Cleaned dataset after preprocessing

---

## 🚀 Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Statistical Analysis
* Data Storytelling using Python

---

## 👩‍💻 Author

**Javeria Athar**

BS Computational Mathematics

---

## 📜 License

This project is created for educational and portfolio purposes.
