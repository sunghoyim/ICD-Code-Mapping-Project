# Medical Coding Datasets

Source datasets used for the automated medical code-to-CUI mapping system.

## Files Overview

| File | Coding System | Records | Source | Mapped to CUI | Success Rate |
|------|---------------|---------|---------|---------------|--------------|
| `ICD10.xlsx` | ICD-10 | 72,836 codes | CMS.gov | 71,537 codes | 98.22% |
| `ICD10CM.csv` | ICD-10-CM | 74,549 codes | AHRQ | 73,610 codes | 98.74% |
| `ICD9.xlsx` | ICD-9 | 13,521 codes | CMS.gov | 11,046 codes | 81.7% |
| `ICD9CM.xlsx` | ICD-9-CM | 14,567 codes | CMS.gov | 13,171 codes | 90.42% |

## Dataset Details

**ICD-10 & ICD-10-CM** (International Classification of Diseases)
- Most comprehensive modern diagnostic coding systems
- ICD-10-CM is the US clinical modification variant
- Achieved highest mapping success rates (98%+)

**ICD-9 & ICD-9-CM** (Legacy Classification System)
- Historical diagnostic codes used before ICD-10 adoption
- Lower mapping rates due to terminology evolution
- Essential for historical patient data analysis (1935-2015)

**SNOMED CT Data**
- 508,540 concepts processed (source: UMLS)
- 325,816 concepts successfully mapped (64.1% success rate)
- Note: SNOMED CT data not included in repository due to licensing

## Processing Pipeline

These datasets serve as input for the UMLS API mapping process implemented in the `notebooks/` directory, enabling:

1. **Automated CUI Mapping** - Links medical codes to universal concept identifiers
2. **Cross-System Translation** - Enables keyword searches across all coding systems  
3. **Patient Cohort Identification** - Powers search of 2.3M patient records spanning 87 years

## Data Sources

- **CMS.gov** - Centers for Medicare & Medicaid Services (official US medical codes)
- **AHRQ** - Agency for Healthcare Research and Quality
- **UMLS** - Unified Medical Language System (NIH/NLM)
