# `labeled_patents.figures`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `gcs_path`
  - Link to the PDF of the patent first page in Google Cloud Storage.
* [FLOAT]     `x_relative_min`
  - X coordinate of top left corner of the bounding box around the figure on the patent first page. Expressed relative to the extreme left (0) and extreme right (1) of the page.
* [FLOAT]     `y_relative_min`
  - Y coordinate of top left corner of the bounding box around the figure on the patent first page. Expressed relative to the extreme top (0) and extreme bottom (1) of the page.
* [FLOAT]     `x_relative_max`
  - X coordinate of bottom right corner of the bounding box around the figure on the patent first page. Expressed relative to the extreme left (0) and extreme right (1) of the page.
* [FLOAT]     `y_relative_max`
  - Y coordinate of bottom right corner of the bounding box around the figure on the patent first page. Expressed relative to the extreme top (0) and extreme bottom (1) of the page.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
