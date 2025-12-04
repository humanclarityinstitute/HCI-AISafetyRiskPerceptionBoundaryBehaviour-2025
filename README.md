
# AI Safety, Risk Perception & Boundary Behaviour 2025 (Dataset, n = 301)

Understanding how everyday people perceive AI safety, risk boundaries, personal comfort, and responsible use in daily life.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046)

**Latest version:** v1.2 — 2025-12-04  
**License:** CC-BY-4.0

**Landing page:** 
https://humanclarityinstitute.com/datasets/ai-safety-risk-perception-2025/   
 
**Data summary:** 
https://humanclarityinstitute.com/data/ai-safety-risk-perception-2025/
  
**Dashboard:** 
https://humanclarityinstitute.com/data-dashboard/

---

##  Key Features
- Captures public perceptions of **AI safety**, **risk limits**, and expectations for responsible AI behaviour  
- Includes **multi-select values**, **AI use cases**, **comfort scales**, and **open-text safety concerns**  
- Fully machine-ready: canonicalised tokens, semicolon-delimited multi-selects, minimal open-text cleaning  
- Real human provenance: **301 fluent-English participants**, UK-equivalent pay, full consent  
- Part of the broader **Human–AI Experience 2025** dataset series

---

##  Files Included

| Filename | Description |
|---------|-------------|
| **ai_safety_risk_perception_boundary_behaviour_raw20251202.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **ai_safety_risk_perception_boundary_behaviour_clean20251202.csv** | Clean, machine-ready dataset. Canonical tokens, standardised multi-selects, minimal text cleaning. |
| **ai_safety_risk_perception_boundary_behaviour_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowable values. |
| **sha256.txt** | SHA-256 checksums for all files in this release. |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

##  Provenance & Data Collection

The dataset was collected on **1 December 2025** via **Prolific** as part of the Human–AI Experience research programme.  
All participants provided **explicit consent** for anonymised open publication.

**Sampling & Quality Controls**
- **Final n:** 301  
- **Countries:** UK, US, Canada, Australia, New Zealand, Ireland  
- **Eligibility:** Fluent English  
- **Compensation:** Average £8.53/hr equivalent  
- **Approval-rate filter:** None  
- **Attention checks:** None used  
- **AI-deception traps:** None included  
- **Anonymisation:** Prolific IDs and timestamps removed before publication  

---

##  Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| **age** | integer | Participant age in years |
| **gender** | string | Self-described gender |
| **country** | string | Country of residence (six English-speaking countries) |
| **ai_primary_use_cases** | multi-select (semicolon-delimited) | Canonical list of how participants primarily use AI |
| **ai_values_multi** | multi-select (semicolon-delimited) | Values participants believe AI systems should prioritise |
| **ai_safety_open_comment** | string (open text) | Free-text concerns about AI safety; minimally cleaned (trim + newline removal) |

**Multi-select formatting:**  
All multi-select variables use canonical semicolon-delimited tokens, e.g.:

```
information_research;work_tasks;learning_studying
```

**Open-text fields** preserve participant meaning exactly, with only safe minimal cleaning applied.

---

## **Related Datasets (Human–AI Experience 2025 Series)**

| Dataset | DOI |
|--------|-----|
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **AI Media & Online Authenticity 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17744452.svg)](https://doi.org/10.5281/zenodo.17744452) |
| **AI Decision Dependence & Cognitive Caution 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17772518.svg)](https://doi.org/10.5281/zenodo.17772518) |
| **Emotion, Identity & Creativity in the Age of AI 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |

---

##  Related Reports

- **Digital Trust — Full Report**  
  https://humanclarityinstitute.com/reports/digital-trust-full-report/

- **Values vs Noise — Full Report**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

##  License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

##  Recommended Citation

```bibtex
@dataset{hci_aisafety_2025,
  author       = {Human Clarity Institute},
  title        = {AI Safety, Risk Perception & Boundary Behaviour 2025},
  year         = {2025},
  publisher    = {Zenodo},
  version      = {1.2},
  doi          = {10.5281/zenodo.17782046},
  url          = {https://doi.org/10.5281/zenodo.17782046}
}
```

---

##  Version History

| Version | Date       | Change                                                     |
|---------|------------|-------------------------------------------------------------|
| v1.2    | 2025-12-05 | Structural improvements to README layout; Improved machine readability |
| v1.1    | 2025-12-04 | Removed Prolific IDs; file replacements                     |
| v1.0    | 2025-12-01 | Initial release                                             |

---

##  Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.
