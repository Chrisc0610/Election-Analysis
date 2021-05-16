# Election Analysis

## Overview of Project
To help Colorado's Board of Elections employee complete and audit for a recent congressional election. The following tasks below explain the steps taken to 
properly analyze the election data.

- Calculate the total number of votes cast.
- Get a complete list of candidates who received votes. 
- Calculate the total number of votes each candidate recieved.
- Determine the largest county turnout.
- Calculate the percentage of votes each candidate won
- Determine the winner of the election.
	

## Election-Audit Results
The results for the Election-Audit are explained in the bullets below.

- How many votes were cast in this congressional election? 
	* The total votes casted in this election was 369,711

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
	* out of the Total Votes of 369,711 each County's number of votes and percentages are below
		* Jefferson: had 38,855 votes with the percentage of 10.5% of the Total Vote count.
		* Denver: had 306,005 votes with the percentage of 82.8% of the Total Vote count.
		* Arapahoe: had 24,801 votes with the percentage of 6.7% of the Total Vote count.

- Which county had the largest number of votes?
	* The county with the largest turn out is Denver.
	
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received
	* Below is the breakdown of votes per candidate along with the percentage of the total votes.
		* Charles Casper Stockham: had 85,213 votes with the percentage of 23.0% of the Total Vote count.
		* Diana DeGette: had 272,892 votes with the percentage of 73.8% of the Total Vote count.
		* Raymon Anthony Doane: had 11,606 votes with the percentage of 3.1% of the Total Vote count.

.
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
	* the winning candidate was Diana Degette with a total Vote Count of 272,892. The calculated percentage of votes is 73.8%

	
## Summary
I believe that this script may be used not only for auditing this congressional board for Colorado but for any State, Country or any voting pool.
Based on our outcomes from the Colorado audit we can see that with this script, we are able to parse through an immense amount of data in a matter 
of seconds. Not only are we able to get the percentage outcomes for each candidate, but what if half way through the race another candidate decides to 
run for office? Well by simply adding the information to our current CSV file the script will automatically add the new candidate names and counties 
to our outcome. Refer to the image below, notice that 3 new candidates from 3 separate counties have joined this election. The script went ahead and 
added the calculations for the votes.
-[sample1](resources/sample1.PNG)


Futhermore, with the past election there were rumors that the election was rigged and that every vote should be counted. Well with this script
we can assure that all ballots will be accounted for. The most simple way to do this is by simply adding a new variable to load data from. By looking at
the example below we can see that our list of candidates for smaller while our list for counties got much bigger. This is a sample of how the script would run 
with a different data set. 


Please note if you were to do it on a country level, the "county" variable would be switched to "states".
