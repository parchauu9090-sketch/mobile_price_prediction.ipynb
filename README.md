# mobile_price_prediction.ipynb
Mobile Phone Price Prediction
A machine learning project to predict mobile phone prices based on their technical specifications.

About the Project
This project analyzes a dataset of mobile phones and builds a predictive model to estimate their prices. Using various regression techniques, the model identifies key factors that influence mobile phone pricing in the US market.

Dataset
The "Mobiles Dataset (2025)" contains information about mobile phones including:

Manufacturer (Company Name)
Model Name
Mobile Weight
RAM
Front Camera resolution
Back Camera resolution
Processor
Battery Capacity
Screen Size
Launch Prices (Pakistan, India, China, USA, Dubai)
Launch Year
Project Steps
Data Exploration

Dataset structure analysis
Missing values check
Data Processing

Cleaning text values and converting to numeric
Processing RAM, camera, battery, screen size, and weight specifications
Price distribution visualization
Correlation Analysis

Identifying the most important features affecting price
Correlation heatmap visualization
Model Building

Linear Regression
Ridge Regression
Lasso Regression
Decision Tree
Random Forest
Gradient Boosting
Model Evaluation

Using RMSE, MAE, R² metrics
Performance comparison visualization
Feature Importance Analysis

Determining which features most impact price prediction
Hyperparameter Optimization

Tuning the Random Forest model for better performance
Results
After comparing different models:

Best model: Random Forest
RMSE on test set: $134.94
MAE on test set: $88.08
R²: 0.8948 (89.48% of price variance explained by the model)
Feature importance analysis showed that the following characteristics have the greatest impact on phone price:

Phone weight (30.61%)
Processor type (25.85%)
RAM amount (22.21%)
Back camera resolution (9.66%)
Brand (especially Huawei - 3.51%)
Technologies
Python 3
pandas
numpy
matplotlib
seaborn
scikit-learn
How to Use
Open the notebook in Google Colab or Jupyter
Run all cells to see the complete analysis
The notebook includes detailed comments and visualizations
Visualizations
The project includes various visualizations:

Price distribution analysis
Outlier detection with box plots
Correlation heatmap
Model performance comparison
Feature importance chart
Actual vs predicted price comparison
