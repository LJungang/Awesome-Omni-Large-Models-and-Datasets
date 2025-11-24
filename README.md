# Awesome-Video-Reasoning-Landscape [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- markdownlint-disable MD033 -->
## The Landscape of Video Reasoning: Tasks, Paradigms and Benchmarks— An Open-Source Survey

## Overview
This Awesome list systematically curates and tracks the latest progress in **Video Reasoning**, covering diverse modalities, tasks, and modeling paradigms. Rather than focusing on a single line of research, we organize the landscape from multiple complementary perspectives. Following the emerging taxonomy of the field, current works are grouped into four major paradigms:

- 🗒️ **CoT-based Video Reasoning** — language-centric, chain-of-thought reasoning with Video-LMMs  
- 🕹️ **CoF-based Video Reasoning** — vision-centric reasoning grounded in world models or video generation  
- 🌈 **Interleaved Video Reasoning** — unified models that integrate multimodal interaction and iterative inference  
- 🔁 **Streaming Video Reasoning** — continuous, low-latency reasoning over long or unbounded video streams with online perception and incremental state updates.
  
We additionally maintain a dedicated **Benchmark** section that summarizes datasets, evaluation settings, and standardized tasks to support fair comparison across paradigms.

This repository aims to provide a structured, up-to-date, and open-source overview of the evolving landscape of video reasoning.  
**Contributions and PRs are warmly welcome — preferably in reverse chronological order (newest first)** to keep the list fresh and easy to browse.


