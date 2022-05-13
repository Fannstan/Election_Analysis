# Election_Analysis 

## Project Overview
The Colorado Board of Elections has asked that we complete an election audit of a recent state - local congressional election. They asked that the audit include:

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7 and Visual Studio Code, 1.67

## Summary
The analysis of the election shows that: 
- There were 369,711 total votes cast


- The Candidates were: 
  -   Charles Casper Stockham
  -   Diana DeGette 
  -   Raymon Anthony Doane


- The Candidate results were: 
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes
  - Diana DeGette received 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes 


- The winner of the election was: 
  - Diana DeGette who received 73.8% of the vote and 272,892 votes 


## Challenge Overview
After presenting the candidate results from the initial election analysis to the Colorado Board of Elections, the Board requested that an additional analysis be conducted on the three counties that were involved in the local election, and to have that information included in the audit.  THe additional data requested was 
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout 

## Challenge Summary
The analysis of the county data shows that: 
- The counties included in the election were: 
  - Jefferson
  - Denver
  - Arapahoe 

- The county Results were: 
  - Jefferson with 10.5% of the turnout and 38,855 votes
  - Denver County with 82.8% of the turnout and 306,055 votes 
  - Arapahoe County with 6.7% of the turnout and 24,801 v

- The Largest County Turnout was:
-   Denver with 82.8% of the turnout and 306,055 votes 

The results of the analysis for candidate and county can also be found in the Analysis Folder, election_results.txt file. To view the entire script, please see PyPoll_Challenge.py file. 

## Audit Summary
The script that was used in this election audit, with some modificiations, can be used for other elections as needed.  For example, in the screen shot below the script was written to show only candidate options and votes and county options and votes.  

![Candidate_County_Options](https://user-images.githubusercontent.com/103215123/168339470-acd38e3a-f4b5-4a1c-bdb9-78b1e8660ff2.png)

In a state wide election, the voting district information may also need to be counted so in that case we would add district list and district votes dictionary. We would then add variables to use in getting information on each district, such as largest_district_name, largest_district_turnout, and winning_district_percentage. Using the same functions in the screenshot below for county vote count, the district vote count could then be determined: 

![County_vote_count](https://user-images.githubusercontent.com/103215123/168340802-60868f4e-c5c6-4392-8822-398138a2118e.png)

Additionally, the audit could also be modified to show the percentage of votes given to each candidate in each county or if the information was collected by the Board of Elections, the voter turnout by political party.  In the later case new lists and dictionaries as well as variables would need to be established for the various political parties recorded in the election and then put into similar formulas used to find voter turnout for each county or candidate.     

