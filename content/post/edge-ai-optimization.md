---
title: "Optimizing Edge AI for RISC-V"
date: 2025-03-05
draft: false
---

## Introduction
This post explores techniques for optimizing edge AI Hybrid models SNNs and QNNs on RISC-V hardware with qemu emulator.

## Key Techniques
1. **Quantization**: Reduced model size by 4x with minimal accuracy loss.
2. **Pruning**: Removed redundant neurons for faster inference.
3. **Hardware-Aware Optimization**: Tailored models for RISC-V accelerators.

## Results
- Achieved **2x faster inference** on RISC-V compared to ARM Cortex-M.
- Published findings in [Microprocessors and Microsystems Journal].

## Code Repository
Check out the code on [GitHub](https://github.com/stevelengui/Hybride-SNN-QNN-Edge-Inference).
