# Restaurant Inspections 🍲

## Overview

This project was developed as part of **INFO 210: Database Management Systems** class at Drexel University and focuses on transforming a raw, unstructured dataset into a well-designed relational database. The work demonstrates end-to-end database development, including data cleaning, normalization, schema design using Vertabelo, and implementation in Oracle SQL.

The project emphasizes applying core database concepts such as *functional dependencies and normalization to reduce redundancy and improve data integrity*. It also involves *designing an efficient relational schema and building SQL-based data ingestion processes* to migrate and organize the data. Overall, this project showcases practical skills in **data modeling, database design, and structured data management**.

---

## Problem Statement

The original dataset provided for this project was:
- highly denormalized
- exhibited significant data quality issues, including
  - redundant records
  - inconsistent formatting
  - a high risk of update anomalies

These characteristics made the data **difficult to query reliably** and **increased the likelihood of analytical errors**.

---

## Data Transformation and Implementation

To address these challenges, I
- performed comprehensive data cleaning
- applied normalization techniques based on relational design principles
- designed a structured schema to support efficient data organization

I then implemented SQL-based data ingestion processes to migrate the refined data into the database.

This approach
- improves data integrity
- enforces consistency
- enables efficient querying

which ultimately reducing the time and effort required for downstream analysis.

---

## Tech Stack

- **Language:** SQL 
- **Tools:** Redgate Data Modeler, Oracle SQL Developer

---

## Images from the project

### 📊 Database 

### Original Physical Model

<img width="1150" height="1370" alt="image" src="https://github.com/user-attachments/assets/aff8abea-b545-4544-ba69-0fdcb6f199f7" />

### Normalized Physical Model

<img width="1686" height="1124" alt="image" src="https://github.com/user-attachments/assets/e87ee350-f97c-4ca8-8c03-5701b8538b22" />

---

## Future Improvements

**1. Automated data cleaning and ETL pipeline**
- Develop an automated pipeline to handle data preprocessing tasks such as deduplication, formatting standardization, and missing value treatment. This would reduce manual intervention, improve reproducibility, and ensure consistent data quality when the dataset is updated or expanded.

**2. Indexing and query performance optimization**
- Implement indexing on high-frequency query attributes and analyze execution plans to optimize SQL performance. This improvement would significantly enhance query efficiency and scalability as the dataset size increases.

**3. Data visualization and analytics integration**
- Connect the relational database to visualization tools (e.g., Tableau, Power BI, or Python-based dashboards) to enable more intuitive data exploration and insight generation, improving the usability and practical value of the database for analysis.

---

## Final Note

The original dataset for this project was provided by my professor, and references marked with “####” in the code correspond to the professor’s account. The complete dataset can be accessed here: [LINK](https://health.data.ny.gov/Health/Food-Service-Establishment-Last-Inspection/cnih-y5dw/about_data). Additionally, the file original-dataset.csv was exported directly from the same source on 04/28/2026.

Thank you for taking the time to review this project.
