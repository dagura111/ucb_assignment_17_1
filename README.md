### Bank Marketing Campaign Analysis

#### Overview

This project focuses on analyzing a bank marketing dataset to develop predictive models that can help in identifying potential customers who are more likely to subscribe to a term deposit. 

#### Data

The dataset used in this analysis (bank-additional-full.csv) contains information related to direct marketing campaigns of a Portuguese banking institution. The data includes customer demographic details, socio-economic factors, and historical contact information. 

#### Deliverables

The main deliverables of this project are:

Preprocessed Dataset: The dataset was preprocessed for modeling, including encoding categorical variables and scaling numerical features.
Comparative Analysis of Classifiers: Several machine learning classifiers were trained and compared:
Logistic Regression
K-Nearest Neighbors
Decision Tree
Support Vector Machine
Hyperparameter Tuning: Utilized GridSearchCV for optimal hyperparameter tuning of each model.
Model Evaluation: Models were evaluated based on accuracy, precision, recall, ROC AUC score, and training time.
Feature Importance Analysis: Specifically for the Decision Tree model, to identify the most influential factors in predicting customer response.

#### Conclusion

Decision Tree emerged as a balanced model with the best recall and ROC AUC score, indicating its effectiveness in identifying potential subscribers and differentiating between the classes.
Support Vector Machine demonstrated the highest precision, though with longer training time.
All models showed high and comparable accuracy, suggesting good generalization capabilities across different approaches.
Recommendations to Bank Marketing Business

#### Features
The most influential features were the duration of contact with the customer and the employment rate. Strategies to optimize call duration and targeting customers during favorable employment conditions might increase the success rate.
