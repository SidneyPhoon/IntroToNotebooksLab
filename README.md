## Introduction to Jupyter Notebooks Lab
This repository contains data and analytic assets for the Lab. The Jupyter Notebook is designed to run on 
<a href="https://datascience.ibm.com" target="_blank">IBM Data Science Experience</a> and analyzes the churn.csv and customer.csv data sets.

In this exercise, there are 3 notebooks to work through, 2 required and 1 optional.

### Getting Started
- Create a **Project** in DSX Cloud and name it *IntroToNotebooks*.  Select "Object Storage (Swift API)" Storage Type.

- Within the *IntroToNotebooks* project, **add a Notebook** and choose to import it from this **URL**: 
https://github.com/SidneyPhoon/IntroToNotebooksLab/blob/master/PredictCustomerChurnStudent_Learn.ipynb

  
  ![Add a notebook](images/create_notebook_URL.png?raw=true)
  
- Work through the "*PredictCustomerChurnStudent_Learn*" notebook
- Add the "*Predict Churn - Score New Data*" notebook into your *IntroToNotebooks* project and work through the notebook.  The **URL** is https://github.com/SidneyPhoon/IntroToNotebooksLab/blob/master/Predict%20Churn%20-%20Score%20New%20Data.ipynb
<br/>

### Optional Lab Exercises

#### 1. Access data in flat files
- Download ![churn.csv](data/churn.csv?raw=true) and ![customer.csv](data/customer.csv?raw=true), and add them into the *IntroToNotebooks* project
- Create a duplicate of the "*PredictCustomerChurnStudent_Learn*" notebook

![Duplicate a notebook](images/duplicate_notebook.png?raw=true)

- Edit the "*PredictCustomerChurnStudent_Learn copy 1*" notebook to read the data from the flat files
- **Tip**: make sure *inferSchema* is set to 'true' when reading in the csv files, otherwise, all columns will be treated as String values.

![infer schema](images/infer_schema.png?raw=true)

#### 2. Inject a new transformer and building a LogisticRegression model
- Add the "*PredictCustomerChurnStudent_Practice*" notebook into your *IntroToNotebooks* project and work through the notebook.  The **URL** is https://github.com/SidneyPhoon/IntroToNotebooksLab/blob/master/PredictCustomerChurnStudent_Practice.ipynb

- Follow the instructions in the notebook and work through it.
