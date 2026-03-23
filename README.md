# 🧠 PPPD Dizziness Handicap Analysis & Prediction

## Overview

**Persistent Postural-Perceptual Dizziness (PPPD)** is a chronic condition that causes ongoing non-spinning dizziness, unsteadiness, or a rocking sensation. It is often triggered by an earlier vertigo episode, concussion, or migraine. Symptoms worsen with movement, upright posture, busy visual environments, or screens — even when medical scans have ruled out structural causes.

Despite its impact on daily life, PPPD remains widely underdiagnosed and poorly understood in clinical data. This project explores how data analytics and machine learning can help uncover patterns in patient-reported dizziness outcomes.

## What This Project Does

Using a simulated dataset of PPPD patients scored on the **Dizziness Handicap Inventory (DHI)** — a standardized 25-question survey measuring how much dizziness disrupts daily life (0–100 scale; higher = worse impact) — this project:

- 📊 **Explores** average DHI scores across demographics (gender, anxiety status)
- 📈 **Visualizes** score distributions and group comparisons
- 🤖 **Builds** a decision tree classifier to predict severe handicap (DHI > 50) based on features like age, anxiety, and visual sensitivity

*Note on data: No real patient datasets used — all values were simulated from the above literature to explore basic patterns and predictors.

## Key Finding

> **Anxiety and visual triggers were the strongest predictors of severe dizziness handicap.**

## Motivation

This personal project reflects my interest in **health data analytics** and **machine learning**, specifically how patient-reported outcomes can be modeled to support clinical understanding and early identification of at-risk individuals.

## Tools & Technologies

- **Python**
- **Pandas** — data manipulation
- **Matplotlib / Seaborn** — visualization
- **Scikit-learn** — decision tree classification

## Project Structure

    ├── data/                # Simulated PPPD patient dataset
    ├── notebooks/           # Exploratory analysis & modeling
    ├── visuals/             # Generated charts and plots
    ├── README.md
    └── requirements.txt

## Getting Started

```bash
git clone https://github.com/yourusername/pppd-dhi-analysis.git
cd pppd-dhi-analysis
pip install -r requirements.txt

## Reference

PPPD definition and symptoms: Based on the 2017 Bárány Society consensus criteria

→ Staab et al. (2017): https://pubmed.ncbi.nlm.nih.gov/29036855/
Dizziness Handicap Inventory (DHI) questionnaire: Standard 25-item tool used for scoring handicap (0–100 scale)

→ Original: Jacobson & Newman (1990)

→ Example full form with scoring: https://southampton.stonybrookmedicine.edu/sites/default/files/Dizziness%20Hanicap%20Inventory%20-%20English.pdf
Typical DHI scores in PPPD patients: Simulated values informed by real study averages (~48–55)

→ Steensnaes et al. (2023): https://pmc.ncbi.nlm.nih.gov/articles/PMC10620245/ (mean DHI 49.2 in PPPD)

→ Teh et al. (2022): https://journals.sagepub.com/doi/abs/10.3233/VES-210087 (mean DHI 48.3) Anxiety and visual trigger correlations: Key predictors drawn from PPPD research

→ Powell et al. (2020/2022): Links between anxiety, visual sensitivity, and symptom severity

→ General support: Multiple studies note anxiety prevalence 45–60% and visual exacerbations in PPPD
