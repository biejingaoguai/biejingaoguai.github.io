---
title: "From Drug Interactions to Music Generation: Two Sides of AI for Science"
date: 2025-11-01T16:00:00+08:00
draft: false
tags: ["AI for Science", "drug interaction", "music generation", "research"]
author: "Juao Fan"
summary: "Exploring two fascinating research directions — using Mamba models for drug-drug interaction analysis, and generative models for music creation."
---

## AI for Science: A Broad Canvas

One of the things I love about the "AI for Science" umbrella is its breadth. In my current research, I'm working on two seemingly unrelated but equally fascinating problems.

## Drug-Drug Interaction Analysis

Understanding how drugs interact with each other is critical for patient safety. We reproduced **mambaDrug** and **mambaHealth**, two models built on the [Mamba architecture](https://arxiv.org/abs/2312.00752) — a state-space model that offers an alternative to transformers.

### Why Mamba?

- **Linear complexity**: Unlike transformers' quadratic attention, Mamba scales linearly with sequence length
- **Selective state spaces**: The model can selectively remember or forget information
- **Efficient inference**: Particularly important for deployment in clinical settings

Our pharmacological analysis focuses on predicting adverse drug-drug interactions, with the goal of submitting to **NeurIPS Workshop**.

## Music Generation

On a completely different note (pun intended 🎵), I've also been exploring **generative models for music**. Specifically, I reproduced **PDMX** and investigated how these models can be used for creative music generation.

### Challenges in Music Generation

- Capturing **long-range structure** (verse, chorus, bridge patterns)
- Maintaining **harmonic consistency** over time
- Balancing **creativity** with musical coherence

## The Common Thread

Despite their differences, both projects share a common philosophy: using structured, sequence-based models to capture complex patterns — whether in molecular interactions or musical compositions.
