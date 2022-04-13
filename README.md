# Challenge3
#** An Analysis of Colorado Board of Elections Audit**

## Overview of Project

The Colorado Board of Elections has given the following tasks to complete the election audit of a recent 
congressional election. We are to determine the following:

1.	Calculate the total number of votes cast.
2.	Get a complete list of candidates who received votes.
3.	Calculate the total number of votes each candidate received.
4.	Calculate the percentage of votes each candidate won.
5.	Determine the winner of the election based on popular vote.


### Resources Used

•	Data Source: election_results.csv
•	Software: Python 3.9.7, Visual Studio Code, 1.66.1

## Election Summary

The summary of the election as shown:

•	There were 369,711 votes cast in the election.

•	The candidates were:

o	Charles Casper Stockham
o	Diana DeGette
o	Raymon Anthony Doane

•	The Candidate results were:

o	Charles Casper Stockham received 23.1% of the vote and 85,213 votes.
o	Diana DeGette received 73.8% of the vote and 272,892 votes.
o	Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.

•	The winner of the election was:

o	Diana DeGette, who received 73.8% of the vote and 272,892 votes.

•	Votes in this precinct were gathered from the following counties:
o	Jefferson
o	Denver
o	Arapahoe

### Voter Turnout by County

County               Vote Total        Percentage of Total

Denver County         306,055             82.8%
Jefferson County       38,855             10.5%
Arapahoe County        24,801              6.7%
 
County with highest vote total: Denver county with 82.8% of the total

### Challenge Overview

The election provided a clear cut winner; Ms. Diana DeGette as well as the county which provided the greatest
concentation of votes; Denver County.

Data items that were not considered in the analysis: 

1. Political Affiliation of each candidate to determine the number of votes by party
2. The number of registered voters within each county as compared to the number of actual voters to determine how many voters (total and as a percentage)
did or did not vote.


###Challenge Summary

This project involved the skills of: 

a. Development of a Python script to perform the required calculations
b. After calcalculation, write the results to the terminal as well as a text file. 


## Limitations of Dataset

As mentioned previously, an improved dataset would involve the following. The existing script could be used (with some modifications) for any election but would be enhanced 
by additional parameters. 

a. Political affiliation of each candidate
b. Number of registered voters within each county
c. A breakdown by age if that data is made possible
