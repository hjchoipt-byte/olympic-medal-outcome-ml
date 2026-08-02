# Predicting Olympic Medal Outcomes in 1,011 Elite Athletes Using Multimodal Machine Learning

## Overview

This repository contains the reproducibility code for the manuscript:

**Predicting Olympic medal outcomes in 1,011 elite athletes using multimodal machine learning**

The notebook reproduces the analyses reported in the manuscript, including data preprocessing, feature selection, machine-learning model development, model interpretation, sensitivity analyses, and supplementary analyses.

---

## Repository Contents

```
Olympic_Medal_ML_Public_Reproducibility_Code.ipynb
README.md
requirements.txt
CITATION.cff
LICENSE
documentation/
aggregate_results/
```

Additional output files are generated automatically after executing the notebook.

---

## Analysis Workflow

The notebook reproduces the analyses in the following order:

1. Environment and global configuration
2. Data loading and integrity checks
3. Descriptive and missing-data analyses
4. Feature preprocessing and forward feature selection
5. SHAP analyses
6. Primary nested cross-validation
7. Complete-case sensitivity analyses
8. Sports-discipline-excluded sensitivity analyses
9. Additional supplementary analyses
10. Reproducibility and validation checks

---

## Machine-Learning Pipeline

The primary analysis includes:

- Missing-data imputation
- Continuous-variable standardization
- Variance inflation factor (VIF) screening
- Forward feature selection (FFS)
- SHAP interpretation using FFS-selected features
- Independent nested cross-validation
- Threshold sensitivity analyses
- Complete-case sensitivity analyses
- Sports-discipline-excluded sensitivity analyses

Three gradient boosting algorithms were evaluated:

- CatBoost
- XGBoost
- LightGBM

---

## Data Availability

The athlete-level dataset is not included in this repository because it contains institutionally restricted athlete health data.

The datasets generated and/or analyzed during the current study are available from the corresponding author upon reasonable request and subject to institutional approval.

---

## Software Requirements

The analysis was performed using Python.

Required package versions are provided in:

```
requirements.txt
```

---

## Reproducibility

The notebook is intended to be executed sequentially from the first section to the final section.

Running all notebook cells reproduces the analyses reported in the manuscript, provided that the original authorized dataset is available.

---

## Citation

If you use this repository, please cite both the associated research article and the archived software release.

### Article

Choi H, et al.

*Predicting Olympic medal outcomes in 1,011 elite athletes using multimodal machine learning.*

Scientific Reports. *(in press)*

### Software

GitHub Repository

https://github.com/hjchoipt-byte/olympic-medal-outcome-ml

Zenodo DOI

(To be added after DOI registration.)

---

## License

This repository is distributed under the MIT License.

https://doi.org/xxxxxxxx

---

## License

This repository is distributed under the MIT License.
