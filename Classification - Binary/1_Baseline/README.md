# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **num_class**: 4
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

0.7 seconds

### Metric details
|           |   Multi-ethnic |   Not Span/Hispanic |   Spanish/Hispanic |   Unknown |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|---------------:|--------------------:|-------------------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |              0 |            0.832881 |                  0 |         0 |   0.832881 |    0.20822  |       0.693691 |  0.567213 |
| recall    |              0 |            1        |                  0 |         0 |   0.832881 |    0.25     |       0.832881 |  0.567213 |
| f1-score  |              0 |            0.908822 |                  0 |         0 |   0.832881 |    0.227205 |       0.75694  |  0.567213 |
| support   |             17 |         3683        |                516 |       206 |   0.832881 | 4422        |    4422        |  0.567213 |


## Confusion matrix
|                              |   Predicted as Multi-ethnic |   Predicted as Not Span/Hispanic |   Predicted as Spanish/Hispanic |   Predicted as Unknown |
|:-----------------------------|----------------------------:|---------------------------------:|--------------------------------:|-----------------------:|
| Labeled as Multi-ethnic      |                           0 |                               17 |                               0 |                      0 |
| Labeled as Not Span/Hispanic |                           0 |                             3683 |                               0 |                      0 |
| Labeled as Spanish/Hispanic  |                           0 |                              516 |                               0 |                      0 |
| Labeled as Unknown           |                           0 |                              206 |                               0 |                      0 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
