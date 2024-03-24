# Unlocking the Potential of Healthcare Informatics through Disease Code Mapping

**Bridging the Gap Between Disease Names and Standardized Codes**

![Introduction](images/Intro.png)

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Objectives](#objectives)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Discussion](#discussion)
7. [Conclusion](#conclusion)
8. [Code](#code)
9. [Data](#data)
10. [Documentation](#documentation)
11. [Acknowledgments](#acknowledgments)

## Introduction
In the world of healthcare, accurate diagnosis codes are crucial for patient cohort identification and data-driven decisions. This project focuses on mapping various diagnosis codes to simplify patient identification and streamline data analysis.

## Problem Statement
Start-up companies often face challenges in obtaining corresponding codes for disease names, impeding the construction of comprehensive patient cohorts. Diagnostic codes are essential tools in healthcare for identifying patient cohorts, facilitating research, and driving evidence-based decision-making. However, as the coding landscape has evolved, accurately mapping disease codes across different coding systems has become a significant challenge. In the context of the Mayo Clinic Platform (MCP), which collaborates with companies and health institutions to define cohorts, efficient disease code mapping is vital for expanding patient identification, regardless of the diagnostic coding system used.

## Objectives
The primary goal is to create an efficient mapping technique that bridges the gap between disease names and standardized codes, thereby streamlining the process of identifying accurate and standardized codes. An algorithm will be developed to be deployed in MCP data to extract or find patients with any diagnosis code.

## Methodology
### Mapping Process
![Mapping Process](images/Mapping-process.png)

Our approach involves developing heuristics and guidelines for precise translations between different coding systems, such as SNOMED CT and ICD-10-CM. The mapping process considers various relationships between concepts, including one-to-one and many-to-one mappings.

### Leveraging UMLS for Mapping
The Unified Medical Language System (UMLS) plays a pivotal role in bridging concepts between ICD codes and SNOMED CT.

## Results
### Conversion Process Overview
- **Finding a Reliable Source for All Diagnosis Codes**
- **Linking Diagnosis Codes to CUIs (Concept Unique Identifiers)**
- **Creation of a Reference Table**

![Conversion Process](images/Conversion-process.png)

## Discussion
Our research underscores the importance of bridging the gap between ICD codes and SNOMED CT through the Concept Unique Identifier (CUI), empowering data-driven healthcare informatics.

## Conclusion
![Conclusion](images/Conclusion.png)

Efficient disease code mapping is essential for propelling the field of healthcare informatics, enabling comprehensive data analysis, and ultimately improving patient outcomes.

## Code
The `code` folder contains the code used in the mapping process. For detailed information about the code and its usage, refer to the [Code Documentation](code/README.md) within the `code` folder.

## Data
The `data` folder holds datasets and resources used in the mapping process. For detailed information about the data and its usage, refer to the [Data Documentation](data/README.md) within the `data` folder.

## Documentation
For comprehensive documentation, please explore our [full project documentation](documentation/README.md) located in the `documentation` folder.

## Acknowledgments
I express my heartfelt gratitude to several individuals whose support and guidance have been instrumental in the success of this internship project:

- **Nasibeh Zanjirani Farahani**: My mentor, for her unwavering support, expert guidance, and invaluable insights throughout this project.
- **Zachary WareJoncas**: My supervisor, for his constant encouragement, constructive feedback, and dedicated mentorship.

This project was made possible by the collective efforts and support of these individuals and organizations. I am truly grateful for their contributions to my professional growth and the advancement of healthcare informatics.
