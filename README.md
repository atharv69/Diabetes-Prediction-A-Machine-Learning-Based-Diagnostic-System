# Predicting Diabetes with Machine Learning: A Logistic Regression & SVM Approach
Predicting Diabetes with Machine Learning: A Logistic Regression & SVM Approach
Diabetes is a chronic health condition that affects millions worldwide, making early detection crucial for effective treatment. This project utilizes machine learning techniques, specifically Logistic Regression, to classify individuals as diabetic or non-diabetic using the PIMA Indian Diabetes dataset.

Dataset Overview
The dataset consists of medical diagnostic features such as glucose levels, BMI, insulin levels, and age to predict diabetes risk. The target variable, Outcome, indicates whether a patient has diabetes (1) or not (0).

Data Preprocessing
Loading the Dataset:

The dataset is imported into a Pandas DataFrame, and exploratory data analysis (EDA) is performed to understand missing values, feature distributions, and class imbalance.

Feature Scaling:
Since medical attributes have different scales, StandardScaler is applied to standardize features for better model performance.
Handling Class Imbalance:

The dataset has an uneven distribution of diabetic (1) and non-diabetic (0) cases. To balance the data, techniques like stratified sampling are used.

Feature Selection:
The Outcome column is separated from features to create X (independent variables) and Y (target variable).

Model Training & Evaluation

Splitting Data:
The dataset is split into 80% training and 20% testing using train_test_split, ensuring the class distribution remains balanced.

Logistic Regression:
A Logistic Regression model is trained to classify patients as diabetic or non-diabetic.
Performance Metrics:

The model achieves:
Accuracy: 78.4% on training data, 75.6% on test data.
Precision & Recall: Evaluated to measure how well the model identifies diabetic cases.

Conclusion
The Logistic Regression model provides a solid baseline for diabetes prediction. However, real-world medical datasets often require more sophisticated techniques. Future improvements could include:

More complex models like Random Forests, SVMs, or Neural Networks for higher accuracy.
This machine learning-based approach offers a valuable decision-support tool for early diabetes detection, aiding in timely medical interventions. 
