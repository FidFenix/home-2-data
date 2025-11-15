## Goal
The goal for this project is to build an end-to-end, automated data-science workflow that involves visualization, pipelines, tracking,tuning, and deep learning in one deproducible notebook with markdown explanations and read like a concise data-science report.
The data to be used should be https://archive.ics.uci.edu/dataset/222/bank+marketing

## Steps that should be in the notebook
- Introduction and EDA: 
1. Describe dataset and business goal. 
2. Visualize with seaborn package
- Data preparation with pipelines: 
1. Implement scikit-learn Pipeline with ColumnTransformer. The numeric column should be imputer + scaler and the categorical column should be imputer + one-hot encoder.
- Model building and comparison
1. Implement logistic regression
2. Implement decision tree, random forest and XGBoost.
3. Evaluate and compare F1, ROC AUC, and accuracy.
- Automation and tracking
1. use mlflow to log parameters, metrics, and models.
- Hyperparameter tuning
1. Apply gridsearchCV inside the pipeline
- Deep learning baseline using pytorch
1. Build small feed-forward BCELoss with 20 epochs and compare to the previous models.
- Summary and reflection