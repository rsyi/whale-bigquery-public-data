# `imdb.reviews`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `review`
  - User review's in IMDb.
* [STRING]    `split`
  - It has two categories test and train.
* [STRING]    `label`
  - It has three categories Negative, Positive and Unsupervised. All Unsupervised label has only split equals-to train.
* [STRING]    `movie_id`
  - UniqueId for the movie in IMDb.
* [INTEGER]   `reviewer_rating`
  - Reviewer rating for particular movie in IMDb. For train-unsupervised, reviewer_rating is NULL.
* [STRING]    `movie_url`
  - Movie url for corresponding movie_id
* [STRING]    `title`
  - Title of the movie for corresponding movie_id

-------------------------------------------------------------------------------
*Do not make edits above this line.*
