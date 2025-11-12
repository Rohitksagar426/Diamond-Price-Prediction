# Diamond-Price-Prediction
A machine learning project that predicts diamond prices based on features like carat, cut, color, depth, table, and dimensions. It includes data cleaning, EDA, feature engineering, and regression modeling to identify key factors influencing diamond pricing.
This project focuses on building a Machine Learning model to predict the price of diamonds based on their key attributes such as carat, cut, color, depth, table, length, width, and height. The goal is to analyze how different physical and qualitative features influence diamond pricing and to create a reliable predictive model that can estimate prices accurately.

📊 Dataset Description

The dataset contains various attributes that describe the physical and visual characteristics of diamonds:

Feature	Description
carat	Weight of the diamond (larger carats generally increase price)
cut	Quality of the cut (e.g., Fair, Good, Very Good, Premium, Ideal)
color	Diamond color grade (from D = best to J = worst)
clarity (optional if included)	Measure of how clear the diamond is
depth	Total depth percentage = (z / mean(x, y)) * 100
table	Width of the diamond’s top relative to its widest point
length (x)	Length dimension of the diamond in mm
width (y)	Width dimension of the diamond in mm
height (z)	Height dimension of the diamond in mm
price	Target variable — Price of the diamond in USD
🧩 Project Workflow

Data Loading & Cleaning

Imported the dataset and handled missing values or outliers.

Converted categorical features (like cut and color) into numerical format using encoding techniques.

Exploratory Data Analysis (EDA)

Analyzed correlations between features and diamond price.

Visualized relationships using scatter plots, box plots, and heatmaps.

Identified which features have the highest impact on price.

Feature Engineering

Created new features (e.g., volume = length × width × height).

Scaled numerical features to improve model performance.

Model Building

Trained multiple regression models such as:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Evaluated models using metrics like R² score, MAE, and RMSE.

Model Evaluation & Prediction

Compared model performances.

Selected the best-performing model for final predictions.

📈 Results

The final model achieved a strong correlation between predicted and actual prices.

Insights from EDA showed that carat weight and cut quality are the most influential factors in determining diamond prices.

🛠️ Tools & Technologies Used

Python

Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn (for data visualization)

Scikit-learn (for ML modeling and evaluation)

🚀 Future Improvements

Implement more advanced models such as XGBoost or CatBoost.

Deploy the model using Streamlit or Flask for real-time price prediction.

Enhance data preprocessing with outlier detection and feature optimization.
