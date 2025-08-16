# Medical Code Translation Tool for Patient Cohort Identification

**Automating disease name translation to standardized medical codes for clinical research**

![Introduction](images/Intro.png)

## Presentation Links
- [Presentation](documentation/MayoClinicPresentation.pdf) - Full project overview and technical details

- [Summary Poster](documentation/MayoClinicInternPoster.pdf) - Key highlights and findings

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Technologies Used](#technologies-used)
4. [Objectives](#objectives)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Future Work](#future-work)

## Introduction
This project addresses a critical challenge faced by healthcare startups and researchers working with the Mayo Clinic Platform: translating disease names and keywords into standardized medical codes for accurate patient cohort identification.

Healthcare startups often lack expertise in complex medical coding systems like ICD-10-CM and SNOMED CT, yet need these codes to search clinical databases effectively. Manual translation is time-consuming and error-prone, creating barriers to timely research and development.

I developed a Python-based automation tool that instantly converts disease names into comprehensive sets of diagnosis codes, enabling faster and more accurate patient cohort discovery. The system processes keyword searches and returns all relevant standardized codes, streamlining the research workflow for Mayo Clinic Platform partners.

**Key Impact:** Mapped over 500,000 diagnosis codes with high accuracy, significantly reducing manual effort and improving cohort identification precision for clinical research teams.

## Problem Statement

Healthcare startups partnering with Mayo Clinic Platform face a significant technical barrier: they possess disease names and medical keywords but lack the specialized knowledge to translate these into standardized diagnostic codes (ICD-10-CM, SNOMED CT) required for clinical database searches.

**The Challenge:**
- Startups spend hours manually researching code mappings
- Incomplete or incorrect code selection leads to missed patients in cohort identification
- Complex relationships between coding systems create translation errors
- Manual processes don't scale for large research projects

**Business Impact:**
Without efficient code translation, partner organizations struggle to define comprehensive patient cohorts, delaying research timelines and potentially missing critical patient populations. This bottleneck limits the Mayo Clinic Platform's ability to support external partners effectively.

**Technical Gap:**
Existing mapping resources require deep medical coding expertise and don't provide automated, keyword-based search capabilities that non-expert users need for rapid cohort development.

## Technologies Used

- **Python** - Core development language (pandas, numpy for data processing)
- **SparkSQL** - Large-scale data processing and joins with patient data
- **UMLS (Unified Medical Language System)** - Medical concept mapping via CUIs
- **Data visualization libraries** - matplotlib/seaborn for charts and patient distribution analysis
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
