# Election_Analysis

## Overview of Election Audit
The purpose of this election audit was to determine a few metrics regarding this election data. First, the data was used to determine the votes each of the 3 candidate recieves. This was used to determine the winner of the election.

Next, the total votes were grouped by county in which the votes came from. This data was then used to determine the county that had the largest voter turnout. 

These metrics were then displayed so the user so they could view the results of the election.

## Election-Audit Results
Based on the analysis of the election data, a few results can be highlighted. 

The total votes in the election was 369,711 votes.

The breakdown for each county and their votes as well as their percentage of the total vote is...
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

From this, the county with the largest voter turnout was Denver County. 

The breakdown for each candidate and their votes as well as their percentage of the total vote is...
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

From this, the winner of the election was Diana DeGette, with 272,892 votes which accounts for 73.8% of the total votes.

## Election-Audit Summary
This Election-Audit provides a script that can be used to help future campaigns in this area make informed decisions.
First, the county with the most voter participation is Denver County. If a candidate hopes to win this election, campaign strategies should target this county to maximize the amount of votes that candidate recieves.

This script was created in a way that it can be modular and used for any district. The declared variables are open ended and are filled in based on the csv file the script is given. That means that if a district has many more counties or more candidates, the script will still function as intended. If we are given a csv file where the columns are in a different order, the script can be easily changed to access a different column to pull out the appropriate county or candidate name. 

One thing that could be added to this script that would greatly benefit a campaign team would be to determine the percentage of votes each candidate recieved based on county. This can be adjusted in the code to track the county of each vote with respect to the candidate. So every time a candidate gains a vote, a tally will be made for each county within that candidates votes. This would show how successful each candidate was in each county. As I previously mentioned, if a future campaign where to run for election in this district, they should focus their efforts on Denver County. If this addition to the code is added, I would imagine that Diana DeGette (This election winner) recieved the most amount of votes from Denver County. 
