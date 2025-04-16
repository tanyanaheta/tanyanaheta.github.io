---
layout: default
title: "Financial Sentiment Analysis with FinBERT"
---

## Problem

Investor filings contain valuable sentiment signals, but extracting them at scale is difficult. This project explored how forward-looking tone in 10-Ks and earnings reports relates to market expectations.

## Pipeline Overview

- Parsed 500+ filings using regex and heuristics to extract forward-looking sections.
- Applied FinBERT for sentence-level sentiment classification.
- Aggregated sentiment scores at section, company, and sector level.
- Compared tone against real earnings performance to identify correlations.

## Impact

Enabled directional insights for sectors like tech and energy. Framework supports dashboards for investor research or corporate strategy teams.