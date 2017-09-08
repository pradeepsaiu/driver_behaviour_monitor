# Project: Analyzing Bus driver behaviour using Mobile

## Description
Google Nexus4 phones are placed inside campus shuttles, and an app is developed to collect sensor data from the phones.
* We try to monitor the driving behaviour of the user based on the information recieved from the sensors.
* We can also predict the traffic based on the speed and number of stops driver makes.

## Install

This project requires Python >= 2.7 and the following Python libraries installed:

* NumPy
* Pandas
* matplotlib
* scikit-learn
* gmaps ( need to use your own config file with google api key + update ipywidgets before installing gmaps)

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda distribution of Python](https://www.anaconda.com/download/) , 
which already has the above packages and more included.


# Data

The data used is collected from campus shuttles at " Binghamton University ", data would be provided upon request.

Data contains 7 different files

* Accelerometer.csv 
* Gyroscope.csv
* Battery.csv
* GPS.csv
* Motionstate.csv ( 'Driving' or 'idle' )
* wifi.csv 
* step.csv 
* speed.csv
* barometer.csv

# Sensors Used:-

* Accelerometer
* Gyroscope
* GPS
