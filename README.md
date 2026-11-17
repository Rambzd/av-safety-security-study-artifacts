# Study Artifacts: Safety and Security Governance, Threat Prioritization, and Tooling Gaps in the Autonomous Driving Industry

This repository contains the anonymized study artifacts accompanying our submission:

> ***Without Cybersecurity, You Cannot Prove Safety: An Empirical Study of Safety and Security Governance, Threat Prioritization, and Tooling Gaps in the Autonomous Driving Industry***

---

## Contents

1. **[`Interview_Protocol.pdf`](Interview_Protocol.pdf)** — **End-to-End Study Protocol**
   - Documents the research questions (SRQ1–SRQ4), purposive maximum-variation sampling across the autonomous driving ecosystem ($N = 15$ practitioners recruited from $200+$ professionals contacted), interview procedure (35–65 minutes), two-layer anonymization protocol (sequential participant identifiers `P1`–`P15` and bracketed organizational placeholders), hybrid inductive–deductive thematic coding workflow, thematic saturation criteria, and IRB ethics protections.

2. **[`Interview_Questionnaire.pdf`](Interview_Questionnaire.pdf)** — **Semi-Structured Interview Guide**
   - Complete IRB-approved semi-structured interview script and follow-up probes organized across all six interview phases:
     - *Opening & Background:* Role level, AD/ADAS experience, and SAE J3016 scope
     - *SRQ1:* Organizational scope, safety vs. security reporting lines, V-model integration, and OEM–Tier-1–Tier-2 supply-chain coordination
     - *SRQ2:* Operational threat priorities vs. academic sensor/perception attack assumptions, and Software-Defined / AI-Defined Vehicle exposure
     - *SRQ3:* Explicit four-way prioritization ranking (*Safety, Security, Cost, and Schedule*), FTTI latency vs. cryptography trade-offs, and regional regulatory vs. litigation drivers
     - *SRQ4:* Practical use of HARA/TARA, static/dynamic analysis, HIL/SIL/vehicle testing, SBOMs, in-vehicle IDS, and OTA patching cadences
     - *Closing:* Industry misconceptions and whether thresholds for "safe enough" and "secure enough" exist

3. **[`Codebook.pdf`](Codebook.pdf)** — **Hierarchical Qualitative Codebook & Representative Quotes**
   - Contains all **6 primary thematic categories** and **37 secondary codes** developed during our hybrid inductive–deductive thematic analysis (178 coded segments across $N = 15$ transcripts), complete with operational code definitions and anonymized verbatim example quotes attributed to `P1`–`P15`.

---

## Figure 1(a) Literature Synthesis Note

To contextualize practitioner threat priorities in Figure 1(a) (*Academic Literature Focus*), we aggregated the attack-taxonomy tables across five autonomous-driving security surveys and Systematizations of Knowledge (SoKs):
- Ren et al., *"The Security of Autonomous Driving: Threats, Defenses, and Future Directions,"* *Proceedings of the IEEE*, 2020.
- Qayyum et al., *"Securing Connected & Autonomous Vehicles: Challenges Posed by Adversarial Machine Learning and the Way Forward,"* *IEEE COMST*, 2020.
- Deng et al., *"Deep Learning-Based Autonomous Driving Systems: A Survey of Attacks and Defenses,"* *IEEE TII*, 2021.
- Kühr et al., *"SoK: Security of the Image Processing Pipeline in Autonomous Vehicles,"* *ACM/IEEE DAC*, 2023.
- Girdhar et al., *"Cybersecurity of Autonomous Vehicles: A Systematic Literature Review of Adversarial Attacks and Defense Models,"* *IEEE OJVT*, 2023.

Each surveyed attack paper was mapped to one or more of the 11 attack surfaces in Figure 1. Because papers addressing multiple surfaces (e.g., camera + LiDAR fusion or sensor spoofing + adversarial patches) were counted in each applicable surface row, the percentages in Figure 1(a) represent non-exclusive shares of the surveyed corpus rather than mutually exclusive categories summing to 100%.
