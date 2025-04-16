---
layout: default
title: Tanya Naheta | Data Scientist
---

## About

I'm a data scientist with over three years of experience translating complex data into business impact across product, fintech, and Responsible AI contexts. My work bridges analytics, strategy, and systems thinking — from building a graph-based recommendation engine at Zillow, to co-developing an evaluation framework for foundation models used in high-stakes applications.

I thrive at the intersection of technical rigor and practical decision-making. Whether it's surfacing forward-looking sentiment from company filings, identifying bias in content moderation systems, or designing interpretable credit risk models, I bring curiosity, structure, and a strong sense of ownership to every challenge.

I'm especially excited about roles where I can connect the dots between data, product, and human decision-making — and help build tools that are both useful and responsible.

---

## Projects

### Featured Work

- [Ethical Foundation Models](projects/ethical-foundation-models.md)  
  <small>Governance analysis and AI Balance Sheet development</small>

- [Multimodal Knowledge Graph for Real Estate](projects/multimodal-knowledge-graph.md)  
  <small>Built a Zillow-style listing graph using CLIP + GraphSAGE</small>

---

### Technical + Strategy Projects

- [Mortgage Risk Classification](projects/mortgage-risk-classification.md)  
  <small>Logistic regression model on 400K+ Fannie Mae loans</small>

- [Financial Sentiment Analysis](projects/financial-sentiment-analysis.md)  
  <small>Forward-looking tone extraction using FinBERT</small>

- [Bias Evaluation of Toxicity Detection](projects/bias-toxicity-evaluation.md)  
  <small>Fairness audit of Detoxify using subgroup analysis</small>

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

<a href="/blog">View all posts →</a>
