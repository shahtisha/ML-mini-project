# Solar Power Output Prediction
This project focuses on predicting solar power output based on various environmental factors using machine learning. The dataset includes weather-related features such as temperature, pressure, wind speed, and more, along with solar-specific metrics like Clearsky DHI, Clearsky DNI, and Clearsky GHI. The goal is to develop a model that accurately forecasts solar power output, which can be valuable for optimizing energy production and consumption.
Files:
training set.csv: The CSV file containing the training dataset.
testing set.csv: The CSV file containing the testing dataset.
solar_power_prediction.ipynb: Jupyter Notebook with the code for data analysis, visualization, and machine learning model implementation.
Data Visualization:
Utilized a heatmap to visualize the Pearson correlation between different features.
Explored the correlation between target features (Clearsky DHI, Clearsky DNI, Clearsky GHI).
Machine Learning Model:
Applied a Decision Tree Regressor and a Random Forest Regressor to predict solar power output.
Evaluated the model's performance using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
