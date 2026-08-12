# Data Management System — 05 Hotel Andes Stay

![Python](https://img.shields.io/badge/Python-3.10-blue )
![SQLite](https://img.shields.io/badge/SQLite-3-green )
![Pandas](https://img.shields.io/badge/Pandas-2.0-orange )

Complete data management system developed in the course **Fundamentals of
Data Management** (TECSUP, 2026).

## What does it do

- **ETL and migration** from a legacy base, with post-migration validation.
- **Metadata catalog** (technical, business, sensitivity and lineage) saved
  within the base itself: the base describes itself.
- **Access control by roles** governed by the catalog: no column is
  handwritten in the code.
- **Data quality** measured in all 5 dimensions, with scorecard before/after.
- **Government**: DAMA matrix (Data Owner/Steward) and audit log.

## Architecture

|Layer | Technology |
| --- | --- |
| Ingestion | Menu by roles, CSV from external sources |
| Storage | SQLite (projection to Data Lakehouse) |
| Processing | Python + pandas |
| Consumption | Interactive menu, reports and graphs |

## Results

- Quality: from 83.5 to 92.0 out of 100 (5 measured dimensions).
- 68 columns cataloged with sensitivity and lineage.
- Compliance: Peruvian law 29733 (sensitive data) through access control and audit.

## How to execute it

1. Open the notebook in Google Colab.
2. Run all the cells in order.
3. Run 'menu()` and choose a role.

---
Author: [José Ramiro Portocarrero Cossío.] · [www.linkedin.com/in/josé-ramiro-portocarrero-cossío-a49977115 ]
