# RICE Prioritization Framework & Trade-Off Analysis

**Project**: Wellspring Wearable & Companion Ecosystem  
**Strategist**: Ayush Shah  

---

## 1. Mathematical Framework
$$\mathbf{\text{RICE Score} = \frac{\text{Reach} \times \text{Impact} \times \text{Confidence}}{\text{Effort}}}$$

- **Reach (1–5)**: Proportion of educators benefiting daily.
- **Impact (1–5)**: Direct effect on mental clarity and teaching readiness.
- **Confidence (0%–100%)**: Certainty in technical feasibility and behavioral adoption.
- **Effort (1–5)**: Engineering, hardware calibration, and operational complexity.

---

## 2. Feature Prioritization Matrix

| Feature Module | Reach | Impact | Confidence | Effort | RICE Score | Roadmap Classification |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Feature A: Timed Calendar Nudges** | 5 | 5 | 95% | 3 | **6.33** | **P0 — MVP Core** |
| **Feature B: Ephemeral Idea Journaling** | 4 | 3 | 95% | 2 | **5.70** | **P1 — MVP Core** |
| **Feature C: Biometric Calmness Reports**| 4 | 4 | 70% | 4 | **2.80** | **Phase 1 Extension** |
| **Feature D: Teacher Community Pods**   | 4 | 3 | 80% | 4 | **2.40** | **Phase 2 Expansion** |

---

## 3. Trade-Off Rationale

1. **Why Timed Nudges (P0)?**
   - The greatest friction point for educators is forgetting to transition before a lecture. Timed calendar-synced nudges require zero manual input, solving the root cause of rushing into class with a noisy mind.
2. **Why Ephemeral Idea Journaling (P1)?**
   - Divergent insights that surface during DMN activation evaporate within 60 seconds if uncaptured. A lightweight 1-tap post-session card secures high utility with low engineering effort.
3. **Why Defer Biometric Reports & Community to Phases 1 & 2?**
   - Reports require complex sensor calibration and signal processing; community pods introduce content moderation and network effect dependencies that are secondary to personal habit formation.
