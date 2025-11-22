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
  - [😎Paradigms](#-paradigms)
    - [🗒️ CoT-based Video Reasoning](#️-cot-based-video-reasoning)
    - [🕹️ CoF-based Video Reasoning](#️-cof-based-video-reasoning)
    - [🌈 Interleaved Video Reasoning](#-interleaved-video-reasoning)
    - [🔁 Streaming Video Reasoning](#-streaming-video-reasoning)
  - [✨️ Benchmarks](#-benchmarks)
  - [🌟 Star History](#-star-history)
  - [♥️ Contributors](#️-contributors)

<!-- <small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>`Table of contents generated with markdown-toc`</a></i></small> -->

## 😎 Paradigms

### 🕹️ CoT-based Video Reasoning

<!-- 符号:
√ ✓
x ✗

     徽章
         arxiv: https://img.shields.io/badge/arXiv-2410.12109-b31b1b.svg?style=plastic
         conference: https://img.shields.io/badge/CVPR-2024-blue.svg?style=plastic
         huggingface checkpoint:![hf_checkpoint](https://img.shields.io/badge/🤗-Checkpoints-9C276A.svg)]()
         modelscope
         github model zoos: [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)]()
-->

<!-- 模版：
|** ** [![arXiv](https://img.shields.io/badge/arXiv-[]-b31b1b.svg?style=plastic)](https://arxiv.org/abs/[])|** ** [![](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://om-cat.github.io.)|unreleased|✓|✓|✓|✓|
 -->

| **Title** | **Model & Code** | **Checkpoint** | **Input Modalities** | **Time** | **Venue** |
|----------|-------------------|----------------|----------------------|----------|-----------|
| [Ego-R1: Chain-of-Tool-Thought for Ultra-Long Egocentric Video Reasoning](https://arxiv.org/abs/2506.13654) | [Ego-R1](https://github.com/egolife-ai/Ego-R1) ![](https://img.shields.io/github/stars/egolife-ai/Ego-R1?style=social) | - | Text / Video | 2025-06 | ![](https://img.shields.io/badge/arXiv-2506.13654-b31b1b.svg?style=plastic) |
| [Video-CoT: A Comprehensive Dataset for Spatiotemporal Understanding of Videos Based on Chain-of-Thought](https://arxiv.org/abs/2506.08817) | - | [Project Page](https://video-cot.github.io/) | Text / Video | 2025-06 | ![](https://img.shields.io/badge/ACMMM-2025-blue.svg?style=plastic) |
| [CoT-Vid: Dynamic Chain-of-Thought Routing with Self-Verification for Training-Free Video Reasoning](https://arxiv.org/abs/2505.11830) | - | - | Text / Video | 2025-05 | ![](https://img.shields.io/badge/arXiv-2505.11830-b31b1b.svg?style=plastic) |
| [VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning](https://arxiv.org/abs/2505.12434) | - | [VideoRFT-CoT](https://huggingface.co/datasets/QiWang98/VideoRFT-Data) | Text / Video | 2025-05 | ![](https://img.shields.io/badge/arXiv-2505.12434-b31b1b.svg?style=plastic) |
| [VCR-Bench: A Comprehensive Evaluation Framework for Video Chain-of-Thought Reasoning](https://arxiv.org/abs/2504.07956) | - | [VCR-Bench](https://vlm-reasoning.github.io/VCR-Bench/) | Text / Video | 2025-04 | ![](https://img.shields.io/badge/arXiv-2504.07956-b31b1b.svg?style=plastic) |
| [VideoEspresso: A Large-Scale Chain-of-Thought Dataset for Fine-Grained Video Reasoning](https://arxiv.org/abs/2411.14794) | [VideoEspresso](https://github.com/hshjerry/VideoEspresso) ![](https://img.shields.io/github/stars/hshjerry/VideoEspresso?style=social) | [HF Dataset](https://huggingface.co/datasets/hshjerry0315/VideoEspresso-Test) | Text / Video | 2024-11 | ![](https://img.shields.io/badge/CVPR-2025-blue.svg?style=plastic) |
| [OMCAT: Omni Context Aware Transformer](https://arxiv.org/abs/2410.12109) | [OMCAT](https://om-cat.github.io.) ![](https://img.shields.io/github/stars/om-cat/om-cat.github.io?style=social) | unreleased | Text / Image / Audio / Video | 2024-10 | ![](https://img.shields.io/badge/arXiv-2410.12109-b31b1b.svg?style=plastic) |
| [Baichuan-Omni Technical Report](https://arxiv.org/abs/2410.08565) | [Baichuan-Omni](https://github.com/westlake-baichuan-mllm/bc-omni) ![](https://img.shields.io/github/stars/westlake-baichuan-mllm/bc-omni?style=social) | [Unreleased](https://github.com/westlake-baichuan-mllm/bc-omni) | Text / Image / Audio / Video | 2024-10 | ![](https://img.shields.io/badge/arXiv-2410.08565-b31b1b.svg?style=plastic) |
| [VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs](https://arxiv.org/abs/2406.07476) | [VideoLLaMA 2 / VideoLLaMA-2.1-AV](https://github.com/DAMO-NLP-SG/VideoLLaMA2) ![](https://img.shields.io/github/stars/DAMO-NLP-SG/VideoLLaMA2?style=social) | [Model Zoo](https://github.com/DAMO-NLP-SG/VideoLLaMA2#earth_americas-model-zoo) | Text / Image / Audio / Video | 2024-06 | ![](https://img.shields.io/badge/arXiv-2406.07476-b31b1b.svg?style=plastic) |
| [VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset](http://arxiv.org/abs/2305.18500) | [VAST](https://github.com/TXH-mercury/VAST) ![](https://img.shields.io/github/stars/TXH-mercury/VAST?style=social) | [Model Zoo](https://github.com/TXH-mercury/VAST#download--vast-models--and-captioners-for-labeling-your-own-data) | Text / Image / Audio / Video | 2023-05 | ![](https://img.shields.io/badge/NeurIPS-2023-blue.svg?style=plastic) |
| [VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset](https://arxiv.org/abs/2304.08345) | [VALOR](https://github.com/TXH-mercury/VALOR) ![](https://img.shields.io/github/stars/TXH-mercury/VALOR?style=social) | [Checkpoint](https://github.com/TXH-mercury/VALOR#download-checkpoints) | Text / Image / Audio / Video | 2023-04 | ![](https://img.shields.io/badge/arXiv-2304.08345-b31b1b.svg?style=plastic) |



### 🧙 CoF-based Video Reasoning
| **Title** | **Model & Code** | **Checkpoint** | **Time** | **Venue** |
|-----------|------------------|----------------|----------|-----------|
| [Are Video Models Ready as Zero-Shot Reasoners? An Empirical Study with the MME-CoF Benchmark](https://arxiv.org/abs/2510.26802) | [MME-CoF](https://github.com/ZiyuGuo99/MME-CoF) ![](https://img.shields.io/github/stars/ZiyuGuo99/MME-CoF?style=social) | [HF Dataset](https://huggingface.co/datasets/ZiyuG/MME-CoF) | 2025-10 | ![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic) |
| [Chain-of-Frames: Advancing Video Understanding in Multimodal LLMs via Frame-Aware Reasoning](https://arxiv.org/abs/2506.00318) | [CoF](https://github.com/SaraGhazanfari/CoF) ![](https://img.shields.io/github/stars/SaraGhazanfari/CoF?style=social) | - | 2025-06 | ![](https://img.shields.io/badge/arXiv-2506.00318-b31b1b.svg?style=plastic) |



### 🌈 Interleaved Video Reasoning

| **Title** | **Model & Code** |  **Checkpoint** | **Time** | **Venue** |
|----------|----------|--------------------|-----------|--|
| [Reasoning via Video: The First Evaluation of Video Models’ Reasoning Abilities through Maze-Solving Tasks](https://arxiv.org/abs/2511.15065) | [VR-Bench](https://huggingface.co/papers/2511.15065) | | 2025-11 | ![](https://img.shields.io/badge/arXiv-2511.15065-b31b1b.svg?style=plastic) |
| [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://arxiv.org/abs/2409.04429) | VILA-U |  |2024-09 | ![arXiv](https://img.shields.io/badge/arXiv-2409.04429-b31b1b.svg?style=plastic) |


### 🔁 Streaming Video Reasoning

| **Title** | **Model & Code** |  **Checkpoint** | **Time** | **Venue** |
|----------|----------|----------|----------|-----------|




## ✨️Benchmarks


| **Name**      | **Paper** | **Dataset** | **Task** | **Time** | **Venue** |
|---------------|-----------|-------------|----------|----------|-----------|
| MME-CoF | [Are Video Models Ready as Zero-Shot Reasoners? An Empirical Study with the MME-CoF Benchmark](https://arxiv.org/abs/2510.26802) | [HF Dataset](https://huggingface.co/datasets/ZiyuG/MME-CoF) | CoF-based | 2025-10 | ![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic) |
| SciVideoBench | [SciVideoBench: Benchmarking Scientific Video Reasoning in Large Multimodal Models](https://arxiv.org/abs/2510.08559) |  | CoT-based | 2025-10 |  |
| OmnixR    | [OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities](http://arxiv.org/abs/2410.12219) |  | CoT-based | 2024-10 |  |
| OmniBench | [OmniBench: Towards the Future of Universal Omni-Language Models](http://arxiv.org/abs/2409.15272) |   | CoT-based | 2024-09 |  |
| VideoVista | [VideoVista: A Versatile Benchmark for Video Understanding and Reasoning](https://arxiv.org/abs/2406.11303) |  | CoT-based | 2024-06 |  |
| CVRR-ES | [How Good is my Video LMM? Complex Video Reasoning and Robustness Evaluation Suite for Video-LMMs](https://arxiv.org/abs/2405.03690) | | CoT-based | 2024-05 |  |
| SOK-Bench | [SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge](https://arxiv.org/abs/2405.09713) |  |  | 2024-05 |  |



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
