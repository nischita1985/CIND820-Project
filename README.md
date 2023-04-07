# CIND820-Project
# Comparing Machine Learning Techniques for Predicting COVID-19 Patient Mortality and Identifying Top 5 High-Risk Medical Conditions
### Dataset
The Covid-19 Dataset has been downloaded from Kaggle.com ( Nizri, 2022). This dataset was provided by the Mexican government(Información referente a Casos covid-19 en México - datos.gob.mx/busca).
### Description
The project is aimed in identifying top 5 high risk medical condition which is 
later associated with mortality of Covid Positive patient by using different Feature Selection method and to compare the efficiency of different 
machine learning models like Decision Tree, Naive Bayes, Logistic regression and Random forest to predict the 
death of patient due to high-risk medical condition. Similarly different 
Data Preprocessing steps are also compared in this project which will provide the insights of data cleaning
process and their resultant performance and will be helpful for future researcher. 
### Methodology
###### Data-Preprocessing: 
In this steps, missing values are removed and imputed and compared. Categorical variable were changed to numercial by one hot encoding and label encoding method.
Since the dataset was highly imbalanced Random under sampling methods were applied to balance the dataset. Outliers from the numerical variables were removed and compared 
without removing outliers.
###### Feature Engineering:
Different Feature Selection Methods were applied to get the top 5 features which are as follows:
* Wrapper Method: From wrapper method Forward Selection Method was applied
* Filtration Method: Chi-Square Test was used
* Embeded Method: Lasso Regression was used
###### Model Evaluation Techniques:
Machine Learning Models used in this project is: Decision Tree, Naive Bayes, Logistic Regression and Random Forest
Evaluation Techniques used in this project for the Performance of the Models were Accuracy, Briers Score, Matthews Correlation Coefficient and K-Fold Cross Validation
### Links For Github Repository
These are the links for CIND820-Project Repository:
* https://github.com/nischita1985/CIND820-Project/blob/main/BalancedImbalanced.ipynb
* https://github.com/nischita1985/CIND820-Project/blob/main/CrossValidation.ipynb
* https://github.com/nischita1985/CIND820-Project/blob/main/DataDescPandaProfiling.txt
* https://github.com/nischita1985/CIND820-Project/blob/main/DataPrepMissingValues.ipynb
* https://github.com/nischita1985/CIND820-Project/blob/main/FeatureSelection.ipynb
* https://github.com/nischita1985/CIND820-Project/blob/main/OutliersDelOutliers.ipynb
* https://github.com/nischita1985/CIND820-Project/blob/main/UnderOverSampling.ipynb
### Contents of My Github Repository
CIND820 Project has all the source codes which was executed in Python Enviroonment.
Comparisons were done for different models based on their performance bewteen:
* Imputing Missing Values/ Deleting Missing Values
* Balanced Dataset/ Imbalanced Dataset
* Under Sampling Technique/ Over Sampling Technique (SMOTE)
* Removing Outliers / Keeping Outliers
* Forward Selection / chi-Square Test / Lasso Regression
## References
* Nizri, M. (2022, November 13). Covid-19 dataset. Kaggle. Retrieved January 22, 2023, from https://www.kaggle.com/datasets/meirnizri/covid19-dataset 
* Información referente a Casos covid-19 en México - datos.gob.mx/busca. de México - Información referente a casos COVID-19 en México. (n.d.). Retrieved January 22, 2023, from https://www.datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico

