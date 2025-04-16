---
layout: default
title: "Mortgage Risk Classification Model"
---

## Problem

Fannie Mae needed a transparent and interpretable model to flag loans likely to become delinquent by 90+ days. The goal was to support early underwriting decisions and optimize capital allocation.

## Pipeline Overview

- Processed 400K+ records combining acquisition and monthly performance data.
- Created a delinquency label and validated feature significance using chi-square and Mann-Whitney U tests.
- Addressed class imbalance with upsampling after splitting to avoid leakage.
- Chose logistic regression for regulatory interpretability; tuned thresholds and regularization.
- Benchmarked against tree-based models to validate trade-offs.

## Impact

Achieved AUC of 0.83. Identified high-risk segments by loan purpose, LTV, and credit score. Designed to integrate into lender-facing dashboards for early risk detection.