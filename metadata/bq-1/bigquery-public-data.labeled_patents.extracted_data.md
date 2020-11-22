# `labeled_patents.extracted_data`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `gcs_path`
  - Link to the PDF of the patent first page in Google Cloud Storage.
* [STRING]    `issuer`
  - Issuer of patent, either "US" or "EU".
* [STRING]    `language`
  - Language of the patent, "EN" for English, "FR" for French, "DE" for German.
* [STRING]    `publication_date`
  - Date (as string) the patent was published, verbatim from the patent.
* [STRING]    `class_international`
  - The first international classification code on the patent.
* [STRING]    `class_us`
  - For US patents only, the first US classification code on the patent.
* [STRING]    `application_number`
  - The (string) identifier assigned to the patent when it was filed, verbatim from the patent including non-numeric characters.
* [STRING]    `filing_date`
  - Date (as string) the patent was filed, verbatim from the patent.
* [STRING]    `priority_date_eu`
  - For EU patents only, the (string) priority date of the patent, verbatim from the patent.
* [STRING]    `representative_line_1_eu`
  - For EU patents only, the first line of the "representative" field.
* [STRING]    `applicant_line_1`
  - The first line of the "applicant" field.
* [STRING]    `inventor_line_1`
  - The first line of the "inventor" field.
* [STRING]    `title_line_1`
  - The first line of the title of the patent.
* [STRING]    `number`
  - The primary identifier of the patent, "patent number" in the US and "publication number" in the EU, verbatim from the patent including non-numeric characters.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
