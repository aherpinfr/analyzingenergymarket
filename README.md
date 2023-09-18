# Analyzing the energy market

## Introduction

### Context of the project
This analysis aims to get an insight into the energy market at a global scale. 
I wanted to understand how big companies in the renewables market were compared to more traditional companies.
I have the assumption that the oil market generates a lot of revenue but I would like to see oil data on a chart compared to other markets like hydrogen or solar in order to confirm this assumption.

### Goals of the project
The first goal of the project is to write a series of queries that will enable me to understand the database

The second goal of the project is to create a Dashboard with a chart:
* The chart will analyze the number of employees in each company compared to its revenues
* The different categories will be highlighted with colors on the chart 

### Sample size 
In total, I collected information on 105 companies that I categorized into one of the 6 following categories

* Installer
* Investor
* Manufacturer
* Renewables
* Support
* Traditional

### Tools 
Data have been stored in a SQL Server database in a table named "COMPANIES".
The building of the chart is going to be made further with Power BI. 

### Limits
Several companies - like Engie - are in a fuzzy zone because they are investing in both renewables and fossils. For those companies, I asked Chatgpt in which category the bot would put the company and applied the recommendation.

## [Database Analysis](DatabaseAnalysis.md)
### Summary
* 50% of the companies are traditional, 27% are renewables, 23% are one of the fourth other categories
* 94% of the revenues are generated by a traditional company, 5% by a renewable, 1% by one of the others
* Almost 90% of the employees are working for a traditional company, and 6% for renewables.
## [Daraviz & Analysis](DataVisualisationandAnalysis.md)
### Summary
* 2% of the companies are extraordinary, 10% uncommon and the rest 88% are common companies.
  * Non-traditional companies are common companies in the global energy market
  * They all generate less the 200 billion € and have less than 100k employees
* There is a lot of potential for renewables
  * The average company in Renewables makes around 12 billion €, while a traditional company makes on average 120 billion €.
  * This is as much as McKinsey and almost as Decathlon in 2022.



