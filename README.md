# Differentiating-people-with-parkinson-s-disease-from-normal-people
Parkinson's disease is a progressive nervous system disorder that affects movement. it leads to shaking, stiffness, and difficulty with walking, balance, and coordination.The condition becomes worse and doesn't have a cure. Medications can only improve the condition but never cure the disease from the root.It often start with a slight tremor in one hand and a feeling of stiffness in the body. Over time, other symptoms develop, and some people will also have dementia. Most of the symptoms result from a fall in dopamine levels in the brain. We can only measure the level of the disease. By using the biomedical voice measurements of people with Parkisnson's disease, we can differentiate people with parkisnson's from normal people. Also, measure the level on the disease. 

## Dataset used:
I have used the Oxford Parkinson's Disease Detection Dataset available on kaggle. The dataset was created by Max Little of the University of Oxford.This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD.
 
## Tools used:

### Python:
It is a widely used user friendly, high level programming language. Along with code readability, it makes programming easy by its compactness. It has by far the easiest syntax and it is majorly used in machine learning and data science practices.

### XGboost: 
XGBoost is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. In this project, this model is used and passed to a cross validation function.

### Numpy: 
NumPy is a python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. It is an open source project. NumPy stands for Numerical Python. It was used to divide dataset into features and targets in this program.

### Pandas: 
Pandas is a high-level data manipulation tool developed by Wes McKinney. It is built on the Numpy package and its key data structure is called the DataFrame. DataFrames allow you to store and manipulate tabular data in rows of observations and columns of variables. In this program it was used to feed data.

### Matplotlib: 
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Here it was used to plot various graphs. 

### Seaborn: 
Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. Here it was used to plot heatmap.

## Conclusion:

After training the Xgboost model we were able to differentiate people with parkinson's disease from normal people using the dataset containing a range of biomedical voice measurements.

