DiabRisk — Diabetes Prediction 
DiabRisk is a machine learning-based diagnostic tool designed to predict diabetes risk using health survey indicators. 
This version represents a significant upgrade from the original pilot study, moving from a small-sample dataset (PIMA) to a large-scale, generalized model utilizing over 70,000 records.
Project Overview-
The primary goal of this upgrade was to address the issue of overfitting found in smaller datasets. 
By leveraging a much larger data volume, the model has achieved a high degree of generalization, ensuring it performs reliably on new, unseen data.
Dataset Transformation
Feature -(Current)Dataset Source(Kaggle) CDC BRFSS 2015 (Behavioral Risk Factor Surveillance System)
Record Count768 rows70,692 rows (50/50 Balanced Split) FocusProof of ConceptEnterprise-Scale Generalization
Technical StackLanguage: 
PythonLibraries: Pandas, Scikit-learn, Matplotlib, Seaborn, 
PickleModel: Random Forest Classifier (Regularized)
Environment: Model Performance & GeneralizationThe model was trained using an 80/20 train-test split with a focus on minimizing the "Generalization Gap.
Training Accuracy: 76.91%
Testing Accuracy: 74.14%
Accuracy Gap: 2.77% (Confirms the model is generalized and not overfitted)
ROC-AUC Score: 0.82Key Insights (Feature Importance)
The Random Forest model identified the following as the top three predictors of diabetes:General Health (GenHlth)High Blood Pressure (HighBP)Body Mass Index (BMI)


Previous deployed project(with pimna dataset 780 rows) link to give you an idea of what this project will look like in future- 
