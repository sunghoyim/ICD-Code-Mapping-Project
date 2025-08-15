# Unlocking the Potential of Healthcare Informatics through Disease Code Mapping

**Bridging the Gap Between Disease Names and Standardized Codes**

![Introduction](images/Intro.png)

## Presentation Links
- [Presentation](documentation/MayoClinic_StaffMeeting_Presentation.pptx) - This presentation provides a comprehensive overview of the project.

- [Summary Poster](documentation/Summary_Poster.pptx) - This poster offers a brief summary of the project's key highlights and findings.

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Technologies Used](#technologies-used)
4. [Objectives](#objectives)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Future Work](#future-work)

## Introduction
In the world of healthcare, accurate diagnosis codes are crucial for patient cohort identification and data-driven decisions. This project focuses on mapping various diagnosis codes to simplify patient identification and streamline data analysis.

## Problem Statement
Start-up companies often face challenges in obtaining corresponding codes for disease names, impeding the construction of comprehensive patient cohorts. Diagnostic codes are essential tools in healthcare for identifying patient cohorts, facilitating research, and driving evidence-based decision-making. However, as the coding landscape has evolved, accurately mapping disease codes across different coding systems has become a significant challenge. In the context of the Mayo Clinic Platform (MCP), which collaborates with companies and health institutions to define cohorts, efficient disease code mapping is vital for expanding patient identification, regardless of the diagnostic coding system used.

## Technologies Used

- **Python** - Core development language
- **SparkSQL** - Large-scale data processing
- **UMLS (Unified Medical Language System)** - Medical concept mapping
- **Data visualization tools** - Results presentation
- **Jupyter Notebooks** - Analysis and development environment

## Objectives
The primary goal is to create an efficient mapping technique that bridges the gap between disease names and standardized codes, thereby streamlining the process of identifying accurate and standardized codes. An algorithm will be developed to be deployed in MCP data to extract or find patients with any diagnosis code.

## Methodology
### Mapping Process
![Mapping Process](images/Mapping-process.png)

The solution employs sophisticated heuristics and guidelines for precise translations between coding systems:

- **One-to-one mappings** - Direct concept translations
- **Many-to-one mappings** - Complex concept consolidation
- **CUI-based linking** - Using Concept Unique Identifiers as bridge points

### Leveraging UMLS for Mapping
The Unified Medical Language System serves as the foundational bridge, enabling robust concept mapping between ICD codes and SNOMED CT through standardized medical terminology.

## Results
### Conversion Process Overview
- **Finding a Reliable Source for All Diagnosis Codes**
- **Linking Diagnosis Codes to CUIs (Concept Unique Identifiers)**
- **Creation of a Reference Table**

![Conversion Process](images/Conversion-process.png)

## Future Work

- **Clinical Validation** - Real-world testing with clinical datasets
- **Discover Environment Migration** - Transition to production environment
- **OMOP Integration** - Alignment with Observational Medical Outcomes Partnership standards
- **Expanded Coding Systems** - Support for additional diagnostic code families
