# Car Price Prediction with Machine Learning
Car price prediction is a machine learning project that involves predicting the price of cars based on several features such as company name, doornumber, mileage, engine specifications, and other factors. The objective of this project is to build a predictive model that can accurately estimate the price of a car based on the given input features.

The project involved several stages, starting with data collection and cleaning, exploratory data analysis, feature engineering, model selection, and evaluation. The data was collected from various sources and involved a total of 205 observations with 26 variables. The data was then cleaned by removing missing values, duplicates, and outliers.

Exploratory data analysis was performed to understand the distribution of the variables, the relationship between different variables, and identify any patterns or trends. Feature engineering was then performed to transform the data into a suitable format for modeling. This involved handling categorical variables, scaling numerical variables, and removing highly correlated variables.

Several machine learning models were then trained on the preprocessed data to predict the car prices. The models evaluated included linear regression, Lasso regression, ElasticNet regression, decision tree regression, random forest regression, and XGBoost regression. The performance of each model was evaluated using the R-squared value and mean squared error.
# Conclusion:
## EDA Insights:
*   The dataset consists of 205 records and 26 attributes.
*   The target variable (price) has a mean value of 13276.71 and a standard deviation of 7988.85, with a minimum price of 5118 and a maximum price of 45400.

*   The majority of the cars in the dataset have a fuel type of gas and an aspiration type of std.
*   The car body type of sedan is the most common, followed by hatchback and wagon.

*   Convertible cars are most expensive compare to other segments cars.
*   High hourse power in car cause low milege and vice versa.

*   Most expensive cars are generaaly made by BMW.
*   Most of the cars in the dataset have a front-wheel drivetrain, with rear-wheel and four-wheel drivetrains being less common
*   The majority of the cars have an engine type of ohc, followed by ohcf and ohcv.

*   The number of cylinders in most of the cars is four, followed by six and five.
*   Most of the cars in the dataset have two doors, followed by four doors.

*   Toyota is the most common car company in the dataset, followed by Nissan and Mazda.
*   There is a positive correlation between price and engine size, horsepower, curb weight, and car width.

*   There is a negative correlation between price and city miles per gallon (mpg) and highway mpg.
## Results of ML model:

---
*   Data cleaning: The dataset had missing values, outliers, and incorrect data types, which were handled by imputing missing values, treating outliers, and converting data types.

*   Feature Engineering: New features were created from existing ones, such as car area and weight_to_area, to improve model performance.
*   Feature Selection: Correlation matrix and heatmap were used to select the most relevant features for the prediction model.

*   Data Normalization: The data was standardized using the MinMaxScaler function to normalize the data and make it easier for the model to learn.
*   Model Selection: Five different regression models, including Linear Regression, Lasso, ElasticNet, Decision Tree, Random Forest, and XGBoost, were trained and compared using cross-validation.
