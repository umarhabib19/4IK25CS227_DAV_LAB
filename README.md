# DAV Lab Experiments

## Experiment 8: Titanic Survival Prediction

The notebook uses logistic regression to predict passenger survival and reports classification metrics with a confusion matrix.

**Notebook:** [Open the rendered Experiment 8 notebook](4IK25CS227_EXP_08.ipynb)

### Confusion matrix preview

The preview shows the matrix layout; numeric counts are generated when the notebook runs. The notebook saves the resulting plot as `experiment_08_confusion_matrix.png`.

| Actual / Predicted | Not Survived | Survived |
|---|---|---|
| Not Survived | True negatives | False positives |
| Survived | False negatives | True positives |

The notebook expects `Titanic-Dataset.csv` at `/content/Titanic-Dataset.csv` (the default Google Colab path).

