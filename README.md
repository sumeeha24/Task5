# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Overview
This project performs *Exploratory Data Analysis (EDA)* on the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data?select=train.csv).  
The goal is to explore the data, visualize key patterns, and summarize insights that could help in predicting survival.

## 🛠 Tools & Libraries
- *Python*  
- *Pandas* – Data manipulation and analysis  
- *Matplotlib* – Data visualization  
- *Seaborn* – Statistical plots  

## 📂 Files in this Repository
- Titanic_EDA.ipynb → Jupyter Notebook with complete EDA code and visualizations.  
- Titanic_EDA.pdf → PDF report version of the notebook for easy reading.  
- train.csv → Titanic dataset (if included; otherwise download from Kaggle).  

## 📊 Steps Performed
1. *Data Loading & Inspection*
   - Checked dataset shape, column types, and missing values.
   - Summary statistics using .describe().

2. *Data Cleaning*
   - Filled missing values for Age, Embarked, and Fare.
   - Created new features like FamilySize and HasCabin.

3. *Univariate Analysis*
   - Distribution plots for Age and Fare.
   - Count plots for Sex and Passenger Class.

4. *Bivariate Analysis*
   - Survival rates by Gender and Passenger Class.
   - Age and Fare distributions by Survival.

5. *Multivariate Analysis*
   - Pairplots and correlation heatmaps.

6. *Key Insights*
   - Females had a much higher survival rate than males.
   - Higher-class passengers (Pclass 1) had better survival chances.
   - Younger passengers tended to survive more often.
   - Higher fares correlated with higher survival.

## 📈 Visuals
The notebook contains:
- Histograms
- Count plots
- Bar plots
- Violin plots
- Heatmaps
- Pairplots

## 📌 How to Run
1. Download the dataset from Kaggle.
2. Open Titanic_EDA.ipynb in Jupyter Notebook or Google Colab.
3. Run all cells to generate the analysis and plots.
