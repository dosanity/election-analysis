# Election Analysis

## Project Overview
We are tasked by a Colorado Board of Elections employee to complete the election audit of a recent local congressional election. We are reporting the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on popular vote. We are looking to automate the process using Python so that we can use the code to audit other congressional districts, senatorial districts, and local elections. In this analysis, we will research three different voting methods: Mail-in ballots, punch cards, and Direct Recording Electronic (DRE) counting machines. Mail-in ballots are typically hand counted at the central office. Punch cards are collected and then fed into a machine that tabulates vote totals and sends the results to the central office. Finally, memory cards from DRE counting machines are sent to the central office and read by a computer. The votes cast by these three methods will determine the final election results. We are generating a vote count report to certify the U.S. congressional race.

We are given the following tasks:
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources

+ Data Source: election_result.csv
+ Software: Python 3.10, Visual Studio 1.69.2

## Summary 
The analysis of the election show that:
+ There were 369,711 votes casted in the election.
+ The candidates were: 
  + Charles Casper Stockham
  + Diana DeGette
  + Raymon Anthony Doane
+ The candidate results were:
  + Charles Casper Stockham received 23.0% of the votes and 85,213 number of votes.
  + Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  + Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.
+ The winner of the election was:
  + Diana DeGette, who received 73.8% of the votes and 272,892 number of votes.
  
## Challenge Overview
The Colorado Board of Elections has requested additional data to complete the election audit of a recent local congressional election. 

We are given the following tasks: 
1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes from each county out of the total count.
3. Determine the county with the highest turnout.

## Challenge Summary
The analysis of the counties in the election show that:

+ The county results were:
  + Jefferson received 10.5% of the votes and 38,855 number of votes.
  + Denver received 82.8% of the votes and 306,055 number of votes.
  + Arapahoe received 6.7% of the votes and 24,801 number of votes.
+ The largest county turnout was:
  + Denver, which received 82.8% of the votes and 306,055 number of votes.
