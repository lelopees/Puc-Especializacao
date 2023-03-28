# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.2 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.350583 |  nan        |
| auc       | 0.5      |  nan        |
| f1        | 0.201366 |    0.100773 |
| accuracy  | 0.111955 |    0.100773 |
| precision | 0.111955 |    0.100773 |
| recall    | 1        |    0.100773 |
| mcc       | 0        |    0.100773 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.350583 |  nan        |
| auc       | 0.5      |  nan        |
| f1        | 0.201366 |    0.100773 |
| accuracy  | 0.111955 |    0.100773 |
| precision | 0.111955 |    0.100773 |
| recall    | 1        |    0.100773 |
| mcc       | 0        |    0.100773 |


## Confusion matrix (at threshold=0.100773)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |                0 |            21512 |
| Labeled as 1 |                0 |             2712 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
