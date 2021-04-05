# Election_Analysis

## Election Analysis Overview
A Colorado Board of Elections employee requested an election audit of a recent, local congressional election. The purpose of this election audit was to determine if the election results can be automated via python (versus excel). Since we are successful in its automation, it will go on to audit future elections for not only congress, but also senetorial + local elections.

The audit entailed the following: 
1. Calculation of total number of votes cast
2. Complete list of candidates who recieved a vote
3. Calculation of the total number of votes each candidate recieved
4. Percentage calculation of votes each candidate won
5. Winner determination based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6; Visual Studio Code 

## Canditate Winner Results:
The election analysis shows the following:
- There were 369,712 of votes cast
- List of candidates that recieved votes: 
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- Candidate results by percentage and number
  - Charles Casper Stockham received 23.0%, with a number of 85,213 total votes
  - Diana DeGette received 73.8% of the vote, with a number of 272,892 total votes
  - Raymon Anthony Doane received 3.1% of the vote, with a number of 11,606 total votes
The winner of the election based on popular vote was Diane DeGette, having 73.8% of the vote and 272,892 total votes

## Election-Audit Overview Cont.
 Seth and Tom were pleased with the primary election audit results to the election committe, but, decided to go furthur and requested additional data to complete the audit

The additional data requests as follows:
1. Voter turn out for each county
2. Percentage of votes from each county out of the total count
3. The county with the highest turn out

## Resources
- Data Source: election_results.csv
- Software: Pythom 3.7.6; Visual Studio Code

## County Results:
Here is the additional data which completes the audit:
- Voter turn out for each county
  - Jefferson: 38,855
  - Denver: 306,055
  - Arapahoe: 24,801
- Percentage of votes by each county
  - Jefferson: 10.5%
  - Denver: 82.8% 
  - Arapahoe: 6.7%
- The county with the highest voter turn out by total count and percentage was Denver

## Election Audit Summary
Overall, I propose that the election commission use this script for local and senatorial elections.
