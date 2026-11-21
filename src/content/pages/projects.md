---
title: 'Projects'
description: 'Selected work by Angelina Huang in quantitative finance, machine learning, and research prototypes.'
updated: 2026-11-21
---

How do you tell a useful signal from a convincing result? These projects approach that question through market models, controlled learning experiments, and corporate disclosures.

## Quant & Markets

<div class="recruiter-resources">
  <article class="recruiter-resource">
    <p class="resource-index">Asset pricing</p>
    <h3>CAPM: Market beta for 10 U.S. stocks</h3>
    <p>Estimated market exposure across sectors and tested how well the model holds up. Rolling regressions showed beta changed over time, while the residuals showed fat tails and volatility clustering.</p>
    <p><a href="https://github.com/Angelinaaa77/StockMarket-Projects/tree/main/capm_project">Read the CAPM study</a></p>
  </article>
  <article class="recruiter-resource">
    <p class="resource-index">Volatility and risk</p>
    <h3>GARCH: Equity volatility and value at risk</h3>
    <p>Compared volatility models across four global equity indices and backtested 99% value at risk out of sample. The asymmetric model with skewed, heavy-tailed shocks passed all eight tests in the study.</p>
    <p><a href="https://github.com/Angelinaaa77/StockMarket-Projects/tree/main/garch_project">Read the GARCH study</a></p>
  </article>
</div>

## Machine Learning from Scratch

<div class="recruiter-resources">
  <article class="recruiter-resource">
    <p class="resource-index">Supervised learning</p>
    <h3>Neural Network Backpropagation</h3>
    <p>Implemented a neural network in NumPy and compared eight learning rates on MNIST from the same starting weights. The best settings reached 92.2% test accuracy after ten epochs.</p>
    <p><a href="https://github.com/Angelinaaa77/Neural-Network-Backpropagation#readme">See the learning-rate experiment</a></p>
  </article>
  <article class="recruiter-resource">
    <p class="resource-index">Transformers</p>
    <h3>GPT-2 from Scratch</h3>
    <p>Reimplemented the GPT-2 small forward pass in NumPy using pretrained weights. Added causal multi-head attention and checked the outputs against Hugging Face’s implementation.</p>
    <p><a href="https://github.com/Angelinaaa77/GPT2-from-scratch#readme">See the implementation and tests</a></p>
  </article>
  <article class="recruiter-resource">
    <p class="resource-index">Reinforcement learning</p>
    <h3>Q-learning and SARSA in GridWorld</h3>
    <p>Implemented both algorithms in NumPy and compared their learned policies. Both found six-step routes, but SARSA’s route stayed farther from a costly state.</p>
    <p><a href="https://github.com/Angelinaaa77/Q-learning-SARSA-GridWorld#readme">Compare the policies and value maps</a></p>
  </article>
  <article class="recruiter-resource">
    <p class="resource-index">Reinforcement learning</p>
    <h3>Q-learning in Othello</h3>
    <p>Implemented the learning updates for a self-play agent in Python. The study compares tabular learning on smaller boards with linear value approximation on the full 8×8 board.</p>
    <p><a href="https://github.com/Angelinaaa77/Q-Learning-Othello#readme">See the self-play experiments</a></p>
  </article>
</div>

## Research Prototypes

<div class="recruiter-resources">
  <article class="recruiter-resource">
    <p class="resource-index">Financial text analysis</p>
    <h3>HackMIT Greenwash Audit</h3>
    <p>A research prototype, documented as TextQuant, that flags sustainability claims missing the scope, baseline, or method needed to verify them. It compares rules, document-level statistics, and a rubric-guided language model.</p>
    <p><a href="https://github.com/Angelinaaa77/hackmit-greenwash-audit#readme">Read the prototype’s methodology</a></p>
  </article>
</div>
