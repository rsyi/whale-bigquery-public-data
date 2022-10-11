# `ebi_chembl.product_patents_30`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `prod_pat_id`
  - Primary key
* [STRING]    `product_id`
  - Foreign key to products table - FDA application number for the product
* [STRING]    `patent_no`
  - Patent numbers as submitted by the applicant holder for patents covered by the statutory provisions
* [DATETIME]  `patent_expire_date`
  - Date the patent expires as submitted by the applicant holder including applicable extensions
* [INTEGER]   `drug_substance_flag`
  - Patents submitted on FDA Form 3542 and listed after August 18, 2003 may have a drug substance flag set to 1, indicating the sponsor submitted the patent as claiming the drug substance
* [INTEGER]   `drug_product_flag`
  - Patents submitted on FDA Form 3542 and listed after August 18, 2003 may have a drug product flag set to 1, indicating the sponsor submitted the patent as claiming the drug product
* [STRING]    `patent_use_code`
  - Code to designate a use patent that covers the approved indication or use of a drug product
* [INTEGER]   `delist_flag`
  - Applicants under Section 505(b)(2) are not required to certify to patents where this flag is set to 1
* [DATETIME]  `submission_date`
  - The date on which the FDA receives patent information from the new drug application (NDA) holder. Format is Mmm d, yyyy

-------------------------------------------------------------------------------
*Do not make edits above this line.*
