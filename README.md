# Hack-IT-Submission
OCBC Hack-IT Project - US Traffic 2015

# Executive Summary

Traffic congestion is a problem in many cities around the world, it is especially bad in Los Angeles, ranked worst traffic in the world in a study (https://www.usatoday.com/story/money/2017/02/20/los-angeles-new-york-and-san-francisco-most-congested-us-cities/98133702/)

In this notebook, we seek to identify common traffic trends portrayed in the US Traffic 2015 dataset. With the common trends identified, we seek to create a predictive model that can predict for the total volume of traffic for a station in Los Angeles.

Predicting traffic information is an important task for various stakeholders from policy makers to ride sharing apps. The models created in this project serves as a preliminary approach to modelling road traffic volume.

To approach this dataset, we first identified potential features that can explain variations in traffic data. With these features, we conducted a bivariate analysis with traffic volumes to test the hypothesis. From the dataset, we observed 5 trends:

1) Weekend

2) Month

3) Holiday

4) Functional Classification

5) Road capacity

With the features identified, we created a predictive model using sklearn's Random Forest Regression, Ridge Regression and Support Vector Machine algorithms. We find the optimal model by gridsearching across suitable hyperparamters.

# Problem Statement

Identify patterns in the US 2015 Traffic dataset. Use machine learning tools to create a predictive model for traffic volume in Los Angeles.
