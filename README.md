# Awesome-Omni-Large-Models-and-Datasets[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- markdownlint-disable MD033 -->

🔥 Omni large models and datasets for understanding and generating multi-modalities.

- [Awesome-Omni-Large-Models-and-Datasets](#awesome-omni-large-models-and-datasets)
  - [😎Models](#models)
    - [🗒️ Taxonomy](#️-taxonomy)
    - [🕹️ Modality Understanding](#️-modality-understanding)
    - [🧙 Modality Generation](#-modality-generation)
    - [🌈 Unified Model for Understanding and Generating Modalities](#-unified-model-for-understanding-and-generating-modalities)
  - [✨️Datasets](#️datasets)
    - [Pretraining Dataset](#pretraining-dataset)
    - [Training Dataset](#training-dataset)
    - [Benchmark](#benchmark)
  - [🌟 Star History](#-star-history)
  - [♥️ Contributors](#️-contributors)

`<small><i>``<a href='http://ecotrust-canada.github.io/markdown-toc/'>`Table of contents generated with markdown-toc`</a></i>``</small>`

## 😎Models

### 🗒️ Taxonomy

<!-- arxiv: [![arXiv](https://img.shields.io/badge/arXiv-2406.09272-b31b1b.svg?style=plastic)]()
  -->

### 🕹️ Modality Understanding

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
| **VITA: Towards Open-Source Interactive Omni Multimodal LLM** [![arXiv](https://img.shields.io/badge/arXiv-2408.05211-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2408.05211)                               |                        **VITA** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/VITA-MLLM/VITA)                        |                                                                                    unreleased                                                                                    | &#10003; | &#10007; | &#10003; | &#10007; |
| **VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs** [![arXiv](https://img.shields.io/badge/arXiv-2406.07476-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2406.07476) | **VideoLLaMA 2** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)]([https://om-cat.github.io.](https://github.com/DAMO-NLP-SG/VideoLLaMA2)) |                 [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/DAMO-NLP-SG/VideoLLaMA2#earth_americas-model-zoo)                 | &#10003; | &#10003; | &#10003; | &#10003; |
| **GroundingGPT:Language Enhanced Multi-modal Grounding Model** [![arXiv](https://img.shields.io/badge/ACL-2024-blue.svg?style=plastic)](https://arxiv.org/abs/2401.06071)                        |                 **GroundingGPT** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/lzw-lzw/GroundingGPT)                 | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/TXH-mercury/VAST#download--vast-models--and-captioners-for-labeling-your-own-data) | &#10003; | &#10003; | &#10003; | &#10003; |
| **VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset** [![NeurIPS](https://img.shields.io/badge/NeurIPS-2023-blue.svg?style=plastic)](http://arxiv.org/abs/2305.18500)                |                       **VAST** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/TXH-mercury/VAST)                       | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/TXH-mercury/VAST#download--vast-models--and-captioners-for-labeling-your-own-data) | &#10003; | &#10003; | &#10003; | &#10003; |
| **VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset**[![arXiv](https://img.shields.io/badge/arXiv-2304.08345-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2304.08345) | **VALOR**[![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)]([https://github.com/TXH-mercury/VALOR) | [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/TXH-mercury/VALOR#download-checkpoints) | &#10003; | &#10003; | &#10003; | &#10003; |

### 🧙 Modality Generation

 *The last four columns represent the output modalities supported by the model.

| Title | Model | Checkpoint | Text | Image | Audio | Video |
| :---- | :---: | :--------: | :--: | :---: | :---: | :---: |
| -     |   -   |     -     |  -  |   -   |   -   |   -   |

### 🌈 Unified Model for Understanding and Generating Modalities

 *The last four columns represent the input & output modalities supported by the model.

| Title                                                                                                                                                                                                                                         |                                                                                                  Model                                                                                                  |                                                                                                                                                                                                                                                                                                                                                         Checkpoint                                                                                                                                                                                                                                                                                                                                                         |   Text   |  Image  |  Audio  |  Video  |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------: | :------: | :------: | :------: |
| **Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation** [![arXiv](https://img.shields.io/badge/arXiv-2410.13848-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.13848)                               |                           **Janus** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/kaistAI/Janus)                           |                                                                                                                                                                                                                                                                                                   [![hf_checkpoint](https://img.shields.io/badge/🤗-Janus--7B-9C276A.svg)](https://github.com/westlake-baichuan-mllm/bc-omni)                                                                                                                                                                                                                                                                                                   | &#10003; | &#10003; | &#10007; | &#10007; |
| **Emu3: Next-Token Prediction is All You Need** [![arXiv](https://img.shields.io/badge/arXiv-2409.18869-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2409.18869)                                                                         |                          **emu3** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/baaivision/Emu3)                          | [![hf_checkpoint](https://img.shields.io/badge/🤗-Emu3--Chat-9C276A.svg)](https://huggingface.co/BAAI/Emu3-Chat)[![ms_checkpoint](https://img.shields.io/badge/🤖-Emu3--Chat-8A2BE2.svg)](https://huggingface.co/BAAI/Emu3-Chat)`<br>`[![hf_checkpoint](https://img.shields.io/badge/🤗-Emu3--Gen-9C276A.svg)](https://huggingface.co/BAAI/Emu3-Gen)[![ms_checkpoint](https://img.shields.io/badge/🤖-Emu3--Gen-8A2BE2.svg)](https://huggingface.co/BAAI/Emu3-Gen)`<br>`[![hf_checkpoint](https://img.shields.io/badge/🤗-Emu3--VisionTokenizer-9C276A.svg)](https://huggingface.co/BAAI/Emu3-VisionTokenizer)[![ms_checkpoint](https://img.shields.io/badge/🤖-Emu3--VisionTokenizer-8A2BE2.svg)](https://huggingface.co/BAAI/Emu3-VisionTokenizer) | &#10003; | &#10003; | &#10003; | &#10007; |
| **Show-o: One Single Transformer to Unify Multimodal Understanding and Generation** [![arXiv](https://img.shields.io/badge/arXiv-2408.12528-b31b1b.svg?style=plastic)]([https://arxiv.org/abs/2408.12528](https://arxiv.org/abs/2408.12528)) |                          **Show-o** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/showlab/Show-o)                          |                                                                                                                                                                                                                                                                                             [![github_model_zoos](https://img.shields.io/badge/ModelZoo-black?logo=github)](https://github.com/showlab/Show-o#hugging-face-models)                                                                                                                                                                                                                                                                                             | &#10003; | &#10003; | &#10007; | &#10007; |
| **Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model** [![arXiv](https://img.shields.io/badge/arXiv-2408.11039-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2408.11039)                                   | **Transfusion** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)]([https://om-cat.github.io.](https://github.com/lucidrains/transfusion-pytorch)) |                                                                                                                                                                                                                                                                                                                                                         unreleased                                                                                                                                                                                                                                                                                                                                                         | &#10003; | &#10003; | &#10007; | &#10007; |

## ✨️Datasets

### Pretraining Dataset

### Training Dataset

<!-- 模版：
|**[数据集名字]**|链接|✗|✗|✓|描述|
 -->

| Dataset Name       |                                                                          Paper                                                                          |                                                                          Link                                                                          | Audio-Image-Text | Speech-Video-Text | Audio-Video-Text |                                                                            Detail                                                                            |
| :----------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------: | :---------------: | :--------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **OCTAV** |                                                          **OMCAT: Omni Context Aware Transformer** [![arXiv](https://img.shields.io/badge/arXiv-2410.12109-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2410.12109)                                                          |                                                          [unreleased](https://om-cat.github.io.)                                                          |     &#10007;     |     &#10007;     |     &#10003;     | **OCTAV-ST** has**127,507** unique videos with single QA pairs;`<br>`**OCTAV-MT** **25,457** unique videos with a total of **180,916** QA pairs. |
| **VAST-27M** | **VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset** [![NeurIPS](https://img.shields.io/badge/NeurIPS-2023-blue.svg?style=plastic)](http://arxiv.org/abs/2305.18500) | **VAST** [![project_repo](https://img.shields.io/badge/Github-181717?style=plastic&logo=github&logoColor=white)](https://github.com/TXH-mercury/VAST) |     &#10007;     |     &#10007;     |     &#10003;     |                                                     **27M** Clips;`<br>`**297M** Captions.                                                     |

### Benchmark

| Name          | Paper                                                        | Link                                                         | SI:Text  | SI:Image | SI:Audio | SI:Video | SO:Text  | Detail                                                       |
| ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | -------- | -------- | -------- | -------- | ------------------------------------------------------------ |
| **OmnixR**    | **OmnixR: Evaluating Omni-modality Language Models on Reasoning across Modalities** [![arXiv](https://img.shields.io/badge/arXiv-2410.12219-b31b1b.svg?style=plastic)](http://arxiv.org/abs/2410.12219) | Unreleased                                                   | &#10003; | &#10003; | &#10003; | &#10003; | &#10003; | **Omni$` \times`$R$`_\text{synth} `$**:100videos<br>**Omni$` \times`$R$`_\text{real} `$**:100videos |
| **OmniBench** | **OmniBench: Towards The Future of Universal Omni-Language Models**[![arXiv](https://img.shields.io/badge/arXiv-2409.15272-b31b1b.svg?style=plastic)](http://arxiv.org/abs/2409.15272) | [![hf_checkpoint](https://img.shields.io/badge/🤗-OmniBench-9C276A.svg)](https://huggingface.co/datasets/m-a-p/OmniBench)<br>[![hf_checkpoint](https://img.shields.io/badge/🤗-OmniInstruct--v1-9C276A.svg)](https://huggingface.co/datasets/m-a-p/OmniInstruct_v1) | &#10003; | &#10003; | &#10003; | &#10007; | &#10007; |                                                              |

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=LJungang/Awesome-Omni-Large-Models-and-Datasets&type=Date)](https://star-history.com/#LJungang/Awesome-Omni-Large-Models-and-Datasets&Date)

## ♥️ Contributors

<!--
<a href="https://github.com/LJungang/Awesome-Omni-Large-Models-and-Datasets/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LJungang/Awesome-Omni-Large-Models-and-Datasets" />
</a>
 -->

<a href="https://github.comLJungang/Awesome-Omni-Large-Models-and-Datasets/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LJungang/Awesome-Omni-Large-Models-and-Datasets" alt="Contributors for Awesome Omni Large Models and Datasets"/>
</a>

<!-- markdownlint-enable MD033 -->
