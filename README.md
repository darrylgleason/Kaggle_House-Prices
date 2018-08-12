This work is used to create a submission for the "House Prices: Advanced Regression Techniques" Kaggle competition (https://www.kaggle.com/c/house-prices-advanced-regression-techniques). The goal of the competition is to most accurately predict the sale price of residential homes in Ames, Iowa given various feature data for each property. Property data includes 79 features describing year of construction, number of rooms, etc.

The data is imported, cleaned, and processed before four methods are used to develop models for predictions:
    1. Ordinary Least Squares
    2. Ridge Regression with Cross-Validation
    3. Random Forest
    4. Gradient Boosting
Generally, Gradient Boosting outperforms the other three models, so it is chosen to make predictions on the testing data. The model indicates that the five most important features for determining home price include:
    1. Above-ground living area square footage
    2. Overall house material and finish quality
    3. Lot size/area square footage
    4. Unfinished basement area square footage
    5. Garage area square footage
    
Per the Kaggle evaluation details: "Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price." Upon submission, the house prices predicted by this model received a score of approximately 0.136. As of 2018-08-12, the tenth-place score is approximately 0.110.
