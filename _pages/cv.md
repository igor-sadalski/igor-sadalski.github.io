---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-logo {
    height: 36px;
    width: auto;
    vertical-align: middle;
    margin-left: 12px;
    display: inline-block;
  }
</style>

## Work Experience

**Machine Learning Scientist**, Cellular Intelligence<img src="{{ '/images/somite_logo.png' | prepend: base_path }}" alt="Cellular Intelligence" class="cv-logo"> (Boston, USA)
*Sep. '24 – Present*

* **6th engineer** at a Harvard-MIT spin-off building multi-modal foundation models for life sciences ($60M+ raised, led by Khosla Ventures).
* Co-authored publications at **ICML, ICLR, and Nature Machine Intelligence** on pre-training strategies and measurement noise scaling laws for single-cell foundation models.
* Designed and implemented pre-training and post-training pipelines for **billion-parameter transformers** on terabytes of single-cell genomics data across **32 AMD MI325x GPUs** using PyTorch FSDP and SLURM.
* Developed a reasoning LLM via rejection sampling for data curation, **SFT** for cold-start, and **GRPO** with vLLM rollouts — improving automated biological annotation quality.
* Wrote high-throughput fused **Triton kernels** (sparse-gate embedding, Softmax, LayerNorm) for single-cell genomics, reducing training memory overhead and increasing GPU utilisation.

## Research Experience

**Visiting Researcher**, Harvard University<img src="{{ '/images/harvard_logo.png' | prepend: base_path }}" alt="Harvard University" class="cv-logo"> (PI: Prof. Stephanie Gil)
*Apr. '24 – Sep. '24*

* Designed efficient **transformer attention mechanisms** for spatio-temporal demand forecasting, applied to shuttle bus scheduling on the Harvard campus.

**Undergraduate Researcher**, Caltech<img src="{{ '/images/caltech_logo.png' | prepend: base_path }}" alt="Caltech" class="cv-logo"> (PI: Prof. Aaron Ames)
*Jun. '23 – Aug. '23*

* Developed **CVAEs** and **diffusion models** to learn residual dynamics for drones, enabling tighter safety guarantees with discrete-time control barrier functions; resulted in an **ICRA 2024** publication.

**Undergraduate Researcher**, Caltech<img src="{{ '/images/caltech_logo.png' | prepend: base_path }}" alt="Caltech" class="cv-logo"> (PI: Prof. Aaron Ames)
*Jun. '22 – Aug. '22*

* Accelerated **model predictive control** solvers by implementing custom matrix operations, reducing per-step computation time for real-time robotic control.

## Education

**MSc Computer Science (Machine Learning), with Distinction**, Imperial College London<img src="{{ '/images/imperial_college_logo.png' | prepend: base_path }}" alt="Imperial College London" class="cv-logo">
*Sep. '23 – Sep. '24*
* *Selected Coursework*: Deep Learning, Reinforcement Learning, Graph-Based Learning, Software Engineering for ML Systems, Natural Language Processing.

**BEng Engineering (Robotics)**, Imperial College London<img src="{{ '/images/imperial_college_logo.png' | prepend: base_path }}" alt="Imperial College London" class="cv-logo">
*Oct. '20 – Jun. '23*

## Awards

* **Fulbright Scholarship** — one of only three recipients in Poland (declined to work in industry), '24/'25
* **MSc Distinction** — highest classification for UK master's degree, '24
* **Best Student in Poland** — perfect score in matriculation exams, '20

## Open Source Contributions

**Stanford Biomni — General-Purpose Biomedical AI Agent** — *Autumn '25*
Implemented state-of-the-art foundation models (ESM-2, Transformer, scGPT, STATE) with standardized interfaces *(Python, LangChain)*.

**MIT Hackers Club (Sundai.ai) — Various Projects** — *Autumn '24*
Built a multiplayer LLM-powered game *(Next.js, TypeScript, Tailwind, Convex, Vercel)*.

## Technical Skills

* **Systems**: AWS, GCP, Git, Docker, Linux, SLURM
* **ML**: PyTorch, Hugging Face, DeepSpeed, FlashAttention, FSDP, DDP, CUDA, ROCm, LangChain, Optuna, Composer, Weights & Biases, Triton
* **Web**: FastAPI, React, TypeScript, Nginx

## Teaching and Leadership

**Polish AI Olympiad**, Volunteer — *Feb. '24 – Jun. '25*
Contributed to the design of final-round problems for the Polish AI Olympiad.

**Open Avenues**, Volunteer Teacher — *Sep. '24 – Sep. '25*
Designed and delivered weekly machine learning and AI classes for community college students across the US.

**Imperial Driverless**, Founder — *Sep. '21 – Sep. '22*
Founded and led a team of 20+ students building autonomous driving software; coordinated perception, planning, and control, and competed on the Silverstone F1 track.
