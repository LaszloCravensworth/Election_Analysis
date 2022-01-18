# Election_Analysis

## Project Overview
&nbsp;&nbsp;&nbsp; A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.
<br />
1. Calculate the number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
&nbsp;&nbsp;&nbsp;* Data Source: election_results.csv
<br />
&nbsp;&nbsp;&nbsp;* Software: Python 3.9.7 64-bit, Visual Studio Code, 1.63.2

## Summary

&nbsp;&nbsp;&nbsp; The analysis of the election shows that:
* There were 369,711 votes cast in the election.
* The candidates were:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; * Charles Casper Stockham

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; * Diana Degette

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; * Raymon Anthony Doane

* The candidate results were:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *Candidate Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *Candidate Diana Degette received 73.8% of the vote and 272,892 number of votes.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *Candidate Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes

## Overview

&nbsp;&nbsp;&nbsp; The challenge here was to submit additional data to the Colorado Board of Elections for an election audit.  The requested data was to include:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1) The voter turnout for each county
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2) The percentage of votes from each county out of the total count
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3) The county with the highest turnout

&nbsp;&nbsp;&nbsp;I worked through the election_results.csv file, used for loops and conditional statements, with membership and logical operators to find the requested results. Then I printed everything to the election_results.txt file.  This provided me with all of the data I needed to write a written analysis of final vote counts.

## Summary
&nbsp;&nbsp;&nbsp;The additional information the Colorado Board of Elections was asking for wasn't too difficult to extract.  I was able to take previous code for the individual candidates and expand on it. Here I will demonstrate the new code and how it integraded with realative ease.

&nbsp;&nbsp;&nbsp;In this code I was able to add an empty list and dictionary for the county names.  I also initialized a counter for the largest voter turn out. Within the "for row in reader:" loop I started extracting the county name in each row. This was all very similar in how I counted through all of the candidates, found the number of votes, percentages and outcomes.
<br />
<br />
<br />
![code1](https://github.com/LaszloCravensworth/Election_Analysis/blob/main/Resources/Results_code_1.png)
<br />
<br />
&nbsp;&nbsp;&nbsp;Here I expanded on the for loop with an if statement. This adds county names and starts counting up the totals. I was then able to write the results to the election_results.txt file.
<br />
<br />
<br />
![code2](https://github.com/LaszloCravensworth/Election_Analysis/blob/main/Resources/Results_code_2.png)
![code3](https://github.com/LaszloCravensworth/Election_Analysis/blob/main/Resources/Results_code_3.png)
<br />
<br />
&nbsp;&nbsp;&nbsp;This made a clear presentation of the candidate and county voter turnout, percentages, largest county turnout and of course the winner of the election. The results put Denver county as the largest county turnout which represented a huge 82.8% of the votes.  The winner of the election was Diana DeGette with a 73.8% win over her opponents.  It's safe to say that Diana DeGette received most of her votes from Denver County. The Board of Colorado Elections presented with the additional data they requested for their audit.
<br />
<br />
![results](https://github.com/LaszloCravensworth/Election_Analysis/blob/main/Resources/Election_results.png)
