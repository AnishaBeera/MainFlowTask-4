# MainFlowTask-4

🏠 Task 4: Regression Analysis for Predicting House Prices

Objective:
 Develop a linear regression model to accurately predict housing prices using key property features.

📊 Project Breakdown:
Dataset Selection:
File: house_prices.csv
Core Columns: Size (sq ft), Location (urban/suburban/rural), Number of Rooms, Price (target).

1. Data Exploration & Cleaning:
-Inspected missing values and applied appropriate imputation.
-Explored distributions of numerical variables (Size, Price) to understand spread and central tendencies.
-Identified and addressed outliers to enhance model stability.

2. Preprocessing:
-Scaled numerical features using Min‑Max/Standardization for uniformity.
-Encoded categorical ‘Location’ via One‑Hot Encoding to transform it into model‑ready inputs.

3. Feature Selection:
-Performed correlation analysis to assess predictor‑target relationships.
-Removed low‑impact features to reduce noise and improve model clarity.

4. Model Training:
-Split data into training (80%) and testing (20%) with a fixed random seed for reproducibility.
Built and trained a Linear Regression model using scikit‑learn.

5. Evaluation:
-Assessed model performance using RMSE for prediction error quantification.
-Examined R² to measure the model’s explanatory power on housing price variance.
