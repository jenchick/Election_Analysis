# Election Analysis

## Project Overview
### Purpose
A Colorado Board of Elections employee requested an election audit of a recent local congressional election.  The audit tasks to complete are as follows:
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Election Audit Results
- There were 369,711 total votes cast in the election.
### By County
The analysis of the election indicates that:
- Counties in the Precinct:
    - Jefferson
    - Denver
    - Arapahoe
- The county results were:
    - Jefferson County placed 10.5% of the vote and 38,855 votes were cast.
    - Denver County placed 82.8% of the vote and 306,055 votes were cast.
    - Arapahoe County placed 6.7% of the vote and 24,801 votes were cast.
- The county with the largest number of votes was: 
    - Denver County
### By Candidate
- The candidates in the election were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote with 85,213 total votes.
    - Diana DeGette received 73.8% of the vote with 272,892 total votes.
    - Raymon Anthony Doane received 3.1% of the vote with 11,606 total votes.
- The winning candidate with the largest number of votes was: 
    - Diane DeGette

## Summary
I propose that the election commission use this type of script for future elections to report on county voter participation and election results.  The script can be easily modified to accomodate other types of elections if similar data is provided that can be 1.) mapped to the new CSV data file and 2.) modified with proper headers depending on the type of election (Local, County, City, State, etc.)

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1
