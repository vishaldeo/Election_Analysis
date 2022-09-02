# Election_analysis

## Election Audit Overview
As a Data scientist/Analyst Engineer I was contacted by Colorado Board of Elections employees for analysis for local  congressional election.  They have clear requirement for the analysis and provide their requirement below :

### Scope of Requirement

 * How many votes were cast in this congressional election?
 * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
 * Which county had the largest number of votes?
 * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
 * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

### Resource Data for analysis  
  - Data Source: election_results.csv


## Election Audit Results

The Election data that was provided, below are the results :

* Calculate the total number of votes cast.

  - There were `369711` votes cast in the election.


* Calculate the total number of votes from each county and their percentage .

  - There are 3 County in the Colorado Election Board and below are their Vote Summary :

    ```python
    Jefferson County had 10.5% of the vote with 38,855 voters.

    Denver County had 82.8% of the vote with 306,055 voters.

    Arapahoe County had 6.7% of the vote with 24,801 voters.

* County with largest votes
    ```
      Denver County had the largest number of voters.


* Candidates vote share and percentage

    ```python
        Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
        Diana DeGette received 73.8% of the vote and 272,892 votes.
        Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.


*  Winner candidate analysis
      ```python
      The winner candidate is Diana DeGette, who received 73.8% of the vote and 272,892 votes.


## Election Audit Summary

This Colorado Election analysis tool is very useful to analysis with any election analysis. As currently we are analyzing for County and Candidates Voting percentage, based on the data provided it can be further enhanced other scenario :
  * Calculate the voting % by Zip Code
  * Voting for Entire US election by State
  * Voting distribution by Gender , Qualification , region


  This required minimal change in the Election analysis tool and the results can be achieved.
