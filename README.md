# Titanic---Machine-Learning-from-Disaster
## Introduction
The Titanic Machine Learning Competition is a challenge that asks participants to create a model that predicts which passengers survived the Titanic shipwreck based on various passenger information, such as name, age, gender, socio-economic class, etc. 
## Objective
The objective of this competition is to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data. Participants are provided with two datasets: train.csv and test.csv. The train.csv dataset contains details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”. The test.csv dataset contains similar information but does not disclose the “ground truth” for each passenger. Participants must use the patterns found in the train.csv data to predict whether the other 418 passengers on board (found in test.csv) survived.
## Dataset
The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The train.csv file contains the following variables:

- PassengerId: unique identifier for each passenger
- Survived: whether the passenger survived (0 = No, 1 = Yes)
- Pclass: socio-economic status (SES) of the passenger (1st = Upper, 2nd = Middle, 3rd = Lower)
- Name: passenger name
- Sex: passenger gender
- Age: passenger age
- SibSp: number of siblings/spouses aboard the Titanic
- Parch: number of parents/children aboard the Titanic
- Ticket: ticket number
- Fare: passenger fare
- Cabin: cabin number
- Embarked: port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

The test.csv file contains the same variables, except for the Survived variable, which is the target variable to be predicted.

## Evaluation Metric
The evaluation metric for this competition is accuracy, which is the percentage of passengers correctly predicted by the model.
