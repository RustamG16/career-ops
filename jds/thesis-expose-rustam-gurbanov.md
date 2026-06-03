# Master's Thesis Exposé — Rustam Gurbanov

**Source:** `Rustam_Gurbanov/Exposé_RustamG (1).pdf`  
**Student:** 12135224 · AAU Game Studies and Engineering  
**Supervisor:** Univ.-Prof. Dipl.-Ing. Dr. Martin Pinzger  
**Timeline:** Oct 2025 – Mar 2026 (six months)

## Title

Automated Quality Assurance of Gamified Tutorials in a Quality Management Web Application Using LLM-Driven End-to-End Testing and Mutation Testing

## Abstract (summary)

Industrial QM web app at Infineon with **gamified onboarding tutorials** for complex chip-grouping workflows. Thesis designs and evaluates:

- **E2E testing** with **Playwright**
- **Mutation testing** with **Stryker** (test adequacy)
- **LLM-assisted** test generation/refinement via **GitHub Copilot** (feedback-driven)
- **Design Science Research** — compare LLM-assisted vs manual/recorded tests (mutation score, failure detection, maintenance effort)

## Industrial context (Infineon)

- **Chip grouping tool** for Quality Management — reduces test vehicles via device grouping
- Replaces multi-platform manual workflow; **QMhub** hosts guided tutorials (Shepherd.js)
- Rustam's direct development experience motivates the research

## Research questions

1. How to design E2E tests for gamified tutorial workflows in a QM web app?
2. Can LLM-supported feedback improve application and tutorial quality over time?
3. Does this improve tool quality and user engagement (testing + user feedback)?

## Tech stack (thesis system)

| Layer | Technologies |
|-------|----------------|
| Frontend | React, HTML, CSS, **Refine**, Shepherd.js (tutorial overlays) |
| Backend | **C#**, **Node.js**, **MySQL**, **Denodo** |
| Data / infra | HICP, **Amazon Redshift** |
| QA | **Playwright** (E2E), **Stryker** (mutation), GitHub Copilot (LLM support) |
| Deploy | Cloud (OpenShift / industrial cloud context from cv) |

## Gamification scope

Embedded step-by-step guidance (progressive disclosure), not points/badges in current scope. Tutorials are observable and testable as part of executable workflows.

## Evaluation metrics

- Mutation score, pass rates, failure detection, maintenance effort
- User feedback: usefulness, clarity, time to complete tutorial workflows

## Career relevance

Positions this profile for: **Full-stack**, **QA automation**, **DevOps**, **digitalization** roles — especially where React + Playwright + enterprise QM/manufacturing intersect.
