# School_District_Analysis
Module 4 Curriculum Repository

**Purpose & Overview**: 

## School Distr Analysis Results

The following bulleted lists provide the outcomes of the Election Audit Analysis, which may also be viewed via .txt file with this folder: [Analysis](https://github.com/deltaLyd/PyPoll_Challenge/tree/main/Analysis)

**Election Results**

• Total Votes: 369,711

**County Votes**

• Jefferson: 10.5% (38,855)

• Denver: 82.8% (306,055)

• Arapahoe: 6.7% (24,801)


**Largest County Turnout** 

Denver

**Election Results by Candidate**

• Charles Casper Stockham: 23.0% (85,213)

• Diana DeGette: 73.8% (272,892)

• Raymon Anthony Doane: 3.1% (11,606)

**Election Winner Statistics**

• Winner: Diana DeGette

• Winning Vote Count: 272,892

• Winning Percentage: 73.8%

## Recommendations to Colorado Board of Elections
### Adapting Code for Use in Auditing all State Elections

Ladies and gentlemen, while the code I have delivered for you is specifically tailored to the precint you requested an analysis of, I can (for a reasonable consulting fee), adapt the code to be applicable to all voting precints in the state of Colorado, that you may have the same confidence in the data you use to conduct you audit(s) for all precincts.  The two main changes I would make are:

1) Altering the "file_to_load" syntax in line 9 to merge multiple CSV files, even if the formatting is different (from all reporting precincts), so the program can run on the entire state's results. 

2) As the purpose of the election audit is to verify the results, I would also recommend including an analysis of the BallotID information, to ensure that each BallotID is only casting 1 vote, and only voting in 1 precinct.
