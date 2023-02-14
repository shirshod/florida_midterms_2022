## Miami-Dade County Midterm Election Results — U.S. Senator (2022)

By: Shirsho Dasgupta (2022)

The code in this repository scrapes precinct-level election results for the Senate race in Miami-Dade county. 

It does it in two ways (which yields the same result):
1. [Directly scraping the webpage](https://github.com/shirshod/florida_midterms_2022/blob/main/precinct_results/miami-dade/dade_senate/senate_dade_scraper.ipynb).
2. [Downloading the periodic report and then scraping that](https://github.com/shirshod/florida_midterms_2022/blob/main/precinct_results/miami-dade/dade_senate/senate_dade_reports.ipynb). This is a backup. 

The column names in the dataframe are generated only after the results have been scraped, meaning that the code is reusable for different races and the dataframe dynamically sizes itself according to the number of candidates or issues on the ballot. It does not matter how many candidates there are or in which order they appear. 

The code then computes the vote shares of each candidate, generates the names of the candidates who are leading (or have won) and are runners-up, their party affiliations and their lead/win margin in each precinct. It also computes the leader/winner and their vote-share and lead/win margin for the entire county. 

The resulting dataframe for each race is then joined with previously prepared spreadsheets containing precinct-level demographic and voter registration data.

A sample final dataframe can be found [here]().

A data dictionary can be found [here](). 

The final dataframe was the foundation of and/or used in these stories and visualizations:

1. [DeSantis rides huge boost in Hispanic support to historic Miami-Dade victory](https://www.miamiherald.com/news/politics-government/election/article268242152.html)
2. [Live Updating: Miami-Dade Senate Election Results by Precinct](https://www.datawrapper.de/_/s1oZg/)
3. [Live Results: How Demings are Rubio are doing in Miami-Dade county](https://www.datawrapper.de/_/bH9pf/)


#### Sources:

[Miami-Dade County Elections Department — Election Results](https://enr.electionsfl.org/DAD/3267/Precincts/44786/0/1052/)

[Miami-Dade County Elections Department — Election Results Reports](https://enr.electionsfl.org/DAD/3267/Reports/)

[Miami-Dade County Elections Department — Precinct Demographics and Voter Registrations](https://www.miamidade.gov/elections/voter-statistics-current-archive.html)

##### Note:
Websites showing live results generally switch over to the next election and may not be displaying the data for the elections being discussed here. Please use [Wayback Machine](https://archive.org/web/) to view archived versions of the dataframe. 
