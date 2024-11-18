In this project we use different feature groups such as economic, energy, demographic, and policy predictors that can influence CO₂ emissions. We use multicollinearity and VIF analysis to remove correlated variables, which is necessary for the model's stability. We then perform linear regression on normalized variables. We use data from the year 2019 as training data and previous years' data to test the predictability of the model. The model achieves an R² value of approximately 0.7, indicating that it explains about 70% of the variance in CO₂ emissions, suggesting strong predictive power on both training and test datasets. 
<br>
While adding more features may improve the R² value, this approach can lead to overfitting. Adding more features increases model complexity, allowing it to capture noise in the training data rather than true underlying patterns. This is particularly concerning in CO₂ emission prediction where relationships between variables should reflect real-world economic and environmental mechanisms. Therefore, we maintain a balance between model complexity and predictive power, prioritizing stable and interpretable features over achieving marginally higher R² values that might indicate overfitting.
