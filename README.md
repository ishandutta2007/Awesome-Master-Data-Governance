# Awesome-Master-Data-Governance

## Top Master Data Governance Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Master Data Management (MDM), Golden Records, Data Quality, Hierarchy Management & Multi-Domain Governance*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Master Data Governance / MDM**. These systems create and maintain trusted “golden” records for customers, products, suppliers, locations, and other domains—enforcing quality, hierarchy, survivorship, and stewardship workflows across the enterprise.



**Examples** include Profisee, Reltio, Semarchy, Ataccama, Stibo Systems, Informatica MDM, SAP Master Data Governance, IBM InfoSphere MDM, Talend MDM, and EnterWorks (the category leaders).



**Open-source emphasis**: Full multi-domain enterprise MDM remains largely commercial. Practical open options center on **product information management (PIM)** platforms with MDM-like capabilities (**AtroPIM / AtroCore**, **Pimcore**), lighter master-data tools, and open data-quality frameworks. This section lists the strongest available open resources and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Profisee](https://profisee.com/)**  

  Enterprise master data management platform known for usability, Microsoft-centric integration, and strong governance workflows; frequently recognized in analyst MDM evaluations.



- **[Reltio](https://www.reltio.com/)**  

  Cloud-native MDM and data-unification platform delivering real-time golden records, AI-assisted matching, and multi-domain master data.



- **[Semarchy](https://www.semarchy.com/)**  

  Intelligent data management platform combining MDM, data quality, and data integration for governed golden records and analytics-ready data.



- **[Ataccama](https://www.ataccama.com/)**  

  Data quality and master data platform with strong profiling, cleansing, and governance capabilities for enterprise data domains.



- **[Stibo Systems](https://www.stibosystems.com/)**  

  Multidomain MDM and product information management specialist serving complex product, supplier, and customer data scenarios.



- **[Informatica MDM](https://www.informatica.com/)**  

  Established enterprise MDM suite covering customer, product, and multi-domain master data with extensive connectivity and governance features.



- **[SAP Master Data Governance (MDG)](https://www.sap.com/)**  

  SAP’s master data governance solution tightly integrated with S/4HANA and the broader SAP ecosystem for material, business partner, and other domains.



- **[IBM InfoSphere MDM](https://www.ibm.com/)**  

  Enterprise master data management capabilities within the IBM data and AI portfolio for creating trusted golden records at scale.



- **[Talend MDM (Qlik / Talend ecosystem)](https://www.talend.com/)**  

  Master data and data-quality capabilities historically part of the Talend portfolio, often used alongside integration and governance tools.



- **[EnterWorks](https://www.enterworks.com/)**  

  Multidomain MDM and PIM platform focused on product, supplier, and customer data for manufacturers, distributors, and retailers.



## Open-Source GitHub Projects

- **[AtroPIM / AtroCore](https://github.com/atrocore/atropim)**  

  Flexible open-source PIM and data-management platform with configurable data models, strong product-master capabilities, and MDM-oriented features on the AtroCore foundation.



- **[Pimcore](https://github.com/pimcore/pimcore)**  

  Open-source platform combining PIM, DAM, MDM-style master data, and digital experience features—widely used for product and customer data hubs.



- **[Broccoli-MDM and lightweight open MDM tools](https://github.com/)**  

  Smaller open-source master data management utilities for loading, editing, and controlling common reference data via a GUI.



- **[Apache Atlas](https://github.com/apache/atlas)**  

  Open metadata management and governance framework often used for data cataloging, lineage, and governance of analytical and master-like datasets.



- **[DataHub (LinkedIn / Acryl)](https://github.com/datahub-project/datahub)**  

  Open-source metadata platform for data discovery, observability, and governance that can complement master-data initiatives.



- **[Open data quality frameworks (Great Expectations, etc.)](https://github.com/great-expectations/great_expectations)**  

  Tools for validating, profiling, and monitoring data quality—essential building blocks of any MDM program.



- **[Entity resolution and matching open libraries](https://github.com/)**  

  Academic and community libraries for deduplication, record linkage, and survivorship logic used inside custom MDM pipelines.



- **[Reference data and hierarchy open managers](https://github.com/)**  

  Simple open applications for managing code lists, hierarchies, and reference data domains.



- **[Talend Open Studio / open integration heritage](https://github.com/)**  

  Historical open integration components sometimes reused in data-quality and consolidation workflows.



- **[Configurable entity-store open platforms](https://github.com/)**  

  Low-code or metadata-driven open systems that can be configured as lightweight multi-domain master data stores.



### Additional Strong Open-Source Options

- Using **AtroPIM / AtroCore** or **Pimcore** when product (and related) master data is the primary domain and an open stack is desired.

- Combining **open metadata platforms** (DataHub, Atlas) with data-quality tools for governance visibility.

- Building domain-specific golden-record pipelines with open matching libraries and a governed database—suitable for narrower scopes.

- Accepting that multi-domain enterprise MDM with sophisticated survivorship, stewardship UI, workflow, and scale still favors commercial platforms (Profisee, Reltio, Semarchy, Informatica, SAP MDG, Stibo, IBM, Ataccama, etc.).

- Focusing open-source efforts on product master data, data quality, metadata, and avoiding lock-in for non-core domains.



**Frameworks for building custom systems**: Define domains and quality rules → match and merge records with open or commercial engines → publish golden records via APIs → steward exceptions in a workflow UI → catalog everything in an open metadata platform. Suitable for organizations with strong data-engineering capacity. Most large enterprises still adopt commercial MDM platforms for multi-domain governance and operational stewardship.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Master data underpins critical business processes and regulatory reporting. Open-source or self-built MDM solutions require careful design of matching rules, auditability, security, and stewardship processes. This list is not architectural or compliance advice.



---

**Made for data governance leaders, MDM architects, and enterprise data teams.**

Let's keep master data trusted, governed, and as open as practical.
