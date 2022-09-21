# `noaa_hurricanes.hurricanes`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `sid`
  - Storm Identifier.
* [STRING]    `season`
* [INTEGER]   `number`
  - The cardinal number of the system for that season. The count includes all basins/nso this will not be continuous for basin files.
* [STRING]    `basin`
  - Basins include: NA - North Atlantic EP - Eastern North Pacific WP - Western North Pacific NI - North Indian SI - South Indian SP - Southern Pacific SA - South Atlantic MM - Missing - should not appear in final IBTrACS product
* [STRING]    `subbasin`
  - Subbasins include: MM - missing - no sub basin for this basin (no subbasins provided for WP/nSI) CS - Caribbean Sea GM - Gulf of Mexico CP - Central Pacific BB - Bay of Bengal AS - Arabian Sea WA - Western Australia EA - Eastern Australia
* [STRING]    `name`
  - Name provided by the agency. IBTrACS ignores most names that include digits or abbreviations.
* [TIMESTAMP] `iso_time`
  - ISO Time provided in Universal Time Coordinates (UTC). Format is YYYY-MM-DD HH:mm:ss Most points are provided at 6 hour intervals. Some agencies provided 3 hour points (e.g./nNew Delhi) or times at important observations (e.g./nlandfall times in the North Atlantic/netc.).
* [STRING]    `nature`
  - Combined storm type. This is assigned based on all available storm types. They include: DS - Disturbance TS - Tropical ET - Extratropical SS - Subtropical NR - Not reported MX - Mixture (contradicting nature reports from different agencies)
* [FLOAT]     `latitude`
* [FLOAT]     `longitude`
* [INTEGER]   `wmo_wind`
  - Maximum sustained wind speed from the WMO agency for the current location. NO adjustment is made for differences in wind speed averaging periods. hurdat/atcf = North Atlantic - U.S. Miami (NOAA NHC) - 1-minute winds tokyo = RSMC Tokyo (JMA) - 10-minute newdelhi = RSMC New Delhi (IMD) - 3-minute reunion = RSMC La Reunion (MFLR) - 10 minute bom = Australian TCWCs (TCWC Perth/nDarwin/nBrisbane) - 10-minute nadi = RSMC Nadi (FMS) - 10 minute wellington = TCWC Wellington (NZMS) - 10-minute
* [INTEGER]   `wmo_pressure`
* [STRING]    `wmo_agency`
  - This is the reporting agency responsible for the basin as currently listed. It should be noted that many of the agencies did not accept official WMO responsibility until relatively recently/ne.g./nLa Reunion in 1993 or IMD in 1990. Therefore the WMO agency is used loosely todescribe the currently reponsible agency.
