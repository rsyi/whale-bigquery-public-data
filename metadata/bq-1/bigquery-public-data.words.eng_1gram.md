# `words.eng_1gram`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `ngram`
  - the ngram
* [INTEGER]   `term_frequency`
  - number of occurrences of ngram within the corpus
* [INTEGER]   `document_frequency`
  - number of corpus documents within which the ngram appeared
* [INTEGER]   `term_rank`
  - ascending rank of the ngram term frequency within the corpus. 1=most frequent
* [INTEGER]   `document_rank`
  - ascending rank of the ngram document frequency within the corpus. 1=most frequent
* [RECORD]    `year`
  - ngram data per-year
* [INTEGER]   `year.year`
  - year
* [INTEGER]   `year.term_frequency`
  - term frequency by year - these are aggregated to the outer term_frequency field
* [INTEGER]   `year.document_frequency`
  - document frequency by year - these are aggregated to the outer document_frequency field

-------------------------------------------------------------------------------
*Do not make edits above this line.*
