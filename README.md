# Fraud Detection

- Is it possible to imporve the performance of a model using synthetic examples?
- Can a GAN learn from examples to create realistic instances of fraud?
- Can a GAN do better than SMOTE?

Credit card fraud detection with an extremely imbalanced dataset was implemented. GAN and SMOTE were used to create synthetic samples to check if the performance of three models can be improved. The models were: logistic regression, random forest and gradient boosting. The GAN created realistic instances, but did not extract useful information from the fraud examples and the model didn't improve its performance. SMOTE had a better performance.


## Main Files
- The dataset: taken from https://www.kaggle.com/mlg-ulb/creditcardfraud
- The notebook: fraud_detection.ipynb
- The Generative Adversarial Network: gan.py

## Usage:
- Is necessary the installation of Jupyter to run the notebook.

## Necessary Packages:
- Python 3.8.3
- Pandas version 1.1.3
- Sci-kit Learn version 0.23.2
- Tensorflow version: 2.4.1
