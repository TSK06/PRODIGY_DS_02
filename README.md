Introduction : This is my submission for task 02 of the Data Science internship at Prodigy Infotech

Data Descripiton :
We used the titanic dataset from kaggle to perform Exploratory Data Analysis(EDA)
Data Dictionary:
## Variable Definitions

The table below provides definitions and keys for the variables used in the dataset:

| Variable | Definition                                | Key                                    |
|----------|-------------------------------------------|----------------------------------------|
| survival | Survival                                  | 0 = No, 1 = Yes                        |
| pclass   | Ticket class                              | 1 = 1st, 2 = 2nd, 3 = 3rd             |
| sex      | Sex                                       |                                        |
| Age      | Age in years                              |                                        |
| sibsp    | Number of siblings / spouses aboard the Titanic |                                |
| parch    | Number of parents / children aboard the Titanic |                                |
| ticket   | Ticket number                             |                                        |
| fare     | Passenger fare                            |                                        |
| cabin    | Cabin number                              |                                        |
| embarked | Port of Embarkation                       | C = Cherbourg, Q = Queenstown, S = Southampton |


pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.
