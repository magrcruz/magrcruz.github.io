---
title: "Asking Why: Causal Question Answering Over Human Affective and Intentional States in Multimodal Video"
collection: publications
category: conferences
permalink: /publication/2026-04-01-asking-why-causal-videoqa
excerpt: "Identifies a gap in causal VideoQA: models handle physical causation but degrade on human affective and intentional states. Proposes benchmark gap analysis and a retrieval-augmented prototype with dual output."
date: 2026-04-01
venue: "LatinX in Computer Vision (LXCV) Workshop, CVPR 2026"
paperurl: "/files/2026-asking-why/paper.pdf"
bibtexurl: "/files/2026-asking-why/cite.bib"
codeurl: "https://github.com/magrcruz/Asking-Why-Causal-Affective-QA"
citation: "Cruz Caceres, M. G. (2026). &quot;Asking Why: Causal Question Answering Over Human Affective and Intentional States in Multimodal Video.&quot; <i>LatinX in Computer Vision (LXCV) Workshop, CVPR 2026</i>."
---

<img src="/images/asking-why-featured.png" alt="Asking Why Teaser" style="width:100%; max-width:800px; margin-bottom: 20px; border-radius: 8px;">

**Poster Presentation** — LatinX in Computer Vision (LXCV) Workshop, CVPR 2026 · Denver, CO, USA

[**[Code / GitHub Repository]**](https://github.com/magrcruz/Asking-Why-Causal-Affective-QA)

### Abstract

Current Video Question Answering (VideoQA) systems can reason causally about physical events but fail when the causal subject is a human affective or intentional state. Datasets such as MELD and MIntRec2.0 provide rich multimodal annotations of emotion and intent in conversational video, yet they are structured exclusively for classification — given a clip, predict a label. No existing benchmark supports the inverse and more useful query: given a natural language question about why an emotional state changed, retrieve and connect the evidence across the video that explains it.

We define the task of Affective Causal VideoQA: taking a natural language question about a person's emotional or intentional arc — "why did she disengage?" "when did he start withdrawing?" — and returning both the temporal evidence clips and a natural language explanation connecting them. The output is designed to be verifiable: a user can check the retrieved clips against the explanation, which is essential for trust in affective reasoning applications. 

We propose a two-stage research program:
1. **Stage 1:** Evaluates existing causal VideoQA models (SeViLA, Video-LLaVA) on affective causal queries derived from MELD and MIntRec2.0, with the hypothesis that performance degrades significantly when the "why" question targets a latent emotional state rather than a physical event.
2. **Stage 2:** Builds a retrieval-augmented prototype in which cross-modal fusion architectures (MAG-BERT, MISA) are adapted to retrieve and assemble temporally grounded causal chains from multimodal conversational video.

Evaluation combines automatic retrieval metrics on repurposed affective annotations and human evaluation of causal explanation quality. No new data collection is required at any stage.