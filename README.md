# flood_prediction_ML
Flood Probability Prediction using Random Forest
Project Overview
This project develops a machine learning model to predict flood probability using climatic, infrastructural, and socio-environmental factors. A Random Forest Regressor was implemented to capture nonlinear relationships between multiple interacting variables influencing flood risk.
The objective is to identify the most influential drivers of flooding and evaluate the predictive performance of ensemble-based methods.
Dataset
The dataset contains 20 explanatory variables including:
•	MonsoonIntensity
•	TopographyDrainage
•	RiverManagement
•	DamsQuality
•	Urbanization
•	ClimateChange
•	WetlandLoss
•	PoliticalFactors
•	and additional environmental and planning indicators
Target Variable:
•	FloodProbability (continuous, 0–1 scale)
Methodology
1.	Data validation and inspection
2.	Feature–target separation
3.	Train-test split (80–20)
4.	Random Forest Regression
5.	Model evaluation using:
•	R² Score
•	Mean Absolute Error (MAE)
•	Root Mean Squared Error (RMSE)
6.	5-Fold Cross-Validation
7.	Feature Importance Analysis
8.	Actual vs Predicted visualization
Model Performance
Test Set Performance:
•	R² Score ≈ 0.73
•	MAE ≈ 0.020
•	RMSE ≈ 0.025
Cross-Validation (5-Fold):
•	Average R² ≈ 0.73
The consistency between test performance and cross-validation results indicates stable generalization capability and low overfitting

