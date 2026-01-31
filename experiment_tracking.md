## Manual Experiment Tracking Table
| Experiment ID | Model Type | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|--------------------|---------------------|------------------------|----------------------------|-------------------------|----------------------|--------------|---------------|
| EXP-01 | Decision Tree | Default | None | All features | 80/20 | 0.94 | 0.96 |
| EXP-02 | Decision Tree | Max depth = 5 | Scaling | Selected | 80/20 | 0.97 | 0.98 |
| EXP-03 | Random Forest | n_estimators=100 | Scaling + Imputation | Selected | 70/30 | 0.98 | 0.99 |
| EXP-04 | Random Forest | n_estimators=200 | Scaling + Imputation | All features | 70/30 | 0.99 | 0.99 |
