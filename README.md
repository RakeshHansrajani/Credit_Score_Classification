# Credit Score Classification Project

### Overview
Welcome to the Credit Score Classification Project repository! This project aims to predict credit scores for individuals using machine learning models. The repository contains code, data, Visualization, and a comprehensive report detailing the project's methodology, results, and recommendations.

### Project Content:
* Dataset.zip: Dataset used for training and evaluation.
* Credit_Score_Classification.ipynb: Jupyter notebook detailing the project workflow.
* Report.pdf/ Report.docx: Comprehensive report with detailed insights and results.
* Visualization_Columns: Charts generated in EDA part.
* Visualization_Model: Charts generated while model building.
* README.md: Project overview and usage instructions.

### Project Process and Steps:
This project aims to predict credit scores based on a given dataset. The process involves several key steps:

* Data Preprocessing: The dataset is cleaned and prepared for analysis. Missing values are handled, redundant columns are removed.

* Exploratory Data Analysis (EDA): Data insights are gained through univariate, bivariate, and multivariate analyses. Visualizations and summary statistics are used to identify patterns and relationships.

* Feature Engineering: New features are created, existing features are transformed, and categorical variables are encoded to improve model performance.

* Model Preprocessing: Data is split into training and testing sets. User defined functions are used to evaluate models, visualize ROC-AUC curves, and create a model comparison scorecard.

* Model Building: Various machine learning models are implemented. Model performance is assessed using relevant metrics. The models that are applied are:
  -	Logistic Regression
  - Decision Trees
  - Decision Trees (with and without pruning)
  -	Random Forest
  -	Random Forest (with and without pruning)
  -	Bagging Ensemble
  -	Adaboost Ensemble
  -	XG Boost Ensemble
  -	Naive Bayes Classifier
  -	k-Nearest Neighbors (KNN)

* Model Comparison: Models are compared using a scorecard that summarizes their performance. This aids in selecting the most suitable model for credit score classification.
