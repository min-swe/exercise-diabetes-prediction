# Diabetes Prediction

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT

100 words to explain what your project is about to a general audience. 

This project is utilising historical data from patients, and tries to predict whether a patient has diabetes based on other medical information like pregnancies, blood pressure, etc.

This project is using the simplest classification model to predict a binary result - whether the patient has diabetes or not.

The performance is good for precision, but some other metrics can be improved.

## DATA

I got the data from https://www.kaggle.com/datasets/mathchi/diabetes-data-set?resource=download.

## MODEL 

I chose a linear regression model as it's the simplest to start out and try if it has enough performance, before trying more complex models.

## HYPERPARAMETER OPTIMSATION

Initially I'm using the default training max_iterations. After trying I needed to tune it larger, and then resolved the training error.

## RESULTS

Overall performance of the model:

- accuracy: 0.8072916666666666
- Precision:	0.9166666666666666
- Recall:	0.5714285714285714
- sensitivity:	0.5714285714285714
- Specificity Score:	5.0
- F1 Score:	0.7039999999999998

The precision seems good. However there may be a better model, or a better-tuned model to have better recall, accuracy and sensitivity.
