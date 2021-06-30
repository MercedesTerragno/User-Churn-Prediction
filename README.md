# Predict Customer Churn with Spark
Machine Learning pipeline using PySpark to predict User Churn in a music streaming platform.

### Table of Contents

1. [Project Motivation](#motivation)
2. [File Descriptions](#files)
3. [Acknowledgements](#acknowledgements)

## Project Motivation <a name="motivation"></a>

Customer engagement is arguably one of the most important aspects in any business. Being able to predict that a user is likely to cancel the service we are providing is essential to take action on time, either offering discounts or any other benefit, potentially preventing the loss and even improving their loyalty. Being able to save customers that are at risk of churning can make a huge difference in terms of revenue.

In this project, we will use Spark to analyze users' log data and build a Machine Learning Pipeline to predict User Churn in a fictional music streaming platform called Sparkify. We will use a small subset of the data (128 MB) for the analysis, and then we will deploy it to AWS EMR to find the best model using the full dataset (12 GB).

## File Descriptions <a name="files"></a>

- sparkify.ipynb: all the code, rationale, and details of the project step by step.
- subset_event_data.json: small subset of data used for analysis.


## Acknowledgements <a name="acknowledgements"></a>

The dataset was provided by [Udacity](https://www.udacity.com/) as part of its Data Scientist Nanodegree Program.
