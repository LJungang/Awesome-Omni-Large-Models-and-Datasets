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
| [Video-R4: Reinforcing Text-Rich Video Reasoning with Visual Rumination](https://arxiv.org/abs/2511.17490)| [github](https://github.com/yunlong10/Video-R4) | - | Text / Video | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.15578-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.15578)|
| [AVATAAR: Agentic Video Answering via Temporal Adaptive Alignment and Reasoning](https://arxiv.org/abs/2511.15578)| - | - | Audio / Video | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.15578-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.15578)|
| [Agentic Video Intelligence: A Flexible Framework for Advanced Video Exploration and Understanding](https://arxiv.org/abs/2511.14446) | - | - | Video | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.14446-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.14446)|
| [Video Spatial Reasoning with Object-Centric 3D Rollout](https://arxiv.org/abs/2511.13190)| - | - | Video | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.13190-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.13190)|
| [ViSS-R1: Self-Supervised Reinforcement Video Reasoning](https://arxiv.org/abs/2511.13054) | - | - | Text / Video | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.13054-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.13054)|
| [Video-Thinker: Sparking "Thinking with Videos" via Reinforcement Learning](https://arxiv.org/pdf/2510.23473)| [github](https://github.com/shijian2001/Video-Thinker) | [HuggingFace](https://huggingface.co/ShijianW01/Video-Thinker-7B) | Text / Video | 2025-10 | [![arXiv](https://img.shields.io/badge/2510.23473-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.23473) |
| [Open-o3 Video: Grounded Video Reasoning with Explicit Spatio-Temporal Evidence](https://arxiv.org/pdf/2510.20579)| [github](https://github.com/marinero4972/Open-o3-Video) | [HuggingFace](https://huggingface.co/marinero4972/Open-o3-Video) | Text / Video | 2025-10 | [![arXiv](https://img.shields.io/badge/arXiv-2510.20579-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.20579) |
| [VideoChat-R1.5: Visual Test-Time Scaling to Reinforce Multimodal Reasoning by Iterative Perception](https://arxiv.org/abs/2509.21100) | - | - | Text / Video | 2025-09 | [![arXiv](https://img.shields.io/badge/arXiv-2509.21100-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2509.21100) |
| [MOSS-ChatV: Reinforcement Learning with Process Reasoning Reward for Video Temporal Reasoning](https://arxiv.org/abs/2509.21113) | - | - | Text / Video | 2025-09 | [![arXiv](https://img.shields.io/badge/arXiv-2509.21113-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2509.21113) |
| [ChronoForge-RL: Chronological Forging through Reinforcement Learning for Enhanced Video Understanding](https://arxiv.org/abs/2509.15800) | - | - | Text / Video | 2025-09 | [![arXiv](https://img.shields.io/badge/arXiv-2509.15800-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2509.15800) |
| [Kwai Keye-VL 1.5 Technical Report](https://arxiv.org/abs/2509.01563) | - | - | Text / Video | 2025-09 | [![arXiv](https://img.shields.io/badge/arXiv-2509.01563-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2509.01563) |
| [Strefer: Empowering Video LLMs with Space-Time Referring and Reasoning via Synthetic Instruction Data](https://arxiv.org/abs/2509.03501) | - | - | Text / Video | 2025-09 | [![arXiv](https://img.shields.io/badge/arXiv-2509.03501-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2509.03501) |
| [Video-MTR: Reinforced Multi-Turn Reasoning for Long Video Understanding](https://arxiv.org/abs/2508.20478) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.20478-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.20478) |
| [Ovis2.5 Technical Report](https://arxiv.org/abs/2508.11737) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.11737-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.11737) |
| [ReasoningTrack: Chain-of-Thought Reasoning for Long-term Vision-Language Tracking](https://arxiv.org/abs/2508.05221) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.05221-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.05221) |
| [TAR-TVG: Enhancing VLMs with Timestamp Anchor-Constrained Reasoning for Temporal Video Grounding](https://arxiv.org/abs/2508.07683) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.07683-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.07683) |
| [Thinking With Videos: Multimodal Tool-Augmented Reinforcement Learning for Long Video Reasoning](https://arxiv.org/abs/2508.04416) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.04416-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.04416) |
| [AVATAR: Reinforcement Learning to See, Hear, and Reason Over Video](https://arxiv.org/abs/2508.03100) | - | - | Audio / Video / Text | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.03100-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.03100) |
| [ReasonAct: Progressive Training for Fine-Grained Video Reasoning in Small Models](https://arxiv.org/abs/2508.01533) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.01533-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.01533) |
| [VideoForest: Person-Anchored Hierarchical Reasoning for Cross-Video Question Answering](https://arxiv.org/abs/2508.03039) | - | - | Text / Video | 2025-08 | [![arXiv](https://img.shields.io/badge/arXiv-2508.03039-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2508.03039) |
| [ARC-Hunyuan-Video-7B: Structured Video Comprehension of Real-World Shorts](https://arxiv.org/abs/2507.20939) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.20939-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.20939) |
| [METER: Multi-modal Evidence-based Thinking and Explainable Reasoning -- Algorithm and Benchmark](https://arxiv.org/abs/2507.16206) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.16206-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.16206) |
| [CoTasks: Chain-of-Thought based Video Instruction Tuning Tasks](https://arxiv.org/abs/2507.13609) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.13609-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.13609) |
| [EmbRACE-3K: Embodied Reasoning and Action in Complex Environments](https://arxiv.org/abs/2507.10548) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.10548-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.10548) |
| [Scaling RL to Long Videos](https://arxiv.org/abs/2507.07966) | - | [HuggingFace](https://huggingface.co/datasets/LongVideo-Reason/longvideo-reason) | Text / Video | 2025-07 |  [![](https://img.shields.io/badge/NeurIPS-2025-blue.svg?style=plastic)]()  |
| [Video Event Reasoning and Prediction by Fusing World Knowledge from LLMs with Vision Foundation Models](https://arxiv.org/abs/2507.05822) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.05822-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.05822) |
| [Kwai Keye-VL Technical Report](https://arxiv.org/abs/2507.01949) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.01949-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.01949) |
| [EgoPrune: Efficient Token Pruning for Egomotion Video Reasoning in Embodied Agent](https://arxiv.org/abs/2507.15428) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.15428-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.15428) |
| [Towards Video Thinking Test: A Holistic Benchmark for Advanced Video Reasoning and Understanding](https://arxiv.org/abs/2507.15028) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.15028-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.15028) |
| [ViTCoT: Video-Text Interleaved Chain-of-Thought for Boosting Video Understanding in Large Language Models](https://arxiv.org/abs/2507.09876) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.09876-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.09876) |
| [Video-RTS: Rethinking Reinforcement Learning and Test-Time Scaling for Efficient and Enhanced Video Reasoning](https://arxiv.org/abs/2507.06485) | - | - | Text / Video | 2025-07 |  [![](https://img.shields.io/badge/EMNLP-2025(Main)-blue.svg?style=plastic)]()|
| [Temporal Chain of Thought: Long-Video Understanding by Thinking in Frames](https://arxiv.org/abs/2507.02001) | - | - | Text / Video | 2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.02001-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.02001) |
| [VLN-R1: Vision-Language Navigation via Reinforcement Fine-Tuning](https://arxiv.org/abs/2506.17221) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.17221-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.17221) |
| [Ego-R1: Chain-of-Tool-Thought for Ultra-Long Egocentric Video Reasoning](https://arxiv.org/abs/2506.13654) | [Ego-R1](https://github.com/egolife-ai/Ego-R1) ![](https://img.shields.io/github/stars/egolife-ai/Ego-R1?style=social) | - | Text / Video | 2025-06 |  [![arXiv](https://img.shields.io/badge/arXiv-2506.13654-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.13654)|
| [DAVID-XR1: Detecting AI-Generated Videos with Explainable Reasoning](https://arxiv.org/abs/2506.14827) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.14827-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.14827) |
| [VersaVid-R1: A Versatile Video Understanding and Reasoning Model from Question Answering to Captioning Tasks](https://arxiv.org/abs/2506.09079) | - | [HuggingFace](https://huggingface.co/datasets/VidBridge-R1/VidBridge-R1_training_data) | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.09079-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.09079) |
| [MiMo-VL Technical Report](https://arxiv.org/abs/2506.03569) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.03569-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.03569) |
| [Video-Skill-CoT: Skill-based Chain-of-Thoughts for Domain-Adaptive Video Reasoning](https://arxiv.org/abs/2506.03525) | - | - | Text / Video | 2025-06 |  [![](https://img.shields.io/badge/EMNLP-2025(Findings)-blue.svg?style=plastic)]() |
| [EgoVLM: Policy Optimization for Egocentric Video Understanding](https://arxiv.org/abs/2506.03097) | - |  [HuggingFace](https://huggingface.co/datasets/omlab/VLM-R1) | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.03097-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.03097) |
| [Reinforcement Learning Tuning for VideoLLMs: Reward Design and Data Efficiency](https://arxiv.org/abs/2506.01908) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.01908-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.01908) |
| [VideoCap-R1: Enhancing MLLMs for Video Captioning via Structured Thinking](https://arxiv.org/abs/2506.01725) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.01725-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.01725) |
| [ReAgent-V: A Reward-Driven Multi-Agent Framework for Video Understanding](https://arxiv.org/abs/2506.01300) | - | - | Text / Video | 2025-06 |  [![](https://img.shields.io/badge/NeurIPS-2025-blue.svg?style=plastic)]() |
| [ReFoCUS: Reinforcement-guided Frame Optimization for Contextual Understanding](https://arxiv.org/abs/2506.01274) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.01274-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.01274) |
| [DIVE: Deep-search Iterative Video Exploration](https://arxiv.org/abs/2506.21891) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.21891-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.21891) |
| [How Far Can Off-the-Shelf Multimodal Large Language Models Go in Online Episodic Memory Question Answering?](https://arxiv.org/abs/2506.16450) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.16450-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.16450) |
| [VideoDeepResearch: Long Video Understanding With Agentic Tool Using](https://arxiv.org/abs/2506.10821) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.10821-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.10821) |
| [Wait, We Don't Need to "Wait"! Removing Thinking Tokens Improves Reasoning Efficiency](https://arxiv.org/abs/2506.08343) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.08343-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.08343) |
| [DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO](https://arxiv.org/abs/2506.07464) | [Github](https://github.com/mlvlab/DeepVideoR1) | - | Text / Video | 2025-06 |  [![arXiv](https://img.shields.io/badge/arXiv-2506.07464-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.07464) |
| [Video-CoT: A Comprehensive Dataset for Spatiotemporal Understanding of Videos Based on Chain-of-Thought](https://dl.acm.org/doi/10.1145/3746027.3758313) | - | [Project Page](https://video-CoT.github.io/) | Text / Video | 2025-06 |  [![](https://img.shields.io/badge/ACM--MM-2025-blue.svg?style=plastic)](https://dl.acm.org/doi/10.1145/3746027.3758313)|
| [VideoChat-A1: Thinking with Long Videos by Chain-of-Shot Reasoning](https://arxiv.org/abs/2506.06097) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.06097-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.06097) |
| [Chain-of-Frames: Advancing Video Understanding in Multimodal LLMs via Frame-Aware Reasoning](https://arxiv.org/abs/2506.00318) | - | - | Text / Video | 2025-06 | [![arXiv](https://img.shields.io/badge/arXiv-2506.00318-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2506.00318) |
| [Reinforcing Video Reasoning with Focused Thinking](https://arxiv.org/abs/2505.24718) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.24718-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.24718) |
| [A2Seek: Towards Reasoning-Centric Benchmark for Aerial Anomaly Understanding](https://arxiv.org/abs/2505.21962) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.21962-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.21962) |
| [Omni-R1: Reinforcement Learning for Omnimodal Reasoning via Two-System Collaboration](https://arxiv.org/abs/2505.20256) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.20256-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.20256) |
| [Vad-R1: Towards Video Anomaly Reasoning via Perception-to-Cognition Chain-of-Thought](https://arxiv.org/abs/2505.19877) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.19877-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.19877) |
| [VerIPO: Cultivating Long Reasoning in Video-LLMs via Verifier-Guided Iterative Policy Optimization](https://arxiv.org/abs/2505.19000) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.19000-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.19000) |
| [Fact-R1: Towards Explainable Video Misinformation Detection with Deep Reasoning](https://arxiv.org/abs/2505.16836) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.16836-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.16836) |
| [Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning](https://arxiv.org/abs/2505.15966) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.15966-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.15966) |
| [UniVG-R1: Reasoning Guided Universal Visual Grounding with Reinforcement Learning](https://arxiv.org/abs/2505.14231) | - | [HuggingFace](https://huggingface.co/datasets/GD-ML/UniVG-R1-data) | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.14231-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.14231) |
| [VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning](https://arxiv.org/abs/2505.12434) | - |  [HuggingFace](https://huggingface.co/datasets/QiWang98/VideoRFT-Data) | Text / Video | 2025-05 | [![](https://img.shields.io/badge/arXiv-2505.12434-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.12434)  |
| [Seed1.5-VL Technical Report](https://arxiv.org/abs/2505.07062) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.07062-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.07062) |
| [TEMPURA: Temporal Event Masked Prediction and Understanding for Reasoning in Action](https://arxiv.org/abs/2505.01583) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.01583-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.01583) |
| [Fostering Video Reasoning via Next-Event Prediction](https://arxiv.org/abs/2505.22457) | - | [HuggingFace](https://huggingface.co/datasets/haonan3/V1-33K) | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.22457-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.22457) |
| [SiLVR: A Simple Language-based Video Reasoning Framework](https://arxiv.org/abs/2505.24869) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.24869-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.24869) |
| [VideoReasonBench: Can MLLMs Perform Vision-Centric Complex Video Reasoning?](https://arxiv.org/abs/2505.23359) | - |  [HuggingFace](https://huggingface.co/datasets/lyx97/reasoning_videos) | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.23359-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.23359) |
| [RVTBench: A Benchmark for Visual Reasoning Tasks](https://arxiv.org/abs/2505.11838) | - |  [HuggingFace](https://huggingface.co/datasets/yiqingshen/rvtbench/tree/main/rvtbench) | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.11838-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.11838) |
| [CoT-Vid: Dynamic Chain-of-Thought Routing with Self-Verification for Training-Free Video Reasoning](https://arxiv.org/abs/2505.11830) | - | - | Text / Video | 2025-05 | [![](https://img.shields.io/badge/arXiv-2505.11830-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.11830) |
| [VCRBench: Exploring Long-form Causal Reasoning Capabilities of Large Video Language Models](https://arxiv.org/abs/2505.08455) | - | - | Text / Video | 2025-05 | [![](https://img.shields.io/badge/arXiv-2505.08455-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.08455) |
| [Empowering Agentic Video Analytics Systems with Video Language Models](https://arxiv.org/abs/2505.00254) | - | - | Text / Video | 2025-05 | [![arXiv](https://img.shields.io/badge/arXiv-2505.00254-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2505.00254) |
| [TinyLLaVA-Video-R1: Towards Smaller LMMs for Video Reasoning](https://arxiv.org/abs/2504.09641) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.09641-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.09641) |
| [VideoChat-R1: Enhancing Spatio-Temporal Perception via Reinforcement Fine-Tuning](https://arxiv.org/abs/2504.06958) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.06958-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.06958) |
| [Spatial-R1: Enhancing MLLMs in Video Spatial Reasoning](https://arxiv.org/abs/2504.01805) | - | [HuggingFace](https://huggingface.co/datasets/RUBBISHLIKE/SpaceR-151k) | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.01805-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.01805) |
| [Improved Visual-Spatial Reasoning via R1-Zero-Like Training](https://arxiv.org/abs/2504.00883) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.00883-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.00883) |
| [Eagle 2.5: Boosting Long-Context Post-Training for Frontier Vision-Language Models](https://arxiv.org/abs/2504.15271) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.15271-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.15271) |
| [LVC: A Lightweight Compression Framework for Enhancing VLMs in Long Video Understanding](https://arxiv.org/abs/2504.06835) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.06835-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.06835) |
| [From 128K to 4M: Efficient Training of Ultra-Long Context Large Language Models](https://arxiv.org/abs/2504.06214) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.06214-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.06214) |
| [MR. Video: "MapReduce" is the Principle for Long Video Understanding](https://arxiv.org/abs/2504.16082) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.16082-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.16082) |
| [Multimodal Long Video Modeling Based on Temporal Dynamic Context](https://arxiv.org/abs/2504.10443) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.10443-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.10443) |
| [WikiVideo: Article Generation from Multiple Videos](https://arxiv.org/abs/2504.00939) | - | - | Text / Video | 2025-04 | [![arXiv](https://img.shields.io/badge/arXiv-2504.00939-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.00939) |
| [VCR-Bench: A Comprehensive Evaluation Framework for Video Chain-of-Thought Reasoning](https://arxiv.org/abs/2504.07956) | - | [HuggingFace](https://vlm-reasoning.github.io/VCR-Bench/) | Text / Video | 2025-04 | [![](https://img.shields.io/badge/arXiv-2504.07956-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2504.07956) |
| [Exploring the Effect of Reinforcement Learning on Video Understanding: Insights from SEED-Bench-R1](https://arxiv.org/abs/2503.24376) | - |  [HuggingFace](https://huggingface.co/datasets/TencentARC/SEED-Bench-R1) | Text / Video | 2025-03 | [![arXiv](https://img.shields.io/badge/arXiv-2503.24376-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2503.24376) |
| [Video-R1: Reinforcing Video Reasoning in MLLMs](https://arxiv.org/abs/2503.21776) | - |  [HuggingFace](https://huggingface.co/datasets/Video-R1/Video-R1-data) | Text / Video | 2025-03 | [![arXiv](https://img.shields.io/badge/arXiv-2503.21776-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2503.21776) |
| [TimeZero: Temporal Video Grounding with Reasoning-Guided LVLM](https://arxiv.org/abs/2503.13377) | - | [HuggingFace](https://huggingface.co/datasets/Boshenxx/TimeR1-Dataset) | Text / Video | 2025-03 | [![arXiv](https://img.shields.io/badge/arXiv-2503.13377-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2503.13377) |
| [ST-Think: How Multimodal Large Language Models Reason About 4D Worlds from Ego-Centric Videos](https://arxiv.org/abs/2503.12542) | - | - | Text / Video | 2025-03 | [![arXiv](https://img.shields.io/badge/arXiv-2503.12542-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2503.12542) |
| [VideoMind: A Chain-of-LoRA Agent for Long Video Reasoning](https://arxiv.org/abs/2503.13444) | - |  [HuggingFace](https://huggingface.co/datasets/yeliudev/VideoMind-Dataset/tree/main) | Text / Video | 2025-03 | [![arXiv](https://img.shields.io/badge/arXiv-2503.13444-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2503.13444) |
| [Aurelia: Test-time Reasoning Distillation in Audio-Visual LLMs](https://arxiv.org/abs/2503.23219) | - | - | Audio / Video / Text | 2025-03 | [![arXiv](https://img.shields.io/badge/arXiv-2503.23219-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2503.23219) |
| [video-SALMONN-o1: Reasoning-enhanced Audio-visual Large Language Model](https://arxiv.org/abs/2502.11775) | - | - | Audio / Video / Text | 2025-02 | [![arXiv](https://img.shields.io/badge/arXiv-2502.11775-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2502.11775) |
| [TheoremExplainAgent: Towards Multimodal Explanations for LLM Theorem Understanding](https://arxiv.org/abs/2502.19400) | - |  [HuggingFace](https://huggingface.co/datasets/TIGER-Lab/TheoremExplainBench) | Text / Video | 2025-02 |  [![](https://img.shields.io/badge/ACL-2025(Main)-blue.svg?style=plastic)]() |
| [CoS: Chain-of-Shot Prompting for Long Video Understanding](https://arxiv.org/abs/2502.06428) | - | - | Text / Video | 2025-02 | [![arXiv](https://img.shields.io/badge/arXiv-2502.06428-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2502.06428) |
| [Long-VITA: Scaling Large Multi-modal Models to 1 Million Tokens with Leading Short-Context Accuray](https://arxiv.org/abs/2502.05177) | - | - | Text / Video | 2025-02 | [![arXiv](https://img.shields.io/badge/arXiv-2502.05177-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2502.05177) |
| [Temporal Preference Optimization for Long-Form Video Understanding](https://arxiv.org/abs/2501.13919) | - | - | Text / Video | 2025-01 | [![arXiv](https://img.shields.io/badge/arXiv-2501.13919-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2501.13919) |
| [InternLM-XComposer2.5-Reward: A Simple Yet Effective Multi-Modal Reward Model](https://arxiv.org/abs/2501.12368) | - | - | Text / Video | 2025-01 |  [![](https://img.shields.io/badge/ACL-2025(Findings)-blue.svg?style=plastic)]() |
| [MECD+: Unlocking Event-Level Causal Graph Discovery for Video Reasoning](https://arxiv.org/abs/2501.07227) | - | - | Text / Video | 2025-01 | [![arXiv](https://img.shields.io/badge/arXiv-2501.07227-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2501.07227) |
| [Building a Mind Palace: Structuring Environment-Grounded Semantic Graphs for Effective Long Video Analysis with LLMs](https://arxiv.org/abs/2501.04336) | - | - | Text / Video | 2025-01 | [![arXiv](https://img.shields.io/badge/arXiv-2501.04336-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2501.04336) |
| [Video-of-Thought: Step-by-Step Video Reasoning from Perception to Cognition](https://arxiv.org/abs/2501.03230) | - | - | Text / Video | 2025-01 | ICML 2024 Oral |
| [Thinking in Space: How Multimodal Large Language Models See, Remember, and Recall Spaces](https://arxiv.org/abs/2412.14171) | - | - | Text / Video | 2024-12 | [![arXiv](https://img.shields.io/badge/arXiv-2412.14171-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2412.14171) |
| [Expanding Performance Boundaries of Open-Source Multimodal Models with Model, Data, and Test-Time Scaling](https://arxiv.org/abs/2412.05271) | - | [HuggingFace](https://github.com/OpenGVLab/InternVL) | Text / Video | 2024-12 | [![arXiv](https://img.shields.io/badge/arXiv-2412.05271-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2412.05271) |
| [STEP: Enhancing Video-LLMs' Compositional Reasoning by Spatio-Temporal Graph-guided Self-Training](https://arxiv.org/abs/2412.00161) | - | - | Text / Video | 2024-12 | [![arXiv](https://img.shields.io/badge/arXiv-2412.00161-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2412.00161) |
| [PruneVid: Visual Token Pruning for Efficient Video Large Language Models](https://arxiv.org/abs/2412.16117) | - | - | Text / Video | 2024-12 | [![arXiv](https://img.shields.io/badge/arXiv-2412.16117-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2412.16117) |
| [VideoEspresso: A Large-Scale Chain-of-Thought Dataset for Fine-Grained Video Reasoning via Core Frame Selection](https://openaccess.thecvf.com/content/CVPR2025/html/Han_VideoEspresso_A_Large-Scale_Chain-of-Thought_Dataset_for_Fine-Grained_Video_Reasoning_via_CVPR_2025_paper.html) | [VideoEspresso](https://github.com/hshjerry/VideoEspresso) ![](https://img.shields.io/github/stars/hshjerry/VideoEspresso?style=social) |  [HuggingFace](https://huggingface.co/datasets/hshjerry0315/VideoEspresso-Test) | Text / Video | 2024-11 | [![](https://img.shields.io/badge/CVPR-2025-blue.svg?style=plastic)](https://openaccess.thecvf.com/content/CVPR2025/html/Han_VideoEspresso_A_Large-Scale_Chain-of-Thought_Dataset_for_Fine-Grained_Video_Reasoning_via_CVPR_2025_paper.html) |
| [Adaptive Video Understanding Agent: Enhancing efficiency with dynamic frame sampling and feedback-driven reasoning](https://arxiv.org/abs/2410.20252) | - | - | Text / Video | 2024-10 | [![arXiv](https://img.shields.io/badge/arXiv-2410.20252-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.20252) |
| [VideoINSTA: Zero-shot Long Video Understanding via Informative Spatial-Temporal Reasoning with LLMs](https://arxiv.org/abs/2409.20365) | - | - | Text / Video | 2024-09 | [![arXiv](https://img.shields.io/badge/arXiv-2409.20365-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.20365) |
| [MECD: Unlocking Multi-Event Causal Discovery in Video Reasoning](https://arxiv.org/abs/2409.17647) | - |  [HuggingFace](https://github.com/tychen-SJTU/MECD-Benchmark) | Text / Video | 2024-09 |  [![](https://img.shields.io/badge/NeurIPS-2024(Spotlight)-blue.svg?style=plastic)]() |
| [Veason-R1: Reinforcing Video Reasoning Segmentation to Think Before It Segments](https://arxiv.org/abs/2407.05513) | - | - | Text / Video | 2024-07 | [![arXiv](https://img.shields.io/badge/arXiv-2407.05513-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2407.05513) |

### 🧙 CoF-based Video Reasoning
| **Title** | **Code** | **Checkpoint** | **Time** | **Venue** |
|-----------|------------------|----------------|----------|-----------|
| [Video-as-Answer: Predict and Generate Next Video Event with Joint-GRPO](https://arxiv.org/abs/2511.16669) | [GitHub](https://github.com/KlingTeam/VANS) ![](https://img.shields.io/github/stars/KlingTeam/VANS?style=social)|[Hugging_Face](https://huggingface.co/KlingTeam/VANS)|2025-11| [![](https://img.shields.io/badge/arXiv-2511.16669-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.16669) |
| [Reasoning via Video: The First Evaluation of Video Models’ Reasoning Abilities through Maze-Solving Tasks](https://arxiv.org/abs/2511.15065) | [GitHub](https://github.com/ImYangC7/VR-Bench) ![](https://img.shields.io/github/stars/ImYangC7/VR-Bench?style=social) | [Hugging_Face](https://huggingface.co/HY-Wan/Wan-R1) | 2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.15065-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.15065)  |
| [Thinking with Video: Video Generation as a Promising Multimodal Reasoning Paradigm](https://arxiv.org/abs/2511.04570)| [GitHub](https://github.com/tongjingqi/Thinking-with-Video) ![](https://img.shields.io/github/stars/tongjingqi/Thinking-with-Video) | - | 2025-11| ![](https://img.shields.io/badge/arXiv-2511.04570-b31b1b.svg?style=plastic)|
| [Are Video Models Ready as Zero-Shot Reasoners? An Empirical Study with the MME-CoF Benchmark](https://arxiv.org/abs/2510.26802) | [GitHub](https://github.com/ZiyuGuo99/MME-CoF) ![](https://img.shields.io/github/stars/ZiyuGuo99/MME-CoF?style=social) |  [Hugging_Face](https://huggingface.co/datasets/ZiyuG/MME-CoF) | 2025-10 | [![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.26802) | 
| [VChain : Chain-of-Visual-Thought for Reasoning in Video Generation](https://arxiv.org/abs/2510.05094)|  [GitHub](https://github.com/Eyeline-Labs/VChain) ![](https://img.shields.io/github/stars/Eyeline-Labs/VChain?style=social) | - |2025-10|![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic) |
| [Chain-of-Frames: Advancing Video Understanding in Multimodal LLMs via Frame-Aware Reasoning](https://arxiv.org/abs/2506.00318) | [GitHub](https://github.com/SaraGhazanfari/CoF) ![](https://img.shields.io/github/stars/SaraGhazanfari/CoF?style=social) | - | 2025-06 | ![](https://img.shields.io/badge/arXiv-2506.00318-b31b1b.svg?style=plastic) |



### 🌈 Interleaved Video Reasoning

| **Title** | **Code** |  **Checkpoint** | **Time** | **Venue** |
|----------|----------|--------------------|-----------|--|
| [Orion: A Unified Visual Agent for Multimodal Perception, Advanced Visual Reasoning and Execution](https://arxiv.org/abs/2511.14210) | - | - | 2025-11 | [![arXiv](https://img.shields.io/badge/arXiv-2511.14120-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.14120)  |
| [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://arxiv.org/abs/2409.04429) | - | -   |2024-09 | [![arXiv](https://img.shields.io/badge/arXiv-2409.04429-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.04429)  |


### 🔁 Streaming Video Reasoning

| **Title** | **Code** |  **Checkpoint** | **Time** | **Venue** |
|----------|----------|----------|----------|-----------|
| [StreamVLN: Streaming Vision-and-Language Navigation via SlowFast Context Modeling](https://arxiv.org/abs/2507.05240) | - | - |  2025-07 | [![arXiv](https://img.shields.io/badge/arXiv-2507.05240-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2507.05240) |
| [Streaming Video Understanding and Multi-round Interaction with Memory-enhanced Knowledge](https://arxiv.org/abs/2501.13468) | - | - |  2025-01 | [![](https://img.shields.io/badge/ICLR-2025-blue.svg?style=plastic)]() |




## ✨️Benchmarks

| **Name**      | **Paper** | **Link** | **Task** | **Time** | **Venue** |
|--------------------|-----------|-------------|----------|----------|-----------|
| V-ReasonBench | [V-ReasonBench: Toward Unified Reasoning Benchmark Suite for Video Generation Models](https://arxiv.org/abs/2511.16668) | - | CoF-based | 2025-11 | [![](https://img.shields.io/badge/arXiv-2511.16668-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.16668) |
| VR-Bench|[Reasoning via Video: The First Evaluation of Video Models’ Reasoning Abilities through Maze-Solving Tasks](https://arxiv.org/abs/2511.15065) | [GitHub](https://github.com/ImYangC7/VR-Bench) ![](https://img.shields.io/github/stars/ImYangC7/VR-Bench?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/amagipeng/VR-Bench) | CoF-based |2025-11 |[![arXiv](https://img.shields.io/badge/arXiv-2511.15065-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.15065)  |
| Gen-ViRe   | [Can World Simulators Reason? Gen-ViRe: A Generative Visual Reasoning Benchmark](https://arxiv.org/abs/2511.13853) | [GitHub](https://github.com/L-CodingSpace/GVR) ![](https://img.shields.io/github/stars/L-CodingSpace/GVR?style=social)| CoF-based | 2025-11 |[![](https://img.shields.io/badge/arXiv-2511.13853-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.13853)|
| TiViBench | [TiViBench: Benchmarking Think-in-Video Reasoning for Video Generative Models](https://arxiv.org/abs/2511.13704) | - | CoF-based | 2025-11 | [![](https://img.shields.io/badge/arXiv-2511.13704-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2511.13704) |
| VideoThinkBench |[Thinking with Video: Video Generation as a Promising Multimodal Reasoning Paradigm](https://arxiv.org/abs/2511.04570)| [GitHub](https://github.com/tongjingqi/Thinking-with-Video) ![](https://img.shields.io/github/stars/tongjingqi/Thinking-with-Video) | CoF-based | 2025-11| ![](https://img.shields.io/badge/arXiv-2511.04570-b31b1b.svg?style=plastic)|
| MME-CoF | [Are Video Models Ready as Zero-Shot Reasoners? An Empirical Study with the MME-CoF Benchmark](https://arxiv.org/abs/2510.26802) | [Hugging_Face](https://huggingface.co/datasets/ZiyuG/MME-CoF) | CoF-based | 2025-10 | [![](https://img.shields.io/badge/arXiv-2510.26802-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.26802) |
| SciVideoBench | [SciVideoBench: Benchmarking Scientific Video Reasoning in Large Multimodal Models](https://arxiv.org/abs/2510.08559) |  | CoT-based | 2025-10 | [![](https://img.shields.io/badge/arXiv-2510.08559-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2510.08559)  |
| Scaling RL to Long Videos | [Long-RL: Scaling RL to Long Sequences](https://arxiv.org/abs/2507.07966) | [Hugging_Face](https://huggingface.co/datasets/LongVideo-Reason/longvideo-reason) | - | 2025-07 | [![](https://img.shields.io/badge/NeurIPS-2025-blue.svg?style=plastic)]() |
| ReasoningTrack | [ReasoningTrack: Chain-of-Thought Reasoning for Long-term Vision-Language Tracking](https://arxiv.org/abs/2508.05221) | - | CoT-based | 2025-08 | - |
| METER | [METER: Multi-modal Evidence-based Thinking and Explainable Reasoning -- Algorithm and Benchmark](https://arxiv.org/abs/2507.16206) | - | CoT-based | 2025-07 | - |
| Video-TT | [Towards Video Thinking Test: A Holistic Benchmark for Advanced Video Reasoning and Understanding](https://arxiv.org/abs/2507.15028) | - | CoT-based | 2025-07 | - |
| ImplicitQA | [ImplicitQA: Going beyond frames towards Implicit Video Reasoning](https://arxiv.org/abs/2506.21742) | [Hugging_Face](https://huggingface.co/datasets/ucf-crcv/ImplicitQA) | CoT-based | 2025-06 | - |
| Video-CoT | [Video-CoT: A Comprehensive Dataset for Spatiotemporal Understanding of Videos Based on Chain-of-Thought](https://arxiv.org/abs/2506.08817) | - | CoT-based | 2025-06 | - |
| Implicit-VideoQA | [Looking Beyond Visible Cues: Implicit Video Question Answering via Dual-Clue Reasoning](https://arxiv.org/abs/2506.07811) | [GitHub](https://github.com/tychen-SJTU/Implicit-VideoQA)![](https://img.shields.io/github/stars/tychen-SJTU/Implicit-VideoQA?style=social) | CoT-based | 2025-06 | - |
| MORSE-500 | [MORSE-500: A Programmatically Controllable Video Benchmark to Stress-Test Multimodal Reasoning](https://arxiv.org/abs/2506.05523) | [Hugging_Face](https://huggingface.co/datasets/video-reasoning/morse-500) | CoT-based | 2025-06 | - |
| SpookyBench | [Time Blindness: Why Video-Language Models Can't See What Humans Can](https://arxiv.org/abs/2505.24867) | - | CoT-based | 2025-05 | - |
| Video-Holmes | [Video-Holmes: Can MLLM Think Like Holmes for Complex Video Reasoning?](https://arxiv.org/abs/2505.21374) | [GitHub](https://github.com/TencentARC/Video-Holmes) ![](https://img.shields.io/github/stars/TencentARC/Video-Holmes?style=social) | CoT-based | 2025-05 | - |
| VideoEval-Pro | [Paper](https://arxiv.org/abs/2505.14640) | - | - | 2025-05 | - |
| Breaking Down Video LLM Benchmarks | [Paper](https://arxiv.org/abs/2505.14321) | - | - | 2025-05 | - |
| RTV-Bench | [Paper](https://arxiv.org/abs/2505.02064) | [GitHub](https://github.com/LJungang/RTV-Bench) ![](https://img.shields.io/github/stars/LJungang/RTV-Bench?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/RTVBench/RTV-Bench) |Streaming| 2025-05 | [![](https://img.shields.io/badge/NeurIPS-2025(DB)-blue.svg?style=plastic)]() |
| MINERVA | [Paper](https://arxiv.org/abs/2505.00681) | [GitHub](https://github.com/google-deepmind/neptune?tab=readme-ov-file#minerva) ![](https://img.shields.io/github/stars/google-deepmind/neptune?style=social)| - | 2025-05 | - |
| VCR-Bench | [Paper](https://arxiv.org/abs/2504.07956) | [GitHub](https://github.com/zhishuifeiqian/VCR-Bench) ![](https://img.shields.io/github/stars/zhishuifeiqian/VCR-Bench?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/VLM-Reasoning/VCR-Bench) | |2025-04 | - |
| SEED-Bench-R1 | [Paper](https://arxiv.org/abs/2503.24376) | [GitHub](https://github.com/TencentARC/SEED-Bench-R1) ![](https://img.shields.io/github/stars/TencentARC/SEED-Bench-R1?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/TencentARC/SEED-Bench-R1) | |2025-03 | - |
| H2VU-Benchmark | [Paper](https://arxiv.org/abs/2503.24008) | - | - | 2025-03 | - |
| OmniMMI | [Paper](https://arxiv.org/abs/2503.22952) | [GitHub](https://github.com/OmniMMI/OmniMMI) ![](https://img.shields.io/github/stars/OmniMMI/OmniMMI?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/ColorfulAI/OmniMMI) | |2025-03 | [![](https://img.shields.io/badge/CVPR-2025-blue.svg?style=plastic)]() |
| HAVEN | [Paper](https://arxiv.org/abs/2503.19622) | [GitHub](https://github.com/Hongcheng-Gao/HAVEN) ![](https://img.shields.io/github/stars/Hongcheng-Gao/HAVEN?style=social)<br>[Hugging_Face](https://github.com/Hongcheng-Gao/HAVEN/blob/main/Data/test_data.json) ||2025-03 | - |
| V-STaR | [Paper](https://arxiv.org/abs/2503.11495) | [GitHub](https://github.com/V-STaR-Bench/V-STaR) ![](https://img.shields.io/github/stars/V-STaR-Bench/V-STaR?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/V-STaR-Bench/V-STaR) | |2025-03 | - |
| Reasoning is All You Need for Video Generalization | [Paper](https://arxiv.org/abs/2503.10691) | - | - | 2025-03 | - |
| Towards Fine-Grained Video Question Answering | [Paper](https://arxiv.org/abs/2503.06820) | - | - | 2025-03 | - |
| SVBench | [Paper](https://arxiv.org/abs/2502.10810) | - | Streaming | 2025-02 | - |
| MMVU | [Paper](https://arxiv.org/abs/2501.12380) | [GitHub](https://github.com/yale-nlp/MMVU) ![](https://img.shields.io/github/stars/yale-nlp/MMVU?style=social)<br>[Hugging_Face](https://huggingface.co/datasets/yale-nlp/MMVU) | CoT-based|2025-01 | - |
| OVO-Bench | [Paper](https://arxiv.org/abs/2501.05510) | [GitHub](https://github.com/JoeLeelyf/OVO-Bench) ![](https://img.shields.io/github/stars/JoeLeelyf/OVO-Bench?style=social),[Hugging_Face](https://huggingface.co/datasets/JoeLeelyf/OVO-Bench) |Streaming| 2025-01 | - |
| HLV-1K | [Paper](https://arxiv.org/abs/2501.01645) | - | CoT-based  | 2025-01 | - |
| Thinking in Space | [Paper](https://arxiv.org/abs/2412.14171) | - | CoT-based  | 2024-12 | - |
| 3DSRBench | [Paper](https://arxiv.org/abs/2412.07825) | - | CoT-based  | 2024-12 | - |
| Black Swan | [Paper](https://arxiv.org/abs/2412.05725) | [GitHub](https://github.com/sahithyaravi/BlackSwan) ![](https://img.shields.io/github/stars/sahithyaravi/BlackSwan?style=social)<br>[Hugging_Face](https://huggingface.co/collections/UBC-ViL/black-swan-abductive-and-defeasible-reasoning-67de1a4ab7ddc22edf0b0542) | |2024-12 | [![](https://img.shields.io/badge/CVPR-2025-blue.svg?style=plastic)]() |
| TOMATO | [Paper](https://arxiv.org/abs/2410.23266) | - | CoT-based  | 2024-10 | - |
| OmniBench | [OmniBench: Towards the Future of Universal Omni-Language Models](http://arxiv.org/abs/2409.15272) |   | CoT-based | 2024-09 |  [![](https://img.shields.io/badge/arXiv-2409.15272-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.15272) |
| OmnixR    | [OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities](http://arxiv.org/abs/2410.12219) |  | CoT-based | 2024-10 |  [![](https://img.shields.io/badge/arXiv-2410.12219-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.12219) |
| TemporalBench | [Paper](https://arxiv.org/abs/2410.10818) | - | CoT-based  | 2024-10 | - |
| VideoVista | [VideoVista: A Versatile Benchmark for Video Understanding and Reasoning](https://arxiv.org/abs/2406.11303) |  | CoT-based | 2024-06 |  [![](https://img.shields.io/badge/arXiv-2406.11303-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2406.11303) |
| SOK-Bench | [SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge](https://arxiv.org/abs/2405.09713) |  | CoT-based | 2024-05 |  [![](https://img.shields.io/badge/arXiv-2405.09713-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2405.09713) |
| CVRR-ES | [How Good is my Video LMM? Complex Video Reasoning and Robustness Evaluation Suite for Video-LMMs](https://arxiv.org/abs/2405.03690) | | CoT-based | 2024-05 |  [![](https://img.shields.io/badge/arXiv-2405.03690-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2405.03690) |


## ✈ Related Survey

In addition, several recent and concurrent surveys have discussed multimodal or video reasoning. The works listed below offer complementary perspectives to ours, reflecting the field’s rapid and parallel development:
- [Awesome-Video-Reasoning](https://github.com/Video-Reason/Awesome-Video-Reasoning)
- [Awesome-Multimodal-Spatial-Reasoning](https://github.com/zhengxuJosh/Awesome-Multimodal-Spatial-Reasoning)
- [Awesome-Video-LMM-Post-Training](https://github.com/yunlong10/Awesome-Video-LMM-Post-Training)
- [Awesome-LLMs-for-Video-Understanding](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding)
- [Awesome-MCoT](https://github.com/yaotingwangofficial/Awesome-MCoT)


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
