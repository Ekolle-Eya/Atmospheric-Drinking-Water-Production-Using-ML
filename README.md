# Atmospheric-Drinking-Water-Production-Using-ML
This is a predictive machine learning model use to determine drinking water production from Atmospheric Water Generator (AWG). The model uses two features (Temperature and Relative Humidity) to pridict water production.
The features in the data include Temperature, Humidity, Water Production_Day, Avg_Number of People and Avg_Number of Household.
[viz](RegressionPlot)
<img width="1246" height="470" alt="Regression_plot" src="https://github.com/user-attachments/assets/543296e0-a848-402f-8ae5-c9bbcb48d2e5" />


### Data
The primary data source used for the machine learning algorithm is the 'AWG_Solution.csv' which contained all detailed information. This is a real world data based on my research that was conducted in Zambia in 9 districts. The data was collected from AWG machine made by HuProTect Switzerland (a company that produces portable drinking water from air).

### Tools
1) Google Colab
2) Python
3) Excel

### Data Cleaning and Preparation
The data is clean with no missing values. I clean the data using Excel then use python for feature engineering by adding the new feature Avg_Number of Housholds.

### Exploratory Data Analysis
EDA involve exploring the key independent varaible(Temperature and Humidity) which can have possitive correlation  with the dependent variable 'Water Production_Day'.
Created regression plots of the training data using Matplotlip and Seaborn to evalute linear relationships between variables.

### Machine Learning Algorithms
Algorithms involved Regression
1) Linear Regression
2) Multiple Linear Regression
3) Rndom Forest Regressor

### Model Training
The training involved spliting the data into training set and test with '80%' of the ovarall data allocated for training and '20%' for testing.

### Model Evaluation
Included 4 model evaluation techniques
1) Root Mean Squared Error (RMSE)
2) R-squared (R²)
3) Cross Validation Score (using 5 folds)

### Results
The results of the predictionso of all models was examined, evaluated and compared amongst each other. It showed that the best performing model is Multiple Linear Regression with the lowest MSE ((45525.0)and highest R-squared (0.95).The cross validation score showed an exception result of R-squared in 5 folds (0.96570862, 0.94176996, 0.9349316 , 0.98106729, 0.93848702).

### References
1) EKCOLAB Organization
2) HuProTec Switzerland
