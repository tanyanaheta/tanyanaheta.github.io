---
title: "Financial Sentiment Analysis with FinBERT"
description: "Used FinBERT to extract forward-looking sentiment from 500+ earnings reports and 10-K filings for sector-level insights."
tags: ['NLP', 'Finance', 'FinBERT', 'Sentiment Analysis', 'Strategy']
layout: single
author_profile: true
---


## Problem

Investors and analysts need structured insights from unstructured filings. This project explored how sentiment from 10-Ks and earnings reports could serve as a predictive signal of company strategy and tone.

## Pipeline Overview

- **Data**: 500+ company filings (HTML, PDF).
- **Preprocessing**: Parsed sections using regex and heuristics; removed disclaimers and boilerplate.
- **Modeling**: Applied FinBERT to classify sentence-level sentiment.
- **Feature Engineering**: Extracted forward-looking phrases and aggregated sentiment at section and sector level.
- **Evaluation**: Compared sentiment to earnings outcomes, confirmed FinBERT’s superior domain alignment over generic BERT.

## Impact

The pipeline revealed that tech companies consistently used more optimistic language, aligning with market growth expectations. The model showed clear use cases for investor dashboards and strategy monitoring tools.
        