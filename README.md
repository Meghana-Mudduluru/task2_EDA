# task2_EDA

# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains my submission for **Task 2: Exploratory Data Analysis** as part of the AI & ML Internship program.

The goal of this task was to perform EDA on the Titanic dataset using Python and visualization libraries like Matplotlib, Seaborn, and Plotly.

---

## ✅ Objective

- Understand the dataset by calculating summary statistics
- Visualize distributions and outliers
- Analyze relationships between features
- Identify patterns, trends, and anomalies
- Make basic inferences from the data

---

## 📊 Dataset Description

**Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

The dataset contains information about passengers aboard the Titanic, including:

- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Cabin`, `Embarked`

---

## 🧰 Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 📝 Steps Performed

### 1. **Summary Statistics**
- Used `.describe()` to compute mean, median, standard deviation, min, max
- Identified columns with missing values
- Observed distributions of `Age`, `Fare`, etc.

### 2. **Visualizations**
- Created **histograms** for `Age` and `Fare` to show distributions
- Used **boxplots** to identify outliers

### 3. **Feature Relationships**
- Built a **correlation heatmap** for numeric features to find linear relationships
- Plotted **pairplots** to visualize clusters and spread

### 4. **Patterns and Anomalies**
- Found that:
  - Females had higher survival rates
  - First-class passengers had better survival chances
  - Higher fares often correlated with survival
  - Outliers were present in `Fare` and `Age`

### 5. **Basic Inferences**
- Passenger class, gender, and fare amount had a strong influence on survival
- Age distribution showed many passengers were young adults
- Cabin column had too many missing values and was dropped

---

## 📌 Key Insights

- **Sex**: Females were more likely to survive
- **Pclass**: 1st class passengers had higher survival rates
- **Fare**: Passengers who paid higher fares were more likely to survive
- **Age**: Children and younger passengers had a higher chance of survival

---

## 🙌 Acknowledgements

Thanks to the internship team for the opportunity. This task helped me learn how to:
- Analyze real-world data
- Use visualizations to support insights
- Prepare data for machine learning models
