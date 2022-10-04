# `fda_drug.drug_enforcement`
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
* [STRING]    `more_code_info`
* [INTEGER]   `event_id`
  - A numerical designation assigned by FDA to a specific recall event used for tracking purposes.
* [STRING]    `distribution_pattern`
  - General area of initial distribution such as, “Distributors in 6 states: NY, VA, TX, GA, FL and MA; the Virgin Islands; Canada and Japan”. The term “nationwide” is defined to mean the fifty states or a significant portion. Note that subsequent distribution by the consignees to other parties may not be included.
* [STRING]    `openfda_application_number`
  - This corresponds to the NDA, ANDA, or BLA number reported by the labeler for products which have the corresponding Marketing Category designated. If the designated Marketing Category is OTC Monograph Final or OTC Monograph Not Final, then the application number will be the CFR citation corresponding to the appropriate Monograph (e.g. “part 341”). For unapproved drugs, this field will be null.
* [STRING]    `openfda_brand_name`
  - The brand or trade name of the product.
* [STRING]    `openfda_dosage_form`
  - The dosage form of the drug product.
* [STRING]    `openfda_generic_name`
  - The dosage form of the drug product.
* [STRING]    `openfda_manufacturer_name`
  - Name of company corresponding to the labeler code segment of the NDC.
* [STRING]    `openfda_product_ndc`
  - The labeler manufacturer code and product code segments of the NDC number, separated by a hyphen.
* [STRING]    `openfda_product_type`
  - The route of administration of the drug product.
* [STRING]    `openfda_route`
  - The type of drug product.
* [STRING]    `openfda_substance_name`
  - The list of active ingredients of a drug product.
* [STRING]    `openfda_spl_id`
  - A unique identifier for a particular version of a Structured Product Label for a product. Also referred to as the document ID.
* [STRING]    `openfda_spl_set_id`
  - A unique identifier for the Structured Product Label for a product, which is stable across versions of the label.
* [STRING]    `openfda_pharm_class_moa`
  - Mechanism of action. Molecular, subcellular, or cellular level functional activity of a drug product’s pharmacologic class.
* [STRING]    `openfda_pharm_class_cs`
  - Chemical structure. Chemical structure classification of a pharmacologic class.
* [STRING]    `openfda_pharm_class_pe`
  - Physiologic effect. Tissue, organ, or organ system level functional activity of a pharmacologic class.
* [STRING]    `openfda_pharm_class_epc`
  - Established pharmacologic class. A pharmacologic class associated with an approved indication of an active moiety that the FDA has determined to be scientifically valid and clinically meaningful.
* [STRING]    `openfda_upc`
  - Documentation forthcoming.
* [STRING]    `openfda_unii`
  - The Unique Ingredient Identifier of the drug or substance.
* [STRING]    `openfda_rxcui`
  - The RxNorm Concept Unique Identifier. RxCUI is a unique number that describes a semantic concept about the drug product, including its ingredients, strength, and dosage forms.
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

-------------------------------------------------------------------------------
*Do not make edits above this line.*
