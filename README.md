# Titanic Dataset: Exploratory Data Analysis (EDA)

## 📄 Introduction
This project analyzes the Titanic dataset to understand the factors that influenced passenger survival. The goal is to perform Exploratory Data Analysis (EDA) using Python libraries like pandas, matplotlib, seaborn, and numpy.

## 🛠 Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## 📝 Dataset
The dataset contains information about Titanic passengers, including:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## 🔍 Steps in the Project
1. **Data Loading:** Loaded the dataset using pandas.
2. **Data Cleaning:** Handled missing values for columns like `Age`, `Embarked`, `Cabin`, and `Fare`.
3. **Data Overview:** Checked basic information and statistics of the dataset.
4. **Data Visualization:** 
   - Histogram of passenger ages
   - Boxplot to check feature distribution
   - Correlation map to see relationships between numerical features
   - Survival count (0 = Not Survived, 1 = Survived)
   - Gender distribution
   - Relationship between Age and Fare
5. **Summary Statistics:** Calculated mean, median, and standard deviation for numerical features.

## ⚙ How to Run
1. Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn
Open the titanic.ipynb notebook in Jupyter Notebook or JupyterLab.

Run all cells sequentially to reproduce the analysis.

✅ Conclusion

This EDA project provides insights into passenger demographics, survival rates, and relationships between features in the Titanic dataset. It is a foundational project for learning data analysis and visualization in Python.
