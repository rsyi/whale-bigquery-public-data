# `usfs_fia.population_evaluation_type`
`bq-1` | `bigquery-public-data`
Describes the type of evaluation. Evaluation type is needed to generate summary reports for an inventory.	

Pages in FIA Documentation: 7-15

## Column details
* [INTEGER]   `evaluation_type_sequence_number`
  - A unique sequence number used to identify a population evaluation type record.
* [INTEGER]   `evaluation_group_sequence_number`
  - Foreign key linking the population evaluation record to the population evaluation group record.
* [INTEGER]   `evaluation_sequence_number`
  - Foreign key linking the estimation unit record to the evaluation record.
* [STRING]    `evaluation_type`
  - Describes the type of evaluation. Evaluation type is needed to generate summary reports for an inventory. For example, a specific evaluation is associated with the evaluation for tree volume (EXPVOL). At the present time, nine types of evaluations can be produced. See also the REF_POP_EVAL_TYP_DESCR table.
* [STRING]    `eval_type_created_by`
  - See SURVEY.CREATED_BY description for definition.
* [DATE]      `eval_type_created_date`
  - See SURVEY.CREATED_DATE description for definition
* [INTEGER]   `eval_type_created_in_instance`
  - See SURVEY.CREATED_IN_INSTANCE description for definition.
* [STRING]    `eval_type_modified_by`
  - See SURVEY.MODIFIED_BY description for definition.
* [DATE]      `eval_type_modified_date`
  - See SURVEY.MODIFIED_DATE description for definition.
* [INTEGER]   `eval_type_modified_in_instance`
  - See SURVEY.MODIFIED_IN_INSTANCE description for definition.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
