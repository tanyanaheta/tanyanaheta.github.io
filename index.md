---
layout: default
title: Tanya Naheta | Data Scientist
---

## About

I'm a data scientist with 3+ years of experience turning complex data into clear, actionable insights. I’ve led projects at Zillow to improve real estate discovery using graph-based recommendations, co-developed a multidimensional evaluation framework for foundation models at NYU, and delivered interpretable credit risk models to support loan strategy.

Across roles, I’ve worked at the intersection of analytics, product, and responsible AI - using tools like Python, SQL, and graph ML to connect technical signals to business decisions. At Acclaim, I built SQL pipelines and delivered dashboards to client success teams, helping translate operational data into measurable KPIs. I care deeply about designing analyses and systems that are not just technically strong, but decision-ready.

Whether it's surfacing forward-looking sentiment from 10-Ks, modeling user behavior, or aligning AI systems with real-world incentives, I bring structure, curiosity, and ownership to every project.

---

## Projects

### Featured Work

- [Ethical Foundation Models](projects/ethical-foundation-models.md)  
  <small>Developed the AI Balance Sheet to evaluate foundation models across ethical, technical, business, and environmental dimensions</small>

- [Multimodal Knowledge Graph for Real Estate](projects/multimodal-knowledge-graph.md)  
  <small>Built a graph-based recommendation engine at Zillow by combining CLIP image embeddings, TF-IDF text, and GraphSAGE modeling</small>

---

### Technical + Strategy Projects

- [Mortgage Risk Classification](projects/mortgage-risk-classification.md)  
  <small>Interpretable logistic regression model trained on 400K+ Fannie Mae records to assess default risk</small>

- [Financial Sentiment Analysis](projects/financial-sentiment-analysis.md)  
  <small>Used FinBERT to extract forward-looking tone from 500+ earnings reports and 10-K filings</small>

- [Bias Evaluation of Toxicity Detection](projects/bias-toxicity-evaluation.md)  
  <small>Audited Detoxify’s fairness using identity subgroup analysis on Civil Comments and RealToxicityPrompts</small>

---

## Blog

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br/>
      <small>{{ post.excerpt }}</small>
    </li>
  {% endfor %}
</ul>
