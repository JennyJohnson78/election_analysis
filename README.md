# Election Analysis
## Project Overview
A Colorado Board of Elections employee has requested an election audit of a recent local congressional election.

- How many votes were cast in this congressional election?
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
- Which county had the largest number of votes?
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

### Resources
Data Source: election_results.csv
Software: Python 3.8.8 and Visual Studio Code 1.61.0

## Analysis
- 369,711 votes were cast in this congressional election

![image](https://user-images.githubusercontent.com/67409852/136733788-4215823a-d5db-4af2-9b79-7084a302616c.png)

-The three counties that were audited were Arapahoe, Denver, and Jefferson counties. Arapahoe residents cast 24,801 votes, or 6.7% of the total votes. Denver residents cast 306,055 or 82.8% of the total votes, and Jefferson residents cast 38,855 or 10.5% of the total votes.

![image](https://user-images.githubusercontent.com/67409852/136734145-21d2145c-7255-4596-8464-cfa241cf4792.png)

- Denver had the largest number of votes:

![image](https://user-images.githubusercontent.com/67409852/136734257-8c2a9907-085a-4ce7-89ca-83c28529f456.png)

-The three candidates are: Diana DeGette, Charles Casper Stockham, and Raymon Anthony Doane. DeGette received 272,892 votes, accounting for 73.8% of the vote. Stockham received 85,213 votes, or 23% of the vote. Doane received 11,606 votes, or 3.1% of the vote.

![image](https://user-images.githubusercontent.com/67409852/136734540-a2673b92-a255-48bb-bff3-fee5e09aef67.png)

-Diana DeGette won the election. Her vote count was 272,892, or 73.8% of the vote.

![image](https://user-images.githubusercontent.com/67409852/136734675-2eed9b4a-6f07-42b8-9598-c3e7edc31321.png)

## Summary
This script can be used, with some modifications, for any election. Because this code is DRY (does not repeat code chunks unnecessarily) and can be easily changed to fit any election, it can be used again and again in any state, or at the national level. For instance, if a larger dataset of election data needed to be audited, like a national election, information can be extracted by creating additional variables to be iterated through. In addition, while this audit only shows the county with the largest number of votes, this code can be easily written, using the same template, to find the county (or state, if looking at national election data) that has the lowest number of votes. The possibilities for this code is endless and takes the guesswork out of election audits.
