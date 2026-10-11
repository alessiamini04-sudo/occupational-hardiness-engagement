# Occupational Hardiness and Work Engagement

A Python project exploring how commitment, control, and challenge
are associated with work engagement among Italian workers,
accounting for age and gender.

## Data

Secondary analysis of the dataset accompanying **Panari et al. (2026)**.
I did not collect the original data.

- Original dataset: **1,152 observations**
- Main analysis: **841 complete cases**
- Larger sample for sensitivity analysis: **1,129 participants**

[Original study](https://doi.org/10.1038/s41598-025-29016-z) |
[Dataset on OSF](https://osf.io/cegvt/?view_only=1cdd5ff1d22f44f28a10e8bee7ed3acc)

## Analysis

- Data cleaning, missing-value checks, and descriptive statistics
- Correlations and multiple linear regression in two blocks
- Model diagnostics and HC3 robust confidence intervals
- Sensitivity analysis comparing outcome definitions and samples

Work engagement is calculated as the mean of vigor, dedication,
and absorption.

## Main findings

The full model accounts for approximately **25% of the variation
in engagement** in the main sample.

- **Commitment** shows the largest standardized association
  among the three hardiness dimensions.
- **Challenge** shows a smaller positive adjusted association.
- **Control** shows no clear adjusted association in the main
  analysis, but a positive association emerges in the larger
  sample using the alternative outcome.

The positive associations for commitment and challenge are
consistent across the three analyses examined.

## Limitations

The data are cross-sectional and self-reported, so the findings
do not establish causality. Missing absorption scores affect
sample selection, and the sensitivity analysis does not remove
possible selection bias. Model fit is evaluated within the sample,
not on new participants.

## How to run

Open `hardiness_engagement.ipynb` in **Google Colab**.

1. Download `Occupational_hardiness_ITA.sav` from the OSF repository.
2. Create a folder named `Hardiness_Project` inside your Google
   Drive's **My Drive** and upload the dataset there.
3. Run all notebook cells in order and authorise the Drive connection.

Figures are saved in `Hardiness_Project/figures`.

**Libraries:** pandas, NumPy, Matplotlib, seaborn, SciPy,
statsmodels, and pyreadstat. Software versions are recorded
in the notebook.

## Author

Alessia Mini — BSc in Psychological Sciences and Techniques,
University of Milano-Bicocca.
