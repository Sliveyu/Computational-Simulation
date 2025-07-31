# Proton vs Photon Treatment Planning

## Overview - Why This Project?

Accurately modeling physical systems is central to many real-world domains. In this case, the project addressed a key challenge in **medical physics** and applied **data analytics, simulation modeling, and quantitative evaluation** to assess and compare five radiotherapy treatment plans for prostate cancer. Using clinical datasets and the open-source planning framework **MatRad**, I investigated how beam configurations influence **tissue-specific radiation exposure**, plan efficiency, and treatment quality.

While domain-specific, this project showcases how analytical thinking and evidence-based methods can be used to optimise outcomes, validate models, and communicate clearly across technical and non-technical audiences. The techniques used are core to analytical roles in any industry and demonstrates how **data science methods can be applied to complex, technical problems**, making them accessible for broader decision-making.

---

## Objectives

- Simulate and compare **proton and photon radiotherapy plans** for prostate cancer using clinical data.
- Analyze how **beam orientation and type** affect radiation dose delivered to target tissue and nearby organs.
- Apply **quantitative metrics** (mean dose, dose-volume histograms, homogeneity index) to evaluate treatment quality.
- Validate model outputs by assessing **variance, reproducibility, and clinical compliance** with dose constraints.
- Communicate key findings through **data visualisation and interpretation**, making technical insights accessible to a non-specialist audience.
- Identify **model limitations and optimisation opportunities** to improve treatment planning accuracy and reliability.

---

## Key Insights

- The **45°/315° proton beam configuration** resulted in a **24.2% reduction in rectal dose** compared to 5 field IMRT photon plans, showing a clear advantage in tissue sparing.
- Proton therapy delivered **superior dose conformity** while minimizing exposure to nearby organs (bladder, rectum, femoral heads), validating its effectiveness in precision treatment planning.
- **Photon plans showed improved dose uniformity** as beam count increased (from 5 to 9 fields), but at the cost of higher exposure to surrounding tissue.
- Simulation outputs showed **<±0.5% performance variance**, far exceeding the ±5% industry threshold—demonstrating **high model reliability** and reproducibility.
- Identified **optimisation limitations** in the MatRad framework, prompting suggestions for improved algorithms, automated contouring, and increasingly diverse patient datasets.

## Thank you for reading!
---