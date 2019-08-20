

# Starbucks Offer

### Table of Contents

- [Project Motivation](#motivation)
- [Project Components](#components)
  - [Data Cleaning](#etl_pipeline)
  - [EDA](#ml_pipeline)
  - [Modelling](#flask)
- [Contribute](#contribute)
- [Acknowledgement](#ack)

***

<a id='motivation'></a>

## 1. Project Motivation

I've been a loyal Starbucks customer since I can remember. One thing I've thought about is how data science can be used to improve a business, and this is exactly what I've set out to do--use machine learning to provide better offers to its customers, taking into consideration various factors like age, salary, gender, etc.

<a id='components'></a>

## 2. Project Components

There are three components in this project:

<a id='etl_pipeline'></a>

### 2.1. Data Cleaning

Notebook `1_Data Cleaning.ipynb` contains the code for general cleaning of the data, like dealing with NaN values and renaming column names

<a id='ml_pipeline'></a>

### 2.2. EDA

EDA stands for Exploratory Data Analysis where insights about the data are gathered using data analysis techniques and various statistics are discovered, usually accompanied by graphs and charts. This is contained in the notebook `2_EDA.ipynb`

<a id='flask'></a>

### 2.3. Modelling

The final notebook `3_Modelling.ipynb` consists of combining all the datasets and using the `RandomForestClassifier` to generate predictions about which customer should get the offer based on various parameters.

***

<a name="contribute"/>

## Contribute
1.  Fork the repository from Github
2.  Clone your fork

`git clone https://github.com/kaustubh-ai/Starbucks-Offer.git`

3.  Add the main repository as a remote

`git remote add upstream https://github.com/kaustubh-ai/Starbucks-Offer.git`

4.  Create a pull request!

***

<a name="ack"/>

## Acknowledgement

I'd like to thank [Udacity](https://www.udacity.com) for providing me with the dataset and motivation for this project
