# `nlm_rxnorm.rxnsab_06_23`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `vcui`
  - CUI of the versioned SRC concept for a source
* [STRING]    `rcui`
  - CUI of the root SRC concept for a source
* [STRING]    `vsab`
  - The versioned source abbreviation for a source, e.g., NDDF_2004_11_03
* [STRING]    `rsab`
  - The root source abbreviation, for a source e.g. NDDF
* [STRING]    `son`
  - The official name for a source
* [STRING]    `sf`
  - The Source Family for a source
* [STRING]    `sver`
  - The source version, e.g., 2001
* [STRING]    `vstart`
  - The date a source became active, e.g., 2001_04_03
* [STRING]    `vend`
  - The date a source ceased to be active, e.g., 2001_05_10
* [STRING]    `imeta`
  - The version of the Metathesaurus a source first appeared, e.g., 2001AB
* [STRING]    `rmeta`
  - The version of the Metathesaurus a source was removed, e.g., 2001AC
* [STRING]    `slc`
  - The source license contact information. A semi-colon separated list containing the following fields: Name; Title; Organization; Address 1; Address 2; City; State or Province; Country; Zip or Postal Code; Telephone; Contact Fax; Email; URL
* [STRING]    `scc`
  - The source content contact information. A semi-colon separated list containing the following fields: Name; Title; Organization; Address 1; Address 2; City; State or Province; Country; Zip or Postal Code; Telephone; Contact Fax; Email; URL
* [STRING]    `srl`
  - 0,1,2,3,4 - explained in the License Agreement.
* [STRING]    `tfr`
  - The number of terms for this source in RXNCONSO.RRF, e.g., 12343 (not implemented yet)
* [STRING]    `cfr`
  - The number of CUIs associated with this source, e.g., 10234 (not implemented yet)
* [STRING]    `cxty`
  - The type of relationship label (Section 2.4.2 of UMLS Reference Manual)
* [STRING]    `ttyl`
  - Term type list from source, e.g., MH,EN,PM,TQ
* [STRING]    `atnl`
  - The attribute name list, e.g., MUI,RN,TH,...
* [STRING]    `lat`
  - The language of the terms in the source
* [STRING]    `cenc`
  - Character set as specified by the IANA official names for character assignments http://www.iana.org/assignments/character-sets
* [STRING]    `curver`
  - A Y or N flag indicating whether or not this row corresponds to the current version of the named source
* [STRING]    `sabin`
  - A Y or N flag indicating whether or not this row is represented in the current MetamorphoSys subset. Initially always Y where CURVER is Y, but later is recomputed by MetamorphoSys.
* [STRING]    `ssn`
  - The short name of a source as used by the NLM Knowledge Source Server.
* [STRING]    `scit`
  - Citation information for a source. A semi-colon separated list containing the following fields: Author(s); Author(s) address; Author(s) organization; Editor(s); Title; Content Designator; Medium Designator; Edition; Place of Publication; Publisher; Date of Publication/copyright; Date of revision; Location; Extent; Series; Availability Statement (URL); Language; Notes

-------------------------------------------------------------------------------
*Do not make edits above this line.*
