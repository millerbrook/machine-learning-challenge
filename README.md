# machine-learning-challenge

In this homework I tried logistic regression, random forest, k nearest neighbors, support vector machines, and neural network.

---
### Logistic Regression

For Logistic Regression, the initial test report was:

Training Data Score: 0.9922071392659628
Testing Data Score: 0.9894419306184012

After using GridSearchCV, the accuracy report was:
0.8559552479378022

---

### Random Forest  

The RF score was:
0.9864253393665159

After using GridSearchCV, the accuracy report was:
0.9856704908188743

---
### Support Vector Machine (SVM)
For SVM, the initial test report was:

Test Acc: 0.992

After using GridSearchCV to hypertune the parameters, SVM returned the following values:

0.990447204576341

---
### K Nearest Neighbors

For KNN, the initial test report was:

ideal K was 3,  
Test Acc: 0.990  


After using GridSearchCV, the accuracy report was: 

0.9904475206219778
with K value of 5

This difference between K values seemed surprising.

The KNN score was the highest gridsearchcv score reported, with SVM close behind.

---

### Neural Network

I ran a neural network that had strong accuracy. However, I ran into problems with running a Keras estimator in GridSearchCV, and my current attempt doesn't work. Feedback on how to fix the problems in this would be greatly appreciated.

---

### Overall Request for Feedback

I don't feel that I have a great understanding of the hypertuning process. Specifically, I am confused about why the scores were lower after running gridsearchcv than the initial model. Is this typical? Indicative of poor grid parameter choices? Any guidance would be helpful.