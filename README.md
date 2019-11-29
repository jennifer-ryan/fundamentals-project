# Tips Dataset Project

This repository contains an exploration of the famous 'tips dataset' for the assessment in the *Fundamentals of Data Analysis* module for the Higher Diploma in Data Analytics with Galway-Mayo Institute of Technology.


## About this Repository

The repository can be accessed [here](https://github.com/jennifer-ryan/fundamentals-project). Clicking the 'clone or download' button will allow you to download the repository to your machine. Some of the jupyter notebook output may not render correctly in the GitHub repository but should function as intended on a local machine. 

The contents of this repository are:

1. A **README** file that outlines the layout of the project.
2. A **Jupyter Notebook** that contains a discussion of the variables in the output and an examination of some of the relationships between these variables. The notebook contains a table of contents to aid navigation.


## Python Libraries

For this project I use the following Python libraries:

- **pandas** and **numpy** for statistical analysis.
- **matplotlib.pyplot** and **seaborn** for data visualisation.
- **sklearn** for regression analysis.


## Project Description

A broad outline of this project is as follows:

1. **Descriptive Statistics:** The dataset is explored as a whole and then by each variable to get an overall impression and help to identify potential relationships for later exploration.
2. **Relationship Between Tip and Total Bill:** Using linear regression, I attempt to see if there is a correlation between the total bill and the tip values. It appears there is a strong positive linear relatonship in that as the total bill grows so does the tip.
3. **Relationship Between Other Variables:** Other varible relationships are examined, particularly the tip as a ratio of the bill and how this is affected by the number of customers at the table. It appears from this data that there is a moderate negative relationship between these factors as the tip ratio falls when group size grows. It seems that many of the differences between other variables may be related to this relationship between group size and tip percentage. 
