---
title: 'CrowdSelect: Synthetic Instruction Data Selection with Multi-LLM Wisdom'
collection: publications
category: conferences
permalink: /publications/crowdselect
excerpt: 'Distilling advanced Large Language Models' instruction-following capabilities into smaller models using a selected subset has become a mainstream approach in model training. While existing synthetic instruction data selection strategies rely mainly on single-dimensional signals (i.e., reward scores, model perplexity), they fail to capture the complexity of instruction-following across diverse fields. Therefore, we investigate more diverse signals to capture comprehensive instruction-response pair characteristics and propose three foundational metrics that leverage Multi-LLM wisdom, informed by (1) diverse LLM responses and (2) reward model assessment. Building upon base metrics, we propose CrowdSelect, an integrated metric incorporating a clustering-based approach to maintain response diversity. Our comprehensive experiments demonstrate that our foundation metrics consistently improve performance across 4 base models on MT-bench and Arena-Hard. CrowdSelect, efficiently incorporating all metrics, achieves state-of-the-art performance in both Full and LoRA fine-tuning, showing improvements of 4.81% on Arena-Hard and 11.1% on MT-bench with Llama-3.2-3b-instruct. We hope our findings will bring valuable insights for future research in this direction.'
date: 2025-03-03
venue: 'ARR 2026 October cycle'
status: 'Submitted to'
paperurl: 'https://arxiv.org/abs/2508.03644'
sitelink: 'https://github.com/listentm/crowdselect'
citation: 'Li, Y., Yang, L., Shen, W., Zhou, P., Wan, Y., Lin, W., & Chen, D. (2025). CrowdSelect: Synthetic Instruction Data Selection with Multi-LLM Wisdom. arXiv preprint arXiv:2503.01836.'
---
