# House Prices
Instructors: Vincent Jeanselme (vjeansel@andrew.cmu.edu).  


This project has been created for [PreCollege Artifical Intelligence](https://admission.enrollment.cmu.edu/pages/access-artificial-intelligence) at Carnegie Mellon University in July 2018.

------

## Description
What is the price of your dream house ? This dataset will allow you to answer this question by building a regression model. This model will be based on 79 variables describing each and every aspect of houses in Ames, Iowa. Your goal is to predict the price of the house given these multiple variables.  

This project explores a real application of machine learning in order to modelize a problem and to understand the influence of different parameters. You will explore every step of the process: analyzing, visualizing, cleaning the data in order to build and then evaluate different models.  
You will learn how to build a model in python using standard libraries such as `numpy`, `pandas` and `sklearn` in order to solve your first supervised regression problem. Understanding the data will be a strong focus of this project because machine learning is not magic. It is a tool reflecting an understanding of the data which has to complete the human reflection but not replace it.

## Planning
0. Project Presentation
1. Data Analysis
    - What is the distribution of prices ?
    - Are there any strong correlation ?
    - How to represent this data in low dimension ?
2. Data Cleaning
    - Are there missing data ?
    - How to correct missing data ?
    - How to deal with categorical features ?
3. Evaluation Metrics
    - How do we know that a prediction is good ?
    - What exactly is a regression ?
4. Modelization & Analysis
    - Linear Regression, Regression Tree, Random Forest
    - What are the key components for predicting the price ?
    - What is my model missing ?
    - Which renovation do I have to do in order to sell my house at a higher price ?
5. Bonus: Improvements
    - What is an outlier ?
    - What is a skewed distribution ?
    - Cross Validation
6. Bonus: Other applications

## How to run a notebook ?
1. Install Anaconda
    Anaconda will allow you to easily manage your python packages.
2. Install numpy, pandas and sklearn
    These libraries contain functions in order to manipulate your data and use machine learning algorithms.
    Open a terminal and type:
    ```
    conda install numpy pandas sklearn scipy matplotlib seaborn
    ```
3. Clone the git repository on your computer
    Open a terminal and type:
    ```
    git clone https://github.com/Jeanselme/AI4ALL
    ```
4. Run the jupyter notebook
    ```
    jupyter notebook
    ```
## Acknowledgments
This project is based on the Kaggle Competition [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques#description) using the [Ames Housing Dataset](https://ww2.amstat.org/publications/jse/v19n3/decock.pdf) compiled by Dean De Cock.
We also thank all the competitors who published Kernels helping us to create this project.  
And also the excellent [Medium article](https://hackernoon.com/memorizing-is-not-learning-6-tricks-to-prevent-overfitting-in-machine-learning-820b091dc42) about overfitting by Julien Despois.

