---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Machine Learning | Python
---

<h1 align="center"> Machine Learning With Python</h1>

<p align="center"><img src="https://tecnico.ulisboa.pt/files/2017/06/priberam-machine-learning-lunch-seminar-joao-xavier-1140x641.jpg"></p>

<h2> Table of Contents </h2>

- [Materials](#materials)
- [Machine Learning Introduction](#machine-learning-introduction)
  - [Important Definitions in Machine Learning](#important-definitions-in-machine-learning)
  - [Machine Learning Applications](#machine-learning-applications)
  - [Machine Learning Prerequisites](#machine-learning-prerequisites)
  - [Machine Learning Overview](#machine-learning-overview)
- [Machine Learning : Regression](#machine-learning--regression)
  - [Linear Regression](#linear-regression)

## Materials
- Pattern recognition and machine learning [Book](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf).


## Machine Learning Introduction

### Important Definitions in Machine Learning

- What is Artificial intelligence?
  - Artificial intelligence (AI) is the ability of a computer or a robot controlled by a computer to do tasks that are usually done by humans.
- What is Machine Learning?
  - Machine learning is a subfield of artificial intelligence, which is broadly defined as the capability of a machine to imitate intelligent human behavior.
- What is Big data?
  - big data is larger, more complex data sets, especially from new data sources.
- What is Data Science?
  -  preparing data for analysis, including cleaning, aggregating, and manipulating the data to perform advanced data analysis. After data analytics we could predict or draw insights from data.

<center><img width="300" src="https://www.researchgate.net/publication/330948278/figure/fig1/AS:723867312062471@1549594824742/The-field-of-data-science-including-statistics-big-data-and-artificial-intelligence-8.ppm"/></center>


### Machine Learning Applications

- Facial Recognition
- Recommendation Engines
- Optical Character Recognition
- Advertising and business intellgince
- Filtering News Feed
- Self Driving "Autonomous" Vehicles
- Fraud Detection

### Machine Learning Prerequisites

- Mathematical Knowledge: Linear Algebra, Probability and Statistics, Multivariant Calculas
- Programming with Python


### Machine Learning Overview


1. ML Introduction
2. Supervised Machine Learning
   1. Regression
   2. Classisfication
   3. Neural Networks
   4. Support vector Machine
3. Unsupervised Machine Learning

--- 


## Machine Learning : Regression

Supervised Learning develop predictive model based on both input and output data.

Unsupervised learning group and interpret data based on input data only.


### Linear Regression

- **Important Equations:**
  - Slope: `(y2-y1)/(x2-x1)`, slope can be zero, +ve, or -ve.
  - Linear Regression: `Y'= aX + b`
    - `a` is the slope, and `b` is the y-intercept when X = 0
  - Hypothesis function: `h(x) = theta_0 + theta_1*X`

![Linear Regression Rules](../assets/MLPython/LinearRegressionRules.png)

![Gradient Descent](../assets/MLPython/GradientDescent.png)

![Gradient Descent Detailed](../assets/MLPython/GradientDescentDetailed.png)


- **Important Definitions:**
  - X = inputs
  - Y = output
  - m = number of rows
  - n = numbe of features
  - h(x) = predectied values
  - cost J = error value
  - Theta = X parameters


- Big Learning Rate vs. Small Learning Rate (Alpha)
  - choosing the learning rate wether being small or large will compensate between accuracy and speed of the algorithm.

- Linear Regression for Multiple Features (With Multivariables)
  - Multivariant Linear Regression equation

  ![multivariant Linear Regression](../assets/MLPython/multivariantLinearRegression.png)


  - Multivariant Gradient For linear regression equation

    ![multivariant Gradient Descent](../assets/MLPython/multivariantGradientDescent.png)
