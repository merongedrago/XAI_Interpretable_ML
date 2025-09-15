# XAI_Interpretable_ML

[![Open Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/merongedrago/XAI_Interpretable_ML/blob/main/Interpretable_ML.ipynb)  

The jupyter notebook explores the factors that contribute to customer churn (customers leaving the company for a competitor). The following are the main tasks that are implemented in the jupyter notebook: 

1. Exploratory Data Analysis to check Assumptions
2. Linear Regression
3. Logistic Regression
4. Generalized Additive Model (GAM)
5. Model Comparison

If unable to access the csv file as it is local. 
1. An option is to clone this repository locally and run the jupyter notebook to observe the results.
2. Replace the snippet of code importing the dataset with the following as to be able to download the data from Kaggle

```path = kagglehub.dataset_download("blastchar/telco-customer-churn")
data = pd.read_csv(path +'/WA_Fn-UseC_-Telco-Customer-Churn.csv') 
data.head()

