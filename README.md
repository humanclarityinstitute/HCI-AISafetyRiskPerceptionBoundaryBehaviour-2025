# AI Safety, Risk Perception & Boundary Behaviour 2025 (Dataset)

**Human Clarity Institute (HCI)**  
**DOI:** 10.5281/zenodo.17782047 
**Version:** v1.0  
**Licence:** CC-BY-4.0  
**Date Published:** 2025-12-02  
**Landing page:** <https://humanclarityinstitute.com/datasets/ai-safety-risk-perception-2025/>  
**Data summary:** <https://humanclarityinstitute.com/data/ai-safety-risk-perception-2025/>  
**Dashboard:** https://humanclarityinstitute.com/data-dashboard/

Part of the Human Clarity Institute’s **AI–Human Experience Data Series**, documenting how people perceive AI safety, uncertainty, boundary risks, system trust, and behavioural responses to emerging AI capabilities.

---

## Repository / Access Links

**GitHub:**    https://github.com/humanclarityinstitute/HCI-AISafetyRiskPerceptionBoundaryBehaviour-2025
**Zenodo:**    https://doi.org/10.5281/zenodo.17782047  
**Figshare:**  https://doi.org/10.6084/m9.figshare.30757625 

This dataset is archived in **GitHub**, **Zenodo**, and **Figshare** for long-term preservation.

---

# 1. Citation

**APA:**  
Human Clarity Institute. (2025). *AI Safety, Risk Perception & Boundary Behaviour 2025* [Data set]. https://doi.org/10.5281/zenodo.17782047  

**BibTeX**  
```bibtex
@dataset{hci_ai_safety_risk_perception_boundary_behaviour_2025,
  author    = {Human Clarity Institute},
  title     = {AI Safety, Risk Perception \& Boundary Behaviour 2025},
  year      = {2025},
  publisher = {Human Clarity Institute},
  doi       = {10.5281/zenodo.17782047},
  url       = {https://humanclarityinstitute.com/datasets/ai-safety-risk-perception-2025/},
  license   = {CC-BY-4.0}
}
```

---

# 2. Summary

**Purpose:**  
To measure how adults evaluate the safety of AI tools, identify potential risks, understand system boundaries, recognise unsafe or overconfident behaviour, and assess their personal thresholds for disengaging from AI systems.

**Scope:**  
Adults aged 18+, across six English-speaking countries.  
Data collected December 2025 via Prolific.  
Final sample size: **n = 301**.

**Themes:**  
AI safety concerns, perceived risk levels, boundary testing, system trust, cautious behaviour, uncertainty, harmful outcome expectations, misuse fears, perceived overreach, risk tolerance, and willingness to stop or avoid AI use.

**Outputs:**  
Likert-style scale responses, scenario-based boundary judgements, open-text reflections, demographic variables, and AI usage patterns.

**Data Integrity Note:**  
This dataset has been fully cleaned, anonymised, and verified according to HCI’s open-data protocol.  
A SHA-256 checksum file is included to ensure long-term data integrity.

---

# 3. Example Prompt / Quote (for RAG context)

“Imagine an AI system gave you an answer that felt unsafe or overconfident. How would you decide whether to trust it, ignore it, or stop using the system?”

---

# 4. Data Sources

| Source   | Description                        | Access / DOI             |
|----------|------------------------------------|--------------------------|
| Prolific | Participant recruitment platform   | https://www.prolific.com |
| —        | No external datasets used          | —                        |

---

# 5. Sample & Files

- **Sample size:** n = 301  
- **Countries:** UK, US, Australia, Canada, New Zealand, Ireland  
- **Files included:**  
  - ai_safety_risk_perception_boundary_behaviour_clean20251202.csv  
  - ai_safety_risk_perception_boundary_behaviour_raw20251202.csv  
  - ai_safety_risk_perception_boundary_behaviour_2025_data_dictionary.csv  
  - README.md  
  - sha256.txt  

---

# 6. Keywords

