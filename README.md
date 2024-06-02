# Predicting CO2 Emissions of Vehicles Using Real-Time Telematics Data

This repository contains the code and data for a project that explores the prediction of CO2 emissions from various vehicles using real-time telematics data. The project utilizes the 'Car Fuel & Emissions 2000-2013' dataset, which encompasses diverse vehicle specifications, including emissions (CO2, NOx, CO), noise levels, engine size, fuel type, and compliance standards.

**Key Objectives:**

- Develop a machine learning model that accurately predicts CO2 emissions based on vehicle data.
- Identify key factors influencing vehicle emissions.
- Determine the correlation between engine capacity and CO2 emissions.
- Analyze if certain manufacturers and models have better emission standards.
- Predict noise level based on engine capacity, fuel type, and transmission type.
- Determine if fuel efficiency can be predicted based on engine capacity, transmission type, and fuel type.
- Evaluate CO2 emissions based on the vehicle's model year.

**Methodology:**

- **Data Preprocessing:** The dataset was preprocessed to handle missing values, redundant columns, and inconsistent data.
- **Exploratory Data Analysis (EDA):**  Histograms, scatter plots, and other visualization techniques were used to explore data patterns and relationships.
- **Feature Selection:** Key variables relevant to CO2 emissions were selected based on EDA findings.
- **Machine Learning Models:** Various models were employed, including Linear Regression, Decision Trees, Random Forest, Gradient Boosting, Neural Networks, Support Vector Regression, KNN Regression, AdaBoost Regression, and Bayesian Regression.
- **Model Evaluation:**  Models were evaluated using metrics such as R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

**Insights:**

- Newer vehicles tend to have lower CO2 emissions due to technological advancements, efficient engines, and stricter emission standards.
- Vehicles adhering to higher Euro standards are associated with lower CO2 emissions, reflecting the objective of these standards to reduce emissions.
- Larger engine capacities are associated with higher CO2 emissions as they consume more fuel.
- Higher fuel efficiency, measured in miles per gallon, corresponds to lower CO2 emissions, indicating the importance of fuel-efficient vehicles.
- Engine capacity and fuel efficiency metrics are strong predictors of CO2 emissions, while 'year' and 'euro_standard' play significant roles.

**Key Findings:**

- Bagged Decision Trees Regressor and Random Forest Regressor consistently performed best in terms of R-squared, MSE, and MAE.
- Neural Network 2 demonstrated a negative R-squared, indicating poor performance compared to other models.

**Recommendations:**

- Bagged Decision Trees Regressor and Random Forest Regressor are recommended for predicting CO2 emissions due to their excellent model fit and high predictive accuracy.

**Future Work:**

- Incorporate additional features such as real-time telematics data for improved prediction accuracy.
- Explore other machine learning techniques to further refine the prediction model.
- Investigate the influence of driving patterns and environmental factors on CO2 emissions.
- Develop a framework for incorporating these insights into policymaking and emission reduction strategies.

This project provides valuable insights into the prediction of CO2 emissions from vehicles, highlighting the significance of engine capacity, fuel efficiency, and emission standards. The results contribute to the development of greener transportation options and can be used to inform policy decisions related to environmental management.

This README file provides a comprehensive overview of the project. For further details, please refer to the Jupyter Notebook files and the accompanying documentation within this repository.
