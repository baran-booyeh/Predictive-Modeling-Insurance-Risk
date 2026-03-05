# Insurance Risk & Cost Prediction
### Stop guessing. Start pricing right.

Insurers lose millions annually to mispriced policies, charging too little for high-risk customers, and losing low-risk ones to competitors. This project builds predictive models that flag where those gaps are.

---

## What this solves

Three questions every underwriter and actuary should be asking:

- **Who costs more than we think?** : Identify policyholders whose risk profile doesn't match their premium.
- **What's actually driving claims?** : Strip out noise and surface the variables that move the needle.
- **Which customers cluster together?** : Segment your book of business by risk profile, not just demographics.

---

## Results that matter

| Model | What it does | Business use |
|---|---|---|
| Linear Regression | Predicts cost of a claim | Premium calibration |
| K-Nearest Neighbors | Classifies risk tier | Underwriting decisioning |
| Hierarchical Clustering | Groups similar policyholders | Portfolio segmentation |

Model performance was validated using confusion matrices and error metrics — not just "it ran without errors."

---

## Stack

R · R Markdown · ggplot2 · caret · dplyr

---

## How it's built

```
1. Exploratory analysis   → find the signal in the noise
2. Preprocessing          → clean, encode, scale
3. Model training         → LM, KNN, clustering
4. Evaluation             → compare models head-to-head
5. Interpretation         → translate outputs into decisions
```

---

## Who should care

- **Actuaries** building or validating pricing models
- **Data teams** at insurers, brokers, or MGAs
- **Product managers** evaluating risk-based pricing initiatives
- **Analysts** exploring how statistical learning applies to financial risk

---

## Repository structure

```
├── data/               # Raw and processed datasets
├── notebooks/          # R Markdown analysis files
├── models/             # Trained model outputs
├── figures/            # Plots and visualizations
└── README.md
```

---

## Get started

```r
# Clone and open the main analysis
source("notebooks/insurance_analysis.Rmd")
```

---

*Built with R. Questions or contributions welcome via Issues or PRs.*