AI safety, risk perception, boundary behaviour, uncertainty, trust, harmful outcomes, system limits, cautious responses, digital risk assessment, human–AI interaction.

---

# 7. Method

**Design:**  
Cross-sectional online survey.

**Instrument:**  
A structured questionnaire including:  
- 23 Likert-style scale items  
- Scenario-based boundary judgement task  
- Open-text reflection  
- One multi-select values item
- Full demographic spine (age group, gender, education, work status, country, AI tool use, hours online)

**Sampling:**  
Prolific recruitment.  
Adults from the United Kingdom, United States, Australia, Canada, New Zealand, and Ireland.  
Data collected December 2025.

**Ethics:**  
Informed consent obtained.  
Responses anonymised.  
Participants could withdraw before submission.

---

# 8. Variables

A full variable-by-variable description is provided in the data dictionary:  
`ai_safety_risk_perception_boundary_behaviour_2025_data_dictionary.csv`

Includes:  
- Variable names (snake_case)  
- Question labels  
- Scale ranges  
- Scenario response details  
- Notes on open-text variables  

---

# 9. Processing & Cleaning

**Pipeline:**  
1. Exported raw responses from Google Forms  
2. Verified consent responses  
3. Checked for and resolved duplicate Prolific IDs  
4. Verified completeness of entries  
5. Confirmed Likert numeric ranges  
6. Reviewed for straight-lining (none requiring removal)  
7. Renamed headers to HCI-standard snake_case  
8. Validated demographic categories  
9. Generated data dictionary + README  
10. Produced SHA-256 checksums for long-term integrity

---

# 10. Provenance & Linking

**Creator / Publisher:** Human Clarity Institute  
**isBasedOn:** Independent original data collection  

**Related HCI datasets:**  
- Digital Life 2025 — https://humanclarityinstitute.com/datasets/digital-life-2025/  
- Focus & Distraction 2025 — https://humanclarityinstitute.com/datasets/focus-distraction-2025/  
- AI, Work & Human Identity 2025 — https://humanclarityinstitute.com/datasets/ai-human-2025/  
- Cognitive Load & Decision Offloading 2025 — https://humanclarityinstitute.com/datasets/ai-fatigue-decision-2025/  
- Emotion, Identity & Creativity in the Age of AI 2025 — https://humanclarityinstitute.com/datasets/emotion-identity-creativity-2025/  
- Human Values, Purpose & Meaning 2025 — https://humanclarityinstitute.com/datasets/human-values-purpose-meaning-2025/  
- Digital Trust 2025 — https://humanclarityinstitute.com/datasets/digital-trust-2025/  
- AI Media & Online Authenticity 2025 — https://humanclarityinstitute.com/datasets/ai-media-online-authenticity-2025-dataset/  
- AI Decision Dependence & Cognitive Caution 2025 — https://humanclarityinstitute.com/datasets/ai-decision-dependence-cognitive-caution-2025/  

**Related HCI reports:**  
- Values vs Noise — https://humanclarityinstitute.com/reports/values-vs-noise-full-report/  
- Digital Fatigue & Energy — https://humanclarityinstitute.com/reports/digital-fatigue-and-energy-full-report/  
- Why Can’t I Focus? — https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/  
- Coping & Wellbeing — https://humanclarityinstitute.com/reports/coping-and-wellbeing-full-report/  
- Digital Trust — https://humanclarityinstitute.com/reports/digital-trust-full-report/  
- Values Discovery — https://humanclarityinstitute.com/reports/values-discovery-full-report/  

---

# 11. Licence & Reuse

Licence: **CC-BY-4.0**  
Attribution text:  
“Data © Human Clarity Institute (2025), CC-BY-4.0.”

---

# 12. Version History

| Version | Date       | Change          |
|---------|------------|-----------------|
| v1.0    | 2025-12-02 | Initial release |

---

# 13. Contact & Dashboard Integration

Email: info@humanclarityinstitute.com  
Website: https://humanclarityinstitute.com/  
Dashboard Link: https://humanclarityinstitute.com/data-dashboard/
