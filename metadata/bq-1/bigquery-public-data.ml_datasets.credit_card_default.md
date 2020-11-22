# `ml_datasets.credit_card_default`
`bq-1` | `bigquery-public-data`

## Column details
* [FLOAT]     `id`
  - Anonymized ID of each client
* [FLOAT]     `limit_balance`
  - Amount of given credit in NT dollars (includes individual and family/supplementary credit
* [STRING]    `sex`
  - Gender (1=male, 2=female)
* [STRING]    `education_level`
  - Education Level (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)
* [STRING]    `marital_status`
  - Marital status (1=married, 2=single, 3=others)
* [FLOAT]     `age`
  - Age in years
* [FLOAT]     `pay_0`
  - Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, ... 8=payment delay for eight months, 9=payment delay for nine months and above)
* [FLOAT]     `pay_2`
  - Repayment status in August, 2005 (scale same as above)
* [FLOAT]     `pay_3`
  - Repayment status in July, 2005 (scale same as above)
* [FLOAT]     `pay_4`
  - Repayment status in June, 2005 (scale same as above)
* [STRING]    `pay_5`
  - Repayment status in May, 2005 (scale same as above)
* [STRING]    `pay_6`
  - Repayment status in April, 2005 (scale same as above)
* [FLOAT]     `bill_amt_1`
  - Amount of bill statement in September, 2005 (NT dollar)
* [FLOAT]     `bill_amt_2`
  - Amount of bill statement in August, 2005 (NT dollar)
* [FLOAT]     `bill_amt_3`
  - Amount of bill statement in July, 2005 (NT dollar)
* [FLOAT]     `bill_amt_4`
  - Amount of bill statement in June, 2005 (NT dollar)
* [FLOAT]     `bill_amt_5`
  - Amount of bill statement in May, 2005 (NT dollar)
* [FLOAT]     `bill_amt_6`
  - Amount of bill statement in April, 2005 (NT dollar)
* [FLOAT]     `pay_amt_1`
  - Amount of previous payment in September, 2005 (NT dollar)
* [FLOAT]     `pay_amt_2`
  - Amount of previous payment in August, 2005 (NT dollar)
* [FLOAT]     `pay_amt_3`
  - Amount of previous payment in July, 2005 (NT dollar)
* [FLOAT]     `pay_amt_4`
  - Amount of previous payment in June, 2005 (NT dollar)
* [FLOAT]     `pay_amt_5`
  - Amount of previous payment in May, 2005 (NT dollar)
* [FLOAT]     `pay_amt_6`
  - Amount of previous payment in April, 2005 (NT dollar)
* [STRING]    `default_payment_next_month`
  - Default payment (1=yes, 0=no)
* [RECORD]    `predicted_default_payment_next_month`
* [RECORD]    `predicted_default_payment_next_month.tables`
* [FLOAT]     `predicted_default_payment_next_month.tables.score`
* [STRING]    `predicted_default_payment_next_month.tables.value`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
