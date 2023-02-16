# Decision Tree
Given a train data set, the aim is to build a Decision Tree using the ID3 algorithm in python, without using pre-existing decision tree libraries.

## What is a decision tree ?
A decision tree is a tree or flow-chart like structure, used for classification and/or prediction.
The tree consists of nodes, branches and leaves. Nodes constitute a test on an attibute, branches represent the outcome of said test and a leaf holds a label.
Simply put, given a data set with different columns (attributes) and a column as the target field, a decision tree could predict the target value based on the attributes.
"Play tennis" is an infamous data set used when teaching about decision trees where the idea is to predict whether an indicitual would play tennis on a day based on the factors: weather outlook, temprature, humidity and wind.

## Algorithm
There are a number of decision tree algorithms, namely ID3, C4.5, CART, CHAID and MARS.
This project focuses on the ID3 algorithm in which the best attribute is one with maximum information gain or minimum entropy.

## Train Data set
The train data "income.train.csv" is a modified version of the "Adult" data set.
In this version I have excluded the following attributes: age, fnlwgt, education-num, capital-gain, capital-loss and hours-per-week.
The target field is named "label" and holds two possible values: <=50K and >50k regarding the individual's annual income.

## Code
In the code the final function "id3", creates the decision tree using three inputs; the train data set and the two possible values for the taget field.
