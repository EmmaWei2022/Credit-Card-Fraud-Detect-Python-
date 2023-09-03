# Credit-Card-Fraud-Detect-Python
Update:

### Project Tasks:
- Perform an exploratory data analysis to understand which features might be correlated to fraud
-	Create models with those features and test out their predictive effectiveness.
- Hyperparameters tuning.
- Dealing with imbalanced datasets and improving model performance.


- https://app.datacamp.com/workspace/w/2c5397bc-e6dd-46db-a0b3-28259bf7b9e7

### Business Insights:
- Good predictors to classify fraud transactions (from EDA): amt, category, transaction time, age, state.
- Feature engineering could improve model performance: new features, such as trans_hour, trans_day_of_week, and distance.
- We have created the Decision Tree model as a base model and the Random Forest model as a comparison model. The Random Forest model performs better.
- From the Random Forest model, we found that the top 3 important features are amt, trans_hour, and category, which is consistent with the finding from EDA.
- We tried to deal with the imbalanced dataset and improve model performance with 6 different methods: Oversampling, Undersampling, SMOTE, Tomek Links, SMOTE Tomek, and Class Weights. The class Weights method performs best.
- We have done hyperparameters for all models and imbalanced improving methods to ensure our model could be robust.
- There is much more to do when it comes to K-Fold Cross Validation and tuning hyperparameters.
