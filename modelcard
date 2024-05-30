

# Model Card for University Admission Prediction Model

## Model Details
Model Name: University Admission Prediction Model
Model Version: 1.0
Model Type: Regression
Author: [Saqib Safdar]
Date: [30.5.24]

## Model Overview
The University Admission Prediction Model is designed to predict the probability of a student's admission to a university based on their academic and other related profiles. The model leverages multiple input features such as GRE score, TOEFL score, university rating, SOP, LOR, CGPA, and research experience to provide a likelihood score for admission.

## Intended Use
Primary Users: Prospective students, university admission counselors, educational consultants.
Primary Use Case: To assist in evaluating the likelihood of a student's admission to a university, aiding in decision-making processes for applications and preparation strategies.

## Inputs and Outputs
Inputs:
- GRE Score (260-340)
- TOEFL Score (0-120)
- University Rating (1-5)
- SOP (Statement of Purpose strength, 1-5)
- LOR (Letter of Recommendation strength, 1-5)
- CGPA (Cumulative Grade Point Average, 0-10)
- Research (1 if research experience, 0 if none)

Output:
- Chance of Admit (Probability between 0 and 1)

## Model Training and Evaluation
The model is trained and evaluated using the following steps:

- Data Preparation: The dataset is read into a Pandas DataFrame, and basic exploratory data analysis (EDA) is performed using Seaborn and Matplotlib.


## Model Training:
Initial Training: An XGBoost Regressor is trained without any hyperparameter optimization.
- # Hyperparameter Optimization:
- Grid Search: Hyperparameters such as max_depth, learning_rate, n_estimators, and colsample_bytree are optimized using GridSearchCV.
- Randomized Search: Hyperparameters are further tuned using Gridsearch Method, Random Search, and Bayesian Optimisation Method.



## Model Architecture
Algorithm: XGBoost Linear Regression (can be updated based on the actual model used)
Framework: Python (using libraries such as Pandas, NumPy, and Scikit-learn)

## Performance Metrics
Evaluation Metric: Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R²)

## Performance 

- XG-Boost Algorithm Without Optimization: 66% accuracy
- Gridsearch Method : 83.8 % accuracy
- Random Search Method: 83.7% accuracy
- Bayesian Optimisation Method: 84.3% accuracy

## Limitations
- Data Representation: The dataset may not represent all possible applicant profiles and is limited to the sample it was derived from.
- Feature Limitations: Important factors such as extracurricular activities, interviews, and personal statements are not included.
- Bias: Potential biases in the dataset, such as overrepresentation of certain demographic groups.
- Static Model: The model does not update with new data automatically and requires manual retraining for new trends or changes in admission criteria.

## Ethical Considerations
- Fairness: Ensure the model does not unfairly disadvantage any group of applicants.
- Transparency: Clearly communicate the factors considered in the model to the users.
- Privacy: Handle applicant data with confidentiality and in compliance with data protection regulations.

## Recommendations
For Users: Use the model as a supplementary tool along with other evaluation criteria. Do not rely solely on the model for admission decisions.
For Developers: Continuously monitor and update the model with new data and features to improve accuracy and fairness.

## Maintenance
Maintainer: Saqib Safdar
Contact Information: s.safdar@lse.ac.uk
Update Frequency: The model should be reviewed and updated at least once per admission cycle to incorporate new data and feedback.

## Additional Information
Documentation: [README.md](README.md)
Code Repository: [Project Bayesian Optimization and Hyperparameters Tuning.ipynb](https://github.com/username/repository/blob/main/Project%20Bayesian%20Optimization%20and%20Hyperparameters%20Tuning.ipynb)
Datasheet: [Datasheet.md](Datasheet.md)

This model card provides a comprehensive overview of the University Admission Prediction Model, including its intended use, performance metrics, limitations, and ethical considerations. It aims to ensure transparency and help users understand the context and capabilities of the model.