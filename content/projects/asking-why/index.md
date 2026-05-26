---
title: 'Asking Why: Causal QA Over Human Affective States in Multimodal Video'
date: '2026-01-01'
links:
  - type: code
    url: https://github.com/magrcruz/Asking-Why-Causal-Affective-QA
tags:
  - Causal Reasoning
  - VideoQA
  - Affective Computing
  - Multimodal AI
  - Computer Vision
summary: >
  Independent research identifying a gap at the intersection of causal VideoQA and
  affective computing. Current models reason causally about physical events but degrade
  on latent emotional and intentional states. Proposes benchmark gap analysis and a
  retrieval-augmented prototype. Accepted for poster presentation at LXCV Workshop, CVPR 2026.
---

Current VideoQA models explain *why a ball rolls* but fail when asked *why a person becomes withdrawn*. This research identifies that gap — at the intersection of causal VideoQA and affective computing — and proposes methods to address it.

**Stage 1** evaluates existing causal VideoQA models (SeViLA, Video-LLaVA) on affective causal queries derived from MELD and MIntRec2.0, documenting the failure mode.

**Stage 2** proposes a retrieval-augmented prototype with dual output: timestamped evidence clips + a connected natural language explanation — a grounded, verifiable answer to questions like *"why did she disengage?"*

This work emerged from multimodal intent recognition research conducted during the Google Explore CSR fellowship, where evaluation of MAG-BERT and MISA on MIntRec2.0 surfaced a systematic failure mode in causal reasoning over affective states.

**Accepted for poster presentation at the LatinX in Computer Vision (LXCV) Workshop, CVPR 2026.**

<!--more-->