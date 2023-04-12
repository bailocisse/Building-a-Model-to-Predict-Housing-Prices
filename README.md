# Building a model to predict housing prices

![Github Logo](housesbanner.jpg "Github logo - markdown")

<a class="anchor" id="about_the_project"></a>
>## About the Project

The goal of this data science project is to build an efficient **machine learning model** to predict house prices. To achieve this, our supervised model (the price is the label) will learn from a training data set in which we'll select the most relevant features that best explain the house prices.

This notebook shows the different steps and code to achieve our goal.

+ In the first part of the notebook :
    - We will make some **data explorations** along with **data cleaning** by dealing with duplicate values (if there are any), null values... 
    - Then we will use the **correlation technique** (Pearson correlation matrix) to select the features that are best correlated with the dependant variable (house price)
    - Then we will **build our model** and make some accuracy analysis on three different set of variables.
    - Finally, we are going to verify our model against the **test data**.
+ In the second part of the notebook, we will make further transformations to try perform better on the test dataset :
    - First, we will apply the same transformations as in the first part of the notebook
    - Then, we are going to treat categorical columns with some imputation and the use of ANOVA technique.
    - Finally, we will compare the performance of this new model to the model built in the first part of the notebook on the test data

In a general context, one can use this kind of model in real world to estimate a house price. It can even be useful for real estate agencies. 

As I mentioned above, the goal is to build an efficient machine learning linear model to predict house prices. In the dataset, we have 82 variables (including Unnamed: 0 and Id columns) that describe different aspects of a hundred houses including their prices. 
We're going to operate on this data using python data analytics and data science librairies.

<a class="anchor" id="tools"></a>
>## Tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Matplotlib
5. Seaborn
6. Sklearn
7. Scipy

<a class="anchor" id="installation_instructions"></a>
>## Installation instructions

The code is described in the notebook. You can also find results in the presentation slide deck

<a class="anchor" id="contact"></a>
>## Contact Information

[Mamadou Bailo CISSE](https://www.linkedin.com/in/mamadou-ba%C3%AFlo-cisse-92548090/)

>## Table of Contents Example
* [About the Project](#about_the_project)
* [Tools](#tools)
* [Installation Instructions](#installation_instructions)
* [Contact Information](#contact)
