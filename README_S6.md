# Session 6 Assignment: Pandas I Library

In this assignment we explore 2 datasets with the pandas library. Dataset 1 (df1) is with Netflix and Dataset 2 (df2) is with Titanic.

## Netflix (df1)
As an overview, there are 5 exercises below that demonstrates the application of coding syntax learned:
1. Missing Rating: Use of .isna() or .isnull()
2. Number of films from Singapore in 2021: Use of square brackets [] for filtering and & for Venn-Diagram-like intersection
3. Number of movies in 2020 with full information: Use of .dropna() to get rows with full information only
4. Year with the most titles: Use of .valuecounts()
5. Average titles released per year from 2010: Deploying [] filters, count() and datetime module that would update dynamically when year 2024 passes.

## Titanic (df2)
As an overview, there are 2 exercises below that demonstrates the application of coding syntax learned:
1. Calculating Survival Percentage with the Base as Gender
2. Calculating Survival Percentage by intersection of the criteria of Gender and Class. However due to ambiguity in the English wording, I provide the percentage calculation for 2 scenarios:

   a.Total passengers in the Passenger Class with that Gender
   
   b. Total Overall Passengers in whole Titanic

# Installation of required libraries
```
pip install -r requirements_S6.txt
```
