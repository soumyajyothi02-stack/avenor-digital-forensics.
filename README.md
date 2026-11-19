# avenor-digital-forensics.
AI-powered digital forensics and adversarial ML investigation platform featuring counterfactual contributor attribution, data poisoning analysis, and false-blame prevention.
# AVENOR
### Evidence-Backed Digital Forensics & Adversarial Contributor Investigation

<p align="center">
  **Investigating suspicious dataset contributions without falsely blaming innocent contributors.**
</p>

<p align="center">
  <a href="https://avenor-forensics-core.base44.app">Live Application</a>
</p>

---

## Overview

**AVENOR** is an AI-powered digital forensics and adversarial machine-learning investigation platform designed to investigate suspicious dataset contributions, examine potential data poisoning, and evaluate contributor-level influence on machine-learning model behaviour.

Its central research idea is **evidence-backed counterfactual contributor attribution with false-blame prevention**.

Rather than treating an unusual data pattern or anomaly score as proof of malicious activity, AVENOR is designed to support evidence-based investigation, counterfactual analysis, and uncertainty-aware conclusions.

The platform focuses on an important security research question:

> How can we investigate a contributor's influence on a potentially poisoned machine-learning model without incorrectly accusing an innocent contributor?

## Project Goals

- Investigate potentially suspicious dataset contributions.
- Explore data poisoning and adversarial manipulation.
- Evaluate contributor-level influence on model behaviour.
- Support counterfactual analysis.
- Reduce false attribution through evidence-based assessment.
- Preserve dataset and investigation evidence integrity.
- Present findings in an understandable investigation workflow.

## Application Interface

AVENOR uses a professional digital-forensics interface with an amber-and-cream visual identity, structured navigation, investigation-focused sections, and a dashboard designed to provide an overview of investigative activity.

### Dashboard

The dashboard provides an overview of investigation activity and entry points into the platform's main modules.

![AVENOR Dashboard](docs/screenshots/avenor-dashboard.png)

*Add your actual dashboard screenshot at `docs/screenshots/avenor-dashboard.png`.*

## Main Application Modules

The application interface includes the following sections:

| Module | Purpose |
|---|---|
| Dashboard | Overview of investigative activity |
| Investigations | Investigation management |
| Datasets | Dataset management and inspection |
| Contributors | Contributor-level investigation |
| Evidence Vault | Evidence management and integrity |
| Detection | Suspicious-pattern investigation |
| Attribution | Counterfactual contributor analysis |
| Experiments | Research experiment workspace |
| Reports | Investigation reporting |
| Activity | Investigation activity history |

## Core Research Concept

### 1. Adversarial Data Poisoning

Data poisoning involves manipulating training data to influence the behaviour of a machine-learning model.

AVENOR focuses on investigating scenarios such as:

- Label-flipping attacks.
- Trigger-based or backdoor poisoning.
- Contributor-specific data manipulation.
- Suspicious distribution patterns.

### 2. Counterfactual Contributor Attribution

Counterfactual analysis investigates how model behaviour changes when a contributor's data is excluded.

The intended comparison is:

1. Establish baseline model performance.
2. Exclude a contributor's samples.
3. Evaluate model behaviour under a controlled configuration.
4. Compare attack success rates.
5. Examine changes in clean model performance.
6. Assess the consistency of the observed impact.

A contributor's influence does not establish malicious intent.

### 3. False-Blame Prevention

An important design principle of AVENOR is avoiding unsupported accusations.

An unusual contribution may result from:

- Benign data variation.
- Non-IID distributions.
- Data corruption.
- Label inconsistencies.
- Distribution shift.
- Insufficient evidence.

The investigation methodology should allow an inconclusive outcome when evidence does not support a reliable attribution.

## Evidence Integrity

AVENOR includes an Evidence Vault module intended to support investigation evidence management.

The project incorporates SHA-256 integrity verification as a core evidence-handling concept.

A cryptographic hash can help identify whether the contents of a file have changed between verification points. It does not independently prove the authenticity or origin of a file.

## Technology and Implementation

The application is developed using Base44.

The implementation should be evaluated according to the actual source code and configured services available in the project.

The intended technical areas include:

- Web application development.
- Machine-learning experimentation.
- Adversarial data analysis.
- Counterfactual evaluation.
- Cryptographic integrity verification.
- Investigation and evidence management.
- Data visualisation.

*Add specific framework, model, database and library names only after verifying them against the actual implementation.*

## Security and Research Principles

AVENOR follows these principles:

- Anomaly detection is not proof of malicious intent.
- Counterfactual influence is not proof of intent.
- Investigative conclusions should be supported by evidence.
- Uncertainty must be communicated.
- Synthetic attack simulations must be distinguished from real-world incidents.
- Dataset integrity and investigation traceability matter.
- Research limitations must be disclosed.

## Limitations

AVENOR is a research-oriented project and should not be interpreted as a production-grade digital forensics or incident-response system.

Its conclusions depend on the implemented detection methods, available data, model assumptions, experiment configurations and quality of evidence.

Further validation is required before making claims about detection accuracy, attribution reliability, scalability or resistance to sophisticated attacks.

## Future Improvements

- Expanded adversarial attack benchmarks.
- More robust poisoning detection methods.
- Additional counterfactual attribution strategies.
- Statistical confidence and calibration evaluation.
- Reproducible multi-seed experiments.
- More comprehensive evidence audit mechanisms.
- Expanded research datasets.
- Independent evaluation against established baselines.

## Live Demonstration

**Application:** https://avenor-forensics-core.base44.app

The live application provides access to the AVENOR interface. Feature availability and functionality should be assessed through the deployed application.

## Author

**K. Sawmya Jyothi**

Computer Science and Engineering — Artificial Intelligence and Machine Learning

Project: AVENOR — AI-Powered Digital Forensics & Adversarial Contributor Investigation Platform

---

*Built as an exploration of adversarial machine learning, digital forensics, counterfactual analysis, and responsible contributor attribution.*
