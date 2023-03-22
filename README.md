# Header - README Template

![Github Logo](housesbanner.png "Github logo - markdown")

<a class="anchor" id="about_the_project"></a>
>## About the Project
In this project, we built some machine learning models to predict house prices.
After analyzing the dataset using data description file along with some exploration steps, we selected three sets of features based on their correlation with the SalePrice (dependent variable). We then built three models (model10, model15, model20) against those three sets of features (**10, 15, 20 most correlated features**) and demonstrated that the model model20 was the one that performed the best on the training data regarding **the three metrics $R^2$ (0.88), MAE - Mean Absolute Error - (18 356.27) ,and MSE - Mean Square Error (600 490 969.09)**. 

However, we were not performing well on the test dataset. We then decided to perform **further transformations** by including categorical (ordinal and nominal) variables to build a new model "NewModel". We selected the best correlated categorical features by using **most-frequent imputation** (to deal with null values) and **ANOVA** (ANalysis Of VAriance) technique.

By doing so, we improved :
+ $R^2$ metric from **0.88** (model20) to **0.95** (NewModel) on the train dataset.
+ $R^2$ metric from **0.74** to **0.78** on the test dataset.

<a class="anchor" id="tools"></a>
>## Tools
Include a list of the tools used in the project:
1. Jupyter Notebook
2. MySQL
3. Matplotlib

<a class="anchor" id="installation_instructions"></a>
>## Installation instructions
Include the installation instructions here

<a class="anchor" id="contact"></a>
>## Contact Information
[BillGates](https://www.linkedin.com/in/williamhgates/detail/recent-activity/posts/)
[@BillGates](https://twitter.com/BillGates) - Twitter

>## Table of Contents Example
* [About the Project](#about_the_project)
* [Tools](#tools)
* [Installation Instructions](#installation_instructions)
* [Contact Information](#contact)