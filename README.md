Heart Disease Prediction Project
This project aims to predict heart disease using a dataset from KaggleHub. Two machine learning models, Support Vector Machine (SVM) and Logistic Regression, are trained and evaluated for their performance.

Dataset
The dataset used in this project is: johnsmith88/heart-disease-dataset from KaggleHub.

It contains various features related to heart health, with the target column indicating the presence or absence of heart disease.

Models Used
Support Vector Machine (SVM): A supervised learning model used for classification. In this project, an RBF kernel SVM is utilized.
Logistic Regression: A linear model for binary classification, often used as a baseline for classification tasks.
Results
The models were evaluated based on their accuracy and cross-validation scores.

Model Performance
Model	Accuracy (%)	Cross Validation Score (%)
Logistic Regression	79.5	85.2
SVM	69.9	69.9
As observed from the results, Logistic Regression performed better than SVM in terms of both accuracy and cross-validation score on this particular dataset.

How to Run the Notebook
Open in Google Colab: You can open this notebook directly in Google Colab.
Install Dependencies: Ensure all necessary libraries (pandas, scikit-learn, seaborn, matplotlib, kagglehub) are installed. KaggleHub might require authentication or setting up API keys, if not already configured.
Run Cells: Execute the notebook cells sequentially.
Future Work
Explore other machine learning models (e.g., Random Forest, Gradient Boosting).
Perform hyperparameter tuning for better model performance.
Conduct more extensive feature engineering and selection.
Address the ConvergenceWarning from Logistic Regression by scaling the data or increasing max_iter.
