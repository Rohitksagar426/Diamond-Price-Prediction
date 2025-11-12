# 💎 Diamond Price Prediction

A machine learning project that predicts diamond prices based on features like carat, cut, color, depth, table, and dimensions.  
It includes data cleaning, EDA, feature engineering, and regression modeling to identify key factors influencing diamond pricing.

---

## 🧠 Project Overview
This project focuses on building a Machine Learning model to predict the price of diamonds based on their key attributes such as carat, cut, color, depth, table, length, width, and height.  
The goal is to analyze how different physical and qualitative features influence diamond pricing and to create a reliable predictive model that can estimate prices accurately.

---

## 📊 Dataset Description
The dataset contains various attributes that describe the physical and visual characteristics of diamonds:

| Feature | Description |
|----------|-------------|
| **carat** | Weight of the diamond (larger carats generally increase price) |
| **cut** | Quality of the cut (Fair, Good, Very Good, Premium, Ideal) |
| **color** | Diamond color grade (D = best to J = worst) |
| **depth** | Total depth percentage = (z / mean(x, y)) * 100 |
| **table** | Width of the diamond’s top relative to its widest point |
| **length (x)** | Length dimension in mm |
| **width (y)** | Width dimension in mm |
| **height (z)** | Height dimension in mm |
| **price** | Target variable — Price of the diamond in USD |

---

## ⚙️ Project Workflow

### 1. Data Loading & Cleaning
- Imported the dataset and handled missing values or outliers.  
- Converted categorical features (like *cut* and *color*) into numerical format using encoding techniques.

### 2. Exploratory Data Analysis (EDA)
- Analyzed correlations between features and diamond price.  
- Visualized relationships using scatter plots, box plots, and heatmaps.  
- Identified which features have the highest impact on price.

### 3. Feature Engineering
- Created new features like depth_percentage, table_percentage, and volume.  
- Scaled numerical features to improve model performance.

### 4. Model Building
- Trained multiple regression models such as:  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
- Evaluated models using **R² score**, **MAE**, and **RMSE**.

### 5. Model Evaluation & Prediction
- Compared model performances.  
- Selected the best-performing model for final predictions.

---

## 📈 Results
The final model achieved a strong correlation between predicted and actual prices.  
Insights from EDA showed that **carat weight** and **cut quality** are the most influential factors in determining diamond prices.

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📌 Conclusion
This project demonstrates how machine learning can be applied to real-world pricing problems using data-driven insights.  
It helps understand key factors affecting diamond valuation and can assist jewelers, buyers, and analysts in making informed decisions.
