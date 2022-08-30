
# Statistical Modeling of Solar Flares

    1. Project Motivation
    2. Objectives
    3. Methods Used
    4. Installation
    5. Data
    6. Implementation
    7. Result

## 1. Project Motivation

Solar Flare is an intense localized erruption of radiation in the Sun's atmosphere which is seldom accompained by ejection of particles with high energy travelling at almost the speed of 2000 Km/s. These flares can last a few seconds to several hours.
It is important to model the duration of such events to better understand the long term impacts on our planet.


## 2. Objectives

*   Obtain the dataset and prepare the data for Statistical Modeling
*   Fit Exponential Distribution to the random sample  
*   Fit Lognormal Distribution to the random sample
*   Find MSE to determine the best fit

## 3. Methods Used

* Feature Engineering
* Inferential Statistics
* Data Visualization

## 4. Installation

* Python versions 3.*.
* Python Libraries:
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn
    * Scipy
    * Sklearn

## 5. Data

The data deposited here are the input data used for machine learning efforts by the University of Michigan for predicting solar flare intensities. The input data are produced by their pre-processing pipeline, which is built to extract useful data from multiple sources -- ***Geostationary Operational Environmental Satellites (GOES) and Solar Dynamics Observatory (SDO)/Helioseismic and Magnetic Imager (HMI).***
These input data files are ***SolarFlare.csv*** which is attached above. The GOES files provide a list of **1092 flare events** *(from 01/04/2017 to 06/20/2018)* while the SHARP files provide time sequences of physical parameters derived from 860 HMI Active Region Patches (HARPS) from which the flares originated.   
The unprocessed ***GOES*** data are available from *NOAA Space Weather Prediction Centre(SWPC)*.
*The csv file containing the data is attached separately.*

## 6. Implementation

In this project we have used *exponential distribution* and *lognormal distribution*. I have selected about 500 random samples from the feature engineered to fit our distribution models. MSE have been calculated to find the best fitting model to our dataset. 

## 7. Result

The details of the results are shown in the code.
