# BurnCare Bone Health Prediction Project

## Overview

This repository contains files for the **BurnCare Bone Health Prediction
Project**, part of the MSBD566 -- Predictive Modeling and Analysis
coursework.\
The goal of this project is to predict bone health outcomes in burn
patients, including **fractures** and **osteomyelitis**, using clinical
and treatment-related data.

## Files

-   `MSBD566_Assignment3_Report (1).pdf` -- Project report including
    methodology, results, and discussion.
-   `burncare_bone_eda_classification (1) (1) (2).ipynb` -- Python
    notebook with data preprocessing, exploratory data analysis (EDA),
    and classification modeling.
-   `README.md` -- This documentation file.

## Project Description

Burn injuries can lead to hidden bone complications that are difficult
to detect clinically. This study explores clinical and imaging data to
identify predictors of bone complications, supporting early detection
and intervention.

### Methodology

-   **Data:** 1,538 patient records, 37 clinical features, 2 target
    variables (`has_fracture`, `has_osteomyelitis`).
-   **Model:** Random Forest Classifier with class weighting.
-   **Metrics:** ROC-AUC, PR-AUC, F1-score, Confusion Matrix.

### Key Findings

-   Burn severity index and hospital stay are strong predictors.
-   Material characteristics and bone health descriptors influence
    outcomes.
-   Future integration with CT imaging is planned for enhanced
    prediction.

## Author

**LaPorchia Davis**\
M.S. Biomedical Data Science Candidate -- Meharry Medical College\
Assistant Professor -- Tennessee State University

------------------------------------------------------------------------

© 2025 LaPorchia Davis. All rights reserved.
