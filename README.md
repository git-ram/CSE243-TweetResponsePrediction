# CSE243-TweetResponsePrediction
This is a project for CSE 243 Data Mining course at UC Santa Cruz, Fall 2020. 

# Notes:
Avoid saving datasets into csv files anywhere other than in Preprocess notebook. This will prevent creation of redundant
datasets with various names and feature sets.

# How to use notebooks:

The order for running the notebooks:
1. First run Preprocess to generate a clean dataset
   Note how you save the clean dataset at the end of the Preprocess notebook depending on the columns you keep.
   
2. Run any other notebook for classification, exploration, etc. 
   Note which clean dataset with which columns you import first in these notebooks.