* [STRING]    `track_type`
  - Track type Tropical storms can interact. This identifies : PROVISIONAL - Real time data used to populate the position and other parameters of this system. This is a provisional track that will be replaced when reanalysis of the storm is performed. (Usually within 2 years of the storm's occurence) main - primary track associated with a storm system. spur - usually short lived tracks associated with a main track and either represent alternate positions at the beginning of a system. Can also represent actual system interactions (e.g./nFujiwhara interactions).
* [INTEGER]   `dist2land`
  - Distance to land from the current position. The land dataset includes all continents and any islands larger than XX. The distance is the nearest at the present time in any direction.
* [INTEGER]   `landfall`
  - Nearest location to land within next 6 hours. This can be thought of a landfall flag: =0 -- Landfall within 6 hours. >0 -- No landfall within next 6 hours. Calculations are based on storm center (columns 9,10). Values less than 60 nmile likely are impacted by the system even though the center of the system is not over land. The uses the same land mask as DIST2LAND.
* [STRING]    `iflag`
  - Interpolation Flag A 14 character flag string which denotes the source of each agency's report: Interpolation Flags include: _ == missing reports. No information provided. O == original report as provided by the agency. P == position was interpolated (all variables were interpolated/filled/nincluding intensity) I == Position was provided/nbut Intensity variables (and likely other variables) were interpolated/filled V = Position and intensity variables are original but some variables were interpolated/filled. The order of the 14 characters refers to the following 14 datasets: 1 - USA Agency (see column 18) 2 - Tokyo 3 - CMA 4 - HKO 5 - NewDelhi 6 - Reunion 7 - BoM 8 - Nadi 9 - Wellington 10 - ds824 11 - TD9636 12 - TD9635 13 - Neumann Southern Hemisphere data set 14 - M.L. Chenoweth N Atlantic Historic dataset
* [STRING]    `usa_agency`
  - The agency file providing the information: The representative US agency data is derived from a hierarchical selection: the first dataset in the following list to provide information at the given time is used as the USA_agency: - HURDAT_ATL - HURSAT_EPA - ATCF (for NA and EP basins only) - JTWC_WP - JTWC_IO - JTWC_EP - JTWC_CP - JTWC_SH - CPHC [separate file provided by CPHC for years TBD] - tcvitals - THIS INDICATES THAT THE DATA ARE PRELIMINARY While these agencies are generally orthogonal/nthere are cases where a system is provided in more than one source. In this case/nthe report from the highest source is used. ATCF format info from: https://www.nrlmry.navy.mil/atcf_web/docs/database/new/abdeck.txt HURDAT2 info from: http://www.nhc.noaa.gov/data/hurdat/hurdat2-format-atlantic.pdf
* [FLOAT]     `usa_latitude`
* [FLOAT]     `usa_longitude`
* [STRING]    `usa_record`
  - Record identifier (see notes below) C – Closest approach to a coast/nnot followed by a landfall G – Genesis I – An intensity peak in terms of both pressure and wind L – Landfall (center of system crossing a coastline) P – Minimum in central pressure R – Provides additional detail on the intensity of the cyclone when rapid changes are underway S – Change of status of the system T – Provides additional detail on the track (position) of the cyclone W – Maximum sustained wind speed
* [STRING]    `usa_status`
  - Status of system. Options are:  DB - disturbance/n TD - tropical depression/n TS - tropical storm/n TY - typhoon/n ST - super typhoon/n TC - tropical cyclone/n HU,HR - hurricane/n SD - subtropical depression/n SS - subtropical storm/n EX - extratropical systems/n PT - post tropical/n IN - inland/n DS - dissipating/n LO - low/n WV - tropical wave/n ET - extrapolated/n MD - monsoon depression/n XX - unknown.
* [INTEGER]   `usa_wind`
  - Maximum sustained wind speed in knots: 0 - 300 kts.
* [INTEGER]   `usa_pressure`
  - Minimum central pressure (mb)
* [INTEGER]   `usa_sshs`
  - Saffir-Simpson Hurricane Scale information based on the wind speed provided by the US agency wind speed (US agencies provide 1-minute wind speeds) -5 = Unknown [XX] -4 = Post-tropical [EX/nET/nPT] -3 = Miscellaneous disturbances [WV/nLO/nDB/nDS/nIN/nMD] -2 = Subtropical [SS/nSD] Tropical systems classified based on wind speeds [TD/nTS/nHU/nTY,/nTC/nST/nHR]  -1 = Tropical depression (W<34)  0 = Tropical storm [34<W<64]  1 = Category 1 [64<=W<83]  2 = Category 2 [83<=W<96]  3 = Category 3 [96<=W<113]  4 = Category 4 [113<=W<137]  5 = Category 5 [W >= 137]
* [INTEGER]   `usa_r34_ne`
  - – 34 kt wind radii maximum extent in northeastern quadrant
* [INTEGER]   `usa_r34_se`
  - 34 kt wind radii maximum extent in southeastern quadrant
* [INTEGER]   `usa_r34_sw`
  - – 34 kt wind radii maximum extent in southwestern quadrant
* [INTEGER]   `usa_r34_nw`
  - – 34 kt wind radii maximum extent in northwestern quadrant
* [INTEGER]   `usa_r50_ne`
  - 50 kt wind radii maximum extent in northeastern quadrant
* [INTEGER]   `usa_r50_se`
  - – 50 kt wind radii maximum extent in southeastern quadrant
* [INTEGER]   `usa_r50_sw`
  - – 50 kt wind radii maximum extent in southwestern quadrant
* [INTEGER]   `usa_r50_nw`
  - 50 kt wind radii maximum extent in northwestern quadrant
* [INTEGER]   `usa_r64_ne`
  - – 64 kt wind radii maximum extent in northeastern quadrant
* [INTEGER]   `usa_r64_se`
  - 64 kt wind radii maximum extent in southeastern quadrant
* [INTEGER]   `usa_r64_sw`
  - – 64 kt wind radii maximum extent in southwestern quadrant
* [INTEGER]   `usa_r64_nw`
  - 64 kt wind radii maximum extent in northwestern quadrant
* [INTEGER]   `usa_poci`
  - pressure in millibars of the last closed isobar/n900 - 1050 mb NOT BEST-TRACKED (not reanalyzed)
* [INTEGER]   `usa_roci`
  - radius of the last closed isobar/n0 - 999 n mi. NOT BEST TRACKED (not reanalyzed)
* [INTEGER]   `usa_rmw`
  - radius of max winds/n0 - 999 n mi. NOT BEST TRACKED (not reanalyzed)
* [STRING]    `usa_eye`
  - eye diameter/n0 - 120 n mi. NOT BEST TRACKED (not reanalyzed)
* [FLOAT]     `tokyo_latitude`
* [FLOAT]     `tokyo_longitude`
* [INTEGER]   `tokyo_grade`
  - <Grade> 1 : Not used  2 : Tropical Depression (TD)  3 : Tropical Storm (TS)  4 : Severe Tropical Storm (STS)  5 : Typhoon (TY)  6 : Extratropical Cyclone (L)  7 : Just entering into the responsible area of  Japan Meteorological Agency (JMA)  8 : Not used  9 : Tropical Cyclone of TS intensity or higher
* [INTEGER]   `tokyo_wind`
  - Maximum sustained wind speed [10-min averaging period]
* [INTEGER]   `tokyo_pressure`
  - Central pressure
* [INTEGER]   `tokyo_r50_dir`
  - 1 : Northeast (NE)  2 : East (E)  3 : Southeast (SE)  4 : South (S)  5 : Southwest (SW)  6 : West (W)  7 : Northwest (NW)  8 : North (N)  9 : (symmetric circle)
* [INTEGER]   `tokyo_r50_longitude`
  - The longest radius of 50kt winds or greater
* [INTEGER]   `tokyo_r50_short`
  - The shortest radius of 50kt winds or greater
* [INTEGER]   `tokyo_r30_dir`
  - 1 : Northeast (NE)  2 : East (E)  3 : Southeast (SE)  4 : South (S)  5 : Southwest (SW)  6 : West (W)  7 : Northwest (NW)  8 : North (N)  9 : (symmetric circle)
* [INTEGER]   `tokyo_r30_long`
  - The longest radius of 30kt winds or greater
* [INTEGER]   `tokyo_r30_short`
  - The shortest radius of 30kt winds or greater
* [INTEGER]   `tokyo_land`
  - <Indicator of landfall or passage>  Landfall or passage over the Japanese islands occurred within  one hour after the time of the analysis with this indicator.
* [FLOAT]     `cma_latitude`
  - Latitude from Chinese Meteorological Administration data from Shanghai Typhoon Institute
* [FLOAT]     `cma_longitude`
  - Longitude from Chinese Meteorological Administration data from Shanghai Typhoon Institute
* [INTEGER]   `cma_cat`
  - Intensity category according to the Chinese National Standard for Grade of Tropical Cyclones (which has been used since 15 June 2006): 0 –– Weaker than Tropical Depression or unknown intensity; 1 –– Tropical Depression (TD: 10.8–17.1 m/s); 2 –– Tropical Storm (TS:17.2–24.4 m/s); 3 –– Severe Tropical Storm (STS: 24.5–32.6 m/s); 4 –– Typhoon (TY: 32.7–41.4 m/s); 5 –– Severe Typhoon (STY: 41.5–50.9 m/s); 6 –– Super Typhoon (SuperTY: ≥51.0 m/s); 9 –– Extratropical Cyclone (ET) stage.
* [INTEGER]   `cma_wind`
  - Two-minute mean maximum sustained wind (MSW; m/s) near the TC center. WND = 9 indicates MSW < 10 m/s/nWND = 0 indicates unknown intensity
* [INTEGER]   `cma_pressure`
  - Minimum pressure (hPa) near the TC center.
* [STRING]    `hko_latitude`
  - Latitude from Hong Kong Observatory
* [FLOAT]     `hko_longitude`
  - Longitude from Hong Kong Observatory
* [STRING]    `hko_cat`
  - After 2009/nwe further classified two more storm types above typhoon/nso there are in total 7 storm types LW (Low) <22 kt TD (Tropical Depression) 22 – 33 kt TS (Tropical Storm) 34 – 47 kt STS (Severe Tropical Storm) 48 – 63 kt T (Typhoon) 64 – 80 kt ST (Severe Typhoon) 81 – 99 kt SuperT (Super Typhoon) >= 100 kt
* [INTEGER]   `hko_wind`
* [INTEGER]   `hko_pressure`
* [FLOAT]     `newdelhi_latitude`
* [FLOAT]     `newdelhi_longitude`
* [STRING]    `newdelhi_grade`
  - Types of disturbances: Low pressure area W<17 knots D - Depression 17<=W<28 DD - Deep Depression 28<=W<34 CS - Cyclonic Storm 34<=W<48 SCS - Severe Cyclonic Storm 48<=W<64 VSCS - Very Severe Cyclonic Storm 64<=W<120 SCS - Super Cyclonic Storm W>=120 knots
* [INTEGER]   `newdelhi_wind`
* [INTEGER]   `newdelhi_pressure`
* [FLOAT]     `newdelhi_ci`
* [INTEGER]   `newdelhi_dp`
* [INTEGER]   `newdelhi_poci`
* [FLOAT]     `reunion_latitude`
* [FLOAT]     `reunion_longitude`
* [INTEGER]   `reunion_type`
  - 01= tropics; disturbance ( no closed isobars)  02= <34 knot winds/n<17m/s winds and at least one closed isobar  03= 34-63 knots/n17-32m/s  04= >63 knots/n>32m/s  05= extratropical  06= dissipating  07= subtropical cyclone (nonfrontal/nlow pressure system that comprises  initially baroclinic circulation developing over subtropical water)  08= overland  09= unknown
* [INTEGER]   `reunion_wind`
  - Maximum average wind speed
* [INTEGER]   `reunion_pressure`
  - Central pressure
* [FLOAT]     `reunion_tnum`
  - Dvorak T-number
* [FLOAT]     `reunion_ci`
  - Dvorak CI-number
* [INTEGER]   `reunion_rmw`
  - Radius of maximum winds
* [INTEGER]   `reunion_r34_ne`
  - 34 kt wind radii maximum extent in northeastern quadrant
* [INTEGER]   `reunion_r34_se`
  - 34 kt wind radii maximum extent in southeastern quadrant
* [INTEGER]   `reunion_r34_sw`
  - 34 kt wind radii maximum extent in southwestern quadrant
* [INTEGER]   `reunion_r34_nw`
  - 34 kt wind radii maximum extent in northwestern quadrant
* [INTEGER]   `reunion_r50_ne`
  - 50 kt wind radii maximum extent in northeastern quadrant
* [INTEGER]   `reunion_r50_se`
  - 50 kt wind radii maximum extent in southeastern quadrant
* [INTEGER]   `reunion_r50_sw`
  - 50 kt wind radii maximum extent in southwestern quadrant
* [INTEGER]   `reunion_r50_nw`
  - 50 kt wind radii maximum extent in northwestern quadrant
* [INTEGER]   `reunion_r64_ne`
  - 64 kt wind radii maximum extent in northeastern quadrant
* [INTEGER]   `reunion_r64_se`
  - 64 kt wind radii maximum extent in southeastern quadrant
* [INTEGER]   `reunion_r64_sw`
  - 64 kt wind radii maximum extent in southwestern quadrant
* [INTEGER]   `reunion_r64_nw`
  - 64 kt wind radii maximum extent in northwestern quadrant
* [FLOAT]     `bom_latitude`
  - Latitude from Australian Bureau of Meterology
* [FLOAT]     `bom_longitude`
  - Longitude from Australian Bureau of Meterology
* [INTEGER]   `bom_type`
  - This indicates the type of system that this cyclone was at the time of the observation. Note that cyclones can evolve during their lifetimes and hence change type mid-stream (e.g. Extratropical transition (ETT))
* [INTEGER]   `bom_wind`
  - This is the estimated maximum mean wind around the cyclone – that is in the vicinity of the centre.
* [INTEGER]   `bom_pressure`
  - Central pressure of the cyclone
* [FLOAT]     `bom_tnum`
* [FLOAT]     `bom_ci`
* [INTEGER]   `bom_rmw`
  - This is the mean radius (from the system centre) of the maximum mean wind.
* [INTEGER]   `bom_r34_ne`
  - This is the mean radius (from the system centre) of the extent of winds; gale-force (17m/s) or above. The four sectors show the mean extent in the respective quadrant centred on the cardinal point. Northeast quadrant
* [INTEGER]   `bom_r34_se`
  - This is the mean radius (from the system centre) of the extent of winds; gale-force (17m/s) or above. The four sectors show the mean extent in the respective quadrant centred on the cardinal point. Southeast quadrant
* [INTEGER]   `bom_r34_sw`
  - This is the mean radius (from the system centre) of the extent of winds; gale-force (17m/s) or above. The four sectors show the mean extent in the respective quadrant centred on the cardinal point. Southwest quadrant
* [INTEGER]   `bom_r34_nw`
  - This is the mean radius (from the system centre) of the extent of winds; gale-force (17m/s) or above. The four sectors show the mean extent in the respective quadrant centred on the cardinal point. Northwest quadrant
* [INTEGER]   `bom_r50_ne`
  - These are the mean radius (from the system centre) of the extent of winds; storm-force (25m/s) or above. Northeast quadrant.
* [INTEGER]   `bom_r50_se`
  - These are the mean radius (from the system centre) of the extent of winds; storm-force (25m/s) or above. Southeast quadrant.
* [INTEGER]   `bom_r50_sw`
  - These are the mean radius (from the system centre) of the extent of winds; storm-force (25m/s) or above. Southwest quadrant.
* [INTEGER]   `bom_r50_nw`
  - These are the mean radius (from the system centre) of the extent of winds; storm-force (25m/s) or above. Northwest quadrant.
* [INTEGER]   `bom_r64_ne`
  - These are the mean radius (from the system centre) of the extent of winds; hurricane-force (33m/s) or above. Northeast quadrant
* [INTEGER]   `bom_r64_se`
  - These are the mean radius (from the system centre) of the extent of winds; hurricane-force (33m/s) or above. Southeast quadrant
* [INTEGER]   `bom_r64_sw`
  - These are the mean radius (from the system centre) of the extent of winds; hurricane-force (33m/s) or above. Southwest quadrant
* [INTEGER]   `bom_r64_nw`
  - These are the mean radius (from the system centre) of the extent of winds; hurricane-force (33m/s) or above. Northwest quadrant
* [INTEGER]   `bom_roci`
  - The estimated mean radius of the outermost closed isobar (1-hPa spacing).
* [INTEGER]   `bom_poci`
  - Environmental pressure in which the cyclone is embedded
* [INTEGER]   `bom_eye`
  - Mean radius of the cyclone eye.
* [INTEGER]   `bom_pos_method`
  - This indicates the tools that were used to derive the centre location of the system. ADAM Code Method to derive position NULL Default - unknown 1 no sat/nno rad/nno obs 2 no sat/nno rad/nobs only 3 Sat IR/Vis; no clear eye 4 Sat IR/Vis; clearly defined eye 5 aircraft radar report 6 land-based radar report 7 Sat IR/Vis & rad & obs 8 report inside eye 10 Sat- Scatterometer 11 Sat- Microwave 12 Manned Aircraft Reconnaissance 13 UAV Aircraft Reconnaissance
* [INTEGER]   `bom_pressure_method`
  - This code may need to be expanded to handle new systems in the future/nand also to differentiate between pressure-wind relationships used to derive the central pressure. ADAM code Method WMO Code NULL Unknown or N/A 1 Aircraft or Dropsonde  observation 1 2 Over water observation (e.g.  buoy) 2 3 Over land observation 3 4 Instrument – unknown type 5 5 Derived Directly from DVORAK 4 6 Derived from wind via a P-W  equation 5 7 Estimate from surrounding obs 5 8 Extrapolation from radar 5 9 Other 5
* [FLOAT]     `wellington_latitude`
* [FLOAT]     `wellington_longitude`
* [INTEGER]   `wellington_wind`
* [INTEGER]   `wellington_pressure`
* [FLOAT]     `nadi_latitude`
  - Latitude from Fiji Meteorological Service data from RSMC Hadi
* [FLOAT]     `nadi_longitude`
  - Longitude from Fiji Meteorological Service data from RSMC Hadi
* [INTEGER]   `nadi_cat`
  - Nadi assigned category
* [INTEGER]   `nadi_wind`
* [INTEGER]   `nadi_pressure`
* [FLOAT]     `ds824_latitude`
  - Latitude from DataSet 824 - A historic dataset with data from the 1800s through 1980(ish)
* [FLOAT]     `ds824_longitude`
  - Longitude from DataSet 824 - A historic dataset with data from the 1800s through 1980(ish)
* [STRING]    `ds824_stage`
  - TC - Tropical cyclone
* [INTEGER]   `ds824_wind`
* [INTEGER]   `ds824_pressure`
* [FLOAT]     `td9636_latitude`
  - Latitude from Dataset of a collection of global storms (1842-1980)
* [FLOAT]     `td9636_longitude`
  - Longitude from Dataset of a collection of global storms (1842-1980)
* [INTEGER]   `td9636_stage`
  - This field gives an estimate of the highest winds occurring in the storm at the time and location indicated. The entire storm was coded as to the highest stage reached for some of the earlier years. 0 - Tropical disturbance (1969 onward) 1 - depression < 34 [some variation in definition for S Indian] 2 - Storm 34-63 [with some variation in definition for S Indian] 3 - point where wind reached 64 knots [except N Indian where it is wind 43-47 knots] 4 - Hurricane > 64 [except in N Indian/nWind > 48] 5 - Extratropical 6 - Dissipating 7 - Unknown Intensity or doubtful track
* [INTEGER]   `td9636_wind`
  - Estimated highest wind speed at the time indicated. These estimates are subjective and must be interpreted with caution.
* [INTEGER]   `td9636_pressure`
* [FLOAT]     `td9635_latitude`
  - Latitude from Dataset of a collection of western Pacific Storms (~1945-1976)
* [FLOAT]     `td9635_longitude`
  - Longitude from Dataset of a collection of western Pacific Storms (~1945-1976)
* [FLOAT]     `td9635_wind`
* [INTEGER]   `td9635_pressure`
* [INTEGER]   `td9635_roci`
  - Size. (Radius of system)
* [FLOAT]     `neumann_latitude`
* [FLOAT]     `neumann_longitude`
* [STRING]    `neumann_class`
  - EX - Extratropical TC - Tropical MM - Missing
* [INTEGER]   `neumann_wind`
* [INTEGER]   `neumann_pressure`
* [FLOAT]     `mlc_latitude`
  - Latitude from Mike Chenoweth data with updated data for the North Atlantic for the 1800s.
* [FLOAT]     `mlc_longitude`
  - Longitude from Mike Chenoweth data with updated data for the North Atlantic for the 1800s.
* [STRING]    `mlc_class`
  - Storm classification EX - Extratropical HU - Hurricane LO - Low MH SD - Subtropical depression SS - Subtropical storm TD - Tropical Depression TS - Tropical Storm TW WV - Open Wave
* [INTEGER]   `mlc_wind`
* [INTEGER]   `mlc_pressure`
* [STRING]    `usa_atcf_id`
  - The ATCF ID is assigned by US agencies and can be used to comparethe storm with other US cyclone-related datasets. If two (or more) ATCF tracks make up one storm/nthen the IDs are separated by a colon. The format of the ATCF ID is B<bb><nn><yyyy> where bb is the basin ID/nnn is the number of the storm in that basin and yyyy is the year. Possible basin values are: AL: North Atlantic/nSL: South Atlantic/nEP: East Pacific/nWP: West Pacific/nSH: Southern Hemisphere/nIO: North Indian For the provisional data/nother basin identifiers were provided that include: CP: Central Pacific/nSP: South Pacific/nSI: South Indian/nAS: Arabian Sea (North Indian) and BB: Bay of Bengal (North Indian)
* [STRING]    `source_url`
  - Source 
* [TIMESTAMP] `etl_timestamp`
  - Load time for this data row

-------------------------------------------------------------------------------
*Do not make edits above this line.*
