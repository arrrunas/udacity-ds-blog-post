# README

This repository contains data associated with Udacity's "Write A Data Science Blog Post" project.

### Project objectives and results

The goal of this analysis was to look into US wine reviews and determine:
* what wines are popular in the US
* do expensive wines get better reviews?
* can excellent wines be obtained without breaking the bank?
* are different words used in positive reviews vs negative reviews?

The following libraries were used in the analysis:
* numpy and pandas for data wrangling
* matplotlib.pyplot and seaborn for data visualisation
* wordcloud for making word clouds

Summary of findings:
* The dataset contains a high number of duplicates and some missing values
* Local wines are popular in the US
* Pinot Noir, Chardonnay and Cabernet Sauvignon are the most popular wine varieties in the US
* There is a positive correlation between price and review rating with price increasing by $1.18 on average per 1 rating point
* Italian Sangiovese Grosso wine offers the highest median review rating at a modest price
* There is opportunity for further linguistic analysis of positive vs negative wine reviews
* [Link](https://medium.com/@arunas.umb/this-data-analysis-will-make-you-rethink-fancy-wine-ab962e7ef632) to the Medium post

### Files in repository

* winemag-data_first150k.csv - raw wine reviews data from Kaggle datasets
* 2020.01.05 - wine analysis for blog post.ipynb - Jupyter notebook containing data analysis and visualisations

### Acknowledgements

[Wine reviews dataset](https://www.kaggle.com/zynicide/wine-reviews#winemag-data_first150k.csv) used in this project comes from Kaggle.
