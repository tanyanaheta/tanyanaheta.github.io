---
layout: default
title: "Bias Evaluation of Toxicity Detection"
---

## Problem

Off-the-shelf toxicity classifiers often overflag identity-related language. This project audited Detoxify's behavior across marginalized identity groups.

## Pipeline Overview

- Used Civil Comments and RealToxicityPrompts for evaluation.
- Disaggregated performance by identity mentions (e.g., Muslim, gay, Black).
- Measured subgroup false positive and false negative rates.
- Identified overflagging and underflagging behaviors.

## Impact

Uncovered up to 20% recall gaps for minority identities. Proposed group-specific thresholds and mitigation strategies. Demonstrates why fairness audits must be subgroup-aware, not just globally accurate.