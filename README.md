# 🧪 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective
To perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights using visual and statistical methods.

## 🧰 Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## 📊 Analysis Performed
- Data overview: `.info()`, `.describe()`, null checks
- Univariate analysis:
  - Categorical: `Survived`, `Pclass`, `Sex`, `Embarked`
  - Numerical: `Age`, `Fare`
- Bivariate analysis:
  - Survival by Gender, Class, Embarked
  - Age vs Fare scatter
- Correlation Heatmap
- Pairplot for selected features

## 🔍 Key Findings
- Females had a higher survival rate.
- Passengers in 1st class survived more than 2nd and 3rd.
- Younger passengers had better chances of survival.
- Higher fare was often associated with higher class and survival.
- Most survivors paid higher fares, which often means they were in 1st class.
- Many children (low age values) are seen among survivors — especially from higher classes.
- Suggests that "women and children first" was actually followed.
- People in 3rd class paid very low fares (around $10–$20), and most of them didn’t survive.
- A few passengers paid extremely high fares (>$300), and most of them survived — these are likely very wealthy 1st class passengers.

## 📁 Files Included
- `titanic_eda.ipynb`: Jupyter Notebook with code and visuals
- `README.md`: This file

## 📎 Dataset Source
[Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data?select=train.csv)

---
