This project focuses on developing and optimizing machine learning models to predict apartment prices using the "inmuebles.json" dataset.

The workflow involves loading and preprocessing data, normalizing and filtering it to focus on residential properties in Rio de Janeiro. Logarithmic transformation is applied to numeric variables to improve data distribution, and feature engineering techniques such as dummy variable encoding for categorical features are employed.

Several regression models are trained to forecast apartment prices, including linear regression, decision trees, and random forests. Each model is evaluated using metrics like the coefficient of determination (R^2) to assess its performance in price prediction.

Optimization techniques such as cross-validation and random search for hyperparameter tuning are used to enhance model performance. Cross-validation (K-Fold) is employed to evaluate the model's generalization ability and prevent overfitting. Random search is used to find the best hyperparameter combinations for decision tree and random forest models.

Finally, the models and their optimized versions are compared to select the best approach for predicting apartment prices. The analysis includes prediction error plots and performance metrics to ensure the effectiveness and accuracy of the developed models.