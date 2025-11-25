# Awesome-Backdoor-on-LMMs [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Awesome-Backdoor-on-LMMs is a collection of state-of-the-art, novel, exciting backdoor methods on Large Multi-modal Models (LMMs). It contains papers, codes, datasets, evaluations, and analyses. Any additional things regarding backdoor, PRs, issues are welcome. Any problems, please contact wangzhongqi23s@ict.ac.cn. If you find this repository useful to your research or work, it is really appreciated to star this repository and cite our papers [here](#Reference). :sparkles:

## Reference

If you find this repository helpful for your research, we would greatly appreciate it if you could cite our papers. :sparkles:

```
@article{wang2025dynamicattentionanalysisbackdoor,
  title={Dynamic Attention Analysis for Backdoor Detection in Text-to-Image Diffusion Models}, 
  author={Zhongqi Wang and Jie Zhang and Shiguang Shan and Xilin Chen},
  journal={arXiv preprint arXiv:2504.20518},
  year={2025},
}

@article{zhang2025twt,
  title={Trigger without Trace: Towards Stealthy Backdoor Attack on Text-to-Image Diffusion Models}, 
  author={Jie Zhang and Zhongqi Wang and Shiguang Shan and Xilin Chen},
  journal={arXiv preprint arXiv:2503.17724},
  year={2025},
}

@InProceedings{10.1007/978-3-031-73013-9_7,
  author="Wang, Zhongqi
  and Zhang, Jie
  and Shan, Shiguang
  and Chen, Xilin",
  title="T2IShield: Defending Against Backdoors on Text-to-Image Diffusion Models",
  booktitle="Computer Vision -- ECCV 2024",
  year="2025",
  publisher="Springer Nature Switzerland",
  address="Cham",
  pages="107--124",
  isbn="978-3-031-73013-9"
}
```

## Bookmarks

