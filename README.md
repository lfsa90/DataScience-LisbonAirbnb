# DataScience-LisbonAirbnb

This code was written under the Udacity Data Scientist Nanodegree Project.

## Table of Contents

1. [Installation](#Installation)
2. [Introduction/Motivation](#Introduction)
3. [Data](#Data)
4. [Results](#Results)
5. [Licensing, Authors, and Acknowledgements](#Licensing)

## Installation <a name="Installation"></a>
* The code was developed and tested on anaconda with python 3.73. Nevertheless, it should run with no issues using Python 3.* in any other environment.
* The datasets must be downlowaded from the Airbnb website/data repository, unziped, and placed in the '/Data' folder:
- ([listings_complete.csv](http://data.insideairbnb.com/portugal/lisbon/lisbon/2019-06-26/data/listings.csv.gz)). Important: this file must be renamed to 'listings_complete.csv' before placing it in '/Data' folder;
- ([calendar.csv](http://data.insideairbnb.com/portugal/lisbon/lisbon/2019-06-26/data/calendar.csv.gz));
- ([listings.csv](http://data.insideairbnb.com/portugal/lisbon/lisbon/2019-06-26/visualisations/listings.csv)).

## Introduction / Motivation <a name="Introduction"></a>
This is an Udacity Data Science Nanodegree project.

For this project I chose Airbnb-Lisbon (my hometown) 2019 dataset ([here](http://insideairbnb.com/get-the-data.html)), and was mainly interested in finding the answers to the following questions:
1. Busiest times of the year in Lisbon and price fluctuation;
2. What are the most popular neighbourhoods and house types;
3. Main factors driving higher prices.

## Data <a name="Data"></a>
```text
DataScience-LisbonAirbnb/
├── DataScience-LisbonAirbnb.ipynb
├── utility.py
└── data/
    ├── listings_complete.csv
    ├──	calendar.csv
```
* __DataScience-LisbonAirbnb.ipynb__: Notebook with all the scripts used to analyse data and to answer the questions mentioned above
* __utility.py__: Python file with auxiliar functions/scripts
* __data/listings_complete.csv__: Detailed Listings data for Lisbon ([Airbnb](https://airbnb.com/))
* __data/calendar.csv__: Detailed Calendar Data for listings in Lisbon ([Airbnb](https://airbnb.com/))

## Results <a name="Results"></a>
The detailed analysis and main conclusions/results are availabe in [here](https://www.google.pt]).

## Licensing, Authors, and Acknowledgements <a name="Licensing"></a>
* Thanks to Udacity for all the useful insights and interesting challenges!
* Thanks to Airbnb for making these data sets available to everyone!
