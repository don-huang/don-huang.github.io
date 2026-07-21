---
title: Portfolio Management via Reinforcement Learning
date: 2021-12-31
summary: A sequential portfolio-rebalancing framework that learns policies under changing market states, tracking objectives, and realistic transaction costs.
featured: true
tags:
  - reinforcement learning
  - portfolio optimisation
  - machine learning
links:
  - type: site
    url: https://www.itf.gov.hk/en/project-search/project-profile/index.html?ReferenceNo=UIM/365
    name: ITF Project Profile
---

**Period:** January 2019 – December 2021  
**Funding:** Innovation and Technology Fund (ITF), Hong Kong, Reference No. UIM/365  
**Industry partner:** Magnum Research Limited (AQUMON)

### Problem

Standard portfolio rebalancing rules are based on fixed-weight targets and threshold-trigger mechanisms that do not adapt to evolving market conditions or explicitly account for transaction costs. A principled sequential decision-making framework is needed to learn rebalancing policies that remain effective under diverse market regimes and realistic cost structures.

### Method

The portfolio rebalancing problem is formulated as a Markov Decision Process (MDP) with state variables capturing portfolio composition, market features, and risk indicators; actions corresponding to rebalancing decisions; and a reward function that penalises both tracking error and transaction costs. We explored value-based and policy-gradient reinforcement learning algorithms, including recurrent and sequence-based architectures that condition on the trajectory of market states. Emphasis was placed on sample efficiency, robustness to distribution shift, and deployability in a production rebalancing pipeline.

### Outcome

The project produced a research-to-production foundation for RL-based portfolio management, with documented methodology, experimental benchmarks, and a reusable framework for systematic strategy development and evaluation at AQUMON.

<!--more-->
