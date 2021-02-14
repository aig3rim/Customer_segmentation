# Customer segmentation

## Introduction
This is a source code for my [Medium](https://aigerimshopenova.medium.com/) blog post [Data Driven Cistomer Segmentation](https://aigerimshopenova.medium.com/data-driven-customer-segmentation-c16062741a7c?sk=e86b92ca32bd124cea50ee0378ca0a23).

### Motivation
I believe that the best way to learn about marketing data science is to work through examples.

### Customer segmentation
Customer segmentation is the process of dividing customers into groups based on common characteristics, which allows companies market each group effectively and appropriately.

### Data 
For this analysis I am using a public dataset from UCI Machine Learning Repositiry, which can found [here](http://archive.ics.uci.edu/ml/index.php). This dataset contains information on transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Getting started
You need an installation of Python, plus the following libraries:

* numpy
* pandas
* matplotlib.pyplot
* seaborn
* sklearn

## Summary and key findings
* We applied k-means clustering to understand the difference between segments of an online retail shop
* Using Elbow method and Silhouette coefficient, we found the optimal number of segments, which is 4
* We looked at the most popular items bought by the group of high-value customers, which may help to sell the same/similar items to this high-value group and increase conversion.