## Table of Contents
- [Awesome-Video-Reasoning-Landscape](#awesome-video-reasoning-landscape-)
  - [📑 Task Definition](#-task-definition)
  - [😎 Paradigms](#-paradigms)
    - [🗒️ CoT-based Video Reasoning](#️-CoT-based-video-reasoning)
    - [🕹️ CoF-based Video Reasoning](#️-CoF-based-video-reasoning)
    - [🌈 Interleaved Video Reasoning](#-interleaved-video-reasoning)
    - [🔁 Streaming Video Reasoning](#-streaming-video-reasoning)
  - [✨️ Benchmarks](#-benchmarks)
  - [🌟 Star History](#-star-history)
  - [♥️ Contributors](#️-contributors)

<!-- <small><i><a href='http://eCoTrust-canada.github.io/markdown-toc/'>`Table of contents generated with markdown-toc`</a></i></small> -->

## 📑 Task Definition
TBD

## 😎 Paradigms



<!-- 符号:
√ ✓
x ✗
         arxiv: https://img.shields.io/badge/arXiv-2410.12109-b31b1b.svg?style=plastic
         conference: https://img.shields.io/badge/CVPR-2024-blue.svg?style=plastic
         huggingface checkpoint:![hf_checkpoint](https://img.shields.io/badge/🤗-Checkpoints-9C276A.svg)]()
         modelscope
         github model zoos: [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)]()
-->

<!-- 模版：
|** ** [![arXiv](https://img.shields.io/badge/arXiv-[]-b31b1b.svg?style=plastic)](https://arxiv.org/abs/[])|** ** [![](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://om-cat.github.io.)|unreleased|✓|✓|✓|✓|
[![arXiv](https://img.shields.io/badge/arXiv-2505.02064-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.02064)
 
 -->

 
 ### 🕹️ CoT-based Video Reasoning

| **Title** | **Model & Code** | **Checkpoint** | **Input Modalities** | **Time** | **Venue** |
|----------|-------------------|----------------|----------------------|----------|-----------|
| [AVATAAR: Agentic Video Answering via Temporal Adaptive Alignment and Reasoning](https://arxiv.org/abs/2511.15578)| | | Audio / Video| 2025-11|[![arXiv](https://img.shields.io/badge/arXiv-2511.15578-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.15578)|
| [Agentic Video Intelligence: A Flexible Framework for Advanced Video Exploration and Understanding](https://arxiv.org/abs/2511.14446) | | | video|2025-11|[![arXiv](https://img.shields.io/badge/arXiv-/2511.14446-b31b1b.svg?style=plastic)](https://arxiv.org/abs//2511.14446)|
| [Video Spatial Reasoning with Object-Centric 3D Rollout ](https://arxiv.org/abs/2511.13190)| | | video|2025-11|[![arXiv](https://img.shields.io/badge/arXiv-/2511.13190-b31b1b.svg?style=plastic)](https://arxiv.org/abs//2511.13190)|
| [ViSS-R1: Self-Supervised Reinforcement Video Reasoning](https://arxiv.org/abs/2511.13054) | | | Video|2025-11|[![arXiv](https://img.shields.io/badge/arXiv-/2511.13054-b31b1b.svg?style=plastic)](https://arxiv.org/abs//2511.13054)|
| [Ego-R1: Chain-of-Tool-Thought for Ultra-Long Egocentric Video Reasoning](https://arxiv.org/abs/2506.13654) | [Ego-R1](https://github.com/egolife-ai/Ego-R1) ![](https://img.shields.io/github/stars/egolife-ai/Ego-R1?style=social) | - | Text / Video | 2025-06 |  [![arXiv](https://img.shields.io/badge/arXiv-2506.13654-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.13654)|
| [Video-CoT: A Comprehensive Dataset for Spatiotemporal Understanding of Videos Based on Chain-of-Thought](https://dl.acm.org/doi/10.1145/3746027.3758313) | - | [Project Page](https://video-CoT.github.io/) | Text / Video | 2025-06 |  [![](https://img.shields.io/badge/ACM--MM-2025-blue.svg?style=plastic)](https://dl.acm.org/doi/10.1145/3746027.3758313)|
| [CoT-Vid: Dynamic Chain-of-Thought Routing with Self-Verification for Training-Free Video Reasoning](https://arxiv.org/abs/2505.11830) | - | - | Text / Video | 2025-05 | [![](https://img.shields.io/badge/arXiv-2505.11830-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.11830) |
| [VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning](https://arxiv.org/abs/2505.12434) | - | [VideoRFT-CoT](https://huggingface.co/datasets/QiWang98/VideoRFT-Data) | Text / Video | 2025-05 | [![](https://img.shields.io/badge/arXiv-2505.12434-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.12434)  |
| [VCR-Bench: A Comprehensive Evaluation Framework for Video Chain-of-Thought Reasoning](https://arxiv.org/abs/2504.07956) | - | [VCR-Bench](https://vlm-reasoning.github.io/VCR-Bench/) | Text / Video | 2025-04 | [![](https://img.shields.io/badge/arXiv-2504.07956-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.07956) |
| [VideoEspresso: A Large-Scale Chain-of-Thought Dataset for Fine-Grained Video Reasoning](https://openaccess.thecvf.com/content/CVPR2025/html/Han_VideoEspresso_A_Large-Scale_Chain-of-Thought_Dataset_for_Fine-Grained_Video_Reasoning_via_CVPR_2025_paper.html) | [VideoEspresso](https://github.com/hshjerry/VideoEspresso) ![](https://img.shields.io/github/stars/hshjerry/VideoEspresso?style=social) | [HF Dataset](https://huggingface.co/datasets/hshjerry0315/VideoEspresso-Test) | Text / Video | 2024-11 | [![](https://img.shields.io/badge/CVPR-2025-blue.svg?style=plastic)](https://openaccess.thecvf.com/content/CVPR2025/html/Han_VideoEspresso_A_Large-Scale_Chain-of-Thought_Dataset_for_Fine-Grained_Video_Reasoning_via_CVPR_2025_paper.html) |





### 🧙 CoF-based Video Reasoning
| **Title** | **Model & Code** | **Checkpoint** | **Time** | **Venue** |
|-----------|------------------|----------------|----------|-----------|
|[Video-as-Answer: Predict and Generate Next Video Event with Joint-GRPO](https://arxiv.org/abs/2511.16669) | [VANS](https://github.com/KlingTeam/VANS)|[HF_Ckpt](https://huggingface.co/KlingTeam/VANS)|2025-11| [![](https://img.shields.io/badge/arXiv-2511.16669-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.16669) |
| [Are Video Models Ready as Zero-Shot Reasoners? An Empirical Study with the MME-CoF Benchmark](https://arxiv.org/abs/2510.26802) | [MME-CoF](https://github.com/ZiyuGuo99/MME-CoF) ![](https://img.shields.io/github/stars/ZiyuGuo99/MME-CoF?style=social) | [HF Dataset](https://huggingface.co/datasets/ZiyuG/MME-CoF) | 2025-10 | [![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.26802) |
| [Chain-of-Frames: Advancing Video Understanding in Multimodal LLMs via Frame-Aware Reasoning](https://arxiv.org/abs/2506.00318) | [CoF](https://github.com/SaraGhazanfari/CoF) ![](https://img.shields.io/github/stars/SaraGhazanfari/CoF?style=social) | - | 2025-06 | ![](https://img.shields.io/badge/arXiv-2506.00318-b31b1b.svg?style=plastic) |




### 🌈 Interleaved Video Reasoning

| **Title** | **Model & Code** |  **Checkpoint** | **Time** | **Venue** |
|----------|----------|--------------------|-----------|--|
| [Reasoning via Video: The First Evaluation of Video Models’ Reasoning Abilities through Maze-Solving Tasks](https://arxiv.org/abs/2511.15065) | [VR-Bench](https://huggingface.co/papers/2511.15065) | | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.15065-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.15065)  |
| [Orion: A Unified Visual Agent for Multimodal Perception, Advanced Visual Reasoning and Execution](https://arxiv.org/abs/2511.14210) | | | 2025-11 | [![arXiv](https://img.shields.io/badge/arXiv-2511.14120-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.14120)  |
| [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://arxiv.org/abs/2409.04429) | VILA-U |  |2024-09 | [![arXiv](https://img.shields.io/badge/arXiv-2409.04429-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.04429)  |


### 🔁 Streaming Video Reasoning

| **Title** | **Model & Code** |  **Checkpoint** | **Time** | **Venue** |
|----------|----------|----------|----------|-----------|




## ✨️Benchmarks


| **Name**      | **Paper** | **Dataset** | **Task** | **Time** | **Venue** |
|--------------------|-----------|-------------|----------|----------|-----------|
| V-ReasonBench | [V-ReasonBench: Toward Unified Reasoning Benchmark Suite for Video Generation Models](https://arxiv.org/abs/2511.16668) |  |  CoF-based | 2025-11|[![](https://img.shields.io/badge/arXiv-2511.16668-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.16668)|
| TiViBench |[TiViBench: Benchmarking Think-in-Video Reasoning for Video Generative Models](https://arxiv.org/abs/2511.13704) | |CoF-based | 2025-11|[![](https://img.shields.io/badge/arXiv-2511.13704-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.13704)|
| MME-CoF | [Are Video Models Ready as Zero-Shot Reasoners? An Empirical Study with the MME-CoF Benchmark](https://arxiv.org/abs/2510.26802) | [HF Dataset](https://huggingface.co/datasets/ZiyuG/MME-CoF) | CoF-based | 2025-10 | [![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.26802) |
| SciVideoBench | [SciVideoBench: Benchmarking Scientific Video Reasoning in Large Multimodal Models](https://arxiv.org/abs/2510.08559) |  | CoT-based | 2025-10 | [![](https://img.shields.io/badge/arXiv-2510.08559-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.08559)  |
| OmnixR    | [OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities](http://arxiv.org/abs/2410.12219) |  | CoT-based | 2024-10 |  [![](https://img.shields.io/badge/arXiv-2410.12219-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.12219) |
| OmniBench | [OmniBench: Towards the Future of Universal Omni-Language Models](http://arxiv.org/abs/2409.15272) |   | CoT-based | 2024-09 |  [![](https://img.shields.io/badge/arXiv-2409.15272-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.15272) |
| VideoVista | [VideoVista: A Versatile Benchmark for Video Understanding and Reasoning](https://arxiv.org/abs/2406.11303) |  | CoT-based | 2024-06 |  [![](https://img.shields.io/badge/arXiv-2406.11303-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2406.11303) |
| CVRR-ES | [How Good is my Video LMM? Complex Video Reasoning and Robustness Evaluation Suite for Video-LMMs](https://arxiv.org/abs/2405.03690) | | CoT-based | 2024-05 |  [![](https://img.shields.io/badge/arXiv-2405.03690-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2405.03690) |
| SOK-Bench | [SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge](https://arxiv.org/abs/2405.09713) |  |  | 2024-05 |  [![](https://img.shields.io/badge/arXiv-2405.09713-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2405.09713) |

## ✈ Related Survey

In addition, a number of recent and concurrent surveys have discussed video understanding and video reasoning. The works listed below offer complementary perspectives to ours, reflecting the field’s rapid and parallel development:
- [Awesome-Video-Reasoning](https://github.com/Video-Reason/Awesome-Video-Reasoning)
- [Awesome-Multimodal-Spatial-Reasoning](https://github.com/zhengxuJosh/Awesome-Multimodal-Spatial-Reasoning)
- [Awesome-Video-LMM-Post-Training](https://github.com/yunlong10/Awesome-Video-LMM-Post-Training)
- [Awesome-LLMs-for-Video-Understanding](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding)


## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=LJungang/Awesome-Video-Reasoning-Landscape&type=Date)](https://star-history.com/#LJungang/Awesome-Omni-Large-Models-and-Datasets&Date)

## ♥️ Contributors

<!--
<a href="https://github.com/LJungang/Awesome-Video-Reasoning-Landscape/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LJungang/Awesome-Video-Reasoning-Landscape" />
</a>
 -->

<a href="https://github.comLJungang/Awesome-Video-Reasoning-Landscape/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LJungang/Awesome-Video-Reasoning-Landscape" alt="Contributors for Awesome Video Reasoning Landscape"/>
</a>

<!-- markdownlint-enable MD033 -->
