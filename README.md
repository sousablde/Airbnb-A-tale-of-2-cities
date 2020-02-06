# Data Science Nanodegree
## Write a Data Science Blog Post
### Airbnb: a tale of 2 cities


### Table of Contents

1. [Installation](#installation)
2. [Introduction](#introduction)
3. [Project Motivation](#motivation)
4. [Files](#files)
5. [Instructions](#instructions)
6. [Results](#results)
7. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>
Besides the libraries included in the Anaconda distribution for Python 3.6 the following libraries have been included in this project:
* `LGBM` -  gradient boosting framework that uses tree based learning algorithms.
* `XGBoost` - optimized distributed gradient boosting library designed to be highly efficient, flexible and portable.
* `skopt` - simple and efficient library to minimize (very) expensive and noisy black-box functions.


## Introduction <a name="introduction"></a>
This project involved the exploration of data made public on regarding airbnb listings.
Airbnb was originaly conceptualized as a way to make extra income out of taking advantage of the time that you are away from home as rental time to third parties.
The business model has been surrounded by controversies on how it can change the panorama of available dwelling in large urban centers and word of mouth had postulated the Portugal was one of the worst examples. In the portuguese case the implemented laws forced individual hosts to surrender many of their properties to major property management companies.
Unfortunately the datasets lack information on actual listing ownership so my exploration will adapt to what is available.


## Project Motivation <a name="motivation"></a>
Porto and Lisbon are incredible cities with a booming tech scene, making them great candidates as a future base.
Airbnb helps have a great understanding of how the real estate rental market looks like.


## Files <a name="files"></a>
Data was downloaded from http://insideairbnb.com/. Data is made available through website scraping.


Downloaded files for both cities are:
listings.csv : contains over 106 features regarding physical features of the listing, host characteristics and guest requirements
calendar.csv : contains one year worth od data regarding the price and availability of all the existing listings
reviews.csv : written reviews for each listing

Notebooks
Airbnb - a tale of 2 cities.ipynb: File where EDA is conducted
Data Modeling.ipynb - starter code for regression and gradient boosted models
Feature Selection.ipynb - starter code for feature selection


## Results <a name="results"></a>
The greatest discovery was how much of Airbnb is out of the hands of individuals and are fully business run.
The vast majority of the listings are available year round.
Porto holds the greatest proportion of superhosts when compared with Lisbon.
The top priced neighbourhoods were easily identified.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
I am greatly thankful for the incredible challenge provided by Udacity.