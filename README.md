# Introduction

The voting data for each State is extracted from the States reported results for the 2016 General Election, as well as the voter registration data.  The candidates from the two dominant parties votes are reported, the candidates from other parties are combined into a single value, "All_others".

It's a work in progress. When the State is finished being processed the data will be pushed to the repo.

# Fields

candidate	: (string) <br>
votes	: (number) <br>
state	: (string) <br>
county : (string) <br>
longitude	: (float) point data <br>
latitude:	(float) point data <br>
registered_voters : (number)  Count as of November 2016, each state <br>
county_voter_ratio	: (float)  votes/registered_voters <br>
state_voter_ratio : (float) votes/state total registered voters <br>

# Usage

The data is provided without assuming any liability in any way whatsoever.

You may freely use this data in your own analytics; The only contingency is that you give me credit for the hard work I've done in compiling this information.  

  Lorren Kay.2018
  US General Election 2016 Results       

# Errors

I made best effort to ensure that the data is error free.  If you find an inaccuracy please put in an issue.
