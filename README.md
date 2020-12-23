# Bank-Marketing-Analytics  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
Final Project for Marketing Analytics

## Installations
### Modules
**pip install these modules**

- pandas: data processing
- numpy: linear algebra
- seaborn: data visualization
- matplotlib: data visualization
- sklearn: machine learning

### Data Source
Real-world data were collected from a Portuguese bank that used its own contact-center to do direct marketing campaigns.   
The dataset is available at [UCI Machine Learning Repository -- Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

## Project Motivation
### Background 
Direct marketing is an efficient approach to promote products or services because it focuses on target customers who are more likely to be interested.   
The service to be promoted in this case is long-term deposit applications with good interest rates. We aim to reduce the cost and time by improving efficiency -- making lesser contacts but remaining an approximate number of successes (client subscribing the deposit).
### Business Goal
I will deploy the Cross-Industry Standard Process for Data Mining for this classification project. The goal is to find a model that can explain if the client subscribes the deposit, so that to increase the efficiency of direct marketing campaigns.

## File Description
### bank/bank-full.csv
The dataset is related to 17 campaigns that occurred between May 2008 and November 2010, corresponding to a total of 79354 contacts. The success rate is 8% (6499 successes).
### bank/bank.csv
10% of the examples (4521), randomly selected from the bank-full dataset.
### bank/bank-names.txt
- Citation
- Information and backgroud
- Variable description
### DataUnderstanding.ipynb
A Jupyter Notebook for data wrangling and exproratory data analysis.
### modeling.ipynb
- Data preparation for classification models
- Five models were used to classify the data
Best model is Logistic Regression with an accuracy of 89.63%.

## License
This project is licensed under [MIT License](https://github.com/git/git-scm.com/blob/master/MIT-LICENSE.txt).

## Author
[Zhaoyi Wang](https://github.com/ZhaoyiW)

## Citation
[Moro et al., 2011] S. Moro, R. Laureano and P. Cortez. Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology. 

