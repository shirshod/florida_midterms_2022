## Miami-Dade, Hillsborough and Broward Midterm Election Results by Precinct

The codes in the repository scrape live election results for the midterm elections in [Miami-Dade](https://github.com/shirshod/florida_midterms_2022/blob/main/precinct_results/miamidade) (both Governor and Senate races), [Hillsborough](https://github.com/shirshod/florida_midterms_2022/blob/main/precinct_results/hillsborough) (only Governor race) and [Broward](https://github.com/shirshod/florida_midterms_2022/blob/main/precinct_results/broward) precincts (only Governor race).

The column names in the data frames are generated only after the results have been scraped, meaning that the codes are reusable for different races and the data frames dynamically size themselves according to the number of candidates or issues on the ballot. It does not matter how many candidates there are or in which order they appear. 

The codes then compute the vote shares of each candidate, generate the names of the candidates who are leading (or have won) and are runners-up, their party affiliations and their lead/win margins in each precinct. They also compute the leaders/winners and their vote-shares and lead/win margins for the entire county. 

The resulting dataframe for each race are then joined with previously prepared spreadsheets containing precinct-level demographic and voter registration data, and in the case of Miami-Dade, results from prior election cycles (2018 for the Governor race and 2016 for the Senate race).

The final dataframes powered the Miami Herald’s live election maps and were the foundations of and/or used in these stories (and the maps embedded in them):
1. [DeSantis wins reelection, ushering in a red-state era in Florida](https://www.miamiherald.com/news/politics-government/election/article268224252.html)
2. [DeSantis rides huge boost in Hispanic support to historic Miami-Dade victory](https://www.miamiherald.com/news/politics-government/election/article268242152.html)
3. [Florida Latinos catapulted Republicans in the 2022 election. Are they the outliers?](https://www.miamiherald.com/news/politics-government/article268644252.html)
4. [Live Updating: Miami-Dade Senate Election Results by Precinct](https://www.datawrapper.de/_/s1oZg/)
5. [Live Updating: Miami-Dade Gubernatorial Results by Precinct](https://www.datawrapper.de/_/WNk38/)
6. [Live Results: How Crist and DeSantis are doing in Miami-Dade county](https://www.datawrapper.de/_/JURCT/)
7. [Live Results: How Demings are Rubio are doing in Miami-Dade county](https://www.datawrapper.de/_/bH9pf/)
8. [Vote shares in Hispanic-majority precincts of select Florida counties](https://www.datawrapper.de/_/72L8M/)

#### Sources:

[Miami-Dade County Elections Department — Election Results](https://www.miamidade.gov/global/service.page?Mduid_service=ser1518638765310782)

[Miami-Dade County Elections Department — Precinct Demographics and Voter Registrations](https://www.miamidade.gov/elections/voter-statistics-current-archive.html)

[Hillsborough County Elections Department — Election Results](https://www.votehillsborough.gov/ELECTIONS/Election-Results)

[Hillsborough County Elections Department — Precinct Demographics and Voter Registrations](https://www.votehillsborough.gov/RESEARCH-DATA/Voter-Statistics)

[Broward County Elections Department](https://www.browardvotes.gov/)

[Broward County Precinct Demographics and Voter Registrations](https://www.browardvotes.gov/Records-Data/Voter-Statistics)


##### Note:
Websites showing live results generally switch over to the next election and may not be displaying the data for the elections being discussed here. Please use [Wayback Machine](https://archive.org/web/) to view archived versions of the dataframe. 
