---
title: "When Global Accuracy Lies: Why We Need Identity-Aware Fairness Metrics"
excerpt: "A 20% recall gap for marginalized groups, hidden behind a 92% overall score? This is why we audit."
layout: single
author_profile: true
---


Content moderation models can seem accurate—until you ask how they treat sentences about LGBTQ+ or Muslim communities. I used Civil Comments and RealToxicityPrompts to test Detoxify, a widely used toxicity classifier.

Even though the model hit over 90% accuracy, it misclassified *non-toxic* identity-related sentences at disproportionate rates. Words like “gay,” “Muslim,” or “Black” triggered false positives due to biased training data.

📊 **Insight:** I measured recall and false positive rate by identity group. Gaps of 15–20% were common—meaning the model disproportionately silenced certain groups.

🚨 **So what?** Fairness isn’t about perfection. It’s about visibility. Unless we measure harm at the subgroup level, we’re flying blind.

Structured audits like this aren’t just ethical—they’re *product critical*. If we care about scale, we have to care about who’s affected.
        