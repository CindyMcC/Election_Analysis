# Election_Analysis

## Overview of Election Audit 

This analysis is to audit the election results for a US Congressional district in Colorado and determine the winning candidate based on vote counts.  The votes are a combination of mail in, punch cards, and DIR votes which were combined into a csv file.
  

## Election Audit Results 
The election_results.csv file was used to calculate vote totals.  The votes are from three counties and there are three candidates vying for the Congressional seat.  

*	The total votes were 369,711 based on the file.  No rows from the file were eliminated due to invalid data.

*	A breakdown of each county’s vote total is provided with the percentage of the total votes indicated.  Denver had the highest turnout with over 82% of the votes.


*	The three candidates are listed with their total votes and percentages.


*	Diana DeGette was the winner with 272,892 votes, which is 73.8% of the total.


## Election Audit Summary 
This Python script can be used for any election where an automated method of validating vote counts is needed.  The file_load statement can easily be modified to use a different file name.  The script currently is written to use a csv file type, but can be changed to use a different type by rewriting the load and the reader statements.
