# `cfpb_complaints.complaint_database`
`bq-1` | `bigquery-public-data`

## Column details
* [DATE]      `date_received`
  - Date the complaint was received by the CPFB
* [STRING]    `product`
  - The type of product the consumer identified in the complaint
* [STRING]    `subproduct`
  - The type of sub-product the consumer identified in the complaint
* [STRING]    `issue`
  - The issue the consumer identified in the complaint
* [STRING]    `subissue`
  - The sub-issue the consumer identified in the complaint
* [STRING]    `consumer_complaint_narrative`
  - A description of the complaint provided by the consumer
* [STRING]    `company_public_response`
  - The company's optional public-facing response to a consumer's complaint
* [STRING]    `company_name`
  - Name of the company identified in the complaint by the consumer
* [STRING]    `state`
  - Two letter postal abbreviation of the state of the mailing address provided by the consumer
* [STRING]    `zip_code`
  - The mailing ZIP code provided by the consumer
* [STRING]    `tags`
  - Data that supports easier searching and sorting of complaints
* [STRING]    `consumer_consent_provided`
  - Identifies whether the consumer opted in to publish their complaint narrative
* [STRING]    `submitted_via`
  - How the complaint was submitted to the CFPB
* [DATE]      `date_sent_to_company`
  - The date the CFPB sent the complaint to the company
* [STRING]    `company_response_to_consumer`
  - The response from the company about this complaint
* [BOOLEAN]   `timely_response`
  - Indicates whether the company gave a timely response or not
* [BOOLEAN]   `consumer_disputed`
  - Whether the consumer disputed the company's response
* [STRING]    `complaint_id`
  - Unique ID for complaints registered with the CFPB

-------------------------------------------------------------------------------
*Do not make edits above this line.*
