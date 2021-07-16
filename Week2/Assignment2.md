Assingment Repo link: https://github.com/devpratap11/MLOps_Assignment.git

Commands for part1:

git clone https://github.com/devpratap11/MLOps_Assignment.git
dvc init

mkdir data
dvc add data/creditcard.csv
git add data/creditcard.csv.dvc data/.gitignore
git commit -m "Data added"
dvc cache dir /home/dev/external_cache
dvc remote add -d storage s3://ass2dev/dvcstore
git add .dvc/config
git commit -m "Configure remote storage"
dvc push

----------------------------------------------------------------------
