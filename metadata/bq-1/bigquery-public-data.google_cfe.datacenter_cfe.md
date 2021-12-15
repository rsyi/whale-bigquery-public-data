# `google_cfe.datacenter_cfe`
`bq-1` | `bigquery-public-data`
Carbon-free energy (CFE) scores for Google Cloud regions and other Google data center regions

## Column details
* [INTEGER]   `year`
  - The year for which the Google CFE metric has been aggregated. We will continue to add new data for each year as we make progress. Note that the Google CFE metric will only be included for the years that the Cloud Region or Data Center was operational. For example, the Data Center in Denmark came online in 2020, so the Google CFE data for that region starts in 2020 (and there is no data for Denmark for 2019).
* [STRING]    `cfe_region`
  - The regional boundary of the electric grid we consider when calculating the Google CFE score. For most of the world, the CFE region is defined as the country. However, for countries that have distinct grids, such as the US, there are multiple CFE regions, which are defined by the balancing authority.
* [STRING]    `zone_id`
  - This is the ID associated with the CFE Region based on Tomorrow's ElectricityMap API definition. (http://static.electricitymap.org/api/docs/index.html#zones)
* [STRING]    `cloud_region`
  - The Google Cloud Region that is mapped to the CFE region. For Google Data Centers that are not Cloud Regions, the region will be labeled 'non-cloud-data-center'.
* [STRING]    `location`
  - This is the "friendly name" of the Cloud Region. For Google Data Centers that are not Cloud regions, the location will be the country (non-US) or the state (US) that the Data Center is located in.
* [FLOAT]     `google_cfe`
  - This metric is calculated for every hour in every region and tells us what percentage of the energy we consumed during an hour that is carbon-free. We take into account the carbon-free energy that's already supplied by the grid, in addition to the investments we have made in renewable energy in that location to reach our 24/7 carbon-free objective (https://www.gstatic.com/gumdrop/sustainability/247-carbon-free-energy.pdf). We then aggregate the available average hourly CFE percentage for each region for the year. We do not currently have the hourly energy information available for calculating the metrics for all regions. We anticipate rolling out the calculated metrics using hourly data to regions as the data becomes available.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
