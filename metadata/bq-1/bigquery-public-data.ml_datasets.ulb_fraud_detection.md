# `ml_datasets.ulb_fraud_detection`
`bq-1` | `bigquery-public-data`
This dataset contains anonymized credit card transactions made over 2 days in September 2013 by European cardholders, with 492 frauds out of 284,807 transactions.

The columns in the table labeled V1-V28 are PCA (Principal Component Analysis) transformed features. Dimensionality reducing techniques, such as PCA, reduce the computational effort required to develop and train models. It ensures the dataset provides appropriate privacy protections in this instance given the sensitive nature of credit card transactions. More detailed information on what variables are used to create these features is not available for this same reason. See the Wikipedia Article on Principal Component Analysis to learn more: https://en.wikipedia.org/wiki/Principal_component_analysis

The original features remaining that have not been masked are “Time” and “Amount”. “Time” refers to the number of seconds that elapsed between the time of the first transaction in the dataset and the time the transaction occurred. “Amount” is the transaction amount. The final feature in the dataset is “Class”, which is a binary feature that indicates if a transaction is fraudulent. A value of 1 indicates the transaction was fraud, while 0 it was not.

This dataset is frequently used for education, as well as developing and training ML models. It is well suited for learning to develop and evaluate models for unbalanced classification problems given that only 0.17% of the transactions in this dataset are labeled fraud. You can use BigQuery ML to develop a logistic regression model using this data. The BigQuery Machine Learning introduction guide can help you get started: https://cloud.google.com/bigquery/docs/bigqueryml-intro

Use of this dataset should cite:
     - Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015

TERMS OF USE:
This data is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/. It is provided through the Google Cloud Public Datasets Program and is provided "AS IS" without any warranty, express or implied, from Google. Google disclaims all liability for any damages, direct or indirect, resulting from the use of the dataset.

## Column details
* [FLOAT]     `Time`
* [FLOAT]     `V1`
* [FLOAT]     `V2`
* [FLOAT]     `V3`
* [FLOAT]     `V4`
* [FLOAT]     `V5`
* [FLOAT]     `V6`
* [FLOAT]     `V7`
* [FLOAT]     `V8`
* [FLOAT]     `V9`
* [FLOAT]     `V10`
* [FLOAT]     `V11`
* [FLOAT]     `V12`
* [FLOAT]     `V13`
* [FLOAT]     `V14`
* [FLOAT]     `V15`
* [FLOAT]     `V16`
* [FLOAT]     `V17`
* [FLOAT]     `V18`
* [FLOAT]     `V19`
* [FLOAT]     `V20`
* [FLOAT]     `V21`
* [FLOAT]     `V22`
* [FLOAT]     `V23`
* [FLOAT]     `V24`
* [FLOAT]     `V25`
* [FLOAT]     `V26`
* [FLOAT]     `V27`
* [FLOAT]     `V28`
* [FLOAT]     `Amount`
* [INTEGER]   `Class`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
