#Air Quality Prediction Using Multiple Linear Regression

Overview

##This project develops a Multiple Linear Regression model to predict Absolute Humidity (AH) using air quality sensor measurements and meteorological variables. The dataset contains environmental and pollutant-related features collected from air quality monitoring stations.

##The project demonstrates a complete Machine Learning workflow, including:

* Data Loading
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Feature Scaling
* Multiple Linear Regression Model Training
* Model Evaluation
* Prediction Generation
* Result Interpretation

⸻

##Problem Statement

Air quality monitoring stations collect various pollutant concentrations, sensor readings, and weather measurements. The objective of this project is to analyze how these variables collectively influence atmospheric conditions and accurately predict Absolute Humidity (AH).

This is a Supervised Machine Learning Regression Problem where the target variable is continuous.

⸻

##Dataset Information

##Features

Feature	Description
ID	Unique identifier
Date	Date of observation
Time	Time of observation
CO(GT)	Carbon Monoxide concentration
PT08.S1(CO)	Sensor 1 reading
NMHC(GT)	Non-Methane Hydrocarbons
C6H6(GT)	Benzene concentration
PT08.S2(NMHC)	Sensor 2 reading
NOx(GT)	Nitrogen Oxides concentration
PT08.S3(NOx)	Sensor 3 reading
NO2(GT)	Nitrogen Dioxide concentration
PT08.S4(NO2)	Sensor 4 reading
PT08.S5(O3)	Sensor 5 reading
T	Temperature
RH	Relative Humidity

##Target Variable

Variable	Description
AH	Absolute Humidity

⸻

##Project Workflow

1. Data Collection

* Loaded training dataset
* Loaded testing dataset

2. Data Understanding

* Dataset shape
* Data types
* Statistical summary
* Missing value analysis
* Duplicate value analysis

3. Exploratory Data Analysis (EDA)

Univariate Analysis

* Feature distributions
* Target variable distribution
* Histograms
* Density plots

Outlier Analysis

* Boxplots for numerical features

Bivariate Analysis

* Feature vs Target scatter plots

Correlation Analysis

* Correlation matrix
* Heatmap visualization
* Target correlation analysis

4. Data Preprocessing

* Removed unnecessary columns
* Selected relevant features
* Applied feature scaling using StandardScaler

5. Model Building

Implemented:

* Multiple Linear Regression

6. Model Evaluation

Performance evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

7. Prediction

⸻

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

⸻

Model Evaluation Metrics

The model was evaluated using:

R² Score

Measures how well the independent variables explain the variance in the target variable.

Mean Absolute Error (MAE)

Measures the average magnitude of prediction errors.

Root Mean Squared Error (RMSE)

Measures the standard deviation of prediction errors.

⸻

Key Findings

* Temperature and Relative Humidity showed strong influence on Absolute Humidity.
* Several sensor measurements exhibited significant correlation with the target variable.
* Multiple Linear Regression successfully captured relationships between environmental variables and atmospheric humidity.

⸻

Future Improvements

The following models can be explored to improve performance:

* Ridge Regression
* Lasso Regression
* Polynomial Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

⸻

Results

The trained model successfully predicts Absolute Humidity (AH) using air quality and weather measurements and demonstrates the effectiveness of Multiple Linear Regression for environmental data analysis.

⸻

Author

Machine Learning Project developed as part of regression modeling and environmental data analysis practice using Python and Scikit-Learn.
