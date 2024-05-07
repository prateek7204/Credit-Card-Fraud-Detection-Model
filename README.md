Credit Card Fraud Detection Model
This project implements a machine learning model to detect fraudulent credit card transactions using logistic regression. The model is developed in a Jupyter Notebook environment, utilizing the Pandas library for data manipulation and the LogisticRegression algorithm from Scikit-Learn.

Installation
To run this project locally, ensure you have Python 3.x installed along with the following dependencies:

Jupyter Notebook
Pandas
Scikit-Learn
You can install the dependencies using pip:

Copy code
pip install jupyter pandas scikit-learn
Usage
Clone or download this repository to your local machine.
Navigate to the project directory.
Open the Jupyter Notebook credit_card_fraud_detection.ipynb.
Follow the instructions provided in the notebook to execute the code cells.
Dataset
The dataset used for this project contains credit card transactions made by European cardholders. It includes features such as transaction amount, time, and anonymized principal components. The dataset is available in the file creditcard.csv.

Model Development
Data Preprocessing: Cleaning, scaling, and feature engineering to prepare the data for modeling.
Model Training: Utilizing Logistic Regression for binary classification of fraudulent vs. non-fraudulent transactions.
Model Evaluation: Assessing the model's performance using accuracy_score from Scikit-Learn metrics module.
Results
The model achieved an accuracy of 89% on the test dataset.


Author
Prateek Kumar

