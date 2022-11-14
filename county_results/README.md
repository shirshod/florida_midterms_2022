## Florida Midterm Election Results by County (2022)

By: Shirsho Dasgupta (2022)

The codes in the repository scrape live election results for [Governor]() and [US Senate]() races for each Florida county.

The column names in the dataframes are generated only after the results have been scraped, meaning that the codes are reusable for different races and the dataframes dynamically size themselves according to the number of candidates or issues on the ballot. It does not matter how many candidates there are or in which order they appear. 

The codes then compute the vote shares of each candidate, generate the names of the candidates who are leading (or have won) and are runners-up, their party affiliations and their lead/win margins in each county. They also compute the leaders/winners and their vote-shares and lead/win margins for the entire state. 

The resulting dataframe for each race are then joined with previously prepared spreadsheets containing results from the prior election cycle (2018 for the Governor race and 2016 for the Senate race). 

Sample final data frames can be found at:\
[Governor]()\
[US Senate]()

A data dictionary can be found [here](https://github.com/shirshod/florida_midterms_2022/blob/main/county_results/county_dictionary.pdf). 

The final dataframes powered the Miami Herald’s live election maps and were the foundations of and/or used in these stories (and the maps embedded in them):
1. [DeSantis wins reelection, ushering in a red-state era in Florida](https://www.miamiherald.com/news/politics-government/election/article268224252.html)
2. [Florida Gov. DeSantis’ victory secures star status. Next up: When to run for president](https://www.miamiherald.com/news/politics-government/election/article268224357.html)
3. [DeSantis rewrote the political map in Florida. Will the changes be permanent?](https://www.miamiherald.com/news/politics-government/state-politics/article268607662.html)
4. [Florida Latinos catapulted Republicans in the 2022 election. Are they the outliers?](https://www.miamiherald.com/news/politics-government/article268644252.html)
5. [Live Updating: Florida Senate Election Results by County](https://www.datawrapper.de/_/u2slr/)
6. [Live Updating: Florida Gubernatorial Results by County](https://www.datawrapper.de/_/2jFnd/)
7. [Live Results: How Crist and DeSantis are doing in Florida statewide](https://www.datawrapper.de/_/We3DK/)
8. [Live Results: How Demings and Rubio are doing in Florida statewide](https://www.datawrapper.de/_/v2ISI/)
9. [DeSantis made gains on 2018 vote share all across Florida](https://www.datawrapper.de/_/DmR4A/)

#### Sources:

[Florida Elections Watch Live Results — United States Senator](https://floridaelectionwatch.gov/ContestResultsByCounty/120000)

[Florida Elections Watch Live Results — Governor and Lieutenant Governor](https://floridaelectionwatch.gov/ContestResultsByCounty/160000)

[Florida 2018 Midterm Election Results — Governor and Cabinet](https://results.elections.myflorida.com/Index.asp?ElectionDate=11/6/2018&DATAMODE=)

[Florida 2016 General Election Results — Federal Offices](https://results.elections.myflorida.com/Index.asp?ElectionDate=11/8/2016&DATAMODE=)

##### Note: 
Websites showing live results generally switch over to the next election and may not be displaying the data for the elections being discussed here. Please use [Wayback Machine](https://archive.org/web/) to view archived versions of the dataframe. 
