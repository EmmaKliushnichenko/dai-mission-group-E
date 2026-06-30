# Gender Differences in Executive Roles based on BoardEx Europe data

[![Notebook CI](https://github.com/EmmaKliushnichenko/dai-mission-group-E/actions/workflows/notebook.yml/badge.svg)](https://github.com/EmmaKliushnichenko/dai-mission-group-E/actions/workflows/notebook.yml)

## Team

| Role | Name | Student ID |
|---|---|---|
| Lead | Emma Kliushnichenko | 242989 |
| Member | Mohamed Gomaa | 283950 |
| Member | Ahmed Abdelrazek | 284304 |

## Research Question

Which individual characteristics, including education, age, nationality, professional experience, board experience, committee involvement, and network position, influence the probability of holding a top position in a company, and does gender remain associated with this probability after investigating on these factors?

## Methods Overview

| Block | Method(s) |
|---|---|
| Causal Inference | DoWhy, DAG, backdoor adjustment, propensity-score stratification, IPW cross-check, refutation tests |
| Supervised Learning | Majority baseline, logistic regression, lasso logistic regression, random forest, cross-validation |
| Unsupervised Learning | PCA, K-Means clustering, elbow method, silhouette score, cluster interpretation |

## Data Sources

| Dataset | Source / URL | Access method |
|---|---|---|
| BoardEx Europe project data: data.csv | https://tu-dortmund.sciebo.de/s/wY5kFY6CkMk9LPr | Sciebo share link |

The project data and related files are available through the Sciebo link above. Large data files are not pushed directly to GitHub.

## Reproducibility

To reproduce the analysis, install the required Python packages from `requirements.txt`:

```bash
pip install -r requirements.txt

