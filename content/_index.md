---
title: ""
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      avatar:
        size: medium
        shape: circle
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: Research Interests
      subtitle: Learning and decision-making under uncertainty
      text: |-
        **Reinforcement learning and state representations**

        I study state similarity and bisimulation-based representation learning, with an interest in robustness to stochastic transitions and task-irrelevant observations.

        **Stochastic optimization for learning**

        I explore how sampling and optimization objectives affect representation learning, including auxiliary estimators and primal-dual formulations.

        **Bayesian decisions and reliability**

        My published research combines Bayesian inference from complete and censored observations with Markov decision processes to optimize task termination. I am interested in connections to risk-aware decision-making and learning-based control.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation
---
