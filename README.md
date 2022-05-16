## Overview

TBM is widely used in the construction of various types of hard rock tunnels. The working performance of cutterhead, which is the key tunneling component of TBM, directly affects the efficiency and safety of construction. Due to the complex geology, such as crumbly strata, super hard rock and jointed rock, cutterhead bears large thrust, strong torque and impact cutter loads. Additionally the brittle rock-breaking mechanism and the inappropriate operating parameters may also result in severe vibration of cutterheads of TBM, which would lead to serious strength failure. Therefore, switching cutterheads in TBM is necessary for various rocks during tunneling.

This project provides different rock density based on varous ML algorithms using X-ray data

### The Data

A tunnel boring company which uses X-rays in an attempt wants to know rock density, ideally this will allow them to switch out cutterheads on their equipment before having to mine through the rock!

They have some lab test results of signal strength returned in nHz to their sensors for various rock density types tested. It has almost a sine wave like relationship, where signal strength oscillates based off the density.

## Python libraries
-   Numpy
-   Pandas
-   Matplotlib
-   Seaborn
-   Scikit-Learn

In this project, regression analysis is done by using:
+ Linear Regression
+ Polynomial Regression
+ KNN Regression
+ Support Vector Machine Regression
+ Decision Tree Regression
+ Random Forest Regression

Every models are evaluated based on Root Mean Squared Error. After visualizing these models, we can judge which one is good for our data and which algorithm is making the model overfitting.
