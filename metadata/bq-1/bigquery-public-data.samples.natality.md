# `samples.natality`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `source_year`
  - Four-digit year of the birth. Example: 1975.
* [INTEGER]   `year`
  - Four-digit year of the birth. Example: 1975.
* [INTEGER]   `month`
  - Month index of the date of birth, where 1=January.
* [INTEGER]   `day`
  - Day of birth, starting from 1.
* [INTEGER]   `wday`
  - Day of the week, where 1 is Sunday and 7 is Saturday.
* [STRING]    `state`
  - The two character postal code for the state. Entries after 2004 do not include this value.
* [BOOLEAN]   `is_male`
  - TRUE if the child is male, FALSE if female.
* [INTEGER]   `child_race`
  - The race of the child. One of the following numbers:

1 - White
2 - Black
3 - American Indian
4 - Chinese
5 - Japanese
6 - Hawaiian
7 - Filipino
9 - Unknown/Other
18 - Asian Indian
28 - Korean
39 - Samoan
48 - Vietnamese
* [FLOAT]     `weight_pounds`
  - Weight of the child, in pounds.
* [INTEGER]   `plurality`
  - How many children were born as a result of this pregnancy. twins=2, triplets=3, and so on.
* [INTEGER]   `apgar_1min`
  - Apgar scores measure the health of a newborn child on a scale from 0-10. Value after 1 minute. Available from 1978-2002.
* [INTEGER]   `apgar_5min`
  - Apgar scores measure the health of a newborn child on a scale from 0-10. Value after 5 minutes. Available from 1978-2002.
* [STRING]    `mother_residence_state`
  - The two-letter postal code of the mother's state of residence when the child was born.
* [INTEGER]   `mother_race`
  - Race of the mother. Same values as child_race.
* [INTEGER]   `mother_age`
  - Reported age of the mother when giving birth.
* [INTEGER]   `gestation_weeks`
  - The number of weeks of the pregnancy.
* [STRING]    `lmp`
  - Date of the last menstrual period in the format MMDDYYYY. Unknown values are recorded as "99" or "9999".
* [BOOLEAN]   `mother_married`
  - True if the mother was married when she gave birth.
* [STRING]    `mother_birth_state`
  - The two-letter postal code of the mother's birth state.
* [BOOLEAN]   `cigarette_use`
  - True if the mother smoked cigarettes. Available starting 2003.
* [INTEGER]   `cigarettes_per_day`
  - Number of cigarettes smoked by the mother per day. Available starting 2003.
* [BOOLEAN]   `alcohol_use`
  - True if the mother used alcohol. Available starting 1989.
* [INTEGER]   `drinks_per_week`
  - Number of drinks per week consumed by the mother. Available starting 1989.
* [INTEGER]   `weight_gain_pounds`
  - Number of pounds gained by the mother during pregnancy.
* [INTEGER]   `born_alive_alive`
  - Number of children previously born to the mother who are now living.
* [INTEGER]   `born_alive_dead`
  - Number of children previously born to the mother who are now dead.
* [INTEGER]   `born_dead`
  - Number of children who were born dead (i.e. miscarriages)
* [INTEGER]   `ever_born`
  - Total number of children to whom the woman has ever given birth (includes the current birth).
* [INTEGER]   `father_race`
  - Race of the father. Same values as child_race.
* [INTEGER]   `father_age`
  - Age of the father when the child was born.
* [INTEGER]   `record_weight`
  - 1 or 2, where 1 is a row from a full-reporting area, and 2 is a row from a 50% sample area.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
