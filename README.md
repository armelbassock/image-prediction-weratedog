# image-prediction-weratedog
It is an analyse of a dataset given by weratedog to do an image prediction

## Introduction

The dataset you will process (and analyze and visualize) is the archive of tweets from Twitter user @dog_rates, also known as WeRateDogs.
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 
These scores almost always have a denominator of 10. 
But the numerators? Almost always above 10. 11/10, 12/10, 13/10, etc. Why ? Because “they are Brent dogs”. 
WeRateDogs has over 4 million subscribers and received international media coverage.
Overview of the project stages

### Step 1: data collection

In this step, we collect all three pieces of data described below in the “Data Collection” section of the “wrangle_act.ipynb” notebook.
* The WeRateDogs Twitter Archive
* Twitter API Additional Data providing from the file tweet_json.txt
* Tweet image predictions include in the file image_predictions.tsv

### Step 2: data evaluation

We must use two types of assessment:

* Visual evaluation: Each piece of collected data is displayed in the Jupyter notebook for visual evaluation. Once displayed, the data can additionally be evaluated in an external application (eg Excel, a text editor).
* Programmatic evaluation: pandas functions or methods are used to evaluate data.


### Step 3: data cleaning

We make sure to complete the following items in this step.

* Before cleaning, we make a copy of the original data.
* During cleanup, use the define-code-test framework and document it clearly.
* Cleansing includes merging individual data elements according to tidy data rules. The result should be a high-quality, tidy pandas main data array (or data arrays, if any).

### Step 4: data storage

In the "Data Storage" section of the wrangle_act.ipynb notebook,
store the cleansed data table master file in a CSV file along with the main file named twitter_archive_master.csv.

### Step 5: Analyze and visualize the data

In the Analyze and Visualize Data section of your Jupyter notebook wrangle_act.ipynb, analyze and visualize your scrambled data.

* we produce at least three (3) observations and one (1) visualization.
* we clearly document the assessed and cleaned (if necessary) data used to perform each analysis and visualization.
  
