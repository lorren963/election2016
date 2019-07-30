# Introduction

The voting results for the 2016 General Election pulled from the State report(s).  Voter registration data is included by county.  
The two candidates representing the primary political parties are reported.  All other political parties are aggregated into a single value, "All_others".

It's a work in progress.  More States will be pushed to the repo once they have been converted.

# Fields

candidate	: (string) <br>
votes	: (number) <br>
state	: (string) <br>
county : (string) <br>
longitude	: (float) point data <br>
latitude:	(float) point data <br>
registered_voters : (number) as reported by the State per county as of November 2016 <br>
county_voter_ratio	: (float)  votes/registered_voters <br>
state_voter_ratio : (float) votes/state total registered voters <br>

# Usage

You may freely use the data in your own analytics. I request only that if this data is used as a source for any publication that I am cited as the originator. Thanks!

  Lorren Kay
  US General Election 2016 Data - Votes by County

# Errors

I made best effort to ensure that the data is error free.  But mistakes happen so if you find an error or inaccuracy, please put in an issue so I can fix it.
