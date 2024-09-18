---
title: "PersonaGym: Evaluating Persona Agents and LLMs"
collection: publications
permalink: /publication/PersonaGym
excerpt: 'In this work, we released the first ever dynamic evaluation framework for persona agents in LLMs termed <br>PersonaGym</br>. Additionally we established the first autmatic human-sligned metric for quantifying the abilities of a given persona agent termed <b>PersonaScore</b>. '
date: 2024-07-29
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2407.18416'
---

Persona agents, which are LLM agents that act according to an assigned persona, have demonstrated impressive contextual response capabilities across various applications. These persona agents offer significant enhancements across diverse sectors, such as education, healthcare, and entertainment, where model developers can align agent responses to different user requirements thereby broadening the scope of agent applications. However, evaluating persona agent performance is incredibly challenging due to the complexity of assessing persona adherence in free-form interactions across various environments that are relevant to each persona agent. We introduce <b>PersonaGym</b>, the first dynamic evaluation framework for assessing persona agents, and <b>PersonaScore</b>, the first automated human-aligned metric grounded in decision theory for comprehensive large-scale evaluation of persona agents. Our evaluation of 6 open and closed-source LLMs, using a benchmark encompassing 200 personas and 10,000 questions, reveals significant opportunities for advancement in persona agent capabilities across state-of-the-art models. For example, Claude 3.5 Sonnet only has a 2.97% relative improvement in PersonaScore than GPT 3.5 despite being a much more advanced model. Importantly, we find that increased model size and complexity do not necessarily imply enhanced persona agent capabilities thereby highlighting the pressing need for algorithmic and architectural invention towards faithful and performant persona agents.
