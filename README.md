# Objective:

Using Suport Vector Machine Algorithm To Perform Classification On The Given Data-set To Predict If The Tumor Is Cancerous Or Not.

## More about the given task>>

This breast cancer database was obtained from the University of Wisconsin

Hospitals, Madison from Dr. William H. Wolberg.

```
Attribute Information: (class attribute has been moved to last column)
Sample Code Number(id number) ----> represented by column A.
Clump Thickness (1 - 10)           ----> represented by column B.
Uniformity of Cell Size(1 - 10)    ----> represented by column C.
Uniformity of Cell Shape (1 - 10)  ----> represented by column D.
Marginal Adhesion (1 - 10)         ----> represented by column E.
Single Epithelial Cell Size (1 - 10)----> represented by column F.
Bare Nuclei (1 - 10)                ----> represented by column G.
Bland Chromatin (1 - 10)            ----> represented by column H.
Normal Nucleoli (1 - 10)            ----> represented by column I.
Mitoses (1 - 10)                    ----> represented by column J.
Class: (2 for Benign and 4 for Malignant)----> represented by column K. 


A Benign tumor is not a cancerous tumor and Malignant tumor is a cancerous tumor.
```

## Tasks To Complete:

```
1. Impute the missing values with the most frequent values.

2. Check the accuracy of the model.

3. Predict whether a women has Benign tumor or Malignant tumor, if her Clump thickness is around 6, uniformity of cell size is 2, Uniformity of Cell Shape is 5, Marginal Adhesion is 3, Bland Chromatin is 9, Mitoses is 4, Bare Nuclei is 7, Normal Nuclei is 2 and Single Epithelial Cell Size is 2.

```
## Dependencies:

```
Pandas
Matplotlib
Sklearn
Numpy
Jupyter Notebook

``` 
A Quick Intro To Support Vector Machine(SVM): 

It is one of the most used and populer supervised classification machine learning algorithm, though it can be use for regression(time prediction, outlier detection, clustering).

## How SVM Works?
A support vector machine takes data points and enrolls a hyperplane (which in two dimensions it�s simply a line) that best separates the tags. This line is the decision boundary.

It acts as a discriminative classifier, it means it discrimnate  between classes.

```
Discriminative is the opposite of the Generative(We generate new data).

```

Unoptimized decision boundry could result in greater misclassification on new data. This implies that only support vector are important whereas other training examples are ignorable.

It maximize the space between that line and both of these classes.

## Advantages of SVM:

1. Effective in high dimensional space.
2. Different kernel functions for various decision functions.

## Disadvantages:

1. Poor performance when number of features is much larger than number of samples.
2. SVM directly do not provides probability estimates.
3. Probability estimate is calculated by K- fold cross validation.

## Application:

It is hugely popular and can be alternative for the neural networks. From medical imaging to building regression model to study air quilty in urban areas.

Time series prediction, fincial analysis, pattern recognition, page ranking algorithm and text recognition.







