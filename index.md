---
layout: home
title: Ali Arastehfard
description: Ali Arastehfard is a Ph.D. candidate at the University of Connecticut focused on applied cryptography, privacy-preserving information retrieval, and secure computation.
---

## About me

Hi! I'm Ali Arastehfard, a Ph.D. candidate at the University of Connecticut specializing in applied cryptography. My research focuses on privacy-preserving information retrieval and secure computation. Recently, I’ve been exploring Private RAG, particularly in the context of scalable private web search.

Beyond my core research, I’m increasingly interested in AI security and have had the opportunity to collaborate on several projects in this area through my lab.

Outside of research, I enjoy playing tennis, hiking new trails, and reading books—especially on social and behavioral psychology.

## Updates

{% assign recent_updates = site.data.updates | slice: 0, 8 %}
<ul class="updates-list">
{% for update in recent_updates %}
  <li><strong>{{ update.date }}:</strong> {{ update.description | markdownify | remove: '<p>' | remove: '</p>' | strip }}</li>
{% endfor %}
</ul>

<p class="updates-more"><a href="{{ '/updates/' | relative_url }}">See all updates →</a></p>

## Professional Service

- **ACM Conference on Computer and Communications Security (CCS 2026)** — Artifact Evaluation Program Committee Member / Reviewer
- **NDSS, ACM CCS, USENIX Security, and IEEE Symposium on Security and Privacy (S&P)** — External Reviewer / Subreviewer, 2022–2026
- **IEEE Transactions on Dependable and Secure Computing (TDSC)** — Reviewer, 2024–2026
- **IEEE International Conference on Trust, Privacy and Security in Intelligent Systems, and Applications (IEEE TPS)** — External Reviewer / Subreviewer, 2022–2024
- **ACM International Conference on Autonomous Agents and Multiagent Systems (AAMAS)** — External Reviewer / Subreviewer, 2023
