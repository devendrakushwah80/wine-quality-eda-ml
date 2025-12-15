# 🍷 Wine Quality – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Wine Quality dataset** to understand how physicochemical properties of wine influence its quality score.  
The analysis focuses on data cleaning, statistical exploration, visualization, correlation analysis, and dimensionality reduction to prepare the data for machine learning.

---

## 🎯 Objectives
- Understand the structure and distribution of the dataset
- Analyze relationships between features and wine quality
- Identify key variables impacting wine quality
- Visualize correlations and patterns
- Prepare insights for future ML modeling

---

## 📂 Dataset Information
- **Dataset Name:** Wine Quality Dataset
- **File:** `WineQT.csv`
- **Target Variable:** `quality`

### Features
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

---

## 🛠️ Technologies Used
- **Python**
- **Libraries**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

## 🔍 EDA Steps Performed

### 1️⃣ Data Loading & Inspection
- Loaded dataset using Pandas
- Checked shape, data types, and missing values

### 2️⃣ Statistical Analysis
- Used `describe()` for summary statistics
- Identified skewness and potential outliers

### 3️⃣ Correlation Analysis
- Computed correlation matrix
- Visualized correlations using a heatmap
- Observed strong relationships:
  - Alcohol → positively correlated with quality
  - Volatile acidity → negatively correlated with quality

### 4️⃣ Data Visualization
- Histograms for feature distributions
- Scatter plots for feature interactions
- Annotated correlation heatmap

### 5️⃣ Principal Component Analysis (PCA)
- Applied PCA for dimensionality reduction
- Visualized cumulative explained variance
- Identified optimal number of components

---

## 📊 Key Insights
- Alcohol is one of the strongest predictors of wine quality
- Volatile acidity negatively impacts wine quality
- Some features show moderate multicollinearity
- PCA helps reduce dimensions while retaining variance

---

## 📁 Project Structure
├── WineQT.csv
├── wine_quality_eda.ipynb
├── README.md
├── Requirements.txt


---

## 🚀 Future Work
- Feature engineering
- Outlier treatment
- Machine learning models (Regression / Classification)
- Model evaluation and tuning

---

## 👤 Author
**Devendra Kushwah**  
Aspiring Data Scientist | Python | Machine Learning | Exploratory Data Analysis

---

## ⭐ Support
If you find this project useful, please ⭐ star the repository!

