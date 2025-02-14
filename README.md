## Age Prediction by applying Ridge Regression and SVM on Multimodal Neuroimaging Data


### Overview
In this notebook we:
- implement and compare performance of models trained on different sets of brain features extracted from multimodal imaging data
- algorithms used include support vector machine and ridge regression
- specifically, we perform feature ablation to evaluate the predictive power of 7 sets of neuroimaging features by iteratively excluding them one at the time
- use Mean Absolute Error (MAE) a metric for performance evaluation
- visualize scatterplots of chronological age vs predicted age and illustrate the regression line

##### Dependencies
```
pip install seaborn==0.13.2 pandas==2.2.1 numpy==1.26.4 matplotlib==3.8.3 scipy==1.11.4 scikit-learn==1.2.2
```
