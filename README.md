# Machine Learning with Snowpark Python and Java UDFs

## 1. Overview

In this example, you will be able to use Snowpark for Python, along with your favorite python libraries for data analysis and visualization, as well as the popular scikit learn ML library to address an end to end machine learning use case.

Using rental listings we would like to train a ML model to estimate the rent price of our sale listing


### Using rental listings we would like to train a ML model to estimate the rent price of our sale listing : 

![title](img/BusinessUseCase.png)

### We will use the following architecture to prepare our data, training our XGBoost linear regression model and run our model on Snowflake :

![title](img/TechUseCase.png)


## 2. Prerequisite

* Snowflake account
* Anaconda 

## 3. What you'll learn  

- Get an understanding on how to implement an end-to-end ML pipeline using Snowpark for Python.
- Develop using Snowpark for Python API, and Snowpark for Python UDFs.
- Data Exploration, visualization and preparation using Python popular libraries (pandas, matplotlib).
- Machine Learning using scikit-learn python package and Xgboost
- Deploying and using an ML model for scoring in Snowflake using Snowpark for Python.
- Navigating and using Scored Data into Streamlit .

## 4. Usage/Steps

1. Open terminal and clone this repo or use GitHub Desktop : 

    `git clone https://github.com/Snowflake-Labs/snowpark-python-examples`

2. Move into to the `Real Estate Rentability Prediction` directory and create conda environment from yml file

    `conda env create -f Streamlit_Realestate_LBC.yml`

3. Activate Conda environment just created

    `conda activate Streamlit_Realestate_LBC`

4. Start Jupyter Lab from terminal with the below command

    `jupyter lab`

4. Run through the RealEstateRentabilityPrediction_Setup Notebook. This will create the database and tables needed for this demo. 

5. Then you can now run the RealEstateRentabilityPrediction_Demo.

6. Last but not use Scored Data into Streamlit.
    `jupyter lab`


