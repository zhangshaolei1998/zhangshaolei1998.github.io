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

<span class='anchor' id='about-me'></span>

**Shaolei Zhang** (**张绍磊**) is currently working toward his Ph.D. degree in the [Key Laboratory of Intelligent Information Processing](http://iip.ict.ac.cn/), [Institute of Computing Technology](https://www.cas.cn/), [Chinese Academy of Sciences](https://www.cas.cn/) (中国科学院计算技术研究所), advised by [Yang Feng (冯洋)](https://people.ucas.edu.cn/~yangfeng?language=en). He received his bachelor's degree from [Beijing University of Posts and Telecommunications](http://www.bupt.edu.cn/) in 2020, majoring in computer science and technology (北京邮电大学计算机科学与技术实验班). 

His research interests include nature language processing, <font color=green>machine translation</font>, <font color=red>simultaneous translation</font> and <font color=blue>large language model</font>. He has published over *10 papers* at the top international AI/NLP conferences such as ACL, EMNLP, NeurIPS, ICLR, AAAI. He won the first place in the streaming transcription track of AutoSimTrans 2021.


# 🔥 News
- *2023.12*: &nbsp;🎉	<font color=red>One paper</font> is accepted by ICASSP 2024!
- *2023.10*: &nbsp;🎉	<font color=red>Two papers</font> are accepted by EMNLP 2023!
- *2023.09*: &nbsp;👏	Serve as <font color=red>Area Chair</font> of ACL/EACL/NAACL ARR 2023!
- *2023.09*: &nbsp;🎉	<font color=red>One paper</font> is accepted by NeurIPS 2023!
- *2023.06*: &nbsp;🎉	Our cross-lingual aligned LLM [<font color=red>BayLing</font>](http://nlp.ict.ac.cn/bayling) is released.
- *2023.05*: &nbsp;🎉	<font color=red>Two papers</font> are accepted by ACL 2023.
- *2023.01*: &nbsp;🎉	<font color=red>One paper</font> is accepted by ICLR 2023 (spotlight)!
- *2022.10*: &nbsp;🎉	<font color=red>Three papers</font> are accepted by EMNLP 2022!
- *2022.02*: &nbsp;🎉	<font color=red>Three papers</font> are accepted by ACL 2022!

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2023</div><img src='images/bayling.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BayLing: Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models](https://arxiv.org/abs/2306.10968) \\
**Shaolei Zhang**, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen, Yang Feng

[![paper](https://img.shields.io/badge/Paper-d.svg)](https://arxiv.org/abs/2306.10968) [![homepage](https://img.shields.io/badge/Homepage-ff69b4.svg)](http://nlp.ict.ac.cn/bayling) [![demo](https://img.shields.io/badge/Demo-blue.svg)](http://nlp.ict.ac.cn/bayling/demo) [![huggingface](https://img.shields.io/badge/Huggingface-orange.svg)](https://huggingface.co/ICTNLP/bayling-13b-v1.1) [![](https://img.shields.io/github/stars/ictnlp/BayLing?style=social&label=Code+Stars)](https://github.com/ictnlp/BayLing)

- BayLing (百聆) is a LLM equipped with advanced language alignment.
- BayLing is the first research to use interactive translation tasks to complete the cross-language transfer of LLM's generation capabilities.
- BayLing is selected for inclusion in the [2022-2023 Top 100 Opensource achievements: <font color=red>Open100 (2022-2023)</font>](https://www.benchcouncil.org/evaluation/opencs/annual.html), launched by the International Open Benchmark Council (BenchCouncil).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/truthx.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space](https://arxiv.org/abs/2402.17811) \\
**Shaolei Zhang**, Tian Yu, Yang Feng

[![paper](https://img.shields.io/badge/Paper-d.svg)](https://arxiv.org/abs/2402.17811) [![huggingface](https://img.shields.io/badge/Huggingface-orange.svg)](https://huggingface.co/ICTNLP/Llama-2-7b-chat-TruthX) [![](https://img.shields.io/github/stars/ictnlp/TruthX?style=social&label=Code+Stars)](https://github.com/ictnlp/TruthX)

- TruthX is an inference-time method to elicit the truthfulness of LLMs by editing their internal representations in truthful space, thereby mitigating the hallucinations of LLMs.
- TruthX can control LLMs to generate truthful or hallucinatory responses by editing only a vector in truthful space.
- On [TruthfulQA benchmark](https://paperswithcode.com/sota/question-answering-on-truthfulqa), TruthX yields an average enhancement of 20% in truthfulness across 13 advanced LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GitHub Repo</div><img src='images/st.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Awesome Simultaneous Translation](https://github.com/zhangshaolei1998/Awesome-Simultaneous-Translation) \\
**Shaolei Zhang**

[![](https://img.shields.io/github/stars/zhangshaolei1998/Awesome-Simultaneous-Translation?style=social&label=Code+Stars)](https://github.com/zhangshaolei1998/Awesome-Simultaneous-Translation)

- A repository that collects the tookits, common datasets and paper list related to the research on Simultaneous Translation, including text-to-text machine translation and speech-to-text translation.
</div>
</div>

## 2024
- ![](https://img.shields.io/badge/ArXiv-2024-white.svg?style=social) &nbsp; **Shaolei Zhang**, Tian Yu, Yang Feng. [TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space](https://arxiv.org/pdf/2402.17811.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/TruthX)
- ![](https://img.shields.io/badge/ArXiv-2024-white.svg?style=social) &nbsp; Shoutao Guo, **Shaolei Zhang**, Yang Feng. [SiLLM: Large Language Models for Simultaneous Machine Translation](https://arxiv.org/pdf/2402.13036.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/SiLLM)
- ![](https://img.shields.io/badge/ICASSP-2024-white.svg?style=social) &nbsp; Shoutao Guo, **Shaolei Zhang**, Yang Feng. [Glancing Future for Simultaneous Machine Translation](https://arxiv.org/pdf/2309.06179.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Glance-SiMT)

## 2023
- ![](https://img.shields.io/badge/NeurIPS-2023-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Unified Segment-to-Segment Framework for Simultaneous Sequence Generation](https://openreview.net/pdf?id=GuErIOGLie). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Seg2Seg)
- ![](https://img.shields.io/badge/EMNLP-2023-white.svg?style=social) &nbsp; Zhengrui Ma, **Shaolei Zhang**, Shoutao Guo, Chenze Shao, Min Zhang, Yang Feng. [Non-autoregressive Streaming Transformer for Simultaneous Translation](https://aclanthology.org/2023.emnlp-main.314.pdf).(*<font color=red>Oral</font>*) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/NAST)
- ![](https://img.shields.io/badge/EMNLP-2023-white.svg?style=social) &nbsp; Shoutao Guo, **Shaolei Zhang**, Yang Feng. [Simultaneous Machine Translation with Tailored Reference](https://aclanthology.org/2023.findings-emnlp.202.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Tailored-Ref)
- ![](https://img.shields.io/badge/ACL-2023-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [End-to-End Simultaneous Speech Translation with Differentiable Segmentation](https://aclanthology.org/2023.findings-acl.485.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/DiSeg)
- ![](https://img.shields.io/badge/ACL-2023-white.svg?style=social) &nbsp; Shoutao Guo, **Shaolei Zhang**, Yang Feng. [Learning Optimal Policy for Simultaneous Machine Translation via Binary Search](https://aclanthology.org/2023.acl-long.130.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BS-SiMT)
- ![](https://img.shields.io/badge/ICLR-2023-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Hidden Markov Transformer for Simultaneous Machine Translation](https://openreview.net/pdf?id=9y0HFvaAYD6).(*<font color=red>Spotlight</font>*) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/HMT)
- ![](https://img.shields.io/badge/ArXiv-2023-white.svg?style=social) &nbsp; **Shaolei Zhang**, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen, Yang Feng. [BayLing: Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models](https://arxiv.org/abs/2306.10968). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BayLing)

## 2022
- ![](https://img.shields.io/badge/EMNLP-2022-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Information-Transport-based Policy for Simultaneous Translation](https://aclanthology.org/2022.emnlp-main.65.pdf).(*<font color=red>Oral</font>*) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/ITST)
- ![](https://img.shields.io/badge/EMNLP-2022-white.svg?style=social) &nbsp; **Shaolei Zhang**, Shoutao Guo, Yang Feng. [Wait-info Policy: Balancing Source and Target at Information Level for Simultaneous Machine Translation](https://aclanthology.org/2022.findings-emnlp.166.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Wait-info)
- ![](https://img.shields.io/badge/EMNLP-2022-white.svg?style=social) &nbsp; Shoutao Guo, **Shaolei Zhang**, Yang Feng. [Turning Fixed to Adaptive: Integrating Post-Evaluation into Simultaneous Machine Translation](https://aclanthology.org/2022.findings-emnlp.167.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/PED-SiMT)
- ![](https://img.shields.io/badge/ACL-2022-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Modeling Dual Read/Write Paths for Simultaneous Machine Translation](https://aclanthology.org/2022.acl-long.176.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Dual-Path)
- ![](https://img.shields.io/badge/ACL-2022-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Reducing Position Bias in Simultaneous Machine Translation with Length-Aware Framework](https://aclanthology.org/2022.acl-long.467.pdf).
- ![](https://img.shields.io/badge/ACL-2022-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Gaussian Multi-head Attention for Simultaneous Machine Translation](https://aclanthology.org/2022.findings-acl.238.pdf). [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/GMA)

## 2021
- ![](https://img.shields.io/badge/EMNLP-2021-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Universal Simultaneous Machine Translation with Mixture-of-Experts Wait-k Policy](https://aclanthology.org/2021.emnlp-main.581.pdf).(*<font color=red>Oral</font>*) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/MoE-Waitk)
- ![](https://img.shields.io/badge/EMNLP-2021-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [Modeling Concentrated Cross-Attention for Neural Machine Translation with Gaussian Mixture Model](https://aclanthology.org/2021.findings-emnlp.121.pdf).
- ![](https://img.shields.io/badge/AAAI-2021-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng, Liangyou Li. [Future-Guided Incremental Transformer for Simultaneous Translation](https://arxiv.org/pdf/2012.12465.pdf).(*<font color=red>Oral</font>*)
- ![](https://img.shields.io/badge/AutoSimTrans@NAACL-2021-white.svg?style=social) &nbsp; **Shaolei Zhang**, Yang Feng. [ICT’s System for AutoSimTrans 2021: Robust Char-Level Simultaneous Translation](https://aclanthology.org/2021.autosimtrans-1.1.pdf).(*<font color=red>Oral</font>*)

## 2019
- ![](https://img.shields.io/badge/ICONIP-2019-white.svg?style=social) &nbsp; **Shaolei Zhang**, Gang Lu, Kai Shuang. [Opinion Knowledge Injection Network for Aspect Extraction](https://link.springer.com/chapter/10.1007/978-3-030-36711-4_56).

# 🏆 Honors and Awards
- [2022]	ICT's Special Scholarship (Xia Peisu Award) (计算所所长特别奖（夏培肃奖）, highest award in ICT/CAS)
- [2022]	National Scholarship (国家奖学金)
- [2021]	First place in the streaming transcription track of AutoSimTrans 2021
- [2020]	Beijing Outstanding Graduates Award (北京市优秀毕业生)
- [2018]	Beijing Merit Student (北京市三好学生)
- [2017]	National Scholarship (国家奖学金)

# 👏 Services
- **Area Chair** of ACL/EACL/NAACL ARR 2023 
- **Reviewer** of ACL/EMNLP/COLING
- **Session Chair** of Student Seminar in [CCL 2024](http://cips-cl.org/static/CCL2024/index.html)
- **Session Chair** of Student Seminar in YSSNLP 2024
- 中国中文信息学会青年工作委员会 **学生执委会主任**
- **Programming Chair** of [CSSNLP](https://conference.cipsc.org.cn/cssnlp/) 2020/2021

# 📖 Educations
- *2020.06 - now*: Ph.D. Candidate. Nature language processing. [Key Laboratory of Intelligent Information Processing](http://iip.ict.ac.cn/), [Institute of Computing Technology](https://www.cas.cn/), [Chinese Academy of Sciences](https://www.cas.cn/).
- *2016.09 - 2020.06*: Bachelor's degree. Computer science and technology. [Beijing University of Posts and Telecommunications](http://www.bupt.edu.cn/).

# 💬 Invited Talks
- "如何在大模型时代找到科研切入点？" on CCMT 2024 [[Slides](https://zhangshaolei1998.github.io/slides/CCMT%E5%AD%A6%E7%94%9F%E8%AE%BA%E5%9D%9B_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "从机器翻译到同声传译：挑战与进展" on MLNLP Academic Seminar [[Slides](https://zhangshaolei1998.github.io/slides/MLNLP%E5%AD%A6%E6%9C%AF%E7%A0%94%E8%AE%A8%E4%BC%9A_%E5%90%8C%E5%A3%B0%E4%BC%A0%E8%AF%91%E7%BB%BC%E8%BF%B0_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://link.zhihu.com/?target=http%3A//www.bilibili.com/video/BV1dr4y1W7E9)]
- AI Time Youth Talk for ICLR 2023

# 💻 Internships
- *2019.12 - 2021.12*, Huawei Noah's Ark Lab, industry-university-research collaboration project, China.

<a href='https://clustrmaps.com/site/1bx1j'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=300&t=tt&d=f6ObyrbVLY65qa_IZr0teL9UER09Q1bLih8TUF5yekA'/></a>
