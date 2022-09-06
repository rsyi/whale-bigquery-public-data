# `patents_dsep.disclosures_13`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `family_id`
  - Family ID (simple family). Grouping on family ID will return all publications associated with a simple patent family (all publications share the same priority claims). This is empty if the disclosure could not be matched to any patents.
* [STRING]    `record_id`
  - Unique ID for each record in the database
* [STRING]    `disclosure_event`
  - A disclosure event refers to one or more IPR discloses from a given firm to a given SSO on a given date. A disclosure event may include multiple patents and/or blankets, referring to one or more standards. While some SSO archives are organized around disclosure events and other are not, our disclosure events are constructed from the data in a uniform way.
* [STRING]    `sso`
  - Standard setting organization (SSO) at which the disclosure was made
* [STRING]    `patent_owner_harmonized`
  - Harmonised and cleaned name of the company or organisation that made the disclosure. Accounts for different spellings of a firm name within or across SSOs. But does not account for mergers and acquisitions after the data od diclosure. Note that, in the case of a third party disclosure, the patent owner is not the one that also submitted the seclaration
* [STRING]    `patent_owner_unharmonized`
  - Name of the company, as it appears in the original disclosure, before harminization.
* [INTEGER]   `date`
  - Date of the original statement submitted to the SSO
* [STRING]    `standard`
  - Name of the standard for which the IPR is disclosed (if provided in the original disclosure)
* [STRING]    `committee_project`
  - Name of the committee for which the IPR is disclosed (if provided in the original disclosure)
* [STRING]    `tc_name`
  - Technical committee relevant for the disclosure (if provided in the original disclosure)
* [STRING]    `sc_name`
  - Standard committee relevant for the disclosure (if provided in the original disclosure)
* [STRING]    `wg_name`
  - Working Group relevant for the disclosure (if provided in the original disclosure)
* [STRING]    `licensing_commitment`
  - Licensing commitment with respect to the disclosed patents
* [STRING]    `copyright`
  - Equal to 1 if the disclosed IPR is a copyright instead of a patent
* [STRING]    `blanket_type`
  - A blanket disclosure (sometimes called 'generic disclosure) is a disclosure in which a party indicates it believes it may own relevant IP, but does not provide the identity of any patents or pending patent applications.This field  indicates whether this is the case, and if so, for which specific activity or standard this blanket is submitted. It can take the following values: (0) No blanket, (1) Blanket for all SDO activities, (2) Blanket for a project, committee, subcommitee or technical committee, (3) Blanket for a specific standard or specific technical specification
* [STRING]    `blanket_scope`
  - Indicates to which specific project, subproject, specific standard or specific technical specification the blanket claim refers. Only exists if BLANKET_TYPE has the value 2 or 3.
* [STRING]    `third_party`
  - It indicates wheather the disclosure was made by a third party
* [STRING]    `reciprocity`
  - Indicates whether the disclosure explicitely indicates the licensing commitment is on the condition of reciprocity. Please note that some SSOs may have differerent rules on whether such a condition is 'automatically' implied
* [STRING]    `serial_cleaned`
  - For all US or EP patents, this field shows the serial number of the patent application that was provided in the original disclosure (if any). It is cleaned in the sense that it uses a standardised format (field length, comma's, slashes, etc.) Note that to related these numbers to the serial numbers in years, a translation was used as found on http://www.uspto.gov/web/offices/ac/ido/oeip/taf/filingyr.htm
* [STRING]    `pub_cleaned`
  - For all US or EP patents, this field shows the publication number that was provided in the original disclosure (if any). It is cleaned in the sense that it uses a standardised format

-------------------------------------------------------------------------------
*Do not make edits above this line.*
