Height Prediction from Weight using Linear Regression
Domain: Supervised Machine Learning | Type: Regression | Libraries: pandas, numpy, matplotlib, seaborn, sklearn

*** Project Overview***
In this project, I built a simple linear regression model to predict a person’s height based on their weight. The goal was to understand the linear relationship between these two continuous variables and evaluate how well the model can generalize to unseen data.

*** Steps Involved***
Data Preprocessing: Loaded CSV data, removed unnecessary columns, handled missing values if any.

Exploratory Data Analysis: Used scatterplots and pairplots to visualize the correlation between weight and height.

Train-Test Split: Split data into training (80%) and testing (20%) sets.

Feature Scaling: Applied StandardScaler to normalize weight values before training.

Model Building: Trained a LinearRegression() model from scikit-learn.

***Model Evaluation:***

Calculated key metrics:

R² Score: Measures goodness of fit

MSE & MAE: Measures error between actual vs predicted values

Residual Analysis: Plotted residuals to check model assumptions (normal distribution, homoscedasticity).

Prediction Plot: Visualized predicted vs actual height.

***Evaluation Metrics**
R² Score: Measures the proportion of variance explained by the model.

MAE (Mean Absolute Error): Average of absolute errors.

MSE (Mean Squared Error): Penalizes larger errors.

Residual Plots: Verified if errors are normally distributed and not pattern-based.

***Key Takeaways***
Understood how to implement and interpret a regression model.

Learned the importance of scaling and evaluating model assumptions.

Practiced visualization techniques for understanding model behavior.

Gained practical experience with real-world data and sklearn pipeline.
