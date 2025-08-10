# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Overview
This project focuses on **Exploratory Data Analysis (EDA)** of the Titanic dataset from the famous [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic).  
The aim is to uncover hidden patterns, clean and prepare the data, and gain insights about the factors affecting passenger survival.

---

## 📂 Dataset Information
The dataset contains details of Titanic passengers:

| Column Name | Description |
|-------------|-------------|
| PassengerId | Unique passenger ID |
| Survived | Survival status (`0 = No`, `1 = Yes`) |
| Pclass | Ticket class (`1 = 1st`, `2 = 2nd`, `3 = 3rd`) |
| Name | Passenger name |
| Sex | Gender |
| Age | Passenger age |
| SibSp | No. of siblings/spouses aboard |
| Parch | No. of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation (`C`, `Q`, `S`) |

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - Pandas – Data manipulation
  - NumPy – Numerical operations
  - Matplotlib – Data visualization
  - Seaborn – Statistical plotting

---

## 🔍 EDA Workflow
1. **Data Loading** – Import CSV file & check structure.
2. **Data Cleaning** – Handle missing values, fix data types.
3. **Univariate Analysis** – Study each column individually.
4. **Bivariate Analysis** – Compare survival with other features.
5. **Outlier Detection** – Identify and handle extreme values.
6. **Insights Extraction** – Find patterns that influence survival.

---

## 📊 Key Insights
| Factor | Observation |
|--------|-------------|
| Gender | Females had a much higher survival rate. |
| Class | 1st class passengers survived more than 3rd class. |
| Age | Children had better chances of survival. |
| Embarkation | Passengers from Cherbourg had higher survival rates. |

---







