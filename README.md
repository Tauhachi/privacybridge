# privacybridge
# PrivacyBridge

**An open-source comparative compliance toolkit bridging the EU General Data Protection Regulation (GDPR) and India's Digital Personal Data Protection Act, 2023 (DPDPA).**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Code License: MIT](https://img.shields.io/badge/Code%20License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--05-green.svg)]()

---

## Why this exists

The European Union's GDPR (2018) and India's DPDPA (2023, in force from 2024–25) are the two largest privacy regimes governing the data of more than 1.8 billion people. Yet the two laws emerged from very different legal traditions, regulate similar conduct in materially different ways, and create real operational friction for any organisation handling personal data across both jurisdictions.

Existing resources tend to read either regime in isolation. PrivacyBridge fills that gap with a practitioner-oriented, side-by-side analysis written from the perspective of someone who has worked under both regimes.

This project is intended for:

- **In-house privacy and compliance teams** at multinational organisations with India-EU data flows
- **Privacy lawyers and consultants** advising on cross-border programmes
- **Data Protection Officers (DPOs)** designing compliance frameworks that satisfy both regimes
- **Academic researchers** working in comparative privacy law
- **Students and early-career practitioners** building expertise in the field

---

## What's inside

### 1. Comparative Analysis (`/docs/01-comparative-analysis/`)

Topic-by-topic side-by-side comparison of GDPR and DPDPA, with practical implications flagged.

- `01-scope-and-extraterritoriality.md` — Material and territorial scope; extraterritorial application
- `02-lawful-basis-and-consent.md` — Consent standards, legitimate interests, legitimate uses
- `03-data-principal-rights.md` — Rights of data subjects/principals; comparative gaps
- `04-cross-border-transfers.md` — SCCs, adequacy, DPDPA's whitelist approach
- `05-breach-notification.md` — Notification timelines, thresholds, content requirements
- `06-dpo-governance-and-significant-data-fiduciaries.md` — DPO appointment, SDF designation
- `07-enforcement-and-penalties.md` — Penalty structures, enforcement bodies, recent actions

### 2. Operational Templates (`/docs/02-templates/`)

Practitioner templates calibrated to satisfy both regimes simultaneously.

- Record of Processing Activities (ROPA) template (GDPR Art. 30 + DPDPA disclosure obligations)
- Data Protection Impact Assessment (DPIA) template
- Breach notification template (dual-track for EU SAs and the Indian Data Protection Board)
- Data Principal / Data Subject access request handler
- Privacy notice / transparency notice checklist

### 3. Case Studies (`/docs/03-case-studies/`)

Anonymised, public-source analyses of major enforcement actions and how they would have played out under the other regime.

### 4. Decision Trees (`/docs/04-decision-trees/`)

Flow-chart style decision aids in plain markdown for common compliance questions:

- Does my processing fall within DPDPA scope?
- Can I transfer this data set out of India / out of the EU?
- Which lawful basis applies under each regime?

### 5. Tools (`/tools/`)

Small open-source utilities. Initial scope (to grow over time):

- `privacy-policy-auditor.py` — Checks a privacy notice against a configurable list of required disclosures under GDPR and DPDPA, flags gaps.
- `compliance-checklist-generator.py` — Generates a tailored checklist based on processing profile (sector, data categories, jurisdictions).

---

## Roadmap

This is a living project. The roadmap below is indicative.

| Phase | Timeline | Scope |
|---|---|---|
| **v0.1 (Launch)** | Q2 2026 | Comparative analysis chapters 1–3, ROPA + DPIA templates, project structure |
| **v0.2** | Q3 2026 | Chapters 4–5, breach notification template, first case study, policy auditor v1 |
| **v0.3** | Q4 2026 | Chapters 6–7, decision trees, second case study |
| **v1.0** | Q1–Q2 2027 | Full first edition; commentary on first wave of DPDPA enforcement |
| **v1.x** | Ongoing | Regular updates with new enforcement actions, EDPB / DPB guidance, AI Act intersections |

---

## How to contribute

Privacy law is moving faster than any one author can track. Contributions are welcome from:

- Privacy lawyers and DPOs in either jurisdiction
- Academics in comparative privacy law
- Compliance technologists building practical tools
- Students working on cross-jurisdictional privacy topics

Open an Issue to flag an inaccuracy, propose a new section, or suggest a case study. Pull Requests are welcome — see `CONTRIBUTING.md` for the contribution standard.

All contributors are credited in the project acknowledgements.

---

## How to cite

If you use PrivacyBridge in academic work, please cite as:

> [Author name], *PrivacyBridge: A Comparative Compliance Toolkit for the EU GDPR and India's Digital Personal Data Protection Act, 2023*, available at https://github.com/Tauhachi/privacybridge, [version], [year].

---

## A note on what this is and is not

PrivacyBridge is an **educational and research resource**. It is not legal advice. The analysis reflects the author's reading of public legislation, regulatory guidance, and published commentary as of the date of each document. Privacy law evolves; readers should verify the current state of the law and seek qualified legal advice for any specific compliance question.

No content in this repository derives from any client engagement, confidential information, or proprietary work product. All sources are public.

---

## License

- **Written content** (everything in `/docs/`) is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it freely, including commercially, with attribution.
- **Code** (everything in `/tools/`) is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## About the author

Maya is an India-qualified lawyer working in the field of data protection and privacy law. PrivacyBridge is maintained as an independent personal project, separate from any employer.


---

*"Privacy compliance for the global economy cannot be built jurisdiction by jurisdiction. The bridges have to be built deliberately. This is one of them."*
