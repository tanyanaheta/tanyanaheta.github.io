---
layout: default
title: "Multimodal Knowledge Graph for Real Estate Discovery"
---

## Problem

Real estate search is constrained by filters. This project built a recommendation system to discover listings similar in layout, style, or description.

## Pipeline Overview

- Used Zillow data with images, text, and structured features.
- Extracted CLIP image embeddings and TF-IDF vectors from descriptions.
- Constructed a similarity graph; trained GraphSAGE on multimodal embeddings.
- Evaluated visual and semantic cohesion of listing clusters.

## Impact

Prototype enables discovery of relevant listings beyond keyword filters. Ideal for product teams building search personalization and recommendation tools.