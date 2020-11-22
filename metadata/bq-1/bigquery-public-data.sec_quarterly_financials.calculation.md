# `sec_quarterly_financials.calculation`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [INTEGER]   `group`
  - Sequential number for grouping arcs in a submission. group: [grp]
* [INTEGER]   `arc`
  - Sequential number for arcs within a group in a submission.
* [INTEGER]   `negative`
  - Indicates a weight of -1 (TRUE if the arc is negative), but typically +1 (FALSE).
* [STRING]    `parent_tag`
  - The tag for the parent of the arc parent_tag: [ptag]
* [STRING]    `parent_version`
  - The version of the tag for the parent of the arc parent_version: [pversion]
* [STRING]    `child_tag`
  - The tag for the child of the arc child_tag: [ctag]
* [STRING]    `child_version`
  - The version of the tag for the child of the arc child_version: [cversion]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
