---
title: "Towards Data Contamination Detection for Modern Large Language Models: Limitations, Inconsistencies, and Oracle Challenges"
collection: publications
permalink: /publication/contamination
excerpt: 'In this work we benchmark several of the top data contamination approaches on the state-of-the-art LLMs in order to provide insight to the strengths and limitations of each approach.'
date: 2024-09-18
venue: 'COLING'
paperurl: 'https://arxiv.org/pdf/2409.09927'
---

As large language models achieve increasingly impressive results, questions arise about whether such performance is from generalizability or mere data memorization. Thus, numerous data contamination detection methods have been proposed. However, these approaches are often validated with traditional benchmarks and early-stage LLMs, leaving uncertainty about their effectiveness when evaluating state-of-the-art LLMs on the contamination of more challenging benchmarks. To address this gap and provide a dual investigation of SOTA LLM contamination status and detection method robustness, we evaluate five contamination detection approaches with four state-of-the-art LLMs across eight challenging datasets often used in modern LLM evaluation. Our analysis reveals that (1) Current methods have non-trivial limitations in their assumptions and practical applications; (2) Notable difficulties exist in detecting contamination introduced during instruction fine-tuning with answer augmentation; and (3) Limited consistencies between SOTA contamination detection techniques. These findings highlight the complexity of contamination detection in advanced LLMs and the urgent need for further research on robust and generalizable contamination evaluation.
