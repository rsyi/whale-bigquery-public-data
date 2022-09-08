# `patents.publications_202101`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `publication_number`
  - Patent publication number (DOCDB compatible), eg: 'US-7650331-B1'
* [STRING]    `application_number`
  - Patent application number (DOCDB compatible), eg: 'US-87124404-A'. This may not always be set.
* [STRING]    `country_code`
  - Country code, eg: 'US', 'EP', etc
* [STRING]    `kind_code`
  - Kind code, indicating application, grant, search report, correction, etc. These are different for each country.
* [STRING]    `application_kind`
  - High-level kind of the application: A=patent; U=utility; P=provision; W= PCT; F=design; T=translation.
* [STRING]    `application_number_formatted`
  - Application number, formatted to the patent office format where possible.
* [STRING]    `pct_number`
  - PCT number for this application if it was part of a PCT filing, eg: 'PCT/EP2008/062623'.
* [STRING]    `family_id`
  - Family ID (simple family). Grouping on family ID will return all publications associated with a simple patent family (all publications share the same priority claims).
* [RECORD]    `title_localized`
  - The publication titles in different languages
* [STRING]    `title_localized.text`
  - Localized text
* [STRING]    `title_localized.language`
  - Two-letter language code for this text
* [BOOLEAN]   `title_localized.truncated`
  - Is this text truncated?
* [RECORD]    `abstract_localized`
  - The publication abstracts in different languages
* [STRING]    `abstract_localized.text`
  - Localized text
* [STRING]    `abstract_localized.language`
  - Two-letter language code for this text
* [BOOLEAN]   `abstract_localized.truncated`
  - Is this text truncated?
* [RECORD]    `claims_localized`
  - For US publications only, the claims in plain text
* [STRING]    `claims_localized.text`
  - Localized text
* [STRING]    `claims_localized.language`
  - Two-letter language code for this text
* [BOOLEAN]   `claims_localized.truncated`
  - Is this text truncated?
* [RECORD]    `claims_localized_html`
  - For US publications only, the claims in HTML
* [STRING]    `claims_localized_html.text`
  - Localized text
* [STRING]    `claims_localized_html.language`
  - Two-letter language code for this text
* [BOOLEAN]   `claims_localized_html.truncated`
  - Is this text truncated?
* [RECORD]    `description_localized`
  - For US publications only, the description in plain text, limited to the first 9 megabytes
* [STRING]    `description_localized.text`
  - Localized text
* [STRING]    `description_localized.language`
  - Two-letter language code for this text
* [BOOLEAN]   `description_localized.truncated`
  - Is this text truncated?
* [RECORD]    `description_localized_html`
  - For US publications only, the description in HTML, limited to the first 9 megabytes
* [STRING]    `description_localized_html.text`
  - Localized text
* [STRING]    `description_localized_html.language`
  - Two-letter language code for this text
* [BOOLEAN]   `description_localized_html.truncated`
  - Is this text truncated?
* [INTEGER]   `publication_date`
  - The publication date.
* [INTEGER]   `filing_date`
  - The filing date.
* [INTEGER]   `grant_date`
  - The grant date, or 0 if not granted.
* [INTEGER]   `priority_date`
  - The earliest priority date from the priority claims, or the filing date.
* [RECORD]    `priority_claim`
  - The application numbers of the priority claims of this publication.
* [STRING]    `priority_claim.publication_number`
  - Same as [publication_number]
* [STRING]    `priority_claim.application_number`
  - Same as [application_number]
* [STRING]    `priority_claim.npl_text`
  - Free-text citation (non-patent literature, etc).
* [STRING]    `priority_claim.type`
  - The type of reference (see parent field for values).
* [STRING]    `priority_claim.category`
  - The category of reference (see parent field for values).
* [INTEGER]   `priority_claim.filing_date`
  - The filing date.
* [STRING]    `inventor`
  - The inventors.
