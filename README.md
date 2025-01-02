# COVID-19 Vaccine Hesitancy Analysis and Prediction

This project explores the socio-economic and geographical factors influencing COVID-19 vaccine hesitancy in the United States. Using advanced machine learning models, the analysis aims to predict vaccine hesitancy rates at the county level and provide actionable insights to inform public health strategies.

## Key Features

- **Data Integration**: Combined county-level COVID-19 vaccine administration data, Social Vulnerability Index (SVI), CVAC levels of concern, and vaccine hesitancy estimates for comprehensive analysis.
- **Feature Selection**: Employed a Decision Tree Regressor to identify the top 10 predictive features, including FIPS code, highlighting geographical factors as a key determinant of hesitancy.
- **Model Development**: Built and tuned K-Nearest Neighbors (KNN) and Random Forest Regressor models to predict vaccine hesitancy rates, achieving low Mean Squared Error (MSE) values.
- **Insights**: Found that SVI had a weak negative correlation with vaccination rates, while geographical proximity (FIPS code) emerged as a strong predictor of hesitancy.

## Highlights

- The KNN model achieved the best accuracy with an optimized MSE of 1.68, while Random Forest delivered robust performance with an MSE of 3.30.
- Hyperparameter tuning and Grid Search enhanced model performance, ensuring accurate predictions.
- Insights derived from the models emphasize the importance of location and demographic factors over socio-economic indices like SVI in influencing vaccine hesitancy.

## Applications

The results of this project are valuable for:
- **Policymakers and Public Health Officials**: To target areas with high vaccine hesitancy and optimize vaccination strategies.
- **Future Pandemic Preparedness**: Identifying strong predictors like geographical location can help design better models for health crisis management.

## Future Directions

- Refine the analysis by further exploring individual predictors and testing additional models for improved accuracy.
- Expand the dataset to include more granular socio-economic and health-related variables to enhance predictive capabilities.
