---
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **machine learning, quantitative finance, and large language models**. I am particularly interested in building models and agents that can reason, adapt, and make reliable decisions in financial and strategic environments. My current work focuses on LLM agents, efficient LLM adaptation, limit order books, and machine learning for quantitative trading.

## Current Research Directions

### Strategic LLM Agents

I study how language-based agents learn and evolve in competitive multi-agent environments. My current work on **CASE (Co-evolutionary Agent Skill Evaluation)** investigates how to evaluate natural-language skill revisions through counterfactual comparisons, anchored opponent populations, and diversity-aware selection. The goal is to distinguish genuine strategic improvement from gains caused by favorable opponents or environmental randomness.

### Efficient LLM Adaptation

I am developing **LoCA (Local Credit Assignment)**, a backpropagation-free framework for post-training frozen language models. LoCA combines local targets, a low-rank approximation of the backward operator, and closed-form updates, with the aim of reducing memory and computational requirements while retaining effective task adaptation.

### Machine Learning for Quantitative Finance

My work in quantitative finance focuses on financial time series, asset selection, limit order books, and reinforcement learning. I am interested in developing models that balance predictive performance, economic interpretability, and robustness under changing market conditions.

## Selected Research Projects

### Quantformer

**Quantformer: From Attention to Profit with a Quantitative Transformer Trading Strategy** develops a Transformer-based framework for stock selection using return and turnover information. The resulting strategy achieved an average annual return of approximately 20% and an excess return of approximately 10% in backtesting. The work was published in *Expert Systems with Applications*.

[Paper](https://doi.org/10.1016/j.eswa.2026.131567) · [Code](https://github.com/zhangmordred/QuantFormer)

### Chesformer

**Chesformer** introduces Chebyshev positional encoding for quantitative financial time series. The model was developed as my undergraduate dissertation and received the **Best Graduate Thesis Award**. It maintained robust performance after substantially reducing the stock-selection universe and was presented at the SIAM Conference on Financial Mathematics and Engineering.

### Prompt Engineering for Large Language Models

I co-led a comprehensive review of prompt engineering methods, applications, and evaluation strategies for large language models. The study synthesizes nearly 300 references and discusses how external tools and structured prompting can improve model reliability. It was published in *Patterns* and selected as an **Editors' Pick: Best of 2025**.

[Paper](https://doi.org/10.1016/j.patter.2025.101260)

### Reinforcement Learning for Decentralized Finance

This project studies liquidity provision in Uniswap V3 using adaptive dueling double deep Q-networks and Mamba-based architectures. It examines the trade-off among profitability, liquidity value at risk, and transaction costs in decentralized markets.

[Working Paper](https://arxiv.org/abs/2511.22101)
