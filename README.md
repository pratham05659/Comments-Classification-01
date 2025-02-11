# Comments-Classification-01
<br>
This repository contains code, notebooks, and documentation for my participation in the Kaggle Comment Classification Competition. The goal of the competition is to predict the probabilities for each text sample belonging to multiple categories—Complaint, Demands, Praise, and Questions—using machine learning and natural language processing techniques.
<br>
<br>
----Project Overview----
<br>
Objective:
<br>
Build a multi-label classification model to predict the likelihood that a given comment falls into one or more of the specified categories.
<br>
<br>
-----Dataset:-----
<br>
train.csv: Contains text samples with binary labels indicating whether each sample belongs to a specific category.
<br>
test.csv: Contains text samples for which the predictions need to be generated.
<br>
sample_submission.csv: Provides the required format for your submission, including the unique identifier and the predicted probabilities for each category.
<br>
<br>
-----Techniques and Libraries:------
<br>
Data Exploration & Preprocessing: Pandas, NumPy
<br>
Text Processing: Regular expressions, NLTK
<br>
Feature Engineering: TF-IDF vectorization, word embeddings
<br>
Modeling: scikit-learn (baseline models like Logistic Regression, Random Forest), and deep learning frameworks (TensorFlow/Keras) for advanced modeling
<br>
Evaluation: AUC (Area Under the ROC Curve) for multi-label classification
<br>
Submission: Using Kaggle API for downloading data and submitting predictions
