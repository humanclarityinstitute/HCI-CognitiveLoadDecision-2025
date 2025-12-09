# Cognitive Load, Fatigue & Decision Offloading 2025 (Dataset, n = 503)

How digital and AI-powered tools influence cognitive load, mental fatigue, decision offloading, and the mental after-effects of AI interaction.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17636370.svg)](https://doi.org/10.5281/zenodo.17636370)

**Latest version:** v3.0 — 2025-12-09  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/ai-fatigue-decision-2025/

**Data summary page:**  
https://humanclarityinstitute.com/data/ai-fatigue-decision-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- Measures cognitive load, mental fatigue, and decision offloading in the AI era  
- Captures after-effects of AI interaction (mental replay, overstimulation, difficulty switching off)  
- Includes validated Likert-scale items (1–7), categorical variables, and one open-text reflection  
- Fully cleaned machine-readable dataset with canonical snake_case variable names  
- Part of the **Human–AI Experience 2025** longitudinal data series

---

## Files Included

| Filename | Description |
|---------|-------------|
| **Cognitive_Load_Decision_Offloading_2025_raw20251118.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **Cognitive_Load_Decision_Offloading_2025_clean20251118.csv** | Clean, machine-ready dataset. Canonical tokens, standardised categorical values, minimal text cleaning. |
| **Cognitive_Load_Decision_Offloading_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksums for all files in this release (raw, clean, dictionary, README). |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

## Provenance & Data Collection

Data collected on **18 November 2025** via **Prolific** as part of HCI’s Human–AI Experience research programme.  
Participants provided **explicit informed consent** for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 503  
- **Countries:** UK, US, Australia, New Zealand, Ireland  
- **Eligibility:** Fluent English  
- **Compensation:** £9.22/hour average reward (GBP)  
- **Approval-rate filter:** None  
- **Attention checks:** None  
- **AI deception traps:** None  
- **Anonymisation:** Prolific IDs and all timestamps removed prior to release  

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| work_status | categorical | Participant employment status (canonical categories). |
| ai_tool_use | categorical | Whether participant uses AI tools (`yes`/`no`). |
| mentally_taxed_by_prompts | numeric | Mentally taxed when crafting AI prompts. |
| ai_judgment_blurring | numeric | AI blurs the line between personal judgment and automation. |
| ai_effects_on_thinking | text | Open-text reflections on how AI affects thinking clarity and decision-making. |

**Multi-select formatting:**  
This dataset does not include multi-select items.  

**Open-text fields:**  
Minimal cleaning applied (trim + newline removal).  
Raw participant meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI Badge |
|--------|-----------|
| **Digital Life 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| **Focus & Distraction 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394086.svg)](https://doi.org/10.5281/zenodo.17394086) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **AI, Work & Human Identity 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17604671.svg)](https://doi.org/10.5281/zenodo.17604671) |
| **AI Safety, Risk Perception & Boundary Behaviour 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046) |

---

## Related Reports

- **Digital Fatigue & Energy**  
  https://humanclarityinstitute.com/reports/digital-fatigue-and-energy-full-report/

- **Coping & Wellbeing**  
  https://humanclarityinstitute.com/reports/coping-and-wellbeing-full-report/

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## Recommended Citation

### **APA**
Human Clarity Institute. (2025). *Cognitive Load, Fatigue & Decision Offloading 2025 (Dataset).* https://doi.org/10.5281/zenodo.17636370

### **BibTeX**
    @dataset{hci_cognitive_load_fatigue_decision_offloading_2025,
      author       = {Human Clarity Institute},
      title        = {Cognitive Load, Fatigue & Decision Offloading 2025},
      year         = {2025},
      publisher    = {Zenodo},
      version      = {v3.0},
      doi          = {10.5281/zenodo.17636370},
      url          = {https://doi.org/10.5281/zenodo.17636370}
    }

---

## Version History

| Version | Date | Change |
|---------|------------|---------|
| v3.0 | 2025-12-09 | Structural improvements to README layout; improved machine readability; Regenerated checksums. |
| v1.1 | 2025-12-04 | Removed Prolific IDs; updated data dictionary; regenerated checksums. |
| v1.0 | 2025-11-18 | Initial release. |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.
