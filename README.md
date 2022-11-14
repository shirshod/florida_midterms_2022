# US Midterm Elections, 2022: Florida Results

By: Shirsho Dasgupta (2022)

The codes in this repository scrape live election results for Governor and US Senate races for Florida. The results are scraped at two levels for both races (go to each folder for more details): 

[Precinct-level for Miami-Dade, Hillsborough and Broward counties]().\
[County-level for the entire state]().

The column names in the data frames are generated only after the results have been scraped, meaning that the codes are reusable for different races and the data frames dynamically size themselves according to the number of candidates or issues on the ballot. It does not matter how many candidates there are or in which order they appear. 

The codes then compute the vote shares of each candidate, generate the names of the candidates who are leading (or have won) and are runners-up, their party affiliations and their lead/win margins in each precinct or county. They also compute the leaders/winners and their vote-shares and lead/win margins for the entire county or state. 

The resulting dataframe for each race are then joined with previously prepared spreadsheets containing results from the previous election cycles (2018 for the Governor race and 2016 for the Senate race) and in the case of the precinct-level data, also demographic and political partisanship data for each precinct. 

The codes were set up to run every 10 minutes and write the final dataframes into a Google Sheet.

The final dataframes powered the Miami Herald’s live election maps and were the foundations of and/or used in these stories (and the maps embedded in them):
[DeSantis wins reelection, ushering in a red-state era in Florida](https://www.miamiherald.com/news/politics-government/election/article268224252.html)\
[DeSantis rides huge boost in Hispanic support to historic Miami-Dade victory](https://www.miamiherald.com/news/politics-government/election/article268242152.html)\
[Florida Gov. DeSantis’ victory secures star status. Next up: When to run for president](https://www.miamiherald.com/news/politics-government/election/article268224357.html)\
[DeSantis’ landslide catapults him into spotlight as GOP’s Trump alternative](https://www.miamiherald.com/news/politics-government/article268579667.html)\
[DeSantis rewrote the political map in Florida. Will the changes be permanent?](https://www.miamiherald.com/news/politics-government/state-politics/article268607662.html)\
[Live Updating: Florida Senate Election Results by County](https://www.datawrapper.de/_/u2slr/)\
[Live Updating: Florida Gubernatorial Results by County](https://www.datawrapper.de/_/2jFnd/)\
[Live Updating: Miami-Dade Senate Election Results by Precinct](https://www.datawrapper.de/_/s1oZg/)\
[Live Updating: Miami-Dade Gubernatorial Results by Precinct](https://www.datawrapper.de/_/WNk38/)
[Live Results: How Crist and DeSantis are doing in Florida statewide](https://www.datawrapper.de/_/We3DK/)\
[Live Results: How Demings and Rubio are doing in Florida statewide](https://www.datawrapper.de/_/v2ISI/)
[Live Results: How Crist and DeSantis are doing in Miami-Dade county](https://www.datawrapper.de/_/JURCT/)\
[Live Results: How Demings are Rubio are doing in Miami-Dade county](https://www.datawrapper.de/_/bH9pf/)\
[DeSantis made gains on 2018 vote share all across Florida](https://www.datawrapper.de/_/DmR4A/)


#### Sources:
[Miami-Dade County Elections Department — Election Results](https://www.miamidade.gov/global/service.page?Mduid_service=ser1518638765310782)\

[Miami-Dade County Elections Department — Precinct Demographics and Voter Registrations](https://www.miamidade.gov/elections/voter-statistics-current-archive.html)\

[Hillsborough County Elections Department — Election Results](https://www.votehillsborough.gov/ELECTIONS/Election-Results)\

[Hillsborough County Elections Department — Precinct Demographics and Voter Registrations](https://www.votehillsborough.gov/RESEARCH-DATA/Voter-Statistics)\

[Broward County Elections Department](https://www.browardvotes.gov/)\

[Broward County Precinct Demographics and Voter Registrations](https://www.browardvotes.gov/Records-Data/Voter-Statistics)\

[Florida Department of State, Division of Elections](https://results.elections.myflorida.com/)\

[Florida Elections Watch Live Results](https://floridaelectionwatch.gov/)
