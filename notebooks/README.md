# Medical Code Translation Notebooks

This directory contains Jupyter notebooks that implement the automated medical code-to-CUI mapping system using the UMLS (Unified Medical Language System) API.

## Notebooks Overview

| Notebook | Coding System | Description |
|----------|---------------|-------------|
| `icd10_cui_mapping.ipynb` | ICD-10 | International Classification of Diseases, 10th Revision |
| `icd10cm_cui_mapping.ipynb` | ICD-10-CM | ICD-10 Clinical Modification (US variant) |
| `icd9_cui_mapping.ipynb` | ICD-9 | International Classification of Diseases, 9th Revision |
| `icd9cm_cui_mapping.ipynb` | ICD-9-CM | ICD-9 Clinical Modification (US variant) |
| `snomedct_cui_mapping.ipynb` | SNOMED CT | Systematized Nomenclature of Medicine Clinical Terms |
| `patient_data_analysis.ipynb` | Patient Data Analysis | Exploration of 2.3M patient records across 87 years |

## Technical Process

Each notebook follows a standardized workflow:

1. **Data Import** - Load medical codes from authoritative sources (CMS.gov, AHRQ)
2. **Code Formatting** - Standardize code formats (add decimals, clean data)
3. **UMLS API Integration** - Query UMLS API to retrieve Concept Unique Identifiers (CUIs)
4. **Batch Processing** - Handle large datasets efficiently with error handling
5. **Output Generation** - Export code-to-CUI mappings as CSV files

## Key Results Achieved

- **ICD-10-CM**: 98.74% mapping success rate (73,610/74,549 codes)
- **ICD-10**: 98.22% mapping success rate (71,537/72,836 codes)
- **ICD-9-CM**: 90.42% mapping success rate (13,171/14,567 codes)
- **SNOMED CT**: 64.1% mapping success rate (325,816/508,540 concepts)

## Usage Notes

- All notebooks require UMLS API authentication
- Processing time varies by coding system size
- Output files enable instant keyword-to-medical-code translation for patient cohort identification
