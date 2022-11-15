The code in this repository scrapes precinct-level election results for the Governor race in Hillsborough county. 

The column names in the dataframe are generated only after the results have been scraped, meaning that the code is reusable for different races and the dataframe dynamically sizes itself according to the number of candidates or issues on the ballot. It does not matter how many candidates there are or in which order they appear. 

The code then computes the vote shares of each candidate, generates the names of the candidates who are leading (or have won) and are runners-up, their party affiliations and their lead/win margin in each precinct. They also compute the leader/winner and their vote-share and lead/win margin for the entire county. 

The resulting dataframe for each race is then joined with previously prepared spreadsheets containing precinct-level demographic and voter registration data.

A sample final dataframe can be found [here]().

A data dictionary can be found [here](). 

The final dataframe was the foundation of and/or used in this story and table:
1. [Florida Latinos catapulted Republicans in the 2022 election. Are they the outliers?](https://www.miamiherald.com/news/politics-government/article268644252.html)
2. [Vote shares in Hispanic-majority precincts of select Florida counties](https://www.datawrapper.de/_/72L8M/)

#### Sources:
[Hillsborough County Elections Department — Election Results](https://enr.electionsfl.org/HIL/3311/Precincts/46493/0/447/)

[Hillsborough County Elections Department — Precinct Demographics and Voter Registrations](https://www.votehillsborough.gov/Portals/Hillsborough/Documents/Current%20Voter%20Statistics/2022/September%202022/September%20Summary%20Precinct%20Demographic%20Analysis.pdf)

##### Note:
Websites showing live results generally switch over to the next election and may not be displaying the data for the elections being discussed here. Please use [Wayback Machine](https://archive.org/web/) to view archived versions of the dataframe. 
