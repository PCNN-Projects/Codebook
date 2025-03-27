# PCNN Codebook

This repository contains the harmonized codebook developed for the Post-COVID Netwerk Nederland (PCNN) research consortium. It supports researchers in understanding the structure, origin, and meaning of the variables used in Post-COVID and ME/CFS studies across different cohorts.

---

## Repository Structure

- `codebook.csv` – Main file containing all variables, themes, labels, ontology mappings, and value codings.
- `themes_and_subdomains.md` – A categorized list of all Themes and Subdomains used in the codebook.
- `instruments_overview.md` – Summary of all validated instruments and questionnaires represented in the codebook.

---

## Purpose

This codebook was designed to:
- Enable standardized data harmonization across studies.
- Facilitate ontology-based mapping (e.g., SNOMED CT, LOINC, NCIT).
- Help researchers explore, select, and reuse variables relevant to their analyses.

---

##  Columns in `codebook.csv`

| Column | Description |
|--------|-------------|
| Theme | High-level domain (e.g., General Health, Symptoms) |
| Subdomain | Specific topic within the theme |
| Instrument | Questionnaire/tool used to collect the variable |
| Instrument version | Version info where applicable |
| Variable name DRE | Standardized internal name |
| Variable name - FAIR | Ontology-aligned term |
| Variable coding label | Suggested short label |
| Variable label - NL | Dutch label/question |
| Variable label - EN | English label/question |
| Value labels - NL | Dutch answer options |
| Value labels - EN | English answer options |
| Value coding | Numeric or categorical codes |
| Value label - FAIR | FAIR-aligned answer option |
| Source | Data origin (e.g., Portal, Biobank, Trials, Clinics) |

---

## 💡 Notes

- A number of variables and FAIR ontology mappings are currently under internal and external review. These elements will be gradually refined and expanded in subsequent releases, based on expert input and consortium-wide feedback.
- Future updates will include the addition of new instruments such as **Beighton Score** and **FUNCAP-27**, as well as expanded support for structured metadata.

---

##  Contact

For questions, feedback, or collaboration opportunities, please reach out to the PCNN codebook team:

**Dr. Hajar Hasannejadasl**  
Clinical Data Scientist  
Maastricht University Medical Center (MUMC+)  
📧 hajar.hasannejadasl@mumc.nl

**Shuxin Zhang**  
PhD Candidate & FAIR Data Steward  
 Amsterdam UMC  
📧 s.x.zhang@amsterdamumc.nl

**Dr. B.M. Boxma-de Klerk**  
Assistant Professor, Department of Clinical Epidemiology  
Leiden University Medical Center, Leiden, The Netherlands  
📧 b.m.boxma-de_klerk@lumc.nl

---

##  Last updated: March 2025
