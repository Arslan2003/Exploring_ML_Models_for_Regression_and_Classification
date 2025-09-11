# Applied Machine Learning: Regression & Classification Models
*A hands-on project demonstrating regression and classification with multiple machine learning models*

**ML Models Used:**
- Regression: Linear Regression, Random Forest, XGBoost.
- Classification: K-Nearest Neighbours, Support Vector Machine, Neural Network.
> All models are implemented in Python.

<br>

## Description

This project demonstrates how to explore, implement, optimise, and evaluate different machine learning models for regression and classification tasks on real-world datasets. It is designed to provide hands-on experience for beginner-to-intermediate ML developers seeking to understand predictive modelling, data preprocessing, and model evaluation.

The project uses two datasets:

1. **Housing_Dataset_Regression.csv** – A shorter, messier version of the [California Housing Prices dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices). It includes 9 features and the target variable, *median house value*, which is to be predicted.

2. **Titanic_Dataset_Classification.csv** – A dertier version of the [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset). It includes 10 columns, with *Survived* as the target variable. This dataset is used for binary classification.

There are no restrictions on the choice of models, allowing exploration of multiple regression and classification algorithms. The project emphasises:

- Practice in data cleaning and preprocessing.
- Hands-on implementation of multiple ML algorithms.
- Understanding how these algorithms function.
- Recognition of their strengths and weaknesses.
- Comparison of model performance using relevant metrics.
- Application to two real-world inspired datasets.
- Clean, modular Python code suitable for learning and adaptation.

<br>

## Workflow

1. **Data Preprocessing** – handled missing values, encoded categorical variables, normalised numerical features, and engineered new ones.  
2. **Model Building** – trained three models (Lasso Regressor, Random Forest, XGBoost) for regression; K-Nearest Neighbours, Random Forest, and XGBoost for classification.  
3. **Hyperparameter Tuning** – optimised models using cross-validation and grid search / Bayesian optimisation methods.  
4. **Evaluation** – compared models using MAE, MSE, RMSE, and R² for regression; accuracy, precision, recall, and F1-score for classification.  
5. **Visualisation** – plotted performance metrics and feature importance for model interpretability.
>For a more detailed discussion of methodology, results, and analysis, please refer to the [full report](link-to-report.pdf).
<!--- Add the link to the report --->


## Results

### Regression

| Model           | MAE        | MSE            | RMSE       | R²    |
|-----------------|------------|----------------|------------|-------|
| Lasso Regressor | 53764.9531 | 5022930825.4830 | 70872.6381 | 0.6958 |
| Random Forest   | 52980.4200 | 5076905004.3424 | 71252.4035 | 0.6925 |
| XGBoost         | 52240.2344 | 4932249600.0000 | 70229.9765 | 0.7012 |

**Table 1.** Performance of the regression models on the original dataset.

<br>

| Model           | MAE        | MSE            | RMSE       | R²    |
|-----------------|------------|----------------|------------|-------|
| Lasso Regressor | 53764.9531 | 5022930825.4830 | 70872.6381 | 0.6958 |
| Random Forest   | 52980.4200 | 5076905004.3424 | 71252.4035 | 0.6925 |
| XGBoost         | 48990.7109 | 4534239744.0000 | 67336.7637 | 0.7254 |

**Table 2.** Performance of the regression models on the cleaned dataset.

> **Conclusion:** All three models demonstrated comparable performance, with the optimised XGBoost model achieving the lowest prediction errors.

---

### Classification


| Model           | Accuracy | F-1 Score | Precision | Recall | ROC AUC |
|-----------------|----------|-----------|-----------|--------|---------|
| KNN             | 0.8071   | 0.7158    | 0.7556    | 0.68   | 0.7789  |
| SVM             | 0.7929   | 0.7010    | 0.7234    | 0.68   | 0.7678  |
| Neural Network  | 0.8214   | 0.7312    | 0.7907    | 0.68   | 0.7900  |

**Table 3.** Performance of the basic models on the “Titanic” dataset.

<br>

| Model           | Accuracy | F-1 Score | Precision | Recall | ROC AUC |
|-----------------|----------|-----------|-----------|--------|---------|
| KNN             | 0.8214   | 0.7423    | 0.7659    | 0.72   | 0.7989  |
| SVM             | 0.7929   | 0.7010    | 0.7234    | 0.68   | 0.7678  |
| Neural Network  | 0.8429   | 0.7556    | 0.8500    | 0.68   | 0.8067  |

**Table 4.** Performance of the fine-tuned models on the “Titanic” dataset.

> **Conclusion:** The Neural Network consistently outperformed the other models across all evaluation metrics, and the fine-tuned version further improved predictive performance.




 

