# LIMS2 Migration Schemas

This repository contains schema documentation for existing tables in LIMS2.

## Schemas

Table schemas in data dictionary format are located in the `schemas/` directory. These schemas are organized as one document (CSV format) per LIMS2 table, in a standard data dictionary format, including a column for foreign key associations for each field. 


## Mappings

Mapping documents:

1. [LIMS table manifest](https://github.com/AllenInstitute/CDS-metadata-schemas/docs/mappings/lims_table_manifest.csv)  This is a manifest of all tables which maps foreign key associations between the tables in LIMS. For mapping to individual fields in a given table, see the table documentation in the `schemas/` directory. Additional curation of annotations on table usage is ongoing. 

2. [runplan_schema](https://github.com/AllenInstitute/CDS-metadata-schemas/docs/mappings/runplan_schema.png)  Created by Jose Melchor. This is a diagram with a partial view of tables related to runplans. Associations colored in orange are not direct database associations, but Model associations (aka ‘through’ associations')
