📘 EDA 
📚 Import Libraries
import pandas as pd, import numpy as np, import matplotlib.pyplot as plt, import seaborn as sns

📂 Load Dataset
df = pd.read_csv('filename.csv')

👁️ Initial Data Exploration

df.head() → preview data

df.info() → check data types & nulls

df.describe() → summary statistics

❓ Check Missing Values

df.isnull().sum() → count missing values per column

🧹 Handle Missing Data

df.fillna() or df.dropna() → fill/drop missing data

🧽 Data Cleaning

Remove unwanted columns: df.drop()

Drop duplicates: df.drop_duplicates()

Fix data types: df.astype()

📊 Univariate Analysis

Plot single variable: sns.histplot(), sns.countplot()

🔗 Bivariate Analysis

Relationship between two variables: sns.scatterplot(), sns.boxplot()

🔥 Correlation Analysis

df.corr() → correlation matrix

sns.heatmap(df.corr()) → visualize correlation

📌 Conclusion

Key insights from the dataset are highlighted

