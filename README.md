# PRODIGY_DS_02
![image](https://github.com/user-attachments/assets/d571ca71-c441-4cbd-8cce-582b04932758)

# 🚢 Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

This project performs data cleaning and exploratory data analysis (EDA) on the famous [Titanic dataset](https://www.kaggle.com/c/titanic) from Kaggle. The goal is to understand the relationships between various passenger attributes and survival outcomes.

---

## 📁 Dataset

The dataset used is `train.csv` from the Titanic Kaggle competition. It contains details about passengers such as:

- Name
- Sex
- Age
- Passenger class (Pclass)
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Port of embarkation (Embarked)
- Survival status (0 = No, 1 = Yes)

---

## 🧹 Data Cleaning Steps

- Removed irrelevant or sparsely populated columns: `Cabin`, `Ticket`
- Filled missing `Age` values with the **median**
- Filled missing `Embarked` values with the **mode**
- Checked for and confirmed there were no remaining missing values

---

## 📊 Exploratory Data Analysis (EDA)

We used **Seaborn** and **Matplotlib** for data visualization to uncover patterns:

- **Survival Count**: Distribution of survivors vs non-survivors
- **Survival by Gender**: Females had significantly higher survival rates
- **Survival by Passenger Class**: 1st class passengers had better odds
- **Age Distribution**: Most passengers were between 20–40 years old
- **Age vs Survival**: Younger passengers had better chances
- **Correlation Heatmap**: To identify numerical feature relationships

---

## 🔧 Feature Engineering (Optional)

- Created a new `FamilySize` feature: `SibSp + Parch + 1`
- Ready for further preprocessing like label encoding and model training

---

## 🛠 Technologies Used

- Python 🐍
- Pandas 📊
- NumPy
- Seaborn 🎨
- Matplotlib 📈

---


