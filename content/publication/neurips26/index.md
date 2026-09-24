---
title: 'Rethinking Credit Assignment in Cooperative MARL via Interventional Reward Response'

authors:
  - Chamjin Joo
  - admin
  - Sang Wan Lee

date: '2026-09-24T00:00:00Z'
doi: ''

publishDate: '2026-09-24T00:00:00Z'

publication_types: ['1']

publication: "Advances in Neural Information Processing Systems (NeurIPS)"
publication_short: "NeurIPS 2026 (accepted)"

abstract: "Credit assignment remains a central challenge in cooperative multi-agent reinforcement learning (MARL), especially under partial observability, where individual policy updates may not accurately reflect each agent’s actual contribution to team outcomes. While policy-based methods such as MAPPO and IPPO provide strong optimization frameworks, their updates are typically derived from global rewards and observational value surrogates, without explicitly defining agent-specific credit. Misaligned credit signals can mislead individual policy improvement, resulting in inefficient coordination and weaker team performance. We address this challenge by formulating agent-level credit as an interventional reward response, using Proximal Causal Inference (PCI) to identify credit from observable proxies via an outcome bridge function. Building on this identification strategy, we design a practical credit-aligned update signal and integrate it into policy gradient methods. Empirical evaluations on diagnostic and benchmark tasks demonstrate that the proposed credit signal improves policy learning under partial observability, highlighting proximal identification as a promising foundation for designing credit-aware policy updates in cooperative MARL. To the best of our knowledge, this work presents the first PCI-based solution for online multi-agent cooperation."

summary: "Advances in Neural Information Processing Systems (NeurIPS), 2026 (accepted)"

tags: []
categories: []
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://openreview.net/forum?id=FOmIe6PtvT'
url_video: ''

image:
  caption: 'Figure 1: Causal graph of a Dec-POMDP.'
  focal_point: 'Center'
  preview_only: false

projects: []

slides: ''
---
