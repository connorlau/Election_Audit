# Election Audit Using Python
This code is used to process voting data, which it then uses to output various results of the election. These results describe the distribution of votes among candidates and the distribution of voters among counties. 
## Election Results

###### Total Votes
- There were 369,711 votes cast in total

###### Distribution of Voters Among 3 Counties
- Denver County had the greatest number of voters (306,055), accounting for 82.8% of all voters
- Jefferson County had the second most voters (38,855), accounting for 10.5% of all voters
- Arapahoe County had the least voters (24,801), accounting for 6.7% of all voters

###### Candidate Results
- Diana DeGette won the election with 272,892 votes, winning 73.8% of all votes
- Charles Casper Stockham was the runner up with 85,213 votes, winning 23.0% of all votes
- Raymon Anthony Doane came in last with 11,606 votes, winning 3.1% of all votes

## Election Audit Summary
This code can be used to calculate the results of any election given a set of tabular voting data. However, in elections with a more complex system (i.e the Electoral College), it may require additional modifications. In the example of an Electoral College system, this script must be changed to first assign votes to a state. After the winner of a state is determined by the initial code, the given value of states can be assigned to their winning candidates, which allows for the determination of the winning candidate. 

This script can be used to calculate various voting statistics other than the county to which each voter belongs. With additional data and further modifications, the County script section of the code can be modified to show voting statistics according to race, gender, economic, etc. 
