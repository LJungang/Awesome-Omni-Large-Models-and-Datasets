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

 *The last four columns represent the input modalities supported by the model.

| Title                                                                                                                                                                                                             |                                                                                               Model                                                                                               |                                                                                    Checkpoint                                                                                    |   Text   |  Image  |  Audio  |  Video  |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------: | :------: | :------: | :------: |
| **OMCAT: Omni Context Aware Transformer** [![arXiv](https://img.shields.io/badge/arXiv-2410.12109-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.12109)                                                   |                           **OMCAT** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://om-cat.github.io.)                           |                                                                                    unreleased                                                                                    | &#10003; | &#10003; | &#10003; | &#10003; |
| **Baichuan-Omni Technical Report** [![arXiv](https://img.shields.io/badge/arXiv-2410.08565-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.08565)                                                          |           **Baichuan-Omni** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/westlake-baichuan-mllm/bc-omni)           |                             [![hf_checkpoint](https://img.shields.io/badge/🤗-Unreleased-9C276A.svg)](https://github.com/westlake-baichuan-mllm/bc-omni)                             | &#10003; | &#10003; | &#10003; | &#10003; |
| **VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs** [![arXiv](https://img.shields.io/badge/arXiv-2406.07476-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2406.07476) | **VideoLLaMA 2** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/DAMO-NLP-SG/VideoLLaMA2) |                 [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/DAMO-NLP-SG/VideoLLaMA2#earth_americas-model-zoo)                 | &#10003; | &#10003; | &#10003; | &#10003; |
| **GroundingGPT:Language Enhanced Multi-modal Grounding Model** [![arXiv](https://img.shields.io/badge/ACL-2024-blue.svg?style=plastic)](https://arxiv.org/abs/2401.06071)                        |                 **GroundingGPT** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/lzw-lzw/GroundingGPT)                 | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/TXH-mercury/VAST#download--vast-models--and-captioners-for-labeling-your-own-data) | &#10003; | &#10003; | &#10003; | &#10003; |
| **VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset** [![NeurIPS](https://img.shields.io/badge/NeurIPS-2023-blue.svg?style=plastic)](http://arxiv.org/abs/2305.18500)                |                       **VAST** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/TXH-mercury/VAST)                       | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/TXH-mercury/VAST#download--vast-models--and-captioners-for-labeling-your-own-data) | &#10003; | &#10003; | &#10003; | &#10003; |
| **VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset**[![arXiv](https://img.shields.io/badge/arXiv-2304.08345-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2304.08345) | **VALOR**[![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/TXH-mercury/VALOR) | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/TXH-mercury/VALOR#download-checkpoints) | &#10003; | &#10003; | &#10003; | &#10003; |

### 🧙 CoF-based Video Reasoning

 *The last four columns represent the output modalities supported by the model.

| Title | Model | Checkpoint | Text | Image | Audio | Video |
| :---- | :---: | :--------: | :--: | :---: | :---: | :---: |
| -     |   -   |     -     |  -  |   -   |   -   |   -   |

### 🌈 Interleaved Video Reasoning

 *The last four columns represent the input & output modalities supported by the model.

| Title                                                                                                                                                                                                                                         |                                                                                                  Model                                                                                                  |                                                                                                                                                                                                                                                                                                                                                         Checkpoint                                                                                                                                                                                                                                                                                                                                                         |   Text   |  Image  |  Audio  |  Video  |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------: | :------: | :------: | :------: |
| **Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation** [![arXiv](https://img.shields.io/badge/arXiv-2410.13848-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.13848)                               |                           **Janus** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/deepseek-ai/Janus)                           |                                                                                                                                                                                                                                                                                                   [![hf_checkpoint](https://img.shields.io/badge/🤗-Janus--1.3B-9C276A.svg)](https://huggingface.co/deepseek-ai/Janus-1.3B)                                                                                                                                                                                                                                                                                                   | &#10003; | &#10003; | &#10007; | &#10007; |
| **Emu3: Next-Token Prediction is All You Need** [![arXiv](https://img.shields.io/badge/arXiv-2409.18869-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.18869)                                                                         |                          **emu3** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/baaivision/Emu3)                          | [![hf_checkpoint](https://img.shields.io/badge/🤗-Emu3--Chat-9C276A.svg)](https://huggingface.co/BAAI/Emu3-Chat)[![ms_checkpoint](https://img.shields.io/badge/🤖-Emu3--Chat-8A2BE2.svg)](https://huggingface.co/BAAI/Emu3-Chat)<br>[![hf_checkpoint](https://img.shields.io/badge/🤗-Emu3--Gen-9C276A.svg)](https://huggingface.co/BAAI/Emu3-Gen)[![ms_checkpoint](https://img.shields.io/badge/🤖-Emu3--Gen-8A2BE2.svg)](https://huggingface.co/BAAI/Emu3-Gen)<br>[![hf_checkpoint](https://img.shields.io/badge/🤗-Emu3--VisionTokenizer-9C276A.svg)](https://huggingface.co/BAAI/Emu3-VisionTokenizer)[![ms_checkpoint](https://img.shields.io/badge/🤖-Emu3--VisionTokenizer-8A2BE2.svg)](https://huggingface.co/BAAI/Emu3-VisionTokenizer) | &#10003; | &#10003; | &#10003; | &#10007; |
| **VILA-U: a Unified Foundation Model Integrating Visual Understanding and Generation** [![arXiv](https://img.shields.io/badge/arXiv-2409.04429-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.04429) | Unreleased | Unreleased | &#10003; | &#10003; | &#10007; | &#10003; |
| **Show-o: One Single Transformer to Unify Multimodal Understanding and Generation** [![arXiv](https://img.shields.io/badge/arXiv-2408.12528-b31b1b.svg?style=plastic)]([https://arxiv.org/abs/2408.12528](https://arxiv.org/abs/2408.12528)) |                          **Show-o** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/showlab/Show-o)                          |                                                                                                                                                                                                                                                                                             [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/showlab/Show-o#hugging-face-models)                                                                                                                                                                                                                                                                                             | &#10003; | &#10003; | &#10007; | &#10007; |
| **Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model** [![arXiv](https://img.shields.io/badge/arXiv-2408.11039-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2408.11039)                                   | **Transfusion** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)]((https://github.com/lucidrains/transfusion-pytorch)) |                                                                                                                                                                                                                                                                                                                                                         unreleased                                                                                                                                                                                                                                                                                                                                                         | &#10003; | &#10003; | &#10007; | &#10007; |
| **VITRON: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing**[![nips-2024](https://img.shields.io/badge/NeurIPS-2024-blue.svg?style=plastic)](https://is.gd/aGu0VV) | **VITRON** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/SkyworkAI/Vitron) | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/SkyworkAI/Vitron/blob/main/checkpoints/README.md#checkpoints-preparation) | &#10003; | &#10003; | &#10003; | &#10007; |


## ✨️Benchmarks


| **Name**      | **Paper** | **Dataset** | **Task** | **Time** |
|---------------|-----------|-------------|----------|----------|
| **OmnixR**    | [**OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities**](http://arxiv.org/abs/2410.12219) |  | CoT-based | 2024-10 |
| **OmniBench** | [**OmniBench: Towards the Future of Universal Omni-Language Models**](http://arxiv.org/abs/2409.15272) | OmniBench / OmniInstruct | CoT-based | 2024-09 |
| **VALOR-32K** | [**VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset**](https://arxiv.org/abs/2304.08345) | VALOR-32K | CoT-based | 2023-04 |

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
