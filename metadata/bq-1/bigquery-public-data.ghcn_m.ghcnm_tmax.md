# `ghcn_m.ghcnm_tmax`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - 11 digit identifier, digits 1-3=Country Code, digits 4-8 represent the WMO id if the station is a WMO station. It is a WMO station if digits 9-11="000".
* [INTEGER]   `year`
  - 4 digit year of the station record.
* [STRING]    `element`
  - element type, monthly mean temperature="TAVG" monthly maximum temperature="TMAX" monthly minimum temperature="TMIN"
* [INTEGER]   `value1`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag1`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag1`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag1`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value2`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag2`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag2`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag2`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value3`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag3`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag3`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag3`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value4`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag4`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag4`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag4`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value5`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag5`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag5`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag5`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value6`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag6`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag6`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag6`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value7`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag7`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag7`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag7`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value8`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag8`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag8`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag8`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value9`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag9`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag9`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag9`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value10`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag10`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag10`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag10`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value11`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag11`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag11`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag11`
  - data source flag for monthly value, 21 possibilities
* [INTEGER]   `value12`
  - monthly value (MISSING=-9999).  Temperature values are in hundredths of a degree Celsius, but are expressed as whole integers (e.g. divide by 100.0 to get whole degrees Celsius).
* [STRING]    `dmflag12`
  - data measurement flag, nine possible values: blank = no measurement information applicable a-i = number of days missing in calculation of monthly mean temperature (currently only applies to the 1218 USHCN V2 stations included within GHCNM)
* [STRING]    `qcflag12`
  - quality control flag, seven possibilities within quality controlled unadjusted (qcu) dataset, and 2 possibilities within the quality controlled adjusted (qca) dataset.
* [STRING]    `dsflag12`
  - data source flag for monthly value, 21 possibilities

-------------------------------------------------------------------------------
*Do not make edits above this line.*
