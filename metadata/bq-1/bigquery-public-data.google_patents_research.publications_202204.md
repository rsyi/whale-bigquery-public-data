# `google_patents_research.publications_202204`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `publication_number`
  - Patent publication number (DOCDB compatible), eg: 'US-7650331-B1'.
* [STRING]    `title`
  - The (possibly machine translated) English title.
* [BOOLEAN]   `title_translated`
  - True if the title is machine-translated by Google Translate.
* [STRING]    `abstract`
  - The (possibly machine translated) English abstract.
* [BOOLEAN]   `abstract_translated`
  - True if the abstract is machine-translated by Google Translate.
* [RECORD]    `cpc`
  - The Cooperative Patent Classification (CPC) codes with the hierarchy.
* [STRING]    `cpc.code`
  - Classification code
* [BOOLEAN]   `cpc.inventive`
  - Is this classification inventive/main?
* [BOOLEAN]   `cpc.first`
  - Is this classification the first/primary?
* [STRING]    `cpc.tree`
  - The full classification tree from the root to this code
* [STRING]    `cpc_low`
  - The Cooperative Patent Classification (CPC) codes and their parents, in an array for easier querying.
* [STRING]    `cpc_inventive_low`
  - The inventive Cooperative Patent Classification (CPC) codes and their parents, in an array for easier querying.
* [STRING]    `top_terms`
  - The top 10 salient terms extracted from this patent's title, abstract, claims and description.
* [RECORD]    `similar`
  - Semantically similar documents based on content and metadata.
* [STRING]    `similar.publication_number`
  - Same as [publication_number]
* [STRING]    `similar.application_number`
  - Same as [application_number]
* [STRING]    `similar.npl_text`
  - Free-text citation (non-patent literature, etc).
* [STRING]    `similar.type`
  - The type of reference (see parent field for values).
* [STRING]    `similar.category`
  - The category of reference (see parent field for values).
* [INTEGER]   `similar.filing_date`
  - The filing date.
* [STRING]    `url`
  - URL to the patents.google.com page for this patent.
* [STRING]    `country`
  - Country name.
* [STRING]    `publication_description`
  - Description of the publication type.
* [RECORD]    `cited_by`
  - Publications that cite this publication.
* [STRING]    `cited_by.publication_number`
  - Same as [publication_number]
* [STRING]    `cited_by.application_number`
  - Same as [application_number]
* [STRING]    `cited_by.npl_text`
  - Free-text citation (non-patent literature, etc).
* [STRING]    `cited_by.type`
  - The type of reference (see parent field for values).
* [STRING]    `cited_by.category`
  - The category of reference (see parent field for values).
* [INTEGER]   `cited_by.filing_date`
  - The filing date.
* [FLOAT]     `embedding_v1`
  - (Version 1) Machine-learned vector embedding based on document contents and metadata, where two documents that have similar technical content have a high dot product score of their embedding vectors.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
