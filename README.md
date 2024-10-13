# 1. Introduction 📊
We performed an Exploratory Data Analysis (EDA) on the Google App Store dataset 📈. The goal was to understand the data, identify patterns, and gain insights 🤔.

## 2. Data Import 💻
We imported the necessary libraries: Pandas, NumPy, Matplotlib, and Seaborn 📚. Then, we loaded the dataset using pd.read_csv 🔴.

### 3. Data Preview 👀
We checked the data using df.info() and df.head() 🔍. This helped us understand the data structure and content.

#### 4. Data Cleaning 🧹
We converted the 'Price' column to numeric values using str.replace and astype 🔢. We also handled missing values in the 'Size' column.

##### 5. Size Conversion 📏
We converted KB to MB and rounded values to 2 decimal places using pd.to_numeric and round 🔴.

###### 6. Install Analysis 📈
We analyzed the 'Installs' column by removing '+' and ',' and converting to numeric values using pd.to_numeric 🔢.

###### 7. Binning Installs 📊
We grouped 'Installs' into bins using pd.cut and labeled them 🔑.

###### 8. Price Analysis 💸
We checked the 'Price' column for missing values and unique values using value_counts 🔍.

###### 9. Type Analysis 📊
We analyzed the 'Type' column using value_counts 🔍.

###### 10. Handling Non-Numeric Values 🤔
We handled non-numeric values in the 'Size' column by replacing with NaN or removing rows 🔢.

###### 11. Visualization 📊
We used Seaborn to visualize missing values using heatmap 🔥.

###### 12. EDA using Dtale 📊
We used Dtale to perform interactive EDA and gain deeper insights into the data 🔍.

#GoogleAppStore #EDA #DataAnalysis #DataScience #MachineLearning #Python #Pandas #NumPy #Matplotlib #Seaborn #Dtale
