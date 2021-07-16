# Assingment Repo link 
https://github.com/devpratap11/MLOps_Assignment.git

# Commands used for Part1:

* git clone https://github.com/devpratap11/MLOps_Assignment.git
* dvc init
* mkdir data
* dvc add data/creditcard.csv
* git add data/creditcard.csv.dvc data/.gitignore
* git commit -m "Data added"
* dvc cache dir /home/dev/external_cache
* dvc remote add -d storage s3://ass2dev/datastore
* git add .dvc/config
* git commit -m "Configure remote storage"
* dvc push
* git push origin
----------------------------------------------------------------------
# Part2:
I first trained a Decision Tree model and then a Random Forest Classifier model.
## Expt1-Decision Tree Classfier:
accuracy score = 0.9983429211954701  
f1 score = 0.8876357755960527
## Expt2-Random Forest Classfier:
accuracy score = 0.9995611109160493  
f1 score = 0.9276357755960527

![AWS Bucket screenshot](https://github.com/devpratap11/Fundamentals_of_MLOps_19D070020/blob/main/Week2/screenshot.png "AWS Bucket screenshot")
