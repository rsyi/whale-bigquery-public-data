# `fda_drug.drug_label`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `openfda_spl_set_id`
  - Unique identifier for the Structured Product Label for a product, which is stable across versions of the label. Also referred to as the set ID.
* [STRING]    `package_label_principal_display_panel`
  - The content of the principal display panel of the product package, usually including the product’s name, dosage forms, and other key information about the drug product.
* [STRING]    `openfda_manufacturer_name`
  - Name of manufacturer or company that makes this drug product, corresponding to the labeler code segment of the NDC.
* [STRING]    `openfda_unii`
  - Unique Ingredient Identifier, which is a non-proprietary, free, unique, unambiguous, non-semantic, alphanumeric identifier based on a substance’s molecular structure and/or descriptive information.
* [STRING]    `openfda_product_type`
* [STRING]    `openfda_rxcui`
  - The RxNorm Concept Unique Identifier. RxCUI is a unique number that describes a semantic concept about the drug product, including its ingredients, strength, and dose forms.
* [STRING]    `openfda_route`
  - The route of administation of the drug product.
* [STRING]    `openfda_generic_name`
  - Generic name(s) of the drug product.
* [STRING]    `openfda_brand_name`
  - Brand or trade name of the drug product.
* [STRING]    `openfda_product_ndc`
  - The labeler manufacturer code and product code segments of the NDC number, separated by a hyphen.
* [STRING]    `openfda_original_packager_product_ndc`
* [STRING]    `openfda_substance_name`
  - The list of active ingredients of a drug product.
* [STRING]    `openfda_spl_id`
  - Unique identifier for a particular version of a Structured Product Label for a product. Also referred to as the document ID.
