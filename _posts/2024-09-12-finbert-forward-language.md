---
title: "Beyond Sentiment: Extracting Forward-Looking Signals from Financial Text"
excerpt: "How parsing forward-looking phrases in 10-K filings adds predictive power to FinBERT sentiment pipelines."
layout: single
author_profile: true
---


Natural language models like FinBERT are great at labeling sentiment, but that’s only part of the story. In this project, I explored whether *forward-looking language* in 10-Ks and earnings reports could surface implicit strategy signals.

I developed custom regex patterns to isolate phrases like “we expect,” “anticipate growth,” or “likely to scale.” These were used to subset FinBERT sentiment labels, revealing that sectors with more forward-looking optimism (e.g. tech) aligned with growth trends post-earnings.

🔍 **Why it matters:** Not all positive language is created equal. Forward-looking optimism is often a better proxy for investor confidence than overall tone.

📈 **Next step:** Pair this with earnings surprises or volatility data to model market reactions to tone, not just numbers.

This blend of qualitative parsing with domain-specific NLP reveals a richer layer of financial insight—and it’s how NLP becomes a strategic tool, not just a dashboard labeler.
        
