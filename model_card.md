# Model Card

## Model Description

**Input:**

- Number of times pregnant
- Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- Diastolic blood pressure (mm Hg)
- Triceps skin fold thickness (mm)
- 2-Hour serum insulin (mu U/ml)
- Body mass index (weight in kg/(height in m)^2)
- Diabetes pedigree function
- Age (years)
- Class variable (0 or 1)

**Output:** prediction that given the input, whether the patient has diabetes: class value 1 is interpreted as 'has diabetes', and class value 0 is interpreted as 'does not have diabetes'.

**Model Architecture:** 

I'm using a simple logistic regression model.

## Performance

Metrics:

- accuracy: 0.8072916666666666
- Precision:	0.9166666666666666
- Recall:	0.5714285714285714
- sensitivity:	0.5714285714285714
- Specificity Score:	5.0
- F1 Score:	0.7039999999999998

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

## Limitations

Overall the accuracy and precision seems good. However the recall and sensitivity can probably be improved.

## Trade-offs

Initially I used the default iteration to train the model but got an error that the model would not converge.

I modified the model to have `max_iter=300`, and as a result it now converges.