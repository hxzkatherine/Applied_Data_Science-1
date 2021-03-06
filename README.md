# Predict Future Sales
##### Final Project for Applied Data Science for Practitioners

Predict Future Sales
Kaggle: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data

The main goal of this kaggle competition is to predict the monthly sales for the next month based on the historical daily sales of each store and each product for 34 months. In other words, we use historical sales to predict future sales. Therefore, it's a time-series problem.

#### Project difficulties:

1. Data is scattered in multiple excel files
2. Predictors are not suitable for direct use and require more feature engineering
3. The information brought by the time series should be fully exploited

#### Evaluation method: 
Submissions are evaluated by root mean squared error (RMSE). True target values are clipped into [0,20] range.

#### Hint: 
    
    1. To fully understand the project, please read the Data Analysis section first.
       path: ...\notebooks\Kaggle Predict Future Sales.ipynb
    
    2. This project uses the pipeline approach, which clearly shows all the steps of the model. 
       For ease of reading, the file shows all the predefined functions at the beginning of pipeline.ipynb.
       path: ...\src\models\pipeline.ipynb


#### Project Organization
------------
    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. project and data analysis, data cleaning, visualization, and hyperparameters tuning
    │  └── Kaggle Predict Future Sales.ipynb
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │   │
    │   ├── Dictionaries_origin.ipynb  <- Dictionaries for original data set
    │   └── Dictionaries_model.ipynb   <- Dictionaries for columns appears during the procedure
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   │
    │   ├── functions      <- Scripts of predifined functions for pipeline
    │   │   └── functions.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions for test set and Kaggle test set
    │   │   └── pipeline.ipynb
    │   │
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


"The work I submitted represents my work and my work alone.  I abode by the academic integrity policy and I am aware of the consequences associated with engaging in academic misconduct. "
