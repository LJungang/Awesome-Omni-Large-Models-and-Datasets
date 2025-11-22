# Awesome-Video-Reasoning-Landscape [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- markdownlint-disable MD033 -->
## The Landscape of Video Reasoning: Tasks, Paradigms and Benchmarks— An Open-Source Survey

## Overview
This Awesome list systematically curates and tracks the latest research in Video Reasoning, spanning diverse modalities, tasks, and modeling paradigms. Instead of focusing on a single family of models, we break down the landscape from multiple complementary perspectives. Following the emerging taxonomy of the field, we highlight three major paradigms:

- 🗒️ CoT-based Video Reasoning

- 🕹️ CoF-based Video Reasoning

- 🌈 Interleaved Video Reasoning
  
This repository aims to provide a structured, up-to-date overview of these paradigms, serving as an open-source entry point for researchers exploring the evolving landscape of video reasoning.

## Table of Contents
- [Awesome-Video-Reasoning-Landscape](#awesome-video-reasoning-landscape-)
  - [😎Paradigms](#-paradigms)
    - [🗒️ CoT-based Video Reasoning](#️-cot-based-video-reasoning)
    - [🕹️ CoF-based Video Reasoning](#️-cof-based-video-reasoning)
    - [🌈 Interleaved Video Reasoning](#-interleaved-video-reasoning)
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
|-------|------|------------|----------|------|--------|
| [OMCAT: Omni Context Aware Transformer](https://arxiv.org/abs/2410.12109) | [OMCAT](https://om-cat.github.io.) ![](https://img.shields.io/github/stars/om-cat/om-cat.github.io?style=social) | unreleased | Text / Image / Audio / Video | 2024-10 | ![](https://img.shields.io/badge/arXiv-2410.12109-b31b1b.svg?style=plastic) |
| [Baichuan-Omni Technical Report](https://arxiv.org/abs/2410.08565) | [Baichuan-Omni](https://github.com/westlake-baichuan-mllm/bc-omni) ![](https://img.shields.io/github/stars/westlake-baichuan-mllm/bc-omni?style=social) | [Unreleased](https://github.com/westlake-baichuan-mllm/bc-omni) | Text / Image / Audio / Video | 2024-10 | ![](https://img.shields.io/badge/arXiv-2410.08565-b31b1b.svg?style=plastic) |
| [VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs](https://arxiv.org/abs/2406.07476) | [VideoLLaMA 2 / VideoLLaMA-2.1-AV](https://github.com/DAMO-NLP-SG/VideoLLaMA2) ![](https://img.shields.io/github/stars/DAMO-NLP-SG/VideoLLaMA2?style=social) | [Model Zoo](https://github.com/DAMO-NLP-SG/VideoLLaMA2#earth_americas-model-zoo) | Text / Image / Audio / Video | 2024-06 | ![](https://img.shields.io/badge/arXiv-2406.07476-b31b1b.svg?style=plastic) |
| [VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset](http://arxiv.org/abs/2305.18500) | [VAST](https://github.com/TXH-mercury/VAST) ![](https://img.shields.io/github/stars/TXH-mercury/VAST?style=social) | [Model Zoo](https://github.com/TXH-mercury/VAST#download--vast-models--and-captioners-for-labeling-your-own-data) | Text / Image / Audio / Video | 2023-05 | ![](https://img.shields.io/badge/NeurIPS-2023-blue.svg?style=plastic) |
| [VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset](https://arxiv.org/abs/2304.08345) | [VALOR](https://github.com/TXH-mercury/VALOR) ![](https://img.shields.io/github/stars/TXH-mercury/VALOR?style=social) | [Checkpoint](https://github.com/TXH-mercury/VALOR#download-checkpoints) | Text / Image / Audio / Video | 2023-04 | ![](https://img.shields.io/badge/arXiv-2304.08345-b31b1b.svg?style=plastic) |



### 🧙 CoF-based Video Reasoning

| **Title** | **Model & Code** | **Checkpoint**  | **Time** | **Venue** |
|-------|------|------------|----------|--------|
| - | - | - | xxxx-xx | - |


### 🌈 Interleaved Video Reasoning

| **Title** | **Model & Code** | **Code** | **Checkpoint** | **Time** | **Venue** |
|----------|----------|----------|----------------|----------|-----------|
| [VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation](https://arxiv.org/abs/2409.04429) | VILA-U | - | - | 2024-09 | ![arXiv](https://img.shields.io/badge/arXiv-2409.04429-b31b1b.svg?style=plastic) |




## ✨️Benchmarks


| **Name**      | **Paper** | **Dataset** | **Task** | **Time** |
|---------------|-----------|-------------|----------|----------|
| OmnixR    | [OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities](http://arxiv.org/abs/2410.12219) |  | CoT-based | 2024-10 |
| OmniBench | [OmniBench: Towards the Future of Universal Omni-Language Models](http://arxiv.org/abs/2409.15272) | OmniBench / OmniInstruct | CoT-based | 2024-09 |
| VALOR-32K | [VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset](https://arxiv.org/abs/2304.08345) | VALOR-32K | CoT-based | 2023-04 |

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
