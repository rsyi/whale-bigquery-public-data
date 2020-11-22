# `fda_food.food_enforcement`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `classification`
  - Numerical designation (I, II, or III) that is assigned by FDA to a particular product recall that indicates the relative degree of health hazard. Class I = Dangerous or defective products that predictably could cause serious health problems or death. Examples include: food found to contain botulinum toxin, food with undeclared allergens, a label mix-up on a lifesaving drug, or a defective artificial heart valve. Class II = Products that might cause a temporary health problem, or pose only a slight threat of a serious nature. Example: a drug that is under-strength but that is not used to treat life-threatening situations. Class III = Products that are unlikely to cause any adverse health reaction, but that violate FDA labeling or manufacturing laws. Examples include: a minor container defect and lack of English labeling in a retail food.
* [DATE]      `center_classification_date`
* [DATE]      `report_date`
  - Date that the FDA issued the enforcement report for the product recall.
* [STRING]    `postal_code`
* [DATE]      `termination_date`
* [DATE]      `recall_initiation_date`
  - Date that the firm first began notifying the public or their consignees of the recall.
* [STRING]    `recall_number`
  - A numerical designation assigned by FDA to a specific recall event used for tracking purposes.
* [STRING]    `city`
  - The city in which the recalling firm is located.
* [INTEGER]   `event_id`
  - A numerical designation assigned by FDA to a specific recall event used for tracking purposes.
* [STRING]    `distribution_pattern`
  - General area of initial distribution such as, “Distributors in 6 states: NY, VA, TX, GA, FL and MA; the Virgin Islands; Canada and Japan”. The term “nationwide” is defined to mean the fifty states or a significant portion. Note that subsequent distribution by the consignees to other parties may not be included.
* [STRING]    `recalling_firm`
  - The firm that initiates a recall or, in the case of an FDA requested recall or FDA mandated recall, the firm that has primary responsibility for the manufacture and (or) marketing of the product to be recalled.
* [STRING]    `voluntary_mandated`
  - Describes who initiated the recall. Recalls are almost always voluntary, meaning initiated by a firm. A recall is deemed voluntary when the firm voluntarily removes or corrects marketed products or the FDA requests the marketed products be removed or corrected. A recall is mandated when the firm was ordered by the FDA to remove or correct the marketed products, under section 518(e) of the FD&C Act, National Childhood Vaccine Injury Act of 1986, 21 CFR 1271.440, Infant Formula Act of 1980 and its 1986 amendments, or the Food Safety Modernization Act (FSMA).
* [STRING]    `state`
  - The U.S. state in which the recalling firm is located.
* [STRING]    `reason_for_recall`
  - Information describing how the product is defective and violates the FD&C Act or related statutes.
* [STRING]    `initial_firm_notification`
  - The method(s) by which the firm initially notified the public or their consignees of a recall. A consignee is a person or firm named in a bill of lading to whom or to whose order the product has or will be delivered.
* [STRING]    `status`
  - On-Going = A recall which is currently in progress.  Completed = The recall action reaches the point at which the firm has actually retrieved and impounded all outstanding product that could reasonably be expected to be recovered, or has completed all product corrections. Terminated = FDA has determined that all reasonable efforts have been made to remove or correct the violative product in accordance with the recall strategy, and proper disposition has been made according to the degree of hazard. Pending = Actions that have been determined to be recalls, but that remain in the process of being classified.
* [STRING]    `product_type`
* [STRING]    `country`
  - The country in which the recalling firm is located.
* [STRING]    `product_description`
  - Brief description of the product being recalled.
* [STRING]    `code_info`
  - A list of all lot and/or serial numbers, product numbers, packer or manufacturer numbers, sell or use by dates, etc., which appear on the product or its labeling.
* [STRING]    `address_1`
* [STRING]    `address_2`
* [STRING]    `product_quantity`
  - The amount of defective product subject to recall.
* [STRING]    `more_code_info`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
