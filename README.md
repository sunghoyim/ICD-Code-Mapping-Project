# Healthcare Code Mapping Project
![Introduction](images/Intro.png)

**Project Overview:** Welcome to the Healthcare Code Mapping Project conducted at Mayo Clinic Platform (MCP). Our mission is to bridge the gap between disease names and standardized codes, ultimately enhancing healthcare informatics.

## Table of Contents
- [Introduction](#introduction)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Results](#results)
- [Discussion](#discussion)
- [Acknowledgments](#acknowledgments)
- [Conclusion](#conclusion)
- [Code](#code)
- [Data](#data)
- [Documentation](#documentation)

## Introduction
In the world of healthcare, accurate diagnosis codes are the cornerstone of patient cohort identification and data-driven decisions. Our project focuses on mapping a variety of diagnosis codes to simplify patient identification and streamline data analysis.

### Objectives
Our primary goal is to create an efficient mapping technique that bridges the gap between disease names and standardized codes, facilitating processes within the realm of healthcare informatics.

## Methodology
### Mapping Process
![Mapping Process](images/Mapping-process.png)
Our approach involves the development of heuristics and guidelines for precise translations between different coding systems, such as SNOMED CT and ICD-10-CM. The mapping process takes into consideration different relationships between concepts, including one-to-one and many-to-one mappings.

### Leveraging UMLS for Mapping
The Unified Medical Language System (UMLS) plays a pivotal role in bridging concepts between ICD codes and SNOMED CT.

## Results
Our research has successfully mapped a significant percentage of diagnosis codes to their respective Concept Unique Identifiers (CUIs), with only a small percentage of codes remaining unmapped.

### FuzzyWuzzy Algorithm
The use of the FuzzyWuzzy algorithm has allowed us to achieve highly accurate disease code mappings.

## Discussion
Our research underscores the importance of bridging the gap between ICD codes and SNOMED CT through the Concept Unique Identifier (CUI). This approach empowers data-driven healthcare informatics.

## Acknowledgments
I would like to express my heartfelt gratitude to several individuals whose support and guidance have been instrumental in the success of this internship project.

Nasibeh Zanjirani Farahani: I am deeply thankful to my mentor, Nasibeh Zanjirani Farahani, for her unwavering support, expert guidance, and invaluable insights throughout this project. Her mentorship has been a source of inspiration and a driving force behind the achievements of this research.

Zachary WareJoncas: I extend my sincere appreciation to Zachary WareJoncas, my supervisor, for his constant encouragement, constructive feedback, and dedicated mentorship. His leadership and expertise have played a pivotal role in shaping the project's direction and outcomes.

This project was made possible by the collective efforts and support of these individuals and organizations. I am truly grateful for their contributions to my professional growth and the advancement of healthcare informatics.

## Conclusion
Efficient disease code mapping is essential for propelling the field of healthcare informatics, enabling comprehensive data analysis, and ultimately improving patient outcomes.

## Code
The `code` folder contains the source code for our mapping algorithm. To get started with the code, follow the installation instructions in the [Installation](#installation) section.

## Data
The `data` folder holds datasets and resources used in the mapping process. For detailed information about the data and its usage, refer to the [Data Documentation](data/README.md) within the `data` folder.

## Documentation
For comprehensive documentation, including technical details, data schemas, and usage guidelines, please explore our [full project documentation](documentation/README.md) located in the `documentation` folder.
