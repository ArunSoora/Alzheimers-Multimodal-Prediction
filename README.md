# Multimodal Prediction of Alzheimer's Disease Progression

This project integrates neuroimaging and real-world actigraphy data to identify digital biomarkers and predict cognitive decline in Alzheimer's disease using machine learning models.

## Project Summary

Alzheimer's disease (AD) affects millions globally and often progresses silently until cognitive symptoms become clinically apparent. Traditional assessments, while useful, miss subtle changes. By combining structural MRI, fMRI, and actigraphy data (sleep, activity), this project explores early markers and builds predictive models for MCI-to-AD progression.

## Objectives

- Examine associations between hippocampal volume, DMN connectivity, and actigraphy-derived behavior patterns.
- Develop machine learning models (SVM, neural networks) that predict 2-year cognitive decline in MCI participants using multimodal data.
- Harmonize ADNI and NSRR datasets using ontology-based approaches for semantic alignment.

## Study Aims

**Aim 1:** Investigate cross-sectional relationships between neuroimaging biomarkers and real-world behavioral patterns in older adults.  
**Aim 2:** Build and validate predictive models using multimodal features to improve accuracy over unimodal models.

## Dataset Sources

- [ADNI (Alzheimer’s Disease Neuroimaging Initiative)](https://adni.loni.usc.edu/)
- [NSRR (National Sleep Research Resource)](https://sleepdata.org/)

## Methodology Summary

- **Data Harmonization:** Mapping heterogeneous data via Alzheimer's Disease Data Element Ontology (ADEO)
- **Statistical Models:** Cross-sectional regression analysis (Aim 1)
- **Machine Learning:** SVM and neural networks with 5-fold cross-validation (Aim 2)
- **Metrics:** Standardized beta coefficients, AUC-ROC, DeLong’s test

## Repository Contents

| File Name                           | Description |
|------------------------------------|-------------|
| `AD_Progression_Specific_Aims.pdf` | Core hypotheses, methods, and outcomes |
| `AD_Progression_Proposal_OnePager.pdf` | Narrative summary of study |
| `AD_Progression_Data_Pipeline.ipynb` | Jupyter notebook for data cleaning, visualization, and modeling |
| `AD_Progression_Resources.zip`     | Packaged project resources (code/data) |

## Contributors

- Arun Kumar Soora  
- Aishwarya Kunam  
- Durga Prasad Bukka  
- Vaibhav Thakur  

## Contact

For questions or collaboration, contact Arun Kumar Soora via [LinkedIn](https://www.linkedin.com/in/arun-kumar-soora).
