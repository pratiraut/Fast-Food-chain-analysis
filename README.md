# Fast Food Chain Analysis

## Introduction
This repo contains the data analysis process on a fast food chain which is having their branches in 5 different cities. Presenting the data in a storytelling/visualization manner so stakeholders and board person understand the data in a simple way.  To make a data-driven decision. 

## Process

- Data Cleaning
- Description Statistics
- Data Analysis
- Dashboard

   
### Data Cleaning - Data cleaning is an essential step in the data analysis process.

Excel sheets with unstructured data for valuable insights. In order to  prepare data for later analysis, it is important to have clean data. Depending on the origin of the data, I need to do some of the following steps to ensure that the data are as complete and consistent as possible. 

Cleaning data includes the following steps:
1. Filtering the data.
2. Removing blanks / duplicate  records. 
3. TRIM function- used to remove irregular text spacing and keep single spaces between words.
4. Quantity should not be in decimal so rounding up.

Data structure - Even when having a clean data table, the data structure may not be precisely right for the kind of analysis want to do.

- Calculate new columns :

                   Revenue = Quantity * Price


### Description Statistics - 

In Descriptive statistics, we are describing our data with the help of various representative methods using charts, graphs, tables, excel files, etc. In descriptive statistics, we describe our data in some manner and present it in a meaningful way so that it can be easily understood. Most of the time it is performed on small data sets and this analysis helps us a lot to predict some future trends based on the current findings. Some measures that are used to describe a data set are measures of central tendency and measures of variability or dispersion.

![Descriptive Statistics](https://github.com/pratiraut/Fast-Food-chain-analysis/assets/146583441/09a0e6c6-69f1-4b1e-986c-bcda3b917fba)

- Outliers

  They are data records that differ dramatically from all others, they distinguish themselves in one or more characteristics. In other words, an outlier is a value that escapes normality and can (and probably will) cause anomalies in the results obtained through algorithms and analytical systems. There, they always need some degree of attention.

![Outliners](https://github.com/pratiraut/Fast-Food-chain-analysis/assets/146583441/05cc5faf-6488-44bb-a46d-debd296f8e42)

- Box represents the first and the third quartile.
- Dots which represent all of the outliners in price.
- It seems to be that all of these outliers are accumulated with manager Joao Sliva, maybe we should have a word with him.

### Data Analysis

 Excel pivot table - Pivot table allows us to quickly explore and analyze raw data.

1. What is the best-selling product?

![Best selling](https://github.com/pratiraut/Fast-Food-chain-analysis/assets/146583441/02b9c7b5-90be-4813-9e77-58c8c114d669)


2. Total Revenue -

![Total Revenue](https://github.com/pratiraut/Fast-Food-chain-analysis/assets/146583441/00f941b2-4e2a-457a-bb72-328af30e14a4)


3. Revenue breakdown by Payment method -

![by Payment method](https://github.com/pratiraut/Fast-Food-chain-analysis/assets/146583441/df329f2f-c0b9-499f-8da2-5ff2d2e53e2e)


### Dashboard

A dashboard is a visual representation of KPIs, key business metrics, and other complex data in a way that’s easy to understand.

To make it dynamic I also added slicers for cities.
Slicers apply filters for tables, pivot tables, and pivot charts. They are widely used for creating dashboards that display the summary report of the table. 

Slicers indicate the current filtering state, making it easier to understand what is currently displayed. 

![Dash](https://github.com/pratiraut/Fast-Food-chain-analysis/assets/146583441/643b0b90-8f4d-4c36-9813-5d03dbb2e2f1)

## Concussion and recommendations

- In the other 4 countries, we see the beverages are the top seller. 
- But, In Paris, we can see that the fries are the top seller. 

Recommendations : 

Adding fries in the combo may increase all the other fast food items on the list. 
And giving them the offer of  getting extra fries on the minimum purchase amount of the entire menu. So that they can generate the test of other items as well.

