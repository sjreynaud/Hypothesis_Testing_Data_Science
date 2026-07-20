**📘 Project Overview**

This repository integrates **three major components** demonstrating modern hypothesis‑testing practice in data science:

- A scholarly literature review synthesizing classical NHST, resampling, FDR control, sequential inference, and Bayesian approaches.
- A practical application using a synthetic e‑commerce dataset (n = 500) to evaluate business‑relevant hypotheses.
- A fully reproducible R workflow including data generation, hypothesis testing, and visualization.

This project reflects best practices in statistical reasoning, reproducible analytics, and transparent documentation.

**📁 Repository Structure**

<img width="351" height="457" alt="image" src="https://github.com/user-attachments/assets/1c3eb62f-f919-4670-943e-606c734caf38" />



Each folder is structured to support reproducibility, clarity, and stakeholder review.

**📄 Included Documents**

**Literature Review**

Located in literature-review/.

This document synthesizes foundational and modern hypothesis‑testing methods, including:

- Classical NHST
- Effect sizes and power analysis
- Bootstrap and permutation tests
- False Discovery Rate (FDR) control
- Sequential / always‑valid inference
- Bayesian hypothesis testing

It provides the theoretical backbone for the applied work.

**Practical Application**

Located in practical-application/.

This report applies three classical tests to a synthetic e‑commerce dataset:

- Independent samples t‑test
- Chi‑square test of independence
- One‑tailed t‑test

Includes assumption checks, effect sizes, and interpretation aligned with real‑world analytics workflows.

**🔬 Methods Demonstrated**

Classical Methods

- Independent samples t‑test
- One‑tailed t‑test
- Chi‑square test of independence
- Two‑sample proportion test

**Modern Approaches (Literature Review)**

- Bootstrap resampling
- Permutation tests
- False Discovery Rate (FDR)
- Sequential inference
- Bayesian hypothesis testing

**🧪 Reproducible R Workflow**

**1. Generate Synthetic Data**

Run:
R
source("r-scripts/data_generation.R")

This script:
- Creates a synthetic dataset (n = 500)
- Simulates page views, time spent, A/B versions, and conversion outcomes
- Saves the dataset to practical-application/synthetic_data.csv

**2. Run Hypothesis Tests**

Run:
R
source("r-scripts/hypothesis_tests.R")

This script:
- Computes conversion summaries
- Performs a two‑sample proportion test
- Performs a chi‑square test of independence
- Saves results to outputs/test_results/

**3. Generate Visualizations**

Run:
R
source("r-scripts/visualization.R")

This script:
- Creates histograms of page views and time spent
- Saves figures to outputs/figures/

**🎯 Stakeholder Value**

This repository demonstrates:

**Statistical competency**
Clear understanding of classical and modern hypothesis‑testing frameworks.

**Reproducibility**
Scripts are modular, labeled step‑by‑step, and produce consistent outputs.

**Documentation quality**
The literature review and practical application show strong academic writing and APA‑7 formatting.

**Real‑world relevance**
The applied analysis mirrors workflows used in e‑commerce analytics, experimentation, and data‑driven decision‑making.

**Project readiness**
The project is structured exactly how hiring managers, senior data scientists, and PhD admissions committees expect to see applied statistical work.

**📦 Requirements**
Install required R packages:

** R **
install.packages(c("dplyr", "ggplot2"))

**📬 Author**
Sidney J Reynaud, Jr.  
National University
July 2026