- [Vision-Language Pretraining Models (VLPs)](#Vision-Language Pretraining Models (VLPs))
- 

## Papers

### Vision Language Pretrained Models (VLPs)

#### Backdoor Attack

| Time | Title | Venue |  Paper   |   Code   |
| ----------- | ----- | :---: | :------: | :------: |
| 2021.07     |   BadEncoder: Backdoor Attacks to Pre-trained  Encoders in Self-Supervised Learning    |    IEEE'22   | [link](https://ieeexplore.ieee.org/document/9833644) | [code](https://github.com/jinyuan-jia/BadEncoder) |
|  2021.06    | POISONING AND BACKDOORING CONTRASTIVE LEARNING  |  Arxiv     | [link](https://arxiv.org/abs/2106.09667v2) | - |
|  2024.08   |   BAPLe: Backdoor Attacks on Medical  Foundational Models using Prompt Learning    |   MICCAI'24    | [link](https://papers.miccai.org/miccai-2024/094-Paper3117.html) | [code](https://github.com/asif-hanif/baple) |
|  2022.09  |    Data Poisoning Attacks Against Multimodal Encoders   | ICML'23     | [link](https://proceedings.mlr.press/v202/yang23f.html) | [code](https://github.com/zqypku/mm_poison/) |
| 2023.10     |    GhostEncoder: Stealthy backdoor attacks with dynamic triggers to pre-trained encoders in self-supervised learning   |  CS'24     | [link](https://www.sciencedirect.com/science/article/abs/pii/S0167404824001561) | - |
| 2023.11     |   BadCLIP: Dual-Embedding Guided Backdoor Attack on  Multimodal Contrastive Learning    | CVPR'24      | [link](https://openaccess.thecvf.com/content/CVPR2024/html/Liang_BadCLIP_Dual-Embedding_Guided_Backdoor_Attack_on_Multimodal_Contrastive_Learning_CVPR_2024_paper.html) | [code](https://github.com/LiangSiyuan21/BadCLIP) |
|  2025.03   | MP-Nav: Enhancing Data Poisoning Attacks against Multimodal Learning      |  ICML'25     | [link](https://openreview.net/forum?id=zy7VeNtSLM) | - |
| 2025.03     |   Backdooring CLIP through Concept Confusion    |    Arxiv   |[link](https://arxiv.org/abs/2503.09095)  | - |
| 2024.05     |  Distribution Preserving Backdoor Attack in Self-supervised Learning     |  SSP'24     |[link](https://ieeexplore.ieee.org/abstract/document/10646825) |-|
#### Backdoor Defense

| Time | Title | Venue |  Paper   |   Code   |
| ---- | ----- | :---: | :------: | :------: |
|  2023.03    |   CleanCLIP: Mitigating Data Poisoning Attacks in  Multimodal Contrastive Learning    |   ICCV'23    | [link](https://openaccess.thecvf.com/content/ICCV2023/html/Bansal_CleanCLIP_Mitigating_Data_Poisoning_Attacks_in_Multimodal_Contrastive_Learning_ICCV_2023_paper.html) | [code](https://github.com/nishadsinghi/CleanCLIP) |
| 2023.03     |   Robust Contrastive Language-Image Pre-training against Data Poisoning and Backdoor Attacks    |   NeurIPS'23     | [link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/2232e8fee69b150005ac420bfa83d705-Abstract-Conference.html) | - |
| 2023.03    |  Detecting Backdoors in Pre-trained Encoders  |  CVPR'23    | [link](https://openaccess.thecvf.com/content/CVPR2023/html/Feng_Detecting_Backdoors_in_Pre-Trained_Encoders_CVPR_2023_paper.html) | [code](https://github.com/GiantSeaweed/DECREE) |
| 2023.10   |  Better Safe than Sorry: Pre-training CLIP against Targeted Data Poisoning and Backdoor Attacks   | ICML'24   | [link](https://arxiv.org/abs/2310.05862) | [code](https://github.com/BigML-CS-UCLA/SafeCLIP)|
 | 2024.03    | Unlearning Backdoor Threats: Enhancing Backdoor Defense in Multimodal Contrastive Learning via Local Token Unlearning      |   Arxiv    | [link](https://arxiv.org/abs/2403.16257) | - |
| 2024.09     | Adversarial Backdoor Defense in CLIP      |  Arxiv     | [link](https://arxiv.org/abs/2409.15968) | - |
| 2024.09     | CleanerCLIP: Fine-grained Counterfactual Semantic Augmentation for Backdoor| Arxiv | [link](https://arxiv.org/abs/2409.17601) | - |
|2024.11     |Semantic Shield: Defending Vision-Language Models Against Backdooring and Poisoning via Fine-grained Knowledge Alignment| CVPR'24| [link](https://openaccess.thecvf.com/content/CVPR2024/html/Ishmam_Semantic_Shield_Defending_Vision-Language_Models_Against_Backdooring_and_Poisoning_via_CVPR_2024_paper.html) | [code](https://github.com/IshmamAlvi/Semantic-Shield) |
|2024.12     |Defending Multimodal Backdoored Models by Repulsive Visual Prompt Tuning| Arxiv| [link](https://arxiv.org/abs/2412.20392)| - |
|2024.12     | DETECTING BACKDOOR SAMPLES IN CONTRASTIVE LANGUAGE IMAGE PRETRAINING| ICLR'25|[link](https://iclr.cc/virtual/2025/poster/30032) | [code](https://github.com/HanxunH/Detect-CLIP-Backdoor-Samples) |

 Defense in Contrastive Learning
### Text Conditioned Diffusion Models (TDMs)

#### Backdoor Attack

| Time | Title | Venue |  Paper   |   Code   |
| ---- | ----- | :---: | :------: | :------: |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |

#### Backdoor Defense

| Time | Title | Venue |  Paper   |   Code   |
| ---- | ----- | :---: | :------: | :------: |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |
|      |       |       | [link]() | [code]() |

### Large Vision Language Models (LVLMs)

#### Backdoor Attack

| Time    | Title                                                        |   Venue    |                            Paper                             |                           Code                           |
| ------- | ------------------------------------------------------------ | :--------: | :----------------------------------------------------------: | :------------------------------------------------------: |
| 2024.02 | **Shadowcast: Stealthy Data Poisoning Attacks against Vision-Language Models** | NeurIPS'24 |      [link](https://openreview.net/forum?id=JhqyeppMiD)      |          [code](https://vlm-poison.github.io/)           |
| 2024.02 | **VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models** |  IJCV'25   | [link](https://link.springer.com/article/10.1007/s11263-025-02368-9) |     [code](https://github.com/JWLiang007/VL-Trojan)      |
| 2024.02 | ***Test-Time* BACKDOOR ATTACKS ON MULTIMODAL LARGE LANGUAGE MODELS** |   Arxiv    |          [link](https://github.com/sail-sg/AnyDoor)          |        [code](https://github.com/sail-sg/AnyDoor)        |
| 2024.03 | **ImgTrojan: Jailbreaking Vision-Language Models with ONE Image** |  NAACL'25  |    [link](https://aclanthology.org/2025.naacl-long.360/)     |      [code](https://github.com/xijia-tao/ImgTrojan)      |
| 2024.03 | **TrojVLM: Backdoor Attack Against Vision Language Models**  |  ECCV'24   | [link](https://link.springer.com/chapter/10.1007/978-3-031-73650-6_27) |                            -                             |
| 2024.04 | **PHYSICAL BACKDOOR ATTACK CAN JEOPARDIZE DRIVING WITH VISION-LARGE-LANGUAGE MODELS** |  ICMLW'24  |          [link](https://icml.cc/virtual/2024/38112)          |                            -                             |
| 2024.06 | **Revisiting Backdoor Attacks against Large Vision-Language Models from Domain Shift** |  CVPR'25   | [link](https://www.computer.org/csdl/proceedings-article/cvpr/2025/436400j477/2999SblAZlC) |      [code](https://github.com/LiangSiyuan21/MABA)       |
| 2024.10 | **BACKDOORING VISION-LANGUAGE MODELS WITH OUT-OF-DISTRIBUTION DATA** |  ICLR'25   |      [link](https://openreview.net/forum?id=tZozeR3VV7)      |                            -                             |
| 2025.02 | **Stealthy Backdoor Attack in Self-Supervised Learning Vision Encoders for Large Vision Language Models** |  CVPR'25   |    [link](https://ieeexplore.ieee.org/document/11092582)     |       [code](https://github.com/6zHAOyi/BadVision)       |
| 2025.03 | **BadToken: Token-level Backdoor Attacks to Multi-modal Large Language Models** |  CVPR'25   | [link](https://www.computer.org/csdl/proceedings-article/cvpr/2025/436400ae927/299buyfnYBy) |                            -                             |
| 2025.05 | **Natural Reflection Backdoor Attack on Vision Language Model for Autonomous Driving** |   Arxiv    |           [link](https://arxiv.org/abs/2505.06413)           |                            -                             |
| 2025.06 | **Backdoor Attack on Vision Language Models with Stealthy Semantic Manipulation** |   Arxiv    |           [link](https://arxiv.org/abs/2506.07214)           |                                                          |
| 2025.07 | **Shadow-Activated Backdoor Attacks on Multimodal Large Language Models** |   ACL'25   |   [link](https://aclanthology.org/2025.findings-acl.248/)    |      [code](https://github.com/ericyinyzy/BadMLLM)       |
| 2025.08 | **IAG: Input-aware Backdoor Attack on VLMs for Visual Grounding** |   Arxiv    |           [link](https://arxiv.org/abs/2508.09456)           |                            -                             |
| 2025.09 | **TokenSwap: Backdoor Attack on the Compositional Understanding of Large Vision-Language Models** |   Arxiv    |           [link](https://arxiv.org/abs/2509.24566)           | [code](https://anonymous.4open.science/r/tokenswap-341F) |


#### Backdoor Defense

| Time    | Title                                                        |   Venue    |                       Paper                        |                    Code                    |
| ------- | ------------------------------------------------------------ | :--------: | :------------------------------------------------: | :----------------------------------------: |
| 2025.05 | **Backdoor Cleaning without External Guidance in MLLM Fine-tuning** | NeurIPS‘25 | [link](https://openreview.net/forum?id=os4QYDf3Ms) | [code](https://github.com/XuankunRong/BYE) |
| 2025.06 | **ROBUST ANTI-BACKDOOR INSTRUCTION TUNING IN LVLMS**         |   Arxiv    |      [link](https://arxiv.org/abs/2506.05401)      |                     -                      |
| 2025.06 | **SRD: Reinforcement-Learned Semantic Perturbation**         |  AAAI'26   |    [link](https://www.arxiv.org/abs/2506.04743)    |   [code](https://github.com/Ciconey/SRD)   |

### VLM-based Embodied AI

#### Backdoor Attack

| Time    | Title                                                        |  Venue   |                            Paper                             |                        Code                         |
| ------- | ------------------------------------------------------------ | :------: | :----------------------------------------------------------: | :-------------------------------------------------: |
| 2025.05 | **BadVLA: Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization** |  Arxiv   |           [link](https://arxiv.org/abs/2505.16640)           |     [code](https://github.com/Zxy-MLlab/BadVLA)     |
| 2025.10 | **TabVLA: Targeted Backdoor Attacks on Vision-Language-Action Models** |  Arxiv   |           [link](https://arxiv.org/abs/2510.10932)           |   [code](https://github.com/megaknight114/TabVLA)   |
| 2025.11 | **AttackVLA: Benchmarking Adversarial and Backdoor Attacks on Vision-Language-Action Models** |  Arxiv   |           [link](https://arxiv.org/abs/2511.12149)           |                          -                          |
| 2025.05 | **Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents** | EMNLP’25 |  [link](https://aclanthology.org/2025.findings-emnlp.411/)   |  [code](https://github.com/CTZhou-byte/AgentGhost)  |
| 2025.06 | **Poison Once, Control Anywhere: Clean-Text Visual Backdoors in VLM-based Mobile Agents** |  Arxiv   |           [link](https://arxiv.org/abs/2506.13205)           |                          -                          |
| 2025.07 | **VisualTrap: A Stealthy Backdoor Attack on GUI Agents via Visual Grounding Manipulation** | COLM‘25  | [link](https://openreview.net/forum?id=7HPuAkgdVm#discussion) |    [code](https://github.com/whi497/VisualTrap)     |
| 2025.09 | **Realistic Environmental Injection Attacks on GUI Agents**  |  Arxiv   |           [link](https://arxiv.org/abs/2509.11250)           | [code](https://github.com/zhangyitonggg/attack2gui) |



## Other Related Awesome Repository

- [Awesome Data Poisoning and Backdoor Attacks](https://github.com/penghui-yang/awesome-data-poisoning-and-backdoor-attacks)
- [Awesome-Backdoor-in-Deep-Learning](https://github.com/zihao-ai/Awesome-Backdoor-in-Deep-Learning)
- [Backdoor Learning Resources](https://github.com/THUYimingLi/backdoor-learning-resources)
- [Awesome-LVLM-Attack](https://github.com/liudaizong/Awesome-LVLM-Attack/tree/main)
- [Awesome-Large-Model-Safety](https://github.com/xingjunm/Awesome-Large-Model-Safety)
