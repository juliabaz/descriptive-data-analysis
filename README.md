# descriptive-data-analysis

## Overview

In Lab Assignment 2, we implement and test a Python function called simpleDDA that has the following three (inputs):
* the imput dataframe df in tidy data format;
* a pandas Series that has a specification of the data measurement type nominal, ordinal, interval, ratio of each variable (column) of the dataframe
* for each ordinal variable, a list of the values of the data type in order

and outputs a dataframe that contains the required results (A), (B), and (C) below for each variable of the input dataframe.

The required results are as follows:

(A) Overall Descriptions 
* number of observations
* number of entries
* number of unique values amongst the entries
* number of missing entries

(B) Central Tendency Descriptions 
feature,
* mode, or modes, for all data types
* median, for ordinal, interval, ratio data types
* mean, for interval, ratio data types

(C) Spread Descriptions 
* number of unique values amongst the entries, for nominal data types
* range: (min,max), for ordinal, interval, ratio data types
* IQR: Q3-Q1, for interval, ratio data types
* standard deviation, for interval, ratio data types
