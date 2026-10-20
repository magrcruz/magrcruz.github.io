---
title: "Efficient Image Editing Using Compressed Latent Representations in Diffusion Models"
excerpt: "Undergraduate thesis. Combines Würstchen and PnP-Diffusion for fast, structure-preserving text-guided image editing. Achieves 14× reduction in editing time while maintaining high image quality."
collection: portfolio
date: 2025-01-01
---

<!-- Si tienes una imagen del proyecto, puedes descomentar la siguiente línea: -->
<!-- <img src="/files/2025-image-editing-diffusion/featured.png" alt="Image Editing Architecture" style="width:100%; border-radius: 8px; margin-bottom: 20px;"> -->

**Undergraduate Thesis** — Universidad Católica San Pablo, Arequipa, Peru.  
Presented as a poster at **Khipu Latin American AI Conference, 2025**.

Current diffusion-based image editing methods are slow and struggle to preserve the original image structure. This work combines two state-of-the-art approaches: 

* **Würstchen:** compact latent representations for efficient text-guided generation.
* **PnP-Diffusion:** feature injection during the denoising process to retain spatial consistency.

The combination allows the model to represent the target text while maintaining the original structure, achieving a **14× reduction in editing time** with no significant loss in image quality (evaluated via CLIP Score and CLIP Similarity against source prompts and reference images).

### Key Takeaways & Impact
* **Efficiency:** Reduced editing latency from minutes (~2–4 min) to seconds (~24s).
* **Democratization:** Lower computational overhead makes generative diffusion editing accessible on consumer-grade GP