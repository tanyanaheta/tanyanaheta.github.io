---
title: "Graph-Based Real Estate Discovery: Lessons from Zillow’s Listing Problem"
excerpt: "Why traditional search fails and how GraphSAGE + CLIP helped me fix it."
layout: single
author_profile: true
---


Zillow’s search works… until it doesn’t. Users might search “Victorian with a view in SF,” but listings often rely on inconsistent text, sparse metadata, and low-quality filters. I reframed this as a **semantic discovery problem**.

Using GraphSAGE, I constructed a knowledge graph where each node was a listing combining CLIP embeddings (images), TF-IDF vectors (text), and tabular features. Edges were based on cross-modal cosine similarity.

🏡 **What changed:** Now, listings were grouped by true similarity—style, layout, region—not just filters. This meant better personalization and search recall.

💡 **Takeaway:** Search isn't just about matching words. It’s about meaning. And GraphML let me *engineer meaning* across modalities.
        