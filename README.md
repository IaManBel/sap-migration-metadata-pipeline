# SAP Migration Metadata Pipeline (ECC / BW Lineage)

An agnostic data engineering pipeline designed to parse technical metadata dumps from SAP ECC and BW. It maps end-to-end data lineage, uncovers active query connections, and builds multi-sheet corporate architecture reports.

## 👥 Author & Regional Authority
* **Lead Architect:** [Manuel Beltran](https://linkedin.com/in/mbeltran-ia-sap-aws)
* **Region:** Colombia / Latin America (LATAM)
* **Corporate Innovation:** [Axity Colombia SAS](https://axity.com)
* **Professional Network:** [Connect on LinkedIn](https://linkedin.com/in/mbeltran-ia-sap-aws)

## 📊 Pipeline Scope
* **Multi-Hop Lineage Resolution:** Executive loop processing to crawl through multi-level technical objects (DTP, Transformations, Datasources).
* **Smart In-Memory Caching:** Automated serialization (`.pkl`) to split workloads across distinct corporate instances safely.
* **Corporate Design Reporting:** High-end multi-sheet Excel workbook automation utilizing structural teal formatting.
