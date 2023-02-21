 #Sepsis_Pridiction
 About this file
ID: number to represent patient ID
PRG: Plasma glucose 
PL: Blood Work Result-1 (mu U/ml)
PR: Blood Pressure (mm Hg)
SK: Blood Work Result-2 (mm)
TS: Blood Work Result-3 (mu U/ml)
M11: Body mass index (weight in kg/(height in m)^2
BD2: Blood Work Result-4 (mu U/ml)
Age: patients age (years)
Insurance: If a patient holds a valid insurance card
Sepsis: Positive: if a patient in ICU will develop a sepsis , and Negative: otherwis

# **Conclusion**
 
 In this project, we trained four different classification models: Logistic Regression, Support Vector Machine (SVM), Random Forest, and Neural Network. We used GridSearchCV to find the best hyperparameters for each model and evaluated the performance of each model using validation accuracy.

For Logistic Regression, the best hyperparameter was found to be 'C' with a value of 1.0, and the validation accuracy was 0.9958. For SVM, the best hyperparameters were 'C' with a value of 10.0 and 'gamma' with a value of 0.001, and the validation accuracy was 0.9938. For Random Forest, the best hyperparameters were 'max_depth' with a value of 50 and 'n_estimators' with a value of 100, and the validation accuracy was 0.9979. Finally, for Neural Network, the best hyperparameters were 'alpha' with a value of 10.0 and 'hidden_layer_sizes' with a value of (100, 100), and the validation accuracy was 0.9938.

Based on the validation accuracy, we can conclude that the Random Forest model performed the best with an accuracy of 0.9979, followed by Logistic Regression with an accuracy of 0.9958. SVM and Neural Network had slightly lower accuracy scores but were still highly accurate with scores of 0.9938. Overall, all four models performed very well, and the choice of which model to use will depend on the specific needs of the application.

