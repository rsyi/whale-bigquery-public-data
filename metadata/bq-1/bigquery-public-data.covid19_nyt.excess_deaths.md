# `covid19_nyt.excess_deaths`
`bq-1` | `bigquery-public-data`
Last update: As of Jan. 18, 2021, The New York Times are no longer updating this excess deaths dataset. We have updated data through the end of 2020 or as far as available.

The New York Times is releasing data that documents the number of deaths from all causes that have occurred during the coronavirus pandemic for 32 countries. We are compiling this time series data from national and municipal health departments, vital statistics offices and other official sources in order to better understand the true toll of the pandemic and provide a record for researchers and the public.

Official Covid-19 death tolls offer a limited view of the impact of the outbreak because they often exclude people who have not been tested and those who died at home. All-cause mortality is widely used by demographers and other researchers to understand the full impact of deadly events, including epidemics, wars and natural disasters. The totals in this data include deaths from Covid-19 as well as those from other causes, likely including people who could not be treated or did not seek treatment for other conditions.

We have used this data to produce graphics tracking the oubreak's toll and stories about the United States, Ecuador, Russia, Turkey, Sweden and other countries. We would like to thank a number of demographers and other researchers, listed at the end, who have provided data or helped interpret it.

## Column details
* [STRING]    `country`
* [STRING]    `placename`
* [STRING]    `frequency`
* [DATE]      `start_date`
* [DATE]      `end_date`
* [STRING]    `year`
* [INTEGER]   `month`
* [INTEGER]   `week`
* [INTEGER]   `deaths`
* [INTEGER]   `expected_deaths`
* [INTEGER]   `excess_deaths`
* [STRING]    `baseline`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
