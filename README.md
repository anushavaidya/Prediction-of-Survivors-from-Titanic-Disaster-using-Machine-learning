# Titanic-Machine-learning-from-Disaster 

This project is from one of the competition on Kaggle which explores the use of Machine Learing algorithms inorder to estimate the survivors of the Titanic Disaster. 

## Dataset 

The given dataset is in form of a csv file and it contains the following categories:

| Variable   |      Definition      |    Key     |
|------------|:--------------------:|----------:|
| survival |  Survival |  0 = No, 1 = Yes        |
| name     | Name of the passenger |              |
|  pclass |    Ticket class  |  1 = 1st, 2 = 2nd, 3 = 3rd   |
| sex |  Male of Female |     |
| age | Age in years |     |
| sibsp |# of siblings / spouses aboard the Titanic  |     |
| parch | # of parents / children aboard the Titanic |     |
| ticket  | Ticket number |     |
| fare | Passenger fare |     |
| cabin | Cabin number |     |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton    |


### Variable Notes:
* `pclass`: A proxy for socio-economic status (SES) \
1st = Upper \
2nd = Middle \
3rd = Lower 

* `age`: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

* `sibsp`: The dataset defines family relations in this way...\
Sibling = brother, sister, stepbrother, stepsister \
Spouse = husband, wife (mistresses and fiancés were ignored)

* `parch`: The dataset defines family relations in this way... \
Parent = mother, father \
Child = daughter, son, stepdaughter, stepson \
Some children travelled only with a nanny, therefore parch=0 for them.

## What you will need to run:
* Python 
* Jupyter Notebook
* Pandas
* Sklearn 
* Matplotlib

## How to run:
Open the `main.ipynb` file in a jupyter notebook and run all the cells 
