## 📅 Week-4

## Linear Regression
### Logistic Regression

In a Logistic regression, we might try to predict a continuous value of variables such as the price of a house, blood pressure of a patient, or fuel consumption of a car.

But in logistic regression, we predict a variable which is binary such as yes/no, true/false,  successful or not successful, pregnant/not pregnant, and so on, all of which can be coded as zero or one. 

In logistic regression independent variables should be continuous. If categorical, they should be dummy or indicator coded. This means we have to transform them to some continuous value.

Logistic Regression Application

- To predict the probability of a person having a heart attack within a specified time period,
- To predict the chance of mortality in an injured patient  
- To predict the likelihood of a customer purchasing a product or halting a subscription. 
- To predict the probability of failure of a given process, system or product. 
- To predict the likelihood of a homeowner defaulting on a mortgage.

### Lab: Logistic Regression
In this notebook, you will learn Logistic Regression, and then, you'll create a model with
telecommunications data to predict when its customers will leave for a competitor, so that you can take some action to retain the customer.

## Support Vector Machine

Support Vector Machine is a supervised algorithm that can classify cases by finding a separator. SVM works by first mapping data to a high dimensional feature space so that data points can be categorized, 
even when the data are not otherwise linearly separable.

### Lab: SVM (Support Vector Machines)

In this notebook, you will use SVM (Support Vector Machines) to build and train a model using human cell records, 
and classify cells to whether the samples are benign or malignant.

## Multiclass Prediction

In Multi-class classification, we classify data into multiple class labels. Unlike classification trees and nearest neighbors, the concept of Multi-class classification for linear classifiers is not as straightforward. We can convert logistic regression to Multi-class classification using multinomial logistic regression or SoftMax regression; this is a generalization of logistic regression. SoftMax regression will not work for Support Vector Machines (SVM); One vs. All (One-vs-Rest) and One vs One are two other 
multi-class classification techniques that Lab: Multiclass Predictioncan convert most two-class classifiers to a multi-class classifier.

### Lab: Multiclass Prediction

In this notebook, you will learn how to convert a linear classifier into a multclass classifier. 
## End of Module Review & Evaluation