* [RECORD]    `inventor_harmonized`
  - The harmonized inventors and their countries.
* [STRING]    `inventor_harmonized.name`
  - Name
* [STRING]    `inventor_harmonized.country_code`
  - The two-letter country code
* [STRING]    `assignee`
  - The assignees/applicants.
* [RECORD]    `assignee_harmonized`
  - The harmonized assignees and their countries.
* [STRING]    `assignee_harmonized.name`
  - Name
* [STRING]    `assignee_harmonized.country_code`
  - The two-letter country code
* [RECORD]    `examiner`
  - The examiner of this publication and their countries.
* [STRING]    `examiner.name`
  - Name
* [STRING]    `examiner.department`
  - The examiner's department
* [STRING]    `examiner.level`
  - The examiner's level
* [RECORD]    `uspc`
  - The US Patent Classification (USPC) codes.
* [STRING]    `uspc.code`
  - Classification code
* [BOOLEAN]   `uspc.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `uspc.first`
  - Is this classification the first/primary?
* [STRING]    `uspc.tree`
  - The full classification tree from the root to this code
* [RECORD]    `ipc`
  - The International Patent Classification (IPC) codes.
* [STRING]    `ipc.code`
  - Classification code
* [BOOLEAN]   `ipc.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `ipc.first`
  - Is this classification the first/primary?
* [STRING]    `ipc.tree`
  - The full classification tree from the root to this code
* [RECORD]    `cpc`
  - The Cooperative Patent Classification (CPC) codes.
* [STRING]    `cpc.code`
  - Classification code
* [BOOLEAN]   `cpc.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `cpc.first`
  - Is this classification the first/primary?
* [STRING]    `cpc.tree`
  - The full classification tree from the root to this code
* [RECORD]    `fi`
  - The FI classification codes.
* [STRING]    `fi.code`
  - Classification code
* [BOOLEAN]   `fi.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `fi.first`
  - Is this classification the first/primary?
* [STRING]    `fi.tree`
  - The full classification tree from the root to this code
* [RECORD]    `fterm`
  - The F-term classification codes.
* [STRING]    `fterm.code`
  - Classification code
* [BOOLEAN]   `fterm.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `fterm.first`
  - Is this classification the first/primary?
* [STRING]    `fterm.tree`
  - The full classification tree from the root to this code
* [RECORD]    `locarno`
  - The Locarno classification codes.
* [STRING]    `locarno.code`
  - Classification code
* [BOOLEAN]   `locarno.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `locarno.first`
  - Is this classification the first/primary?
* [STRING]    `locarno.tree`
  - The full classification tree from the root to this code
* [RECORD]    `citation`
  - The citations of this publication. Category is one of {CH2 = Chapter 2; SUP = Supplementary search report ; ISR = International search report ; SEA = Search report; APP = Applicant; EXA = Examiner; OPP = Opposition; 115 = article 115; PRS = Pre-grant pre-search; APL = Appealed; FOP = Filed opposition}, Type is one of {A = technological background; D = document cited in application; E = earlier patent document; 1 = document cited for other reasons; O = Non-written disclosure; P = Intermediate document; T = theory or principle; X = relevant if taken alone; Y = relevant if combined with other documents}
* [STRING]    `citation.publication_number`
  - Same as [publication_number]
* [STRING]    `citation.application_number`
  - Same as [application_number]
* [STRING]    `citation.npl_text`
  - Free-text citation (non-patent literature, etc).
* [STRING]    `citation.type`
  - The type of reference (see parent field for values).
* [STRING]    `citation.category`
  - The category of reference (see parent field for values).
* [INTEGER]   `citation.filing_date`
  - The filing date.
* [STRING]    `entity_status`
  - The USPTO entity status (large, small).
* [STRING]    `art_unit`
  - The USPTO art unit performing the examination (2159, etc).

-------------------------------------------------------------------------------
*Do not make edits above this line.*
