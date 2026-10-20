---
title: "Asking Why: Causal QA Over Human Affective States in Multimodal Video"
excerpt: "Identified a gap at the intersection of causal VideoQA and affective computing, proposing a retrieval-augmented causal reasoning prototype with dual outputs."
collection: portfolio
---

**Independent Research**  
[GitHub Repository](https://github.com/magrcruz/Asking-Why-Causal-Affective-QA)

Identified a gap at the intersection of causal VideoQA and affective computing: existing models (NExT-QA, IntentQA) reason causally about physical events but degrade on latent emotional or intentional states. 

Proposed a two-stage methodology:
1. Benchmark gap analysis via SeViLA/Video-LLaVA evaluation on MELD and MIntRec2.0.
2. A retrieval-augmented causal reasoning prototype with dual output (timestamped evidence clips + natural language explanation). 

This work emerged directly from multimodal intent recognition research conducted under the **Google Explore CSR fellowship**— where evaluation of MAG-BERT and MISA architectures on MIntRec2.0 surfaced a systematic failure mode in causal reasoning over affective states that existing benchmarks did not capture. 

*Accepted for poster presentation at LXCV Workshop, CVPR 2026.*