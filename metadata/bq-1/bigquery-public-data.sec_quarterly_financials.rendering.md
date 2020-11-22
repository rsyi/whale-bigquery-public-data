# `sec_quarterly_financials.rendering`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `submission_number`
  - Accession Number. The 20-character string formed from the 18-digit number assigned by the Commission to each EDGAR submission. submission_number: [adsh]
* [INTEGER]   `report`
  - Represents the report grouping. The numeric value refers to the \"R file\" as computed by the renderer and posted on the EDGAR website. Note that in some situations the numbers skip.
* [STRING]    `file_type`
  - The type of interactive data file rendered on the EDGAR website, H = .htm file, X = .xml file. file_type: [rfile]
* [STRING]    `menu_category`
  - If available, one of the menu categories as computed by the renderer: C=Cover, S=Statements, N=Notes, P=Policies, T=Tables, D=Details, O=Other, and U=Uncategorized. menu_category: [menucat]
* [STRING]    `shortname`
  - The portion of the long name used in the renderer menu.
* [STRING]    `longname`
  - The space-normalized text of the XBRL link \"definition\" element content.
* [STRING]    `roleuri`
  - The XBRL \"roleuri\" of the role.
* [STRING]    `parentroleuri`
  - The XBRL roleuri of a role for which this role has a matching shortname prefix and a higher level menu category, as computed by the renderer.
* [INTEGER]   `parentreport`
  - The value of the report field for the role where roleuri equals this parentroleuri.
* [INTEGER]   `ultimate_parent_report`
  - The highest ancestor report reachable by following parentreport relationships. A note (menucat = N) is its own ultimate parent. ultimate_parent_report: [ultparentrpt]

-------------------------------------------------------------------------------
*Do not make edits above this line.*
