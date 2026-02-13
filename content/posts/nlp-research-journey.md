---
title: "My NLP Research Journey: From SciBERT to Clinical Text Mining"
date: 2025-07-15T14:00:00+08:00
draft: false
tags: ["NLP", "research", "SciBERT", "MIMIC-IV"]
author: "Juao Fan"
summary: "A reflection on my experience as an NLP research assistant — reproducing SciBERT, fine-tuning on clinical data, and lessons learned."
---

## Getting Started with NLP Research

In the summer of 2024, I had the opportunity to work as a **Research Assistant** focusing on Natural Language Processing at BNU-HKBU UIC. This experience opened my eyes to the world of applied NLP in healthcare.

## Bidirectional Encoders

My first major task was to dive deep into **bidirectional encoder architectures**. Understanding how models like BERT process text in both directions simultaneously was crucial for the work ahead. This research contributed to a paper submitted to **FLLM 2024**, where I served as second author.

## Reproducing SciBERT

One of the key tasks was reproducing [SciBERT](https://arxiv.org/abs/1903.10676), a BERT variant pre-trained on scientific text. The reproduction process taught me:

- The importance of **domain-specific pre-training**
- How vocabulary differences affect downstream performance
- Practical challenges in reproducing ML research papers

## Fine-tuning on MIMIC-IV

The **MIMIC-IV** clinical dataset presented unique challenges:

1. **Data preprocessing**: Clinical notes are messy — abbreviations, misspellings, and domain-specific jargon
2. **Privacy considerations**: Working with de-identified health records requires careful handling
3. **Evaluation metrics**: Standard NLP metrics don't always capture clinical relevance

## Key Takeaways

- Reproducing papers is one of the best ways to truly understand a method
- Domain-specific models consistently outperform general-purpose ones on specialized tasks
- Healthcare NLP has enormous potential but requires careful consideration of clinical context

I'm grateful for this experience and excited to continue exploring the intersection of NLP and healthcare.
