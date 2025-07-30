# Titanic-Survival-Prediction

## DE:
## **Vorhersagemodell zur Überlebenswahrscheinlichkeit auf der Titanic**

In diesem Projekt wurde ein vollständiger Machine-Learning-Workflow in einem Jupyter Notebook implementiert, um die Überlebenswahrscheinlichkeit von Passagieren der Titanic zu klassifizieren. Ziel war die Anwendung und Optimierung von ML-Pipelines zur Lösung eines realen Klassifikationsproblems.

**Ergebnis:** Zwei voll funktionsfähige und optimierte Klassifikations-Pipelines, und deren vergleichende Analyse.

Angewandte Fähigkeiten:

* Datenaufbereitung und Pipeline-Entwicklung:
  - Verarbeitung des Titanic-Datensatzes, einschließlich der Auswahl relevanter Merkmale und dem Umgang mit fehlenden Werten durch Imputation
  - Aufbau einer robusten Scikit-learn Pipeline, die eine automatische Vorverarbeitung (Skalierung numerischer und One-Hot-Encoding kategorialer Merkmale) mit dem jeweiligen Klassifikationsmodell kombiniert.
  
* Training und Hyperparameter-Optimierung: 
  - Training eines Random Forest Classifiers und systematische Optimierung der Hyperparameter (n_estimators, max_depth etc.) mittels Grid Search Cross-Validation, um die bestmögliche Modellleistung zu erzielen.
  - Die Aufteilung der Daten erfolgte stratifiziert, um die Klassenverteilung im Trainings- und Test-Set beizubehalten.
  
* Modell-Evaluation und iterativer Vergleich:
  - Umfassende Bewertung des optimierten Random-Forest-Modells anhand eines Klassifikationsberichts, einer Konfusionsmatrix und der Analyse der Merkmalswichtigkeit (Feature Importance), wobei eine Genauigkeit von 83,24 % erreicht wurde
  - Zum Vergleich wurde die Pipeline flexibel angepasst und ein zweites Modell (Logistische Regression) trainiert und bewertet
  - Gegenüberstellung beider Modelle, die eine nahezu identische Genauigkeit, aber sehr unterschiedliche wichtige Merkmale aufzeigten, was die Bedeutung der Modellinterpretation unterstreicht.


## EN:

## **Prediction model for the probability of survival on the Titanic**

In this project, a complete machine learning workflow was implemented in a Jupyter notebook to classify the probability of survival of passengers on the Titanic. The goal was to apply and optimize ML pipelines to solve a real-world classification problem.

**Result:** Two fully functional and optimized classification pipelines, and their comparative analysis.

Applied skills:

* Data preparation and pipeline development:
  - Processing of the Titanic dataset, including selecting relevant features and dealing with missing values by imputation
  - Building a robust scikit-learn pipeline combining automatic preprocessing (scaling numerical and one-hot encoding of categorical features) with the respective classification model.
 
* Training and hyperparameter optimization:

  - Training of a random forest classifier and systematic optimization of hyperparameters (n_estimators, max_depth etc.) using grid search cross-validation to achieve the best possible model performance.
  - The distribution of the data was stratified to maintain the class distribution in the training and test set.
    
* Model evaluation and iterative comparison:
  - Comprehensive evaluation of the optimized random forest model using a classification report, confusion matrix and feature importance analysis, achieving an accuracy of 83.24%
  - For comparison, the pipeline was flexibly adapted and a second model (logistic regression) was trained and evaluated
  - Comparison of both models, which showed almost identical accuracy, but very different important features, which underlines the importance of model interpretation.

