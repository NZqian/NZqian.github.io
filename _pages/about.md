---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



# About me
<span class='anchor' id='about-me'></span>

Ziqian Ning is a research scientist at ByteDance Seed, Shanghai, China, working on music generation. He received his Master's degree from the Audio, Speech and Language Processing Laboratory at Northwestern Polytechnical University ([ASLP@NWPU](http://www.npu-aslp.org/english)), supervised by Prof. [Lei Xie](http://www.nwpu-aslp.org/lxie/).

His research focuses on generative AI for music and speech, including full-length song generation, singing voice generation/conversion, low-latency voice conversion, and text-to-speech. His recent work includes the DiffRhythm series for efficient full-length song generation and the DualVC series for streaming voice conversion.


<!-- # 📜 Research Area
# News
<span class='anchor' id='news'></span>
- We released [Amphion](https://github.com/open-mmlab/Amphion), a toolkit for Audio, Music, and Speech Generation. The technical report is available [Amphion: An Open-Source Audio, Music and Speech Generation Toolkit](https://arxiv.org/abs/2312.09911). The Hugging Face of Amphion is [here](https://huggingface.co/amphion).
- [Multi-Scale Sub-Band Constant-Q Transform Discriminator for High-Fidelity Vocoder](https://arxiv.org/pdf/2311.14957.pdf) accepted by ICASSP2024, also integrated in [Amphion](https://github.com/open-mmlab/Amphion) 
- [SponTTS: modeling and transferring spontaneous style for TTS](https://arxiv.org/pdf/2311.07179.pdf) accepted by ICASSP2024.
- [Leveraging Content-based Features from Multiple Acoustic Models for Singing Voice Conversion](https://arxiv.org/pdf/2310.11160.pdf) accepted by ML4Audio @ NeurIPS 2023.
- [HiGNN-TTS: Hierarchical Prosody Modeling with Graph Neural Networks for Expressive Long-form TTS](https://arxiv.org/pdf/2309.13907.pdf)  accepted by ASRU2023.
</table> -->



<!-- # 📜 Research Area
<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Audio-Visual Speech Processing </font>: <BR>&nbsp;&nbsp; Audio-visual speech recognition; Sound Source localization</td>
    <td style="border: none;"> <font color="#0b5394"> Video Synthesize </font>: <BR>&nbsp;&nbsp; Talking Face Generation </td>
  </tr>
</table> -->


# Experience
<span class='anchor' id='experience'></span>

- *2024.10 - Present*, Seed, ByteDance, Shanghai, China.
- *2024.03 - 2024.09*, Azure Speech, Microsoft, China.
- *2022.06 - 2024.03*, Fuxi AI Lab, Netease, China.
- *2021.07 - 2021.09*, TEG, Tencent, China.


# Publications
<span class='anchor' id='publication'></span>

**Music and Singing Voice Generation**

- [DiffRhythm 2: Efficient and High Fidelity Song Generation via Block Flow Matching](https://arxiv.org/abs/2510.22950), Yuepeng Jiang, Huakang Chen, **Ziqian Ning**, Jixun Yao, Zerui Han, Di Wu, Meng Meng, Jian Luan, Zhonghua Fu, Lei Xie. arXiv preprint, 2025.

- [DiffRhythm+: Controllable and Flexible Full-Length Song Generation with Preference Optimization](https://arxiv.org/abs/2507.12890), Hui Chen, Yu-rou Jiang, Guobin Ma, Chuan-Ming Hao, Shuai Wang, Jixun Yao, **Ziqian Ning**, Meng Meng, Jian Luan, Zhonghua Fu, Lei Xie. arXiv preprint, 2025.

- [DiffRhythm: Blazingly Fast and Embarrassingly Simple End-to-End Full-Length Song Generation with Latent Diffusion](https://arxiv.org/abs/2503.01183), **Ziqian Ning**, Huakang Chen, Yuepeng Jiang, Chunbo Hao, Guobin Ma, Shuai Wang, Jixun Yao, Lei Xie. arXiv preprint, 2025. [Project](https://nzqian.github.io/DiffRhythm/).

- [Drop the beat! Freestyler for Accompaniment Conditioned Rapping Voice Generation](https://arxiv.org/pdf/2408.15474), **Ziqian Ning**, Shuai Wang, Yuepeng Jiang, Jixun Yao, Lei He, Shifeng Pan, Jie Ding, Lei Xie. **AAAI**, 2025. [Demo](https://nzqian.github.io/Freestyler/).

- [VITS-Based Singing Voice Conversion Leveraging Whisper and multi-scale F0 Modeling](https://arxiv.org/pdf/2310.02802.pdf), **Ziqian Ning**, Yuepeng Jiang, Zhichao Wang, Bin Zhang, Lei Xie. **ASRU**, 2023. [Demo](https://nzqian.github.io/SVCC2023-t23-ASLP)

**Voice Conversion (VC)**

- [MeanVC: Lightweight and Streaming Zero-Shot Voice Conversion via Mean Flows](https://arxiv.org/abs/2510.08392), Guobin Ma, Jixun Yao, **Ziqian Ning**, Yuepeng Jiang, Lingxin Xiong, Lei Xie, Pengcheng Zhu. arXiv preprint, 2025. [Demo](https://aslp-lab.github.io/MeanVC/)

- [REF-VC: Robust, Expressive and Fast Zero-Shot Voice Conversion with Diffusion Transformers](https://arxiv.org/abs/2508.04996), Yuepeng Jiang, **Ziqian Ning**, Shuai Wang, Chengjia Wang, Mengxiao Bi, Pengcheng Zhu, Zhonghua Fu, Lei Xie. arXiv preprint, 2025.

- [StableVC: Style Controllable Zero-Shot Voice Conversion with Conditional Flow Matching](https://arxiv.org/pdf/2412.04724), Jixun Yao, Yuguang Yang, Yu Pan, **Ziqian Ning**, Jiaohao Ye, Hongbin Zhou, Lei Xie. **AAAI**, 2025.

- [PromptVC: Flexible Stylistic Voice Conversion in Latent Space Driven by Natural Language Prompts](https://arxiv.org/pdf/2309.09262.pdf), Jixun Yao, Yuguang Yang, Yi Lei, **Ziqian Ning**, Yanni Hu, Yu Pan, Jingjing Yin, Hongbin Zhou, Heng Lu, Lei Xie. **ICASSP**, 2024. [Demo](https://yaoxunji.github.io/prompt_vc/)

- [Expressive-VC: Highly Expressive Voice Conversion with Attention Fusion of Bottleneck and Perturbation Features](https://ieeexplore.ieee.org/abstract/document/10096057), **Ziqian Ning**, Qicong Xie, Pengcheng Zhu, Zhichao Wang, Liumeng Xue, Jixun Yao, Lei Xie, Mengxiao Bi. **ICASSP**, 2023. [Demo](https://nzqian.github.io/Expressive-VC.github.io/)

- [Preserving background sound in noise-robust voice conversion via multi-task learning](https://ieeexplore.ieee.org/abstract/document/10095960), Jixun Yao, Yi Lei, Qing Wang, Pengcheng Guo, **Ziqian Ning**, Lei Xie, Hai Li, Junhui Liu, Danming Xie. **ICASSP**, 2023. [Demo](https://yaoxunji.github.io/background_sound_vc/)


**Streaming Voice Conversion**

- [SynthVC: Leveraging Synthetic Data for End-to-End Low Latency Streaming Voice Conversion](https://arxiv.org/abs/2510.09245), Zhao Guo, **Ziqian Ning**, Guangsheng Ma, Lei Xie. arXiv preprint, 2025.

- [DualVC 3: Leveraging Language Model Generated Pseudo Context for End-to-end Low Latency Streaming Voice Conversion](https://arxiv.org/pdf/2406.07846v1), **Ziqian Ning**, Shuai Wang, Pengcheng Zhu, Zhichao Wang, Jixun Yao, Lei Xie, Mengxiao Bi. **INTERSPEECH**, 2024. [Demo](https://dualvc.github.io/dualvc3/)

- [DualVC 2: Dynamic Masked Convolution for Unified Streaming and Non-Streaming Voice Conversion](https://arxiv.org/pdf/2309.15496.pdf), **Ziqian Ning**, Yuepeng Jiang, Pengcheng Zhu, Shuai Wang, Jixun Yao, Lei Xie, Mengxiao Bi. **ICASSP**, 2024. [Demo](https://dualvc.github.io/dualvc2/)

- [DualVC: Dual-mode Voice Conversion using Intra-model Knowledge Distillation and Hybrid Predictive Coding](https://arxiv.org/pdf/2305.12425.pdf), **Ziqian Ning**, Yuepeng Jiang, Pengcheng Zhu, Jixun Yao, Shuai Wang, Lei Xie, Mengxiao Bi. **INTERSPEECH**, 2023. [Demo](https://dualvc.github.io/)

**Speaker Anonymization**

- [NPU-NTU System for Voice Privacy 2024 Challenge](https://arxiv.org/pdf/2409.04173), Jixun Yao, Nikita Kuzmin, Qing Wang, Pengcheng Guo, **Ziqian Ning**, Dake Guo, Kong Aik Lee, Eng-Siong Chng, Lei Xie. **INTERSPEECH**, 2025.

- [Distinctive and Natural Speaker Anonymization via Singular Value Transformation-assisted Matrix](https://arxiv.org/abs/2405.10786), Jixun Yao, Qing Wang, Pengcheng Guo, **Ziqian Ning**, Lei Xie. **TASLP**.

- [MUSA: Multi-lingual Speaker Anonymization via Serial Disentanglement](https://arxiv.org/pdf/2407.11629), Jixun Yao, Qing Wang, Pengcheng Guo, **Ziqian Ning**, Yuguang Yang, Yu Pan, Lei Xie. **TASLP**, 2025.


**Text to Speech**
- [Fine-grained Preference Optimization Improves Zero-shot Text-to-Speech](https://arxiv.org/abs/2502.02950), Jixun Yao, Yuguang Yang, Yu Pan, Yuan Feng, **Ziqian Ning**, Jianhao Ye, Hongbin Zhou, Lei Xie. arXiv preprint, 2025.

- [Accent-VITS: accent transfer for end-to-end TTS](https://arxiv.org/pdf/2312.16850.pdf), Linhan Ma, Yongmao Zhang, Xinfa Zhu, Yi Lei, **Ziqian Ning**, Pengcheng Zhu, Lei Xie. **NCMMSC**, 2023. [Demo](https://anonymous-accentvits.github.io/AccentVITS/)


# Project Experience
<span class='anchor' id='project-experience'></span>

- **DiffRhythm Series**
  - Lead the development of efficient end-to-end full-length song generation systems that synthesize vocals and accompaniment from lyrics and style prompts, spanning latent diffusion, block flow matching, controllable style conditioning, and preference optimization.
  - Released DiffRhythm as an open-source full-length song generation model. It quickly reached No. 1 on the Hugging Face Space trending chart after release, and the GitHub repository has received 2K+ stars. [Project](https://nzqian.github.io/DiffRhythm/)
  - Extend the original system into DiffRhythm+ and DiffRhythm 2, improving controllability, preference alignment, lyric alignment, generation fidelity, and long-form coherence.
- **Singing Voice Conversion Challenge 2023**
  - Propose a VITS-based singing voice conversion model that leverages Whisper bottleneck features as linguistic information and uses PBTC module extracts multi-scale F0 to better capture the pitch variation. The results of the official competition measurements demonstrate that our system achieves human-level naturalness, ranking first and second in Task 1 and Task 2, respectively. [Demo](https://nzqian.github.io/SVCC2023-t23-ASLP)
- **Online Text-to-speech synthesis system**
  - Develop a text-to-speech system to provide high availability and scalability for online services. Models are encapsulated in separate microservices that are managed using Kubernetes. Kafka is used for inter-model messaging, and the use of message queue makes it possible to parallelize a large number of microservice replicas.


# Patents
<span class='anchor' id='patents'></span>

- [CN115910083A](https://patents.google.com/patent/CN115910083A/en?q=(%E5%AE%81)&inventor=%E5%AD%90%E8%B0%A6&oq=%E5%AE%81%E5%AD%90%E8%B0%A6) Real-time voice conversion method, device, electronic equipment and medium.
- [CN116013336A](https://patents.google.com/patent/CN116013336A/en?q=(%E5%AE%81)&inventor=%E5%AD%90%E8%B0%A6&oq=%E5%AE%81%E5%AD%90%E8%B0%A6) Voice conversion method, device, electronic equipment and storage medium. 
- [CN116364099A](https://patents.google.com/patent/CN116364099A/en?q=(%E5%AE%81)&inventor=%E5%AD%90%E8%B0%A6&oq=%E5%AE%81%E5%AD%90%E8%B0%A6) Voice conversion method, device, electronic apparatus, storage medium, and program product. 
- [CN118136033A](https://patents.google.com/patent/CN118136033A/en?q=(%E5%AE%81)&inventor=%E5%AD%90%E8%B0%A6&oq=%E5%AE%81%E5%AD%90%E8%B0%A6) Method, device, electronic equipment and storage medium for converting drama voice.