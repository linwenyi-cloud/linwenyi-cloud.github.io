---
layout: page
title: AI-Assisted Glaucoma Screening
description: Cost-effectiveness of AI-enabled tele-glaucoma screening in a safety-net population
importance: 1
category: research
---

**2025 – present · University of Southern California** · with Dr. Shinyi Wu

Glaucoma is the second leading cause of irreversible vision loss in the U.S., and minority, low-income, and diabetic populations carry
a disproportionate share of the burden. Deep-learning algorithms can now match clinician accuracy for referable glaucoma, but no U.S.
study has compared AI-assisted tele-screening head-to-head with conventional human-grader tele-screening.

This project asks: _in a high-risk, safety-net diabetic population with existing tele-retinal screening infrastructure, is AI-assisted
tele-glaucoma screening more cost-effective than conventional tele-screening?_

**Approach**

- Built a hybrid decision tree–Markov cohort model simulating long-term progression across glaucoma severity states
  (suspect → mild / moderate / severe, untreated and treated → visual impairment → death), with annual cycles.
- Parameterized with published epidemiological data and real-world cost inputs from the Los Angeles County Department of Health
  Services tele-retinal screening program.
- Implemented in Python with deterministic and probabilistic (Monte Carlo) sensitivity analyses to estimate costs, QALYs, and ICERs.
- Ran scenario analyses on screening performance, prevalence, and patient compliance.

**Preliminary findings:** AI-assisted screening appears cost-effective, with an ICER of roughly $13,000/QALY.
