# Election Analysis

## Project Overview
A Colorado Board of Election employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast
2. Get a complete list of candidates who received votes
3. Calculate the total number of votes each candidate received
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.13, Visual Studio Code 1.74.0

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates were:
  - Charles Casper Stockham
  - Diane Degette
  - Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes
  - Diana DeGette received 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was:
  - Diane Degette who received 73.8% of the vote and 272,892 votes

## Challenge Overview
To complete the election audit, additional information was requested to find the following:

1. The voter turnout by county
2. The percentage of votes by county
3. The county that had the largest turnout

## Challenge Summary

Out of the total 369,711 votes that were casted, each county received the following # and % of votes:
- Jefferson county received 38,855 votes and 10.5% of the vote
- Denver county received *the most* amount of votes with 306,055 votes and 82.8% of the vote
- Arapahoe county received *the least* amount of votes with 24,801 votes and 6.7% of the vote

![Results_Snapshot](https://github.com/cbrooks718/election_analysis/blob/main/analysis/election_results.txt)

## Suggestions for Modification

Given the results, most of the votes cast were from the Denver county with over 80% of votes coming from there. A helpful metric in this case might be to find how many votes candidates received from each county. To do execute this, an if statement can be made inside the initial for loop created to gather the election results.

Secondly, this coding model can be used for larger elections. In order to obtain the county results, the same coding pattern was used to gather candidate results. So, if we wanted to gather state information instead of county information, we can first tell the system in a for loop to: gather info from the dataset, start tallying votes, and display the results just like we did for the county information. Therefore, the code presented can be used for larger elections at both a state and national level.
