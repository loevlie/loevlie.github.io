---
title: "Improving LLM SVG Generation with Reinforcement Learning"
excerpt: "Using Group Relative Policy Optimization to improve vision-language models' ability to generate aesthetic SVGs from text"
collection: portfolio
---

## Overview
Open-source LLMs struggle to generate semantically meaningful and aesthetic SVG graphics from text descriptions. This project applies state-of-the-art reinforcement learning techniques to dramatically improve their capabilities.

## Method
I used Group Relative Policy Optimization (GRPO) with a custom 3-part reward function that encourages:
1. **Structured outputs**: Valid SVG code with proper syntax
2. **Aesthetic quality**: Visually appealing graphics
3. **Semantic alignment**: Match to input text descriptions

The model (Qwen-2.5 7B) learns through trial and error, similar to recent approaches like DeepSeek-R1 and AlphaMaze.

## Results
- **18% improvement** on a comprehensive benchmark evaluating SVG aesthetics, alignment, and code validity
- Significantly better structured outputs compared to base model
- Demonstrates the power of RL for improving visual reasoning in LLMs

## Technical Details
- Model: Qwen-2.5 7B
- RL Algorithm: Group Relative Policy Optimization
- Framework: PyTorch with custom reward functions

[Project Report](https://www.loevliedl.com/static/Portfolio/PDF/RL_for_Visual_Reasoning.pdf)
