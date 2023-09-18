# Car Price Prediction - Portuguese Data Collection

## Table of Content
  * [Overview](#Overview)
  * [Business Understanding](#Business-Understanding)
  * [The Challenge](#The-Challenge)
  * [Data Collection](#Data-Collection)
  * [Installation](#Installation)
  * [Directory Tree](#Directory-Tree)
  * [Technologies Used](#technologies-used)

## Overview
The goal of this project was to create a dataset with a considerable amount of data to build a machine learning system to predict car prices in the Portuguese market.
After the collection of almost 40 000 cars using web scraping, the data was cleaned and processed. With this data several machine learning algorithms and neural networks were trained in order to find the best model for car price prediction.
* Data Collection
* Data Cleaning
* Data Transformation
* Outliers Detection
* Models Training
* Models Evaluation
* Predictions with the Best Model

## Business Understanding
The goal is to offer a solution that is able to predict, with the minimum error possible, the price of a used car.
With this machine learning system, anyone can use it to one or several the following purposes:
* A given car owner can evaluate how much its car can be sold for
* Someone looking to buy a car, can evaluate if a given car is underpriced or overpriced
* A given car trader, can have more information at his disposal to make better decisions

## The Challenge
There was tree big challenges in this project:
* The amount of missing values - besides collecting a large number of variables, in the end I had to reduce its number, sticking with only the ones that were possible to be considered to feed a machine learning system. The variables with a low amount of missing values were included after imputing values;
* Categorical Variables with a large number of values - this turned out to be a challenge since variables like the car Model and the car Version can impact the price;
* The data collection - Collecting data from thousands of cars listed in portuguese websites was a challenging task, since these websites always have limits to bots. Fortunately, Python is a very versatile language that offers a lot of ways to put logic into practice.

## Data Collection
The web scraping was done on 05/2022 and data from 34 909 cars was collected. A continuous data collection system was also built but wasn't used since the nature of this project had a limited time frame.

## Installation
The Code is written in Python 3.10.6 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── Portugal Car Price Prediction.ipynb
├── requirements.txt
└── README.md
```

## Technologies Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)


<img src="https://img.icons8.com/color/30/000000/linkedin.png"/> [Pedro Patinha](https://www.linkedin.com/in/pedromaiapatinha/)
