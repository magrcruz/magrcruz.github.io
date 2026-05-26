---
title: 'Asking Why: Causal Question Answering Over Human Affective and Intentional States in Multimodal Video'

authors:
  - me

date: '2026-04-01T00:00:00Z'
publishDate: '2026-04-01T00:00:00Z'

publication_types: ['paper-conference']

publication: '*LatinX in Computer Vision (LXCV) Workshop, CVPR 2026*'
publication_short: '*LXCV @ CVPR 2026*'

abstract: >
  Current Video Question Answering (VideoQA) systems can reason causally about physical
  events but fail when the causal subject is a human affective or intentional state.
  Datasets such as MELD and MIntRec2.0 provide rich multimodal annotations of emotion
  and intent in conversational video, yet they are structured exclusively for
  classification — given a clip, predict a label. No existing benchmark supports the
  inverse and more useful query: given a natural language question about why an emotional
  state changed, retrieve and connect the evidence across the video that explains it.
  We define the task of Affective Causal VideoQA: taking a natural language question
  about a person's emotional or intentional arc — "why did she disengage?" "when did he
  start withdrawing?" — and returning both the temporal evidence clips and a natural
  language explanation connecting them. The output is designed to be verifiable: a user
  can check the retrieved clips against the explanation, which is essential for trust in
  affective reasoning applications. We propose a two-stage research program. Stage 1
  evaluates existing causal VideoQA models (SeViLA, Video-LLaVA) on affective causal
  queries derived from MELD and MIntRec2.0, with the hypothesis that performance degrades
  significantly when the "why" question targets a latent emotional state rather than a
  physical event. Stage 2 builds a retrieval-augmented prototype in which cross-modal
  fusion architectures (MAG-BERT, MISA) are adapted to retrieve and assemble temporally
  grounded causal chains from multimodal conversational video. Evaluation combines
  automatic retrieval metrics on repurposed affective annotations and human evaluation
  of causal explanation quality. No new data collection is required at any stage.

summary: >
  Identifies a gap in causal VideoQA: models handle physical causation but degrade on
  human affective and intentional states. Proposes benchmark gap analysis and a
  retrieval-augmented prototype with dual output (timestamped evidence clips + NL explanation).

tags:
  - VideoQA
  - Affective Computing
  - Multimodal Learning
  - Causal Reasoning
  - Computer Vision

featured: true

links:
  - type: code
    url: https://github.com/magrcruz/Asking-Why-Causal-Affective-QA

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects:
  - asking-why

slides: ''
---

**Poster Presentation** — LatinX in Computer Vision (LXCV) Workshop, CVPR 2026 · Denver, CO, USA