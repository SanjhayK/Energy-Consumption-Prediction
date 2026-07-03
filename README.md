# Energy Consumption Prediction

## About
This project predicts household appliance energy usage using machine learning. I used a dataset with temperature, humidity, and time-based features to estimate appliance energy consumption.

## Dataset
The dataset is from the UCI Machine Learning Repository.  
Target variable: **Appliances (energy usage in Wh)**

## What I did
- Loaded and explored the dataset  
- Removed unnecessary columns  
- Created time-based features (hour, day, month, weekend)  
- Handled missing values  
- Split data into training and testing sets  
- Trained two models:
  - Linear Regression  
  - Random Forest Regressor  
- Compared model performance  

## Models
- Linear Regression (baseline)
- Random Forest Regressor

## Results
Models were evaluated using MAE, RMSE, and R² score.  
Random Forest performed better than Linear Regression.

## Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn
