This project uses 3 years of simplified batting data from MLB to predict the Exit Speed, Angle, and Direction of a baseball when it is hit. It starts with a naive approach that uses the mean of each target variable as our "best guess" for each outcome. Next, it tries a simulation using the mean and standard deviation of each target variable to select a normally distributed number as our "best guess" for each outcome. Third, single output regressors are employed against the target variables individually and the best regressor for each output is used to collectively predict the target variables. Lastly, a multiple output regressor is employed against the target variables collectively. Each method is scored using Root Mean Squared Error (RMSE).  

Skills featured:  
Multicore processing  
Processor optimization  
Sampling from a normal distribution  
Simulation  
Data visualization  
Data cleaning  

Data manipulation techniques used:  
Feature engineering  

Machine Learning models used:  
Linear regression  
LASSO regression  
Support vector regression  
Random Forest Regression  

Scoring methods:  
Root Mean Squared Error (RMSE)