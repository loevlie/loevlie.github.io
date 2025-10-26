---
title: "Multi-Modal Semantic Segmentation for Autonomous Drones"
excerpt: "Transfer learning and domain adaptation for power line detection across RGB and infrared modalities at KEF Robotics"
collection: portfolio
---

## Overview
At KEF Robotics, I developed a multi-modal semantic segmentation system for tethered drone navigation under severe data constraints. The critical challenge was detecting power lines (thin, deadly obstacles) across both RGB and infrared modalities with minimal labeled real-world data.

## Approach
I designed a three-stage pipeline:
1. **Transfer Learning**: Transformer-based segmentation fine-tuned (source dataset: COCO) on precise simulation data
2. **Domain Adaptation**: Progressive adaptation using limited labeled real-world RGB imagery
3. **Cross-Modal Transfer**: Automated label transfer using geometric correspondence to generate IR training data from RGB predictions

This approach enabled robust power line detection across both modalities in real-world scenarios without expensive manual IR annotation.

## Results
- Successfully detected thin power lines in both RGB and infrared imagery
- 45% boost in inference speed through architecture optimization with only 1% accuracy loss
- Presented at XChangeIdeas Pittsburgh 2023
- Led a team of 5 engineers on this $500K project

## Impact
The system enabled safe autonomous navigation for tethered drones in complex environments with power line hazards, demonstrating the power of transfer learning and domain adaptation for real-world computer vision applications with limited data.
