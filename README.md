# Global Pollution Analysis & Energy Recovery Prediction

## Overview
This project performs an in-depth analysis of global pollution data and explores the relationship between pollution levels and energy recovery. It combines **Exploratory Data Analysis (EDA)**, **feature engineering**, **clustering**, and **machine learning models** to extract insights and make predictions.

---

## Objectives
- Analyze global pollution trends (air, water, soil)
- Engineer meaningful features for better insights
- Cluster countries based on pollution patterns
- Predict energy recovery using machine learning models
- Compare traditional regression with neural networks

---

## Dataset
- Dataset used: `Global_Pollution_Analysis.csv`
- Includes:
  - Air, Water, Soil Pollution Index
  - CO₂ Emissions
  - Industrial Waste
  - Renewable Energy %
  - Energy Recovered (target variable)

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Project Workflow

### 1. Data Preprocessing
- Handling missing values:
  - Numerical → Median
  - Categorical → Mode
- Label encoding for categorical variables

### 2. Feature Engineering
Created advanced features like:
- Total Pollution Index
- Pollution-to-Energy Ratio
- Waste-to-Energy Efficiency
- CO₂ per Energy
- Renewable Energy Contribution

---

### 3. Exploratory Data Analysis (EDA)
- Correlation heatmaps
- Trend analysis over years
- Pollution vs energy insights

---

### 4. Clustering Analysis

#### K-Means Clustering
- Used Elbow Method to find optimal clusters
- Grouped countries based on pollution patterns

#### Hierarchical Clustering
- Dendrogram visualization
- Compared results with K-Means

#### PCA Visualization
- Reduced dimensions for better cluster visualization

---

### 5. Machine Learning Models

#### Linear Regression
- Baseline model for prediction

#### Neural Networks
- Multiple configurations tested:
  - Different hidden layers
  - Learning rates
  - Regularization techniques
- Best model selected based on **R² score**

---

### 6. Model Comparison
- Compared:
  - Linear Regression
  - Multiple Neural Network models
- Evaluated using:
  - R² Score
  - MSE (Mean Squared Error)
  - MAE (Mean Absolute Error)

---

## Key Insights
- Countries can be grouped based on pollution patterns using clustering
- Strong relationships exist between pollution indices and energy recovery
- Engineered features significantly improve model performance
- Neural networks outperform linear regression in capturing complex patterns

---

## Visualizations Included
- Correlation heatmap
- Cluster scatter plots
- PCA visualization
- Actual vs Predicted comparison
- Cluster-based energy analysis

---

## How to Run

1. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
2. Run Jupyter Notebook:
   jupyter notebook
3. Open:
   Assignment_6.ipynb
