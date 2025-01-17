**Credit Risk Modeling Project**

This project focuses on developing and evaluating machine learning models for credit risk assessment. The objective is to predict whether an applicant will be approved for credit based on historical data and several features such as financial, and transactional information.

Key Features:

**Data Preprocessing**: Data cleaning, feature encoding, and label encoding to prepare the dataset for machine learning models.

**Modeling Techniques**: Implemented multiple machine learning algorithms including:

  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting
  - XGBoost
  - CatBoost
  - Naive Bayes
    
**Hyperparameter Tuning**: Utilized **GridSearchCV** for hyperparameter optimization, improving model performance and generalization. For the CatBoost model, key hyperparameters such as iterations, depth, and learning rate were fine-tuned.

**Evaluation**: Evaluated the models based on accuracy, precision, recall, and F1-score to understand their predictive capabilities. CatBoost was selected as the final model due to its high accuracy and performance in both training and test data.

**Business Impact**: The model helps determine credit approval based on risk appetite, targeting different risk levels for decision-making:
  - **Low risk appetite**: Focus on applicants already achieving the target.
  - **High risk appetite**: Consider applicants further from the target to achieve higher returns.
  - **Severe risk appetite**: Incorporates all potential candidates to maximize target achievement, even at higher risk levels.
