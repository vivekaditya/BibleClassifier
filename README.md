# Bible Classification Task

## Introduction
Bible is divided into Old Testament and New Testament, where books belong to either of sets. Mapping can be found in (bible_map.txt)

## Objectives 
The objective here are 3-fold:
1) Build a Classification model to classify text into Old Testament or New Testament, using text column. Use seed = 45 and 70:30 ratio for dividing into training and testing dataset
2) Calculate Cosine distance between "light" and "dark"
3) Add another column to dataframe which contains nouns appearing in corresponding text row.
 

## Setup and Requirements
This project is heavly based on IPython notebook. requirements.txt has the required libraries. The HTML versions of the notebooks are present in the **html** folder. There is also a requirements.tt file.

## Contents
EDA - Do a simple exploratory data analysis.
SkipThough and TfIdf vectorizer based classifiers - Embed the text information into a vector space and Classify based on KNN classifier.
data - Folder contains both the initial tsv and the one with a new column **noun** added. 

## Algorithm/Features/Evaluation Metric
Approach was to do a KNN search and predict the testment. The evaluation metric used in this classification problem is f1 score. Also the confusion matrix is provided along with precision and recall.

## Potential improvements
Improvement can be made in the vector space representation. We can also use the nouns column created in the df. Alse a different model, other than KNN like logistic/SVM couldbe tried.
