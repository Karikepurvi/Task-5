# Exploratory Data Analysis (EDA) – Custom Titanic Dataset

## 📂 Project Overview
This project is part of the Data Analyst Internship Task 5, focusing on performing **Exploratory Data Analysis (EDA)** using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.

The dataset used is a version of the **Titanic dataset**, uploaded manually as `train (2).csv`.

##  Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

##  EDA Steps Performed

1. **Data Loading & Inspection**
   - Checked shape, data types, and missing values
   - Used `.head()`, `.info()`, and `.describe()`

2. **Data Cleaning**
   - Handled missing values in `Age` and `Embarked`
   - Dropped `Cabin` due to many nulls

3. **Univariate Analysis**
   - Histograms and boxplots for `Age`, `Fare`, `Pclass`, etc.

4. **Bivariate Analysis**
   - Count plots comparing `Survived` with `Sex`, `Pclass`
   - Scatter plot for `Age` vs `Fare`

5. **Multivariate Analysis**
   - Correlation matrix with heatmap
   - Pairplot for numeric features

6. **Feature Engineering (Optional)**
   - Created features like `FamilySize`, `IsAlone`, and extracted `Title` from `Name`

7. **Observations and Summary**
   - Documented visual insights and findings

##  Key Insights

- Females had a higher chance of survival.
- Passengers in 1st class survived significantly more.
- Higher fare indicates a higher probability of survival.
- Age had a moderate influence on survival.

Thank you for reviewing my work!


