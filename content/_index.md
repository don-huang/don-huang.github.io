---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '4.5rem'

sections:
  - block: profile-about
    id: about
    content:
      username: admin
      button:
        text: Download CV
        url: uploads/resume.pdf

  - block: research-topics
    id: research-focus
    content:
      title: Research Focus
      text: Rigorous mathematical methods, empirical learning, and deployable financial systems.
      items:
        - name: Stochastic Control & Retirement Finance
          description: Dynamic decision models for withdrawal guarantees, retirement income, and path-dependent financial products.
        - name: Portfolio Optimization & Reinforcement Learning
          description: Robust allocation and rebalancing methods that account for estimation error, constraints, and transaction costs.
        - name: Financial Machine Learning & ESG Analytics
          description: Data-driven models for market regimes, financial text, sustainability signals, and investment research.
        - name: LLMs and AI Agents for Wealth Management
          description: Auditable AI systems that support advisory, portfolio monitoring, and regulated financial workflows.
      cta:
        text: Explore research
        url: /research/

  - block: content-heading
    id: publications
    content:
      level: 2
      title: Selected Publications
      text: Peer-reviewed work in stochastic control, computational finance, and path-dependent models.

  - block: collection
    content:
      count: 4
      filters:
        folders:
          - publications
        publication_type: article-journal
      archive:
        enable: true
        text: View all publications
        link: /publications/
    design:
      view: citation
      columns: 1

  - block: content-heading
    id: projects
    content:
      level: 2
      title: Selected Projects
      text: Research translated into production systems for retirement and institutional wealth management.

  - block: collection
    content:
      count: 3
      filters:
        folders:
          - projects
        featured_only: true
      archive:
        enable: true
        text: View all projects
        link: /projects/
    design:
      view: summary-grid-home
      columns: 2
---
