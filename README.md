# Exploring ML Models for Regression and Classification
*A hands-on project demonstrating regression and classification with multiple machine learning models*

**ML Models Used:**
- Regression: Linear Regression, Random Forest, XGBoost.
- Classification: K-Nearest Neighbours, Support Vector Machine, Neural Network.
> All models are implemented in Python.

<br>

## 📝 Description

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

## 🔄 Workflow

1. **Data Preprocessing** – handled missing values, encoded categorical variables, normalised numerical features, and engineered new ones.  
2. **Model Building** – trained three models (Lasso Regressor, Random Forest, XGBoost) for regression; K-Nearest Neighbours, Random Forest, and XGBoost for classification.  
3. **Hyperparameter Tuning** – optimised models using cross-validation and grid search / Bayesian optimisation methods.  
4. **Evaluation** – compared models using MAE, MSE, RMSE, and R² for regression; accuracy, precision, recall, and F1-score for classification.  
5. **Visualisation** – plotted performance metrics and feature importance for model interpretability.
>For a more detailed discussion of methodology, results, and analysis, please refer to the [full report](Report.pdf).
<!--- Add the link to the report --->

<br>


## 📊 Results

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

<br>

> **Conclusion:** All three models demonstrated comparable performance, with the optimised XGBoost model achieving the lowest prediction errors.

<br>

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

<br>

> **Conclusion:** The Neural Network consistently outperformed the other models across all evaluation metrics, and the fine-tuned version further improved predictive performance.

<br>

## ⚙️ Installation & Usage

This project can be explored in **three ways**: using the Jupyter Notebook (`.ipynb`), running the Python script (`.py`), or experimenting directly in [Google Colab](https://colab.research.google.com/).

<br>

### Option 1: Run in Google Colab (Recommended):
1. Click [here](https://colab.research.google.com/drive/1T9uq_4XXVTDHvQrX08aMO9Bj2Muvis2n?usp=sharing#copy=true). 
2. Colab will open the notebook and prompt you to save a copy to your own Google Drive.
3. You can now edit, run, and experiment in your own copy of this project.

<br>

### **Option 2: Run the Notebook Locally**

1. Clone the repository:
   ```bash
   git clone https://github.com/Arslan2003/Exploring_ML_Models_for_Regression_and_Classification.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Exploring_ML_Models_for_Regression_and_Classification
   ```
3. Install the required packages using ```requirements.txt```
   ```bash
   pip install -r requirements.txt
   ```
4. Open the ```Exploring_ML_Models_for_Regression_and_Classification.ipynb``` using your Jupyter Notebook or Jupyter Lab

<br>

### Option 3: Run the Python Script Locally:
1. Clone the repository and install the requirements as above.
2. Open the ```Exploring_ML_Models_for_Regression_and_Classification.py``` in your preferred Python IDE (e.g., VSCode, PyCharm).
3. Run the script:
   ```bash
   python Exploring_ML_Models_for_Regression_and_Classification.py
   ```
<br>

After getting access to the notebook, play around with the code!

<br>

## 🤝 Contributing
This project is designed for beginner to intermediate users who want to explore and experiment with machine learning. Feel free to try out different data preprocessing steps, test various models and hyperparameters, explore evaluation metrics, and most importantly - have fun learning!

<br>

For more advanced users, contributions such as fixing bugs, adding new models, improving documentation, or suggesting new features are very welcome. If you want to contribute formally:
- Fork the repository first.
- Create a new branch for your feature or fix.
- Ensure your code is well-documented and follows Python best practices.
- Submit a pull request describing your changes clearly.

<br>

## ✍️ Authors
- Arslan Ishanov – project development, model implementation, optimisation, evaluation, and documentation.
- University of Greenwich – for kindly providing the modified datasets and inspiring the development of this project.

<br>

## ⚖️ License

This project is licensed under the **MIT License**.  
- You are free to use, modify, and distribute this code, provided that you include the original copyright and license notice.  
- The software is provided "as-is," without any warranty.  

See the [LICENSE](LICENSE) file for full details.



 

