# 🧠 PPPD Dizziness Handicap Analysis & Prediction

## Overview

**Persistent Postural-Perceptual Dizziness (PPPD)** is a chronic condition that causes ongoing non-spinning dizziness, unsteadiness, or a rocking sensation. It is often triggered by an earlier vertigo episode, concussion, or migraine. Symptoms worsen with movement, upright posture, busy visual environments, or screens — even when medical scans have ruled out structural causes.

Despite its impact on daily life, PPPD remains widely underdiagnosed and poorly understood in clinical data. This project explores how data analytics and machine learning can help uncover patterns in patient-reported dizziness outcomes.

## What This Project Does

Using a simulated dataset of PPPD patients scored on the **Dizziness Handicap Inventory (DHI)** — a standardized 25-question survey measuring how much dizziness disrupts daily life (0–100 scale; higher = worse impact) — this project:

- 📊 **Explores** average DHI scores across demographics (gender, anxiety status)
- 📈 **Visualizes** score distributions and group comparisons
- 🤖 **Builds** a decision tree classifier to predict severe handicap (DHI > 50) based on features like age, anxiety, and visual sensitivity

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

├── data/ # Simulated PPPD patient dataset
├── notebooks/ # Exploratory analysis & modeling
├── visuals/ # Generated charts and plots
├── README.md
└── requirements.txt

## Getting Started

```bash
git clone https://github.com/yourusername/pppd-dhi-analysis.git
cd pppd-dhi-analysis
pip install -r requirements.txt
