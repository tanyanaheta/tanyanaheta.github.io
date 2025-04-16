---
title: What Real Estate Search Gets Wrong — And How We Fixed It with GraphML
excerpt: Using GraphSAGE and CLIP embeddings to build a Zillow-style recommendation engine from noisy listing data.
layout: single
author_profile: true
---

Most real estate sites assume people know exactly what they want. But often, people are looking for a vibe — “modern but cozy,” “industrial with light,” “craftsman with charm.” Filters don’t help much with that.

At Zillow, I worked on a project to surface hidden connections between listings using a multimodal graph of 80K+ homes — combining images, keywords, and structured attributes. We used CLIP embeddings to connect listings by visual style, and trained a GraphSAGE model to learn from graph structure.

We experimented with three link prediction strategies for new listings and found that even noisy, CLIP-based connections outperformed GraphSAGE in isolation. Still, we showed that GraphSAGE embeddings could cluster homes by underlying style when metadata was sparse.

One surprising insight: performance dropped for more frequent keywords — indicating the importance of balancing representation and specificity in embeddings. This reinforced the need for hybrid systems that learn structure but remain interpretable.

This work taught me how to prototype a recommender system from scratch, make trade-offs in model complexity vs. performance, and think through product-ready graph applications.