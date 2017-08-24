## Introduction to Jupyter Notebooks Lab
This repository contains data and analytic assets for the Lab. The Jupyter Notebook is designed to run on 
<a href="https://datascience.ibm.com" target="_blank">IBM Data Science Experience</a> and analyzes the churn.csv and customer.csv data sets.

There are 2 notebooks to work through in this exercise.

### Getting Started
- Create a **Project** in DSX Cloud and name it *IntroToNotebooks*

- Within the *IntroToNotebooks* project, **add a Notebook** and choose to import it from this **URL**: 
  https://github.com/yfphoon/IntroToNotebooks/blob/master/Predict%20Customer%20Churn%20-%20Build%20Model.ipynb
  
  ![Add a notebook](images/create_notebook_URL.png?raw=true)
  
- Work through the "*Predict Customer Churn - Build Model*" notebook
- Add the "*Predict Churn - Score New Data*" notebook into your *IntroToNotebooks* project and work through the notebook.  The **URL** is https://github.com/yfphoon/IntroToNotebooks/blob/master/Predict%20Churn%20-%20Score%20New%20Data.ipynb
<br/>

### Optional Lab Exercises

#### 1. Access data in flat files
- Download ![churn.csv](data/churn.csv?raw=true) and ![customer.csv](data/customer.csv?raw=true), and add them into the *IntroToNotebooks* project
- Create a duplicate of the "*Predict Customer Churn - Build Model*" notebook

![Duplicate a notebook](images/duplicate_notebook.png?raw=true)

- Edit the "*Predict Customer Churn - Build Model copy 1*" notebook to read the data from the flat files
- **Tip**: make sure *inferSchema* is set to 'true' when reading in the csv files, otherwise, all columns will be treated as String values.

![infer schema](images/infer_schema.png?raw=true)

#### 2. Build a LogisticRegression model
- Create a duplicate of the "*Predict Customer Churn - Build Model*" notebook
- Edit the "*Predict Customer Churn - Build Model copy 2*" notebook
- In "*Step 6: Build the Spark pipeline and the Random Forest model*", edit the code to build a LogisticRegression Model
