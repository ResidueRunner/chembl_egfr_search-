# ChEMBL Molecule Search (EGFR)

## Objective
Query the ChEMBL REST API to retrieve molecules targeting **EGFR (CHEMBL203)** and extract activity values.

## Implementation Details
- Used ChEMBL REST API
- Queried activities for target: `CHEMBL203`
- Extracted:
  - Molecule ChEMBL ID
  - Activity Type (IC50, Ki, etc.)
  - Activity Value
  - Activity Units
  - Assay Description
- Filtered valid activity entries
- Exported at least 20 molecules

## Output
-JSON file with at least 20 molecules
