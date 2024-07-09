---
title: "Can LLMs Augment Low-Resource Reading Comprehension Datasets? Opportunities and Challenges"
collection: publications
permalink: /publication/LLM-QA
excerpt: 'In this work, we tackle the low resource issue in certain QA datasets by synthetically augmenting them using GPT-4 to improve downstream fine-tuned performance for LMs trained on the augmented dataset.'
date: 2024-07-18
venue: 'ACL Student Research Workshop'
paperurl: 'https://arxiv.org/abs/2309.12426'
---

Large Language Models (LLMs) have demonstrated impressive zero-shot performance on a wide range of NLP tasks, demonstrating the ability to reason and apply commonsense. A relevant application is to use them for creating high-quality synthetic datasets for downstream tasks. In this work, we probe whether GPT-4 can be used to augment existing extractive reading comprehension datasets. Automating data annotation processes has the potential to save large amounts of time, money, and effort that goes into manually labeling datasets. In this paper, we evaluate the performance of GPT-4 as a replacement for human annotators for low-resource reading comprehension tasks, by comparing performance after fine-tuning, and the cost associated with annotation. This work serves to be the first analysis of LLMs as synthetic data augmenters for QA systems, highlighting the unique opportunities and challenges. Additionally, we release augmented versions of low-resource datasets, that will allow the research community to create further benchmarks for the evaluation of generated datasets.
