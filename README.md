# Data_Pipeline

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: THENTRAL S

*INTERN ID*: CT08WN69

*DOMAIN*: DATA SCIENCE

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

## This is the data pipline project where i started with a bank dataset

About Dataset:

which contains details or atrritibute like (occupation, education, age, etc) to determine a person subscribe to the a term deposit (yes/no), this paticular dataset that i worked with is `Bank Marketing Dataset` this contains information of digital marketing campaigns for selling term deposit products, this dataset contains record around 41,000 rows and 17+input variable and 1 target variable

### About Environment:

 In this project I ued jupyter notebook to do the ETL(Extract,Transform and Load) process and the analysis part
 
### Application of the project:

This project helps to predict a person will purchase a term deposit product based on their attribute like job, age and so on

### Process Involved:

**step 1:** Reading the datset using Pandas read function 

**step 2:** Next data cleaning,checking for null values, eliminating the unnecessary features and seperating the numerical features and categorical features.

**step 3:** Encoding the feature 

for numerical columns SimpleImputer and StandardScalar is used ,In SimpleImputer the missing value  is replaced with the mean value

for categorical columns SimpleImputer is used to fill the missing value using the strategy most frequent and OneHotEncoder (this is a technique which is used to convert categorical variable into a format that cab]n be provideed to machine learning algorithms)

**step 4:** Data Pipeline creation


 in this step we create a model pipeline

   **Pipeline** : is a sequence of ETL process step used to automate and streamline the flow of data from raw input to final output


   using the package `ImPipeline` from Pipeline package which include preproccessing ,then smote this is used to handle the unbalanced data usind BorderlineSMOTE and using the classifier model XGBClassifier

**step 5:** Spiltind the dataset as train and test data, X is independent variable and Y is dependent variable

**step 6:** Finding the performance evaluation metric , `Classification metrics` this provides precision, recall, f1-score, support for a classification problem
