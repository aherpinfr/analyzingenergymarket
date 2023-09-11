# Searching for a specific type of company working in energy then analyzing the market

* List
## Table of contents
## Introduction

### [Context of the project](https://github.com/aherpinfr/analyzingenergymarket/edit/main#context-of-the-project-1)

### Context of the project
This analysis aims to get an insight into the energy market at a global scale. 
I wanted to understand how big companies in the renewables market like Vestas Wind Systems were compared to more traditional companies like Saudi Aramco.
I know that the oil market generates a lot of revenue but I would like to see it on a chart compared to other markets like hydrogen or solar.

### Goals of the project
The first goal of the project is to write a series of queries that will enable me to understand the database
The second goal of the project is to create a Dashboard with a chart:
 - The chart will analyze the number of employees in each company compared to its revenues
 - The different categories will be highlighted wit colors in the chart 

### Sample size 
In total, I collected information on 105 companies that I categorized into one of the 6 following categories

Installer
Investor
Manufacturer
Renewables
Support
Traditional

### Tools 
Data have been stored in a SQL Server database.
The building of the chart is going to be made further with Power BI. 

### Limits
Several companies - like Engie - are in a fuzzy zone because they are investing in both renewables and fossils. For those companies, I asked Chatgpt in which category the bot would put the company and applied the recommendation.

```sql
this is code in sql
```
