# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage o votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.7, Visual Studio Code, 1.49.3

## Summary
The analysis of the election show:
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
After reviewing the election audit material submitted above, the Colorado Board of Elections has requested the following additional information:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.7, Visual Studio Code, 1.49.3

## Challenge Summary
The expanded analysis yielded the following results:
- There were 369,711 votes cast in the election.

- The breakdown of the votes by county are as follows:
    - Jefferson: 10.5% of total votes | vote count = 38,855
    - Denver: 82.8% of total votes | vote count = 306,055
    - Arapahoe: 6.7% of total votes | vote count = 24,801
    
- The Denver county had the largest voter turnout.

The following is an image representation of the results.

![Election Results](https://github.com/MattK1454/Election_Analysis/blob/master/Resources/Election_results.png)

Suggested further applications of election analysis script:
Regarding the possible uses of this election script, I would suggest:

1. The script might be modified to report the percentage and count of each candidates votes for each of the counties analyzed in this audit.
2. The script might be modified to report on the ballots for each county in order to report the voter ballot ids used in each county to look for possibility of replicated or missing ballots by building a list and checking for missing ballots or replications of ballot ids.

## Resources

1. Module 3 Challenge. (n.d.). Retrieved October 03, 2020, 
from https://courses.bootcampspot.com/courses/453/assignments/5589

2. Find Your&nbsp;. (n.d.). Retrieved October 04, 2020, 
from https://www.citationmachine.net/apa/cite-a-website
