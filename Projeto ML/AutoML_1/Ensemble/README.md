# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Default_Xgboost |        3 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.331272 | nan          |
| auc       | 0.666143 | nan          |
| f1        | 0.2763   |   0.135502   |
| accuracy  | 0.879087 |   0.257128   |
| precision | 0.36036  |   0.257128   |
| recall    | 1        |   0.00887562 |
| mcc       | 0.162347 |   0.162929   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.331272 |  nan        |
| auc       | 0.666143 |  nan        |
| f1        | 0.160504 |    0.257128 |
| accuracy  | 0.879087 |    0.257128 |
| precision | 0.36036  |    0.257128 |
| recall    | 0.103245 |    0.257128 |
| mcc       | 0.143413 |    0.257128 |


## Confusion matrix (at threshold=0.257128)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            21015 |              497 |
| Labeled as 1 |             2432 |              280 |

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
