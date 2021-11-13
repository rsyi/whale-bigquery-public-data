# `sunroof_solar.solar_potential_by_censustract`
`bq-1` | `bigquery-public-data`
Sunroof Solar Potential By Census Tract

## Column details
* [STRING]    `region_name`
  - Census Tract
* [STRING]    `state_name`
  - Name of the state containing that region
* [FLOAT]     `lat_max`
  - maximum latitude for that region
* [FLOAT]     `lat_min`
  - minimum latitude for that region
* [FLOAT]     `lng_max`
  - maximum longitude for that region
* [FLOAT]     `lng_min`
  - minimum longitude for that region
* [FLOAT]     `lat_avg`
  - average latitude for that region
* [FLOAT]     `lng_avg`
  - average longitude for that region
* [FLOAT]     `yearly_sunlight_kwh_kw_threshold_avg`
  - 75% of the optimimum sunlight in the county containing that zip code
* [INTEGER]   `count_qualified`
  - # of buildings in Google Maps that are suitable for solar
* [FLOAT]     `percent_covered`
  - % of buildings in Google Maps covered by Project Sunroof
* [FLOAT]     `percent_qualified`
  - % of buildings covered by Project Sunroof that are suitable for solar
* [INTEGER]   `number_of_panels_n`
  - # of solar panels potential for north-facing roof space in that region, assuming 1.650m x 0.992m panels
* [INTEGER]   `number_of_panels_s`
  - # of solar panels potential for south-facing roof space in that region, assuming 1.650m x 0.992m panels
* [INTEGER]   `number_of_panels_e`
  - # of solar panels potential for east-facing roof space in that region, assuming 1.650m x 0.992m panels
* [INTEGER]   `number_of_panels_w`
  - # of solar panels potential for west-facing roof space in that region, assuming 1.650m x 0.992m panels
* [INTEGER]   `number_of_panels_f`
  - # of solar panels potential for flat roof space in that region, assuming 1.650m x 0.992m panels
* [INTEGER]   `number_of_panels_median`
  - # of panels that fit on the median roof
* [INTEGER]   `number_of_panels_total`
  - # of solar panels potential for all roof space in that region, assuming 1.650m 0.992m panels
* [FLOAT]     `kw_median`
  - kW of solar potential for the median building in that region (assuming 250 watts per panel)
* [FLOAT]     `kw_total`
  - # of kW of solar potential for all roof types in that region (assuming 250 watts per panel)
* [FLOAT]     `yearly_sunlight_kwh_n`
  - total solar energy generation potential for north-facing roof space in that region
* [FLOAT]     `yearly_sunlight_kwh_s`
  - total solar energy generation potential for south-facing roof space in that region
* [FLOAT]     `yearly_sunlight_kwh_e`
  - total solar energy generation potential for east-facing roof space in that region
* [FLOAT]     `yearly_sunlight_kwh_w`
  - total solar energy generation potential for west-facing roof space in that region
* [FLOAT]     `yearly_sunlight_kwh_f`
  - total solar energy generation potential for flat roof space in that region
* [FLOAT]     `yearly_sunlight_kwh_median`
  - kWh/kw/yr for the median roof, in DC (not AC) terms
* [FLOAT]     `yearly_sunlight_kwh_total`
  - total solar energy generation potential for all roof space in that region
* [STRING]    `install_size_kw_buckets`
  - # of buildings with potential for various installation size buckets. Format is a JSON array, where each element is a tuple containing (1) lower bound of bucket, in kW, and (2) number of buildings in that bucket.
* [FLOAT]     `carbon_offset_metric_tons`
  - The potential carbon dioxide abatement of the solar capacity that meets the technical potential criteria. The calculation uses eGRID subregion CO2 equivalent non-baseload output emission rates. https://www.epa.gov/sites/production/files/2015-10/documents/egrid2012_summarytables_0.pdf
* [INTEGER]   `existing_installs_count`
  - # of buildings estimated to have a solar installation, at time of data collection
* [GEOGRAPHY] `center_point`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
