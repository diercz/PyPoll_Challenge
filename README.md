# Module 3 PyPoll_Challenge
## Overview of Election Audit

The purpose of the PyPoll Challenge was to assist the Colorado Board of Election employees with an election audit of a recent local congressional election.  We were provided a CSV file with the voter ID, candidate that was voted for and the county the vote came from.  With the data provided we were to utilize python and Visual studio to determine the winner of the election, the percentage of votes each candidate received and the number of votes per candidate.  The second portion of the challenge was to determine the number of votes totaled per county, percentage of the total votes overall and which county had the largest voter turnout.  

## Election-Audit Results

- The total number of votes cast in the election totaled 369,711.
    - Breakdown of votes cast per county and percentage of the overtotal:
        - Jefferson: 38,855; 10.5%
        - Denver: 306,055; 82.8%
        - Arapahoe: 24,801; 6.7%
    - Through the analysis Denver County had the largest total number of voters per the data set for the challenge
    - Breakdown of votes cast per candidate and the percentage of the overall total:
        - Charles Casper Stockholm: 85,213; 23.0%
        - Diana DeGette: 272,892; 73.8%
        - Raymon Anthony Doane: 11,606; 3.1%
    - The winner of the election was Diana Degette with 272,892 votes.  Diana received 73.8% of the overall votes cast in the congressional election.

## Election-Audit Summary

This script is built to produce votes cast for each candidate and provide the number votes and percentage each received during the election.  It also is built to pull in statistical information on where the votes were cast from by county.  In any election moving forward the election committe is able open any csv file with the same data set and can produce the results of the election instantly vs counting the votes or utilizing excel to generate the results.  This will save everyone time and effort in waiting for the results to be counted.  

If requested the script can be modified to produce further results if needed.  One example would be to provide the percentage of votes cast in each county per candidate to provide more context of the geographical area and what counties were voting for each candidate.  Another way the script could be modified is if we received more data with the csv file to provide further detail on the votes cast.  If we were provided cities that the votes were cast we will be able to provide further statistical analysis and narrow down the geographical terriroty of what areas were voting for each candidate as well.  

