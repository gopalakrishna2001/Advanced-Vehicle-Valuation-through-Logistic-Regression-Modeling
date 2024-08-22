# Advanced-Vehicle-Valuation-through-Logistic-Regression-Modeling
Engineered a vehicle price prediction model using Logistic Regression with high accuracy and scalability.

# Libraries Used:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Kaggle
- Zipfile
- Sklearn
- Scipy
# About Data
## Data source
  - [The Imported the car dataset through kaggle API.](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv)
## Dataset Columns
Car_Name,Year,Selling_Price,Present_Price,Kms_Driven,Fuel_Type,Seller_Type,Transmission,Owner
# Visualizing Raw Data
- Selling price & Present price vs Fuel type
  ![image](https://github.com/user-attachments/assets/3bfb39db-4ba3-43d7-8268-a5d4d72f0fd5)
- Average Selling Price by No. of owners
  ![image](https://github.com/user-attachments/assets/1f1e8df2-82dc-462e-8b76-b0cb7aaa204a)
- Average Selling Price by Kilometers Driven
  ![image](https://github.com/user-attachments/assets/d6f04b97-95a8-48f1-8e9a-3306f90e61eb)
- Average Selling price by Seller type
  ![image](https://github.com/user-attachments/assets/59c8bbbd-ac90-4d0c-a840-4cf43db1ca80)
# Visualizing Outliers
- Selling Price
  ![image](https://github.com/user-attachments/assets/4402f3d5-440f-4c3c-9985-389504e1ff12)
- Present Price
  ![image](https://github.com/user-attachments/assets/d2848888-9761-4862-9090-fcf00c3d8e1e)
- Kilometers Driven
  ![image](https://github.com/user-attachments/assets/a972b57f-fa8c-41aa-97a6-dafc692c1c44)
# Feature Engineering
- Column transmission is binary encoded
- Column Fuel Type is Nominal encoded
# Feature Selection
- Pearson's Correlation
- Mutual Information and Information Gain
# Machine Learning Algorithm
- The selling price was predict by logistic regression
- test/train data= 70:30
# Metrics for evaluating Model Prediction
- Coefficient of determination
- Mean Square Error
- Mean Absolute Error
  

    




