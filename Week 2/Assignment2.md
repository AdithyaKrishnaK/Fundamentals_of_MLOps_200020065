Github Repo : https://github.com/AdithyaKrishnaK/MLOps_Assignment

Sequence on commands
```
dvc init
dvc cache dir ..\external_cache\
dvc add .\data\creditcard.csv
git add 'data\creditcard.csv.dvc' 'data\.gitignore'
dvc remote add -d storage s3://lsmlops200020065/dvcstore
dvc push
git push
```
Decision Tree Model <br/>
"Accuracy": 0.9992099996488887, <br/>
"F1 Score": 0.9992309517874781

Random Forest Model <br/>
"Accuracy": 0.9995962220427653, <br/>
"F1 Score": 0.9995819032776061
