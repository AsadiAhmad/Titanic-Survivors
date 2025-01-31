# Titanic-Survivors
Predicting Survivors in the Titanic ship

## About the Dataset
the dataset is for kaggle so you can visit the problem and the related page with clicking [![Static Badge](https://img.shields.io/badge/Kaggle-blue?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://www.kaggle.com/competitions/titanic/data)

### Download Dataset
you can use this Dataset with clicking this badges :

Train set : [![Static Badge](https://img.shields.io/badge/Trainset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/Titanic-Survivors/blob/main/Dataset/train.csv)

Test Set : [![Static Badge](https://img.shields.io/badge/Testset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/Titanic-Survivors/blob/main/Dataset/test.csv)

### Using Dataset on jupyter notebook
on the step 3 of the code file you can easily use the dataset like importing this code:
```sh
train_set_url = "https://raw.githubusercontent.com/AsadiAhmad/Loan-Prediction-SVM/refs/heads/main/Dataset/train.csv"
test_set_url = "https://raw.githubusercontent.com/AsadiAhmad/Loan-Prediction-SVM/refs/heads/main/Dataset/test.csv"

pd.set_option('display.max_rows', None)

train_set = pd.read_csv(train_set_url)
test_set = pd.read_csv(test_set_url)
```

### Dataset Structure

| Column | Description | Type |
| ----------- | ----------- | ----------- |
| Id | Unique Loan ID | Int |
| Income | The income person have | Int |
| Age | Age of person | Int |
| Experience | No. of years of experience | Int |
| Married/Single | Married/Single state : single/married | String |
| House_Ownership | House ownership : owned/rented/norent_noown | String |
| Car_Ownership | Car ownership : yes/no | String |
| Profession | The profession person have | String |
| CITY | The city person live | String |
| STATE | The state person live | String |
| CURRENT_JOB_YRS | How many years the person have the job | Int |
| CURRENT_HOUSE_YRS | How many years the person have the house | Int |
| Risk_Flag | Loan State: 0/1 | Int |
