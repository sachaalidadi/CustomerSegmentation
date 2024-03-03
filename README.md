## About this repository

This repository contains a machine learning model that segments a customer base into different clusters.

The training of this model can be found in the python notebook named `model_training.ipynb`

## About the notebook

The notebook contains two parts:

* EDA (Exploratory Data Analysis): Where we perform a statistical analysis of our dataset
* Model training: We select the relevant models for our problem and optimize the hyperparameters of the model

For this problem, we used two models:

* KMeans
* DBSCAN

## About the dataset

The dataset is a .csv file containing the gender, the age, the annual income and the spending score of the customers.

It was found on the site kaggle.com, you can find it [here](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

## How to replicate the results

The dataset can be found in the repository under the name `Mall_Customers.csv`

To execute the notebook, you need Python 3 and the following libraries:

* matplotlib
* numpy
* pandas
* seaborn
* sklearn

You can install these libraries using the following command:

```shell
pip install requirements.txt
```

requirements.txt is the txt file containing the names of the necessary libraries