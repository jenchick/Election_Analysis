# Election Analysis

## Project Overview
### Purpose
A Colorado Board of Elections employee requested an election audit of a recent local congressional election.  The audit tasks to complete are as follows:
1. Calculate the total number of votes cast.

![image](https://user-images.githubusercontent.com/102322707/168140848-eda5ba45-08bd-4e09-b23a-3a69d07f52f8.png)

2. Determine voter turnout for each county by:

    a.) Calculating the total number of votes for each candidate and county.
    
![image](https://user-images.githubusercontent.com/102322707/168141035-919cf131-39d0-41f0-8177-6361068e99bd.png)

![image](https://user-images.githubusercontent.com/102322707/168142426-e0f4e565-a4a9-451e-b53c-ad6df96c5de4.png)

    b.) Calculating the total percentage of votes for each candidate and county.
![image](https://user-images.githubusercontent.com/102322707/168140682-720c5c52-0fec-405f-8378-90cd8aaba84e.png)

![image](https://user-images.githubusercontent.com/102322707/168142666-fc454a20-c046-418c-9191-fcd278944825.png)


3. Determine the county and candidate with the most votes. 

![image](https://user-images.githubusercontent.com/102322707/168142964-39984864-9917-409a-9b26-ff01a8a46c41.png)

![image](https://user-images.githubusercontent.com/102322707/168142828-8fd3174c-426d-4d3f-9961-f67e8c43bd4b.png)


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

![image](https://user-images.githubusercontent.com/102322707/168140307-48ff1714-e9b5-4ffc-87a3-4ae10cce8d77.png)


## Summary
I propose that the election commission use this type of script for future elections to report on county voter participation and election results.  The script can be easily modified to accomodate other types of elections if similar data is provided that can be 1.) mapped to the new CSV data file and 2.) modified with proper headers depending on the type of election (Local, County, City, State, etc.)

![image](https://user-images.githubusercontent.com/102322707/168139973-11caa85d-0921-4a6a-b4f7-7b5174205d3b.png)

![image](https://user-images.githubusercontent.com/102322707/168140195-cdc4be3e-411e-4daa-a114-6544f373d704.png)

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.66.2
