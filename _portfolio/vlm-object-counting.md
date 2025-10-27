---
title: "Psychology-Inspired Object Counting in Vision-Language Models"
excerpt: "Teaching VLMs to count by treating it as a sequential task with tools, inspired by human cognitive psychology<br/><img src='/images/counting-strategies.png'>"
collection: portfolio
---

## Motivation
Vision-language models (VLMs) notoriously struggle with counting objects in images. However, psychological research shows that humans rely on:
- **Movement**: Physical or visual scanning
- **Visual markers**: Marking objects as counted
- **Sequential processing**: One object at a time

Can we bake these insights into a VLM to improve its counting ability?

## Approach
Rather than treating counting as a "look-once-and-return-a-count" task, I'm developing a system where:
1. **Tool Access**: VLM has access to tools for marking up images and tracking objects
2. **Sequential Processing**: Treats counting as a multi-step sequential task
3. **Reinforcement Learning**: Model learns optimal scanning trajectories through trial and error

## Research Questions
- Can VLMs learn effective scanning strategies for counting?
- Do psychology-inspired inductive biases improve performance?
- What scanning patterns emerge from RL training?

## Status
Currently running experiments on this generative task as part of research with Prof. Jivko Sinapov at Tufts University.

## Impact
This work bridges cognitive psychology and modern AI, potentially improving VLMs' ability to perform tasks requiring sequential visual reasoning.
