---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: Research
      subtitle: ''
      text: |-
        My research sits at the intersection of **financial mathematics**, **stochastic control**, and **machine learning**. On the theoretical side, I work on stochastic optimal control problems arising in retirement product design, derivatives pricing, and dynamic asset allocation — developing regression-based Monte Carlo methods and weak convergence analyses for path-dependent models. On the applied side, I build ML-driven systems for portfolio optimisation, macroeconomic regime detection, ESG scoring, and LLM-enabled investment advisory, deploying these at institutional scale through AQUMON.

        I am interested in problems where rigorous mathematical structure and practical deployability are both essential — and where neither can be compromised.
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
      columns: 1

  - block: collection
    content:
      title: Working Papers
      filters:
        folders:
          - publications
        featured_only: false
        exclude_featured: true
        tag: working-paper
    design:
      view: citation
      columns: 1

  - block: collection
    id: talks
    content:
      title: Invited Talks
      filters:
        folders:
          - events
    design:
      view: card
---
