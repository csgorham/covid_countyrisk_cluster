# covidmobility_tdi


COVID19 affected our lives over the 1.5 year on a global scale, and in every minute way that we function throughout our days. In particular, our mobility changed as we were told to shelter in place and maintain our distance from everyone. Large amounts of data were collected during this time to not only monitor the virus, but also how human beings have reacted to it. Two of the datasets used in this project are publicly on Goolge Cloud’s BigQuery, and a third dataset provides the voting tallies per county for democrats and republicans in the 2020 US election. 

The overarching goal of this project is to assess how counties responded to COVID19 via changes in their mobility, mask usage, and vaccination roll-out. There will be an effort made to perform regression techniques to predict mask usage in all counties based on republican and democratic voting in the 2020 presidential election.


(1)	The  “Mobility Dataset” provides daily reports on how movement trends have changed in response to COVID19 policies, in every county of the United States and also globally. Particular categories studied are retail and recreation, groceries and pharmacies, parks, transit. Stations, workplace and residential.

Initial analysis of the five boroughs in New York City shows that, owing to COVID19 policies, retail/recreation and transit mobility dropped from its baseline by more than 80% during April 2020 and have remained below baseline since with a subsequent major drop during a second-wave. In contrast, mobility in frequenting parks dropped below baseline initially during April 2020 but has increased by upwards of 150% since. Moving beyond NYC, a first outcome of this project is to produce a ` folium’ mapping visualization of mobility trends, for each sector, as a function of US county over time. This will enable an assessment of how different locales responded, and the degree to which the cities, regions, and the whole US body was able to act in unison in the face of the COVID19 threat. 

Using the same dataset, the analysis of the degree in harmony of response will be compared with other regions around the globe which have been given the title of having the “best global responses:” Taiwan, Singapore and South Korea. Unlike the United States, these nations are very near to China and made early and aggressive moves by the government to use the powers of the state to enforce strict regulations. 

https://time.com/5851633/best-global-responses-covid-19/

(2)	The “Mask Use By County” provides data on if masks are used ‘never,’ ‘rarely,’ ‘sometimes,’ ‘frequently,’ or ‘always’ via the county FIPS codes. This data has 3142 rows  covering all US counties. This data will be coupled with the percentage of republican and democratic votes cast in the “2020 election”, per county, and split into train and test sets such that machine learning techniques may be able to predict mask usage tendency as a function of political leaning. This may provide insight in the realms of social psychology.

