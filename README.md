# HOUSE-PRICE-PREDICTION

This project aims to predict house prices using various features like location, age, and other relevant attributes. The dataset used for this project includes various attributes such as longitude, latitude, housing median age, total rooms, total bedrooms, population, households, median income, and ocean proximity. The project involves data preprocessing, visualization, building machine learning models, and evaluating their performance.

Table of Contents
Dataset Information
Libraries Used
Project Structure
Data Exploration and Preprocessing
Data Visualization
Model Building
Model Evaluation
Visualization of Results
Final Predictions
Conclusion
How to Run
Dataset Information
The dataset contains the following feature columns:

longitude: Geographic coordinate, longitude of the property.
latitude: Geographic coordinate, latitude of the property.
housing_median_age: The median age of the houses in the block.
total_rooms: Total number of rooms in the property.
total_bedrooms: Total number of bedrooms in the property.
population: Population in the block.
households: Total number of households in the block.
median_income: Median income of households in the block.
median_house_value: The target variable, representing the median house value.
ocean_proximity: Categorical feature indicating the proximity to the ocean.
Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Seaborn: For creating visualizations.
Matplotlib: For plotting graphs and visualizations.
Scikit-learn: For building and evaluating machine learning models.
Mpl_toolkits: For creating 3D plots.
Project Structure
The project follows these main steps:

Data Exploration and Preprocessing: Loading the dataset, handling missing values, feature engineering, and normalization.
Data Visualization: Visualizing relationships between features and target variables using various plots.
Model Building: Building Linear Regression and Random Forest models.
Model Evaluation: Evaluating the models using metrics like MAE, MSE, and R-squared.
Visualization of Results: Visualizing predictions and feature importance.
Final Predictions: Making predictions on the test dataset and comparing them with actual values.
Data Exploration and Preprocessing
Missing Values Handling: Missing values in the total_bedrooms column were handled using median imputation.
Feature Engineering: New features such as rooms_per_household, bedrooms_per_room, and population_per_household were created to provide additional insights.
Categorical Encoding: The categorical feature ocean_proximity was encoded using one-hot encoding.
Normalization: All features were normalized to ensure they were on the same scale.
Data Visualization
Pairplot: Visualized the relationships between key features and the target variable (median_house_value).
Correlation Matrix: Created a heatmap to understand the correlation between features.
3D Scatter Plot: Visualized the relationship between longitude, latitude, and median_house_value using a 3D scatter plot.
Distribution Plots: Plotted histograms for features like median_income, housing_median_age, and rooms_per_household to understand their distribution.
Model Building
Linear Regression Model: A simple linear regression model was built to predict house prices.
Random Forest Model: A more complex Random Forest model was built to improve prediction accuracy.
Model Evaluation
Linear Regression:
MAE (Mean Absolute Error): Measure of the average absolute difference between actual and predicted values.
MSE (Mean Squared Error): Measure of the average squared difference between actual and predicted values.
R-squared: Measure of the proportion of variance in the dependent variable that is predictable from the independent variables.
Random Forest: Similar metrics were used to evaluate the Random Forest model, with improved performance over Linear Regression.
Visualization of Results
3D Surface Plot: A 3D surface plot was created to visualize how predicted house values change with longitude and latitude.
Feature Importance: The importance of each feature in the Random Forest model was visualized using a bar plot.
Residual Plots: Plotted residuals to check for any patterns and to validate model assumptions.
Final Predictions
The final model predictions were compared against actual values using scatter plots to visualize the accuracy of the predictions.
Conclusion
This project successfully built and evaluated a machine learning model to predict house prices based on various features. The Random Forest model outperformed the Linear Regression model in terms of accuracy, as evidenced by the evaluation metrics. The visualizations provided insights into the data and helped in understanding the relationships between different features and the target variable.
