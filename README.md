# Wine Type Prediction (Multi-class Classification)
This data set is taken from the UCI repository (link [here](https://archive.ics.uci.edu/ml/datasets/wine)). I have done some basic pre-processing of the data in Excel, like adding headers based on the dataset description and converting the dataset to the CSV format. As usual, I've ingested this data from my personal Drive, and this repository has the pre-processed dataset (in CSV format).

## Dataset Information:

**Winelab.csv**: To quote the UCI dataset description:


>*These data are the results of a chemical analysis of
      wines grown in the same region in Italy but derived from three
      different cultivars.
      The analysis determined the quantities of 13 constituents
      found in each of the three types of wines.*
      
Basically, there are 3 different types of wines and their attributes are their chemical compositions (Alcohol, Malic Acid, Ash etc.). Fortunately, this is a dataset with continuous quantitative features only. 

## Goals:
1. Perform feature selection (and engineering) using Principal Component Analysis.
2. Develop a classification model that generalizes well.
3. Compare with other classifiers

## Results:
This is a dataset where the best solution is the simplest. K-Nearest Neighbours outperformed Logistic Regression and Linear SVC. The F1 micro score for KNN was an excellent 0.95.
