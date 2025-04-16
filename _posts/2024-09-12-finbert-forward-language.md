---
title: "Beyond Sentiment: Extracting Forward-Looking Signals from Financial Text"
excerpt: "How parsing forward-looking phrases in 10-K filings adds predictive power to FinBERT sentiment pipelines."
layout: default
author_profile: true
---

Natural language models like FinBERT are great at labeling sentiment, but that’s only part of the story. I explored whether forward-looking language in company filings (e.g., “we expect,” “likely to grow”) could act as a signal of strategic direction.

I filtered FinBERT’s sentiment output based on these future-oriented cues and aggregated sentiment by sector. Tech firms consistently used more optimistic forward-looking tone, aligning with market growth expectations. Other sectors, like consumer goods and logistics, showed less consistency.

Takeaway: Standard sentiment isn’t enough. Focusing on future-oriented language can help analysts surface signals that align more closely with strategy and investor sentiment, and make NLP outputs more useful for actual business decisions.
