<h1 align="center">🤗🤗🤗 Awesome-Backdoor-on-LMMs 🤗🤗🤗</h1>

<p align="center"><em>Curated list of backdoor attacks and defenses on Large Multimodal Models (LMMs), aligned with our work:</em><br><strong>Backdoor Attacks and Defenses on Large
Multimodal Models: A Survey</strong></p>

<p align="center">
    <!-- <a href="https://arxiv.org/abs/2502.14881"><img src="https://img.shields.io/badge/arXiv-2502.14881-b31b1b.svg" alt="arXiv Badge"></a> -->
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome Badge"></a>
    <img src="https://visitor-badge.laobi.icu/badge?page_id=robin-wzq.awesome-backdoor-on-lmms" alt="visitors"/>
    <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg" alt="License Badge"></a>
    <a href="https://github.com/Robin-WZQ/Awesome-Backdoor-on-LMMs"><img src="https://img.shields.io/github/stars/Robin-WZQ/Awesome-Backdoor-on-LMMs?style=social" alt="GitHub stars"></a>
</p>


Awesome-Backdoor-on-LMMs is a collection of state-of-the-art, novel, exciting backdoor methods on Large Multi-modal Models (LMMs). It contains papers, codes, datasets, evaluations, and analyses. Any additional things regarding backdoor, PRs, issues are welcome. Any problems, please contact wangzhongqi23s@ict.ac.cn. If you find this repository useful to your research or work, it is really appreciated to star this repository and cite our papers [here](#Reference). :sparkles:

## Reference

If you find this repository helpful for your research, we would greatly appreciate it if you could cite our papers. :sparkles:

```
@article{wang2025amdet,
  title={Assimilation Matters: Model-level Backdoor Detection in Vision-Language Pretrained Models}, 
  author={Zhongqi Wang and Jie Zhang and Shiguang Shan and Xilin Chen},
  journal={arXiv preprint arXiv:2512.00343},
  year={2025},
}

@article{wang2025dynamicattentionanalysisbackdoor,
  title={Dynamic Attention Analysis for Backdoor Detection in Text-to-Image Diffusion Models}, 
  author={Zhongqi Wang and Jie Zhang and Shiguang Shan and Xilin Chen},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)},
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

## 📜 Table of Contents

- [Vision Language Pretrained Models (VLPs)](#Vision-Language-Pretrained-Models)
- [Text Conditioned Diffusion Models (TDMs)](#Text-Conditioned-Diffusion-Models)
- [Large Vision Language Models (LVLMs)](#Large-Vision-Language-Models)
- [VLM-based Embodied AI](#VLM-based-Embodied-AI)

## 👑 Awesome Papers

### Vision Language Pretrained Models

#### Backdoor Attack

| Time | Title | Venue |  Paper   |   Code   |
| ----------- | ----- | :---: | :------: | :------: |
|  2021.06    | POISONING AND BACKDOORING CONTRASTIVE LEARNING  |  arXiv     | [link](https://arxiv.org/abs/2106.09667v2) | - |
| 2021.07     |   BadEncoder: Backdoor Attacks to Pre-trained  Encoders in Self-Supervised Learning    |    SSP'22   | [link](https://ieeexplore.ieee.org/document/9833644) | [code](https://github.com/jinyuan-jia/BadEncoder) |
|  2022.09  |    Data Poisoning Attacks Against Multimodal Encoders   | ICML'23     | [link](https://proceedings.mlr.press/v202/yang23f.html) | [code](https://github.com/zqypku/mm_poison/) |
| 2023.10     |    GhostEncoder: Stealthy backdoor attacks with dynamic triggers to pre-trained encoders in self-supervised learning   |  CS'24     | [link](https://www.sciencedirect.com/science/article/abs/pii/S0167404824001561) | - |
| 2023.11     |   BadCLIP: Dual-Embedding Guided Backdoor Attack on  Multimodal Contrastive Learning    | CVPR'24      | [link](https://openaccess.thecvf.com/content/CVPR2024/html/Liang_BadCLIP_Dual-Embedding_Guided_Backdoor_Attack_on_Multimodal_Contrastive_Learning_CVPR_2024_paper.html) | [code](https://github.com/LiangSiyuan21/BadCLIP) |
| 2024.05     |  Distribution Preserving Backdoor Attack in Self-supervised Learning     |  SSP'24     |[link](https://ieeexplore.ieee.org/abstract/document/10646825) |-|
|  2024.08   |   BAPLe: Backdoor Attacks on Medical  Foundational Models using Prompt Learning    |   MICCAI'24    | [link](https://papers.miccai.org/miccai-2024/094-Paper3117.html) | [code](https://github.com/asif-hanif/baple) |
|  2025.03   | MP-Nav: Enhancing Data Poisoning Attacks against Multimodal Learning      |  ICML'25     | [link](https://openreview.net/forum?id=zy7VeNtSLM) | - |
| 2025.03     |   Backdooring CLIP through Concept Confusion    |    arXiv   |[link](https://arxiv.org/abs/2503.09095)  | - |

#### Backdoor Defense

| Time | Title | Venue |  Paper   |   Code   |
| ---- | ----- | :---: | :------: | :------: |
|  2023.02    |ASSET: Robust Backdoor Data Detection Across a Multiplicity of Deep Learning Paradigms |USENIX'23| [link](https://www.usenix.org/conference/usenixsecurity23/presentation/pan) | [code](https://github.com/ruoxi-jia-group/ASSET) |
|  2023.03    |   CleanCLIP: Mitigating Data Poisoning Attacks in  Multimodal Contrastive Learning    |   ICCV'23    | [link](https://openaccess.thecvf.com/content/ICCV2023/html/Bansal_CleanCLIP_Mitigating_Data_Poisoning_Attacks_in_Multimodal_Contrastive_Learning_ICCV_2023_paper.html) | [code](https://github.com/nishadsinghi/CleanCLIP) |
| 2023.03     |   Robust Contrastive Language-Image Pre-training against Data Poisoning and Backdoor Attacks    |   NeurIPS'23     | [link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/2232e8fee69b150005ac420bfa83d705-Abstract-Conference.html) | - |
| 2023.03    |  Detecting Backdoors in Pre-trained Encoders  |  CVPR'23    | [link](https://openaccess.thecvf.com/content/CVPR2023/html/Feng_Detecting_Backdoors_in_Pre-Trained_Encoders_CVPR_2023_paper.html) | [code](https://github.com/GiantSeaweed/DECREE) |
| 2023.10   |  Better Safe than Sorry: Pre-training CLIP against Targeted Data Poisoning and Backdoor Attacks   | ICML'24   | [link](https://arxiv.org/abs/2310.05862) | [code](https://github.com/BigML-CS-UCLA/SafeCLIP)|
 | 2024.03    | Unlearning Backdoor Threats: Enhancing Backdoor Defense in Multimodal Contrastive Learning via Local Token Unlearning      |   CVPRW'24    | [link](https://arxiv.org/abs/2403.16257) | - |
| 2024.09     | Adversarial Backdoor Defense in CLIP      |  arXiv     | [link](https://arxiv.org/abs/2409.15968) | - |
| 2024.09     | CleanerCLIP: Fine-grained Counterfactual Semantic Augmentation for Backdoor| arXiv | [link](https://arxiv.org/abs/2409.17601) | - |
|2024.11     |Semantic Shield: Defending Vision-Language Models Against Backdooring and Poisoning via Fine-grained Knowledge Alignment| CVPR'24| [link](https://openaccess.thecvf.com/content/CVPR2024/html/Ishmam_Semantic_Shield_Defending_Vision-Language_Models_Against_Backdooring_and_Poisoning_via_CVPR_2024_paper.html) | [code](https://github.com/IshmamAlvi/Semantic-Shield) |
|2024.11     | DeDe: Detecting Backdoor Samples for SSL Encoders via Decoders| CVPR'25| [link](https://openaccess.thecvf.com/content/CVPR2025/html/Hou_DeDe_Detecting_Backdoor_Samples_for_SSL_Encoders_via_Decoders_CVPR_2025_paper.html) |-|
|2024.12     |Defending Multimodal Backdoored Models by Repulsive Visual Prompt Tuning| arXiv| [link](https://arxiv.org/abs/2412.20392)| - |
|2024.12     | DETECTING BACKDOOR SAMPLES IN CONTRASTIVE LANGUAGE IMAGE PRETRAINING| ICLR'25|[link](https://iclr.cc/virtual/2025/poster/30032) | [code](https://github.com/HanxunH/Detect-CLIP-Backdoor-Samples) |
|2024.12     |Perturb and Recover: Fine-tuning for Effective Backdoor Removal from CLIP|arXiv| [link](https://arxiv.org/abs/2412.00727) | [code](https://github.com/nmndeep/PerturbAndRecover) |
| 2025.02    |Neural Antidote: Class-Wise Prompt Tuning for Purifying Backdoors in CLIP|arXiv| [link](https://arxiv.org/abs/2502.19269) |-|
| 2025.12    |Assimilation Matters: Model-level Backdoor Detection in Vision-Language Pretrained Models|arXiv| [link](https://www.arxiv.org/abs/2512.00343) |[code](https://github.com/Robin-WZQ/AMDET)|


### Text Conditioned Diffusion Models

#### Backdoor Attack

| Time | Title | Venue |  Paper   |   Code   |
| ---- | ----- | :---: | :------: | :------: |
| 2022.11 | Rickrolling the Artist: Injecting Backdoors into Text Encoders for Text-to-Image Synthesis | ICCV'23 | [link](https://arxiv.org/abs/2211.02408) | [link](https://github.com/LukasStruppek/Rickrolling-the-Artist) |
| 2023.05 | Personalization as a Shortcut for Few-Shot Backdoor Attack against Text-to-Image Diffusion Models | AAAI'24 | [link](https://arxiv.org/abs/2305.10701) | [link](https://github.com/Huang-yihao/Personalization-based_backdoor) |
| 2023.05 | Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning | ACM MM'23 | [link](https://arxiv.org/abs/2305.04175) | [link](https://github.com/zhaisf/BadT2I) |
| 2023.06 | VillanDiffusion: A Unified Backdoor Attack Framework for Diffusion Models | NeurIPS'23 | [link](https://arxiv.org/abs/2306.06874) | [link](https://github.com/IBM/VillanDiffusion) |
| 2023.07 | BAGM: A Backdoor Attack for Manipulating Text-to-Image Generative Models | TIFS'24 | [link](https://arxiv.org/abs/2307.16489) | [link](https://github.com/JJ-Vice/BAGM) |
| 2023.08 | Backdooring Textual Inversion for Concept Censorship         | arXiv      | [link](https://arxiv.org/abs/2308.10718)                 | [link](https://github.com/concept-censorship/concept-censorship.github.io) |
| 2023.10 | Nightshade: Prompt-Specific Poisoning Attacks on Text-to-Image Generative Models | S&P'24     | [link](https://arxiv.org/abs/2310.13828)                 | [link](https://github.com/Shawn-Shan/nightshade-release)     |
| 2024.01 | The Stronger the Diffusion Model, the Easier the Backdoor: Data Poisoning to Induce Copyright Breaches Without Adjusting Finetuning Pipeline | ICML'24    | [link](https://arxiv.org/abs/2401.04136)                 | [link](https://github.com/haonan3/SilentBadDiffusion)        |
| 2024.06 | Injecting Bias in Text-To-Image Models via Composite-Trigger Backdoors | arXiv      | [link](https://arxiv.org/abs/2406.15213)                 | -                                                            |
| 2024.07 | Control ControlNet: Multidimensional Backdoor Attack Based on ControlNet | ICONIP'24  | [link](https://easychair.org/publications/preprint/L1B4) | [link](https://github.com/paoche11/ControlNetBackdoor)       |
| 2024.10 | EvilEdit: Backdooring Text-to-Image Diffusion Models in One Second | ACM MM'24  | [link](https://dl.acm.org/doi/10.1145/3664647.3680689)   | [link](https://github.com/haowang-cqu/EvilEdit)              |
| 2024.11 | Combinational Backdoor Attack against Customized Text-to-Image Models | arXiv      | [link](https://arxiv.org/abs/2411.12389)                 | -                                                            |
| 2024.11 | TrojanEdit: Backdooring Text-Based Image Editing Models      | arXiv      | [link](https://arxiv.org/abs/2411.14681)                 | -                                                            |
| 2025.02 | Imperceptible Backdoor Attacks on Text-Guided 3D Scene Grounding | TMM'25     | [link](https://dblp.org/rec/journals/tmm/LiuH25)         | -                                                            |
| 2025.03 | Towards Invisible Backdoor Attack on Text-to-Image Diffusion Model | arXiv      | [link](https://arxiv.org/abs/2503.17724)                 | [link](https://github.com/Robin-WZQ/IBA)                     |
| 2025.03 | Silent Branding Attack: Trigger-free Data Poisoning Attack on Text-to-Image Diffusion Models | CVPR'25    | [link](https://arxiv.org/abs/2503.09669)                 | [link](https://github.com/agwmon/silent-branding-attack)     |
| 2025.04 | BadVideo: Stealthy Backdoor Attack against Text-to-Video Generation | ICCV'25    | [link](https://arxiv.org/abs/2504.16907)                 | [link](https://wrt2000.github.io/BadVideo2025/)              |
| 2025.04 | Erased but Not Forgotten: How Backdoors Compromise Concept Erasure | arXiv      | [link](https://arxiv.org/abs/2504.21072)                 | [link](https://github.com/jonasgrebe/erased-but-not-forgotten) |
| 2025.04 | REDEditing: Relationship-Driven Precise Backdoor Poisoning on Text-to-Image Diffusion Models | arXiv      | [link](https://arxiv.org/abs/2504.14554)                 | -                                                            |
| 2025.06 | TWIST: Text-encoder Weight-editing for Inserting Secret Trojans in Text-to-Image Models | ACL'25     | [link](https://aclanthology.org/2025.acl-long.541/)      | -                                                            |
| 2025.08 | Practical, Generalizable and Robust Backdoor Attacks on Text-to-Image Diffusion Models | arXiv      | [link](https://arxiv.org/abs/2508.01605)                 | -                                                            |
| 2025.08 | BadBlocks: Low-Cost and Stealthy Backdoor Attacks Tailored for Text-to-Image Diffusion Models | arXiv      | [link](https://arxiv.org/abs/2508.03221)                 | -                                                            |


#### Backdoor Defense

| Time | Title | Venue |  Paper   |   Code   |
| ---- | ----- | :---: | :------: | :------: |
| 2024.04 | UFID: A Unified Framework for Black-box Input-level Backdoor Detection on Diffusion Models       | AAAI'25    | [link](https://arxiv.org/abs/2404.01101)                                                                                    | [link](https://github.com/GuanZihan/official_UFID)           |
| 2024.07 | T2IShield: Defending Against Backdoors on Text-to-Image Diffusion Models                         | ECCV'24    | [link](https://arxiv.org/abs/2407.04215)                                                                                    | [link](https://github.com/Robin-WZQ/T2IShield)               |
| 2024.08 | Defending Text-to-image Diffusion Models: Surprising Efficacy of Textual Perturbations Against Backdoor Attacks | arXiv      | [link](https://arxiv.org/abs/2408.15721)                                                                                    | [link](https://github.com/oscarchew/t2i-backdoor-defense)    |
| 2024.11 | Fine-grained Prompt Screening: Defending Against Backdoor Attack on Text-to-Image Diffusion Models | IJCAI'25 | [link](https://www.ijcai.org/proceedings/2025/0068.pdf)                                                                     | -                                                            |
| 2025.01 | Backdoor Defense for Text Encoders in Text-to-Image Generative Models                      | IEEE TDSC'25 | [link](https://www.computer.org/csdl/journal/tq/2025/06/11112743/28UtsBBMwZa)                                              | [link](https://github.com/Wu-sm/Defense-against-backdoor-attacks-in-text-to-image) |
| 2025.02 | BackdoorDM: A Comprehensive Benchmark for Backdoor Learning in Diffusion Model                   | NeurIPS'25 | [link](https://arxiv.org/abs/2502.11798)                                                                                    | [link](https://github.com/linweiii/BackdoorDM)               |
| 2025.03 | Efficient Input-level Backdoor Detection on Text-to-Image Synthesis via Neuron Activation Variation | arXiv    | [link](https://arxiv.org/abs/2503.06453)                                                                                    | -                                                            |
| 2025.04 | Backdoor Defense in Diffusion Models via Spatial Attention Unlearning                            | arXiv      | [link](https://arxiv.org/abs/2504.18563)                                                                                    | -                                                            |
| 2025.04 | Dynamic Attention Analysis for Backdoor Detection in Text-to-Image Diffusion Models              | arXiv      | [link](https://arxiv.org/abs/2504.20518)                                                                                    | [link](https://github.com/Robin-WZQ/DAA)                     |



### Large Vision Language Models

#### Backdoor Attack

| Time    | Title                                                        |   Venue    |                            Paper                             |                           Code                           |
| ------- | ------------------------------------------------------------ | :--------: | :----------------------------------------------------------: | :------------------------------------------------------: |
| 2024.02 | Shadowcast: Stealthy Data Poisoning Attacks against Vision-Language Models | NeurIPS'24 |      [link](https://openreview.net/forum?id=JhqyeppMiD)      |          [code](https://vlm-poison.github.io/)           |
| 2024.02 | VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models |  IJCV'25   | [link](https://link.springer.com/article/10.1007/s11263-025-02368-9) |     [code](https://github.com/JWLiang007/VL-Trojan)      |
| 2024.02 | Test-Time BACKDOOR ATTACKS ON MULTIMODAL LARGE LANGUAGE MODELS |   arXiv    |          [link](https://github.com/sail-sg/AnyDoor)          |        [code](https://github.com/sail-sg/AnyDoor)        |
| 2024.03 | ImgTrojan: Jailbreaking Vision-Language Models with ONE Image |  NAACL'25  |    [link](https://aclanthology.org/2025.naacl-long.360/)     |      [code](https://github.com/xijia-tao/ImgTrojan)      |
| 2024.03 | TrojVLM: Backdoor Attack Against Vision Language Models  |  ECCV'24   | [link](https://link.springer.com/chapter/10.1007/978-3-031-73650-6_27) |                            -                             |
| 2024.04 | PHYSICAL BACKDOOR ATTACK CAN JEOPARDIZE DRIVING WITH VISION-LARGE-LANGUAGE MODELS |  ICMLW'24  |          [link](https://icml.cc/virtual/2024/38112)          |                            -                             |
| 2024.06 | Revisiting Backdoor Attacks against Large Vision-Language Models from Domain Shift |  CVPR'25   | [link](https://www.computer.org/csdl/proceedings-article/cvpr/2025/436400j477/2999SblAZlC) |      [code](https://github.com/LiangSiyuan21/MABA)       |
| 2024.10 | BACKDOORING VISION-LANGUAGE MODELS WITH OUT-OF-DISTRIBUTION DATA |  ICLR'25   |      [link](https://openreview.net/forum?id=tZozeR3VV7)      |                            -                             |
| 2025.02 | Stealthy Backdoor Attack in Self-Supervised Learning Vision Encoders for Large Vision Language Models |  CVPR'25   |    [link](https://ieeexplore.ieee.org/document/11092582)     |       [code](https://github.com/6zHAOyi/BadVision)       |
| 2025.03 | BadToken: Token-level Backdoor Attacks to Multi-modal Large Language Models |  CVPR'25   | [link](https://www.computer.org/csdl/proceedings-article/cvpr/2025/436400ae927/299buyfnYBy) |                            -                             |
| 2025.05 | Natural Reflection Backdoor Attack on Vision Language Model for Autonomous Driving |   arXiv    |           [link](https://arxiv.org/abs/2505.06413)           |                            -                             |
| 2025.06 | Backdoor Attack on Vision Language Models with Stealthy Semantic Manipulation |   arXiv    |           [link](https://arxiv.org/abs/2506.07214)           |                                                          |
| 2025.07 | Shadow-Activated Backdoor Attacks on Multimodal Large Language Models |   ACL'25   |   [link](https://aclanthology.org/2025.findings-acl.248/)    |      [code](https://github.com/ericyinyzy/BadMLLM)       |
| 2025.08 | IAG: Input-aware Backdoor Attack on VLMs for Visual Grounding |   arXiv    |           [link](https://arxiv.org/abs/2508.09456)           |                            -                             |
| 2025.09 | TokenSwap: Backdoor Attack on the Compositional Understanding of Large Vision-Language Models |   arXiv    |           [link](https://arxiv.org/abs/2509.24566)           | [code](https://anonymous.4open.science/r/tokenswap-341F) |
| 2025.11 | MTAttack: Multi-Target Backdoor Attacks against Large Vision-LanguageModels | arXiv | [link](https://arxiv.org/abs/2511.10098) | [code](https://github.com/mala-lab/MTAttack) |
| 2025.11 | BackdoorVLM: A Benchmark for Backdoor Attacks on Vision-Language Models | arXiv | [link](https://arxiv.org/abs/2511.18921) | [code](https://github.com/bin015/BackdoorVLM)|


#### Backdoor Defense

| Time    | Title                                                        |   Venue    |                       Paper                        |                    Code                    |
| ------- | ------------------------------------------------------------ | :--------: | :------------------------------------------------: | :----------------------------------------: |
| 2025.05 | Backdoor Cleaning without External Guidance in MLLM Fine-tuning | NeurIPS‘25 | [link](https://openreview.net/forum?id=os4QYDf3Ms) | [code](https://github.com/XuankunRong/BYE) |
| 2025.06 | ROBUST ANTI-BACKDOOR INSTRUCTION TUNING IN LVLMS         |   arXiv    |      [link](https://arxiv.org/abs/2506.05401)      |                     -                      |
| 2025.06 | SRD: Reinforcement-Learned Semantic Perturbation         |  AAAI'26   |    [link](https://www.arxiv.org/abs/2506.04743)    |   [code](https://github.com/Ciconey/SRD)   |

### VLM-based Embodied AI

#### Backdoor Attack

| Time    | Title                                                        |  Venue   |                            Paper                             |                        Code                         |
| ------- | ------------------------------------------------------------ | :------: | :----------------------------------------------------------: | :-------------------------------------------------: |
| 2025.05 | BadVLA: Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization |  arXiv   |           [link](https://arxiv.org/abs/2505.16640)           |     [code](https://github.com/Zxy-MLlab/BadVLA)     |
| 2025.10 | TabVLA: Targeted Backdoor Attacks on Vision-Language-Action Models |  arXiv   |           [link](https://arxiv.org/abs/2510.10932)           |   [code](https://github.com/megaknight114/TabVLA)   |
| 2025.11 | AttackVLA: Benchmarking Adversarial and Backdoor Attacks on Vision-Language-Action Models |  arXiv   |           [link](https://arxiv.org/abs/2511.12149)           |                          -                          |
| 2025.05 | Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents | EMNLP’25 |  [link](https://aclanthology.org/2025.findings-emnlp.411/)   |  [code](https://github.com/CTZhou-byte/AgentGhost)  |
| 2025.06 | Poison Once, Control Anywhere: Clean-Text Visual Backdoors in VLM-based Mobile Agents |  arXiv   |           [link](https://arxiv.org/abs/2506.13205)           |                          -                          |
| 2025.07 | VisualTrap: A Stealthy Backdoor Attack on GUI Agents via Visual Grounding Manipulation | COLM‘25  | [link](https://openreview.net/forum?id=7HPuAkgdVm#discussion) |    [code](https://github.com/whi497/VisualTrap)     |
| 2025.09 | Realistic Environmental Injection Attacks on GUI Agents  |  arXiv   |           [link](https://arxiv.org/abs/2509.11250)           | [code](https://github.com/zhangyitonggg/attack2gui) |



## Other Related Awesome Repository

- [Awesome Data Poisoning and Backdoor Attacks](https://github.com/penghui-yang/awesome-data-poisoning-and-backdoor-attacks)
- [Awesome-Backdoor-in-Deep-Learning](https://github.com/zihao-ai/Awesome-Backdoor-in-Deep-Learning)
- [Backdoor Learning Resources](https://github.com/THUYimingLi/backdoor-learning-resources)
- [Awesome-LVLM-Attack](https://github.com/liudaizong/Awesome-LVLM-Attack/tree/main)
- [Awesome-Large-Model-Safety](https://github.com/xingjunm/Awesome-Large-Model-Safety)