* [STRING]    `openfda_pharm_class_moa`
  - Mechanism of action of the drug—molecular, subcellular, or cellular functional activity—of the drug’s established pharmacologic class. Takes the form of the mechanism of action, followed by [MoA] (such as Calcium Channel Antagonists [MoA] or Tumor Necrosis Factor Receptor Blocking Activity [MoA].
* [STRING]    `openfda_application_number`
  - This corresponds to the NDA, ANDA, or BLA number reported by the labeler for products which have the corresponding Marketing Category designated. If the designated Marketing Category is OTC Monograph Final or OTC Monograph Not Final, then the application number will be the CFR citation corresponding to the appropriate Monograph (e.g. “part 341”). For unapproved drugs, this field will be null.
* [STRING]    `openfda_nui`
  - Unique identifier applied to a drug concept within the National Drug File Reference Terminology (NDF-RT).
* [STRING]    `openfda_pharm_class_epc`
  - Established pharmacologic class associated with an approved indication of an active moiety (generic drug) that the FDA has determined to be scientifically valid and clinically meaningful. Takes the form of the pharmacologic class, followed by [EPC] (such as Thiazide Diuretic [EPC] or Tumor Necrosis Factor Blocker [EPC].
* [STRING]    `openfda_package_ndc`
  - This number, known as the NDC, identifies the labeler, product, and trade package size. The first segment, the labeler code, is assigned by the FDA. A labeler is any firm that manufactures (including repackers or relabelers), or distributes (under its own name) the drug.
* [STRING]    `carcinogenesis_and_mutagenesis_and_impairment_of_fertility`
  - Information about carcinogenic, mutagenic, or fertility impairment potential revealed by studies in animals. Information from human data about such potential is part of the warnings field.
* [STRING]    `references`
  - This field may contain references when prescription drug labeling must summarize or otherwise relay on a recommendation by an authoritative scientific body, or on a standardized methodology, scale, or technique, because the information is important to prescribing decisions.
* [STRING]    `pregnancy`
  - Information about effects the drug may have on pregnant women or on a fetus. This field may be ommitted if the drug is not absorbed systemically and the drug is not known to have a potential for indirect harm to the fetus. It may contain information about the established pregnancy category classification for the drug. (That information is nominally listed in the teratogenic_effects field, but may be listed here instead.)
* [STRING]    `pharmacokinetics`
  - Information about the clinically significant pharmacokinetics of a drug or active metabolites, for instance pertinent absorption, distribution, metabolism, and excretion parameters.
* [STRING]    `drug_interactions`
  - Information about and practical guidance on preventing clinically significant drug/drug and drug/food interactions that may occur in people taking the drug.
* [STRING]    `id`
  - The document ID, A globally unique identifier (GUID) for the particular revision of a labeling document.
* [STRING]    `indications_and_usage`
  - A statement of each of the drug product’s indications for use, such as for the treatment, prevention, mitigation, cure, or diagnosis of a disease or condition, or of a manifestation of a recognized disease or condition, or for the relief of symptoms associated with a recognized disease or condition. This field may also describe any relevant limitations of use.
* [STRING]    `pharmacokinetics_table`
* [STRING]    `pharmacodynamics_table`
* [STRING]    `microbiology`
  - Documentation forthcoming.
* [STRING]    `contraindications`
  - Information about situations in which the drug product is contraindicated or should not be used because the risk of use clearly outweighs any possible benefit, including the type and nature of reactions that have been reported.
* [INTEGER]   `version`
  - A sequentially increasing number identifying the particular version of a document, starting with 1.
* [STRING]    `spl_medguide`
  - Information about the patient medication guide that accompanies the drug product. Certain drugs must be dispensed with an accompanying medication guide. This field may contain information about when to consult the medication guide and the contents of the medication guide.
* [STRING]    `pediatric_use`
  - Information about any limitations on any pediatric indications, needs for specific monitoring, hazards associated with use of the drug in any subsets of the pediatric population (such as neonates, infants, children, or adolescents), differences between pediatric and adult responses to the drug, and other information related to the safe and effective pediatric use of the drug.
* [STRING]    `information_for_patients`
* [STRING]    `dosage_forms_and_strengths`
* [STRING]    `microbiology_table`
* [STRING]    `recent_major_changes`
  - A list of the section(s) that contain substantive changes that have been approved by FDA in the product labeling. The headings and subheadings, if appropriate, affected by the change are listed together with each section’s identifying number and the month and year on which the change was incorporated in the labeling.
* [STRING]    `description`
  - General information about the drug product, including the proprietary and established name of the drug, the type of dosage form and route of administration to which the label applies, qualitative and quantitative ingredient information, the pharmacologic or therapeutic class of the drug, and the chemical name and structural formula of the drug.
* [STRING]    `dosage_and_administration`
  - Information about the drug product’s dosage and administration recommendations, including starting dose, dose range, titration regimens, and any other clinically sigificant information that affects dosing recommendations.
* [STRING]    `clinical_pharmacology_table`
* [DATE]      `effective_time`
  - Date reference to the particular version of the labeling document.
* [STRING]    `mechanism_of_action`
  - Information about the established mechanism(s) of the drug’s action in humans at various levels (for example receptor, membrane, tissue, organ, whole body). If the mechanism of action is not known, this field contains a statement about the lack of information.
* [STRING]    `geriatric_use`
  - Information about any limitations on any geriatric indications, needs for specific monitoring, hazards associated with use of the drug in the geriatric population.
* [STRING]    `adverse_reactions`
  - Information about undesirable effects, reasonably associated with use of the drug, that may occur as part of the pharmacological action of the drug or may be unpredictable in its occurrence. Adverse reactions include those that occur with the drug, and if applicable, with drugs in the same pharmacologically active and chemically related class. There is considerable variation in the listing of adverse reactions. They may be categorized by organ system, by severity of reaction, by frequency, by toxicological mechanism, or by a combination of these.
* [STRING]    `clinical_pharmacology`
  - Information about the clinical pharmacology and actions of the drug in humans.
* [STRING]    `clinical_studies`
  - This field may contain references to clinical studies in place of detailed discussion in other sections of the labeling.
* [STRING]    `use_in_specific_populations`
  - Information about use of the drug by patients in specific populations, including pregnant women and nursing mothers, pediatric patients, and geriatric patients.
* [STRING]    `nonclinical_toxicology`
  - Information about toxicology in non-human subjects.
* [STRING]    `spl_product_data_elements`
  - Usually a list of ingredients in a drug product.
* [STRING]    `clinical_studies_table`
* [STRING]    `overdosage`
  - Information about signs, symptoms, and laboratory findings of acute ovedosage and the general principles of overdose treatment.
* [STRING]    `pharmacodynamics`
  - Information about any biochemical or physiologic pharmacologic effects of the drug or active metabolites related to the drug’s clinical effect in preventing, diagnosing, mitigating, curing, or treating disease, or those related to adverse effects or toxicity.
* [STRING]    `warnings_and_cautions`
* [STRING]    `dosage_and_administration_table`
* [STRING]    `animal_pharmacology_and_or_toxicology`
  - Information from studies of the drug in animals, if the data were not relevant to nor included in other parts of the labeling. Most labels do not contain this field.
* [STRING]    `how_supplied`
  - Information about the available dosage forms to which the labeling applies, and for which the manufacturer or distributor is responsible. This field ordinarily includes the strength of the dosage form (in metric units), the units in which the dosage form is available for prescribing, appropriate information to facilitate identification of the dosage forms (such as shape, color, coating, scoring, and National Drug Code), and special handling and storage condition information.
* [STRING]    `nursing_mothers`
  - Information about excretion of the drug in human milk and effects on the nursing infant, including pertinent adverse effects observed in animal offspring.
* [STRING]    `set_id`
  - The Set ID, A globally unique identifier (GUID) for the labeling, stable across all versions or revisions.
* [STRING]    `drug_abuse_and_dependence`
  - Information about whether the drug is a controlled substance, the types of abuse that can occur with the drug, and adverse reactions pertinent to those types of abuse.
* [STRING]    `controlled_substance`
  - Information about the schedule in which the drug is controlled by the Drug Enforcement Administration, if applicable.
* [STRING]    `abuse`
  - Information about the types of abuse that can occur with the drug and adverse reactions pertinent to those types of abuse, primarily based on human data. May include descriptions of particularly susceptible patient populations.
* [STRING]    `dependence`
  - Information about characteristic effects resulting from both psychological and physical dependence that occur with the drug, the quantity of drug over a period of time that may lead to tolerance or dependence, details of adverse effects related to chronic abuse and the effects of abrupt withdrawl, procedures necessary to diagnose the dependent state, and principles of treating the effects of abrupt withdrawal.
* [STRING]    `drug_and_or_laboratory_test_interactions`
  - Information about any known interference by the drug with laboratory tests.
* [STRING]    `purpose`
  - Information about the drug product’s indications for use.
* [STRING]    `active_ingredient`
  - A list of the active, medicinal ingredients in the drug product.
* [STRING]    `inactive_ingredient`
  - A list of inactive, non-medicinal ingredients in a drug product.
* [STRING]    `spl_patient_package_insert`
  - Information necessary for patients to use the drug safely and effectively.
* [STRING]    `information_for_owners_or_caregivers`
  - Documentation forthcoming.
* [STRING]    `instructions_for_use`
  - Information about safe handling and use of the drug product.
* [STRING]    `ask_doctor`
  - Information about when a doctor should be consulted about existing conditions or sumptoms before using the drug product, including all warnings for persons with certain preexisting conditions (excluding pregnancy) and all warnings for persons experiencing certain symptoms. The warnings under this heading are those intended only for situations in which consumers should not use the product until a doctor is consulted.
* [STRING]    `ask_doctor_or_pharmacist`
  - Information about when a doctor or pharmacist should be consulted about drug/drug or drug/food interactions before using a drug product.
* [STRING]    `do_not_use`
  - Information about all contraindications for use. These contraindications are absolute and are intended for situations in which consumers should not use the product unless a prior diagnosis has been established by a doctor or for situations in which certain consumers should not use the product under any circumstances regardless of whether a doctor or health professional is consulted.
* [STRING]    `keep_out_of_reach_of_children`
  - Information pertaining to whether the product should be kept out of the reach of children, and instructions about what to do in the case of accidental contact or ingestion, if appropriate.
* [STRING]    `other_safety_information`
  - Information about safe use and handling of the product that may not have been specified in another field.
* [STRING]    `questions`
  - A telephone number of a source to answer questions about a drug product. Sometimes available days and times are also noted.
* [STRING]    `stop_use`
  - Information about when use of the drug product should be discontinued immediately and a doctor consulted. Includes information about any signs of toxicity or other reactions that would necessitate immediately discontinuing use of the product.
* [STRING]    `when_using`
  - Information about side effects that people may experience, and the substances (e.g. alcohol) or activities (e.g. operating machinery, driving a car) to avoid while using the drug product.
* [STRING]    `patient_medication_information`
  - Information or instructions to patients about safe use of the drug product, sometimes including a reference to a patient medication guide or counseling materials.
* [STRING]    `teratogenic_effects`
  - Pregnancy category A: Adequate and well-controlled studies in pregnant women have failed to demonstrate a risk to the fetus in the first trimester of pregnancy, and there is no evidence of a risk in later trimesters. Pregnancy category B: Animal reproduction studies have failed to demonstrate a risk to the fetus and there are no adequate and well-controlled studies in pregnant women. Pregnancy category C: Animal reproduction studies have shown an adverse effect on the fetus, there are no adequate and well-controlled studies in humans, and the benefits from the use of the drug in pregnant women may be acceptable despite its potential risks. Pregnancy category D: There is positive evidence of human fetal risk based on adverse reaction data from investigational or marketing experience or studies in humans, but the potential benefits from the use of the drug in pregnant women may be acceptable despite its potential risks.
* [STRING]    `labor_and_delivery`
  - Information about the drug’s use during labor or delivery, whether or not the use is stated in the indications section of the labeling, including the effect of the drug on the mother and fetus, on the duration of labor or delivery, on the possibility of delivery-related interventions, and the effect of the drug on the later growth, development, and functional maturation of the child.
* [STRING]    `pregnancy_or_breast_feeding`
  - Documentation forthcoming.
* [STRING]    `storage_and_handling`
  - Information about safe storage and handling of the drug product.
* [STRING]    `safe_handling_warning`
  - Documentation forthcoming.
* [STRING]    `boxed_warning`
  - Information about contraindications or serious warnings, particularly those that may lead to death or serious injury.
* [STRING]    `user_safety_warnings`
  - When a drug can pose a hazard to human health by contact, inhalation, ingestion, injection, or by any exposure, this field contains information which can prevent or decrease the possibility of harm.
* [STRING]    `precautions`
  - Information about any special care to be exercised for safe and effective use of the drug.
* [STRING]    `warnings`
  - Information about serious adverse reactions and potential safety hazards, including limitations in use imposed by those hazards and steps that should be taken if they occur.
* [STRING]    `general_precautions`
  - Information about any special care to be exercised for safe and effective use of the drug.
* [STRING]    `laboratory_tests`
  - Information on laboratory tests helpful in following the patient’s response to the drug or in identifying possible adverse reactions. If appropriate, information may be provided on such factors as the range of normal and abnormal values expected in the particular situation and the recommended frequency with which tests should be performed before, during, and after therapy.
* [STRING]    `spl_unclassified_section`
  - Information not classified as belonging to one of the other fields. Approximately 40% of labeling with effective_time between June 2009 and August 2014 have information in this field.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
