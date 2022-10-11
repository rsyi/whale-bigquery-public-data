# `ebi_chembl.docs_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `doc_id`
  - Unique ID for the document
* [STRING]    `journal`
  - Abbreviated journal name for an article
* [INTEGER]   `year`
  - Year of journal article publication
* [STRING]    `volume`
  - Volume of journal article
* [STRING]    `issue`
  - Issue of journal article
* [STRING]    `first_page`
  - First page number of journal article
* [STRING]    `last_page`
  - Last page number of journal article
* [INTEGER]   `pubmed_id`
  - NIH pubmed record ID, where available
* [STRING]    `doi`
  -  Digital object identifier for this reference
* [STRING]    `chembl_id`
  - ChEMBL identifier for this document (for use on web interface etc)
* [STRING]    `title`
  -  Document title (e.g., Publication title or description of dataset)
* [STRING]    `doc_type`
  - Type of the document (e.g., Publication, Deposited dataset)
* [STRING]    `authors`
  - For a deposited dataset, the authors carrying out the screening and/or submitting the dataset.
* [STRING]    `abstract`
  - For a deposited dataset, a brief description of the dataset.
* [STRING]    `patent_id`
  - Patent ID for this document
* [STRING]    `ridx`
  - The Depositor Defined Reference Identifier
* [INTEGER]   `src_id`
  - Foreign key to Source table, indicating the source of this document

-------------------------------------------------------------------------------
*Do not make edits above this line.*
