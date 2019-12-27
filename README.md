# Project : Ford Gobike data analysis from year 2017-2019

# Project : Ford Gobike data analysis from year 2017-2019

## Table of Contents

- [Introduction](#intro)
- [Problem Statement](#problem)
- [Files](#files)
- [Software Requirements](#sr)
- [Exploratory Analysis](#exa)
- [Explanatory Analysis](#ena)

<a id="intro"></a>

## Introduction

This data set contains the trip data of Gobike from year 2017 till 2019. The data set contains attributes such as start station, end station, trip duration, user type, gender, etc.

<a id="problem"></a>

## Problem Statement

My goal is to create visualizations of the dataset in order to get a more clear picture about it, which can be used for analysing to improve the product in the near future. 

<a id="sr"></a>

## Software Requirements

This project uses python(Anaconda), Jupyter Notebook, Any web browser(preferably Google Chrome), Microsoft Excel

<a id="files"></a>

## Files

<pre>

├── ReadMe.md---------# DOCUMENT TO PROVIDE YOU WITH THE BASIC LAYOUT OF THIS PROJECT 
├── exploratory_report.html---------# OBSERVATIONS ON THE DATASET 
├── explanatory_report.html---------# OBSERVATIONS ON THE DATASET WHICH PROVIDES INSIGHTS IN A MORE ELABORATE FORM 
├── data_visualisation.slides.html---------# SLIDE SHOW WITH VISUALISATIONS TO CONCLUDE THE FINDINGS 
 *Also includes other supporting files 

</pre>

<a id="exa"></a>

## Exploratory Analysis

The major concern like for all data are the outliers which will make the statistics look ambiguous and goofy very much like our case today. It is important to identify them and not consider them in our computations. 
1. More subscribers than customers
2. Average trip duration of customers is more than the subscribers despite the subscribers being large in numbers 
3. The Trip duration has been dropping over the years 
These finding can be used to further analyse our data to get new insights and create much more elaborate visualisations

<a id="ena"></a>

## Explanatory Analysis

1. Even though we see that the male users are more, there should be a focus to engage other gender groups as well
2. As we can see in the second point that the average trip duration of the other groups is far more than the male average trip duration, by increasing other gender enagegments more revenue can be generated
3. More offers should be given during the weekends to increase the useage during the same
4. Root cause analysis should be done to understand why the trip duration over time is decreasing
