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

**Shaolei Zhang** (**张绍磊**) is a fifth-year Ph.D. candidate (2020-2025) in [Key Laboratory of Intelligent Information Processing](http://iip.ict.ac.cn/), [Institute of Computing Technology](https://www.cas.cn/), [Chinese Academy of Sciences](https://www.cas.cn/) (中国科学院计算技术研究所), advised by [Yang Feng (冯洋)](https://people.ucas.edu.cn/~yangfeng?language=en). He received his bachelor's degree from [Beijing University of Posts and Telecommunications](http://www.bupt.edu.cn/) in 2020, majoring in computer science and technology (北京邮电大学计算机科学与技术实验班). 

His research interests include nature language processing, <font color=red>simultaneous translation</font> and <font color=blue>large language model</font>. He has published over *20 papers* at the top international AI/NLP conferences such as ACL, NeurIPS, ICLR, EMNLP. He won the first place in the streaming transcription track of AutoSimTrans 2021. 

> I am willing to communicate and share my research, and I am interested in opportunities in the industry, academia or postdoctoral. If you would like to connect with me, please feel free to reach out via Email `zhangshaolei20z@ict.ac.cn` or WeChat `zhangshaolei0331`.


# 🔥 News
- *2024.05*: &nbsp;🎉	<font color=red>6 papers</font> are accepted by ACL 2024!
- *2023.12*: &nbsp;🎉	<font color=red>1 paper</font> is accepted by ICASSP 2024!
- *2023.10*: &nbsp;🎉	<font color=red>2 papers</font> are accepted by EMNLP 2023!
- *2023.09*: &nbsp;👏	Serve as <font color=red>Area Chair</font> of ACL/EACL/NAACL ARR 2023!
- *2023.09*: &nbsp;🎉	<font color=red>1 paper</font> is accepted by NeurIPS 2023!
- *2023.06*: &nbsp;🎉	Our cross-lingual aligned LLM [<font color=red>BayLing</font>](http://nlp.ict.ac.cn/bayling) is released.
- *2023.05*: &nbsp;🎉	<font color=red>2 papers</font> are accepted by ACL 2023.
- *2023.01*: &nbsp;🎉	<font color=red>1 paper</font> is accepted by ICLR 2023 (Spotlight)!
- *2022.10*: &nbsp;🎉	<font color=red>3 papers</font> are accepted by EMNLP 2022!
- *2022.02*: &nbsp;🎉	<font color=red>3 papers</font> are accepted by ACL 2022!

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Multilingual</div><img src='images/bayling.png' alt="sym" width="100%">

<details>
<summary>Demo</summary>
  <img src="images/bayling.gif" alt="img" width="100%" />
</details>

</div>
</div>
<div class='paper-box-text' markdown="1">

[BayLing: Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models](https://arxiv.org/abs/2306.10968) \\
**Shaolei Zhang**, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen, Yang Feng

[![arXiv](https://img.shields.io/badge/Paper-arXiv_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2306.10968) [![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-BayLing-orange.svg)](http://nlp.ict.ac.cn/bayling) [![project](https://img.shields.io/badge/%F0%9F%92%AC%20Online_Demo-BayLing-green.svg)](http://nlp.ict.ac.cn/bayling/demo) [![model](https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-Models-blue.svg)](https://huggingface.co/ICTNLP/bayling-13b-v1.1) [![](https://img.shields.io/github/stars/ictnlp/BayLing?style=social&label=Code+Stars)](https://github.com/ictnlp/BayLing)

- BayLing (百聆) is a LLM equipped with advanced language alignment.
- BayLing is the  <font color=red>Ofirst research to use language alignments to enhance LLM's multilingual capabilities</font>.
- BayLing is selected for inclusion in the [2022-2023 Top 100 Opensource achievements: <font color=red>Open100 (2022-2023)</font>](https://www.benchcouncil.org/evaluation/opencs/annual.html), launched by the International Open Benchmark Council (BenchCouncil).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Trustworthy</div><img src='images/truthx.png' alt="sym" width="100%">

<details>
<summary>Demo</summary>
  <img src="images/truthx.gif" alt="img" width="100%" />
</details>

</div>
</div>
<div class='paper-box-text' markdown="1">

[TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space](https://arxiv.org/abs/2402.17811) \\
**Shaolei Zhang**, Tian Yu, Yang Feng

[![arXiv](https://img.shields.io/badge/Paper-ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2402.17811) [![project](https://img.shields.io/badge/%F0%9F%93%9A%20Homepage-Try%20TruthX-orange.svg)](https://ictnlp.github.io/TruthX-site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-Models-blue.svg)](https://huggingface.co/ICTNLP/Llama-2-7b-chat-TruthX) [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/truthx-alleviating-hallucinations-by-editing/question-answering-on-truthfulqa)](https://paperswithcode.com/sota/question-answering-on-truthfulqa) [![](https://img.shields.io/github/stars/ictnlp/TruthX?style=social&label=Code+Stars)](https://github.com/ictnlp/TruthX)

- TruthX is an inference-time method to activate the truthfulness of LLMs by editing their internal representations, thereby mitigating the hallucinations.
- TruthX can control LLMs to generate truthful or hallucinatory responses by editing only a vector in truthful space.
- On [TruthfulQA benchmark](https://paperswithcode.com/sota/question-answering-on-truthfulqa), TruthX yields an average enhancement of 20% in truthfulness across 13 LLMs.  <font color=red>#Ranked 2 behind GPT-4</font>.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Speech</div><img src='images/streamspeech.png' alt="sym" width="100%">

<details>
<summary>Demo</summary>
  <img src="images/StreamSpeech.gif" alt="img" width="100%" />
</details>

</div>
</div>
<div class='paper-box-text' markdown="1">

[StreamSpeech: Simultaneous Speech-to-Speech Translation with Multi-task Learning](https://arxiv.org/abs/2406.03049) \\
**Shaolei Zhang**, Qingkai Fang, Shoutao Guo, Zhengrui Ma, Min Zhang, Yang Feng

[![arXiv](https://img.shields.io/badge/Paper-ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2406.03049) [![project](https://img.shields.io/badge/%F0%9F%8E%A7%20Demo-Listen%20to%20StreamSpeech-orange.svg)](https://ictnlp.github.io/StreamSpeech-site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-Models-blue.svg)](https://huggingface.co/ICTNLP/StreamSpeech_Models/tree/main) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fictnlp%2FStreamSpeech&count_bg=%2379C83D&title_bg=%23555555&icon=awesomelists.svg&icon_color=%23E7E7E7&title=Visitors&edge_flat=false)](https://hits.seeyoufarm.com) [![](https://img.shields.io/github/stars/ictnlp/StreamSpeech?style=social&label=Code+Stars)](https://github.com/ictnlp/StreamSpeech)

- StreamSpeech is an <font color=red>"All in One" seamless model</font> for over 8 tasks of offline and simultaneous speech recognition, speech translation and speech synthesis.
- StreamSpeech can present intermediate results (i.e., ASR or translation results) during simultaneous translation, offering a more comprehensive low-latency communication experience.
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

[TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space](https://arxiv.org/pdf/2402.17811.pdf). ACL 2024 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Tian Yu, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2402.17811) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/TruthX) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://ictnlp.github.io/TruthX-site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/Llama-2-7b-chat-TruthX)<br><br>

[StreamSpeech: Simultaneous Speech-to-Speech Translation with Multi-task Learning](https://arxiv.org/pdf/2406.03049). ACL 2024 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Qingkai Fang, Shoutao Guo, Zhengrui Ma, Min Zhang, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2406.03049) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/StreamSpeech) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://ictnlp.github.io/StreamSpeech-site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/StreamSpeech_Models)<br><br>

[Truth-Aware Context Selection: Mitigating Hallucinations of Large Language Models Being Misled by Untruthful Contexts](https://arxiv.org/pdf/2403.07556.pdf). ACL 2024 findings (<font color=red>CCF-A</font>).<br>
Tian Yu, **Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2403.07556) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/TACS) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/TACS_Truth_Detection_Classifiers)<br><br>

[Can We Achieve High-quality Direct Speech-to-Speech Translation Without Parallel Speech Data?](https://arxiv.org/pdf/2406.07289) ACL 2024 (<font color=red>CCF-A</font>).<br>
Qingkai Fang, **Shaolei Zhang**, Zhengrui Ma, Min Zhang, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2406.07289) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/ComSpeech) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://ictnlp.github.io/ComSpeech-Site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/ComSpeech_Models)<br><br>

[Decoder-only Streaming Transformer for Simultaneous Translation](https://arxiv.org/pdf/2406.03878). ACL 2024 (<font color=red>CCF-A</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2406.03878) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/DST) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/DST)<br><br>

[A Non-autoregressive Generation Framework for End-to-End Simultaneous Speech-to-Any Translation](https://arxiv.org/pdf/2406.06937). ACL 2024 (<font color=red>CCF-A</font>).<br>
Zhengrui Ma, Qingkai Fang, **Shaolei Zhang**, Shoutao Guo, Min Zhang, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2406.06937) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/NAST-S2x) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://nast-s2x.github.io/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/NAST-S2X)<br><br>

[Agent-SiMT: Agent-assisted Simultaneous Machine Translation with Large Language Models](https://arxiv.org/pdf/2406.06910). Preprint 2024.<br>
Shoutao Guo, **Shaolei Zhang**, Zhengrui Ma, Min Zhang, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/Preprint_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2406.06910) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/SiLLM)<br><br>

[Glancing Future for Simultaneous Machine Translation](https://arxiv.org/pdf/2309.06179.pdf). ICASSP 2024 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ICASSP_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2309.06179) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Glance-SiMT)<br><br>


## 2023
[BayLing: Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models](https://arxiv.org/abs/2306.10968). Preprint 2023.<br>
**Shaolei Zhang**, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/Preprint_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/abs/2306.10968) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BayLing) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](http://nlp.ict.ac.cn/bayling) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/bayling-13b-v1.1)<br><br>

[Unified Segment-to-Segment Framework for Simultaneous Sequence Generation](https://openreview.net/pdf?id=GuErIOGLie). NeurIPS 2023 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/NeurIPS_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://openreview.net/pdf?id=GuErIOGLie) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Seg2Seg)<br><br>

[Non-autoregressive Streaming Transformer for Simultaneous Translation](https://aclanthology.org/2023.emnlp-main.314.pdf). EMNLP 2023 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
Zhengrui Ma, **Shaolei Zhang**, Shoutao Guo, Chenze Shao, Min Zhang, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2023.emnlp-main.314) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/NAST)<br><br>

[Simultaneous Machine Translation with Tailored Reference](https://aclanthology.org/2023.findings-emnlp.202.pdf). EMNLP 2023 findings (<font color=red>CCF-B</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2023.findings-emnlp.202) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Tailored-Ref)<br><br>

[End-to-End Simultaneous Speech Translation with Differentiable Segmentation](https://aclanthology.org/2023.findings-acl.485.pdf). ACL 2023 findings (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2023.findings-acl.485) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/DiSeg)<br><br>

[Learning Optimal Policy for Simultaneous Machine Translation via Binary Search](https://aclanthology.org/2023.acl-long.130.pdf). ACL 2023 (<font color=red>CCF-A</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2023.acl-long.130) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BS-SiMT)<br><br>

[Hidden Markov Transformer for Simultaneous Machine Translation](https://openreview.net/pdf?id=9y0HFvaAYD6). ICLR 2023 **<font color=red>Spotlight</font>**.<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ICLR_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://openreview.net/pdf?id=9y0HFvaAYD6) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/HMT) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Model-orange.svg?style=plastic)](https://github.com/ictnlp/HMT)<br><br>

## 2022
[Information-Transport-based Policy for Simultaneous Translation](https://aclanthology.org/2022.emnlp-main.65.pdf). EMNLP 2022 **<font color=red>Oral</font>** (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2022-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2022.emnlp-main.65) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/ITST)<br><br>

[Wait-info Policy: Balancing Source and Target at Information Level for Simultaneous Machine Translation](https://aclanthology.org/2022.findings-emnlp.166.pdf). EMNLP 2022 findings (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Shoutao Guo, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2022-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2022.findings-emnlp.166) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Wait-info)<br><br>

[Turning Fixed to Adaptive: Integrating Post-Evaluation into Simultaneous Machine Translation](https://aclanthology.org/2022.findings-emnlp.167.pdf). EMNLP 2022 findings (<font color=red>CCF-B</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2022-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2022.findings-emnlp.167) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/PED-SiMT)<br><br>

[Modeling Dual Read/Write Paths for Simultaneous Machine Translation](https://aclanthology.org/2022.acl-long.176.pdf). ACL 2022 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2022-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2022.acl-long.176) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Dual-Path)<br><br>

[Reducing Position Bias in Simultaneous Machine Translation with Length-Aware Framework](https://aclanthology.org/2022.acl-long.467.pdf). ACL 2022 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2022-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2022.acl-long.467)<br><br>

[Gaussian Multi-head Attention for Simultaneous Machine Translation](https://aclanthology.org/2022.findings-acl.238.pdf). ACL 2022 findings (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/ACL_2022-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2022.findings-acl.238) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/GMA)<br><br>

## 2021
[Universal Simultaneous Machine Translation with Mixture-of-Experts Wait-k Policy](https://aclanthology.org/2021.emnlp-main.581.pdf). EMNLP 2021 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2021-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2021.emnlp-main.581) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/MoE-Waitk)<br><br>

[Modeling Concentrated Cross-Attention for Neural Machine Translation with Gaussian Mixture Model](https://aclanthology.org/2021.findings-emnlp.121.pdf). EMNLP 2021 findings (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/EMNLP_2021-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2021.findings-emnlp.121)<br><br>

[Future-Guided Incremental Transformer for Simultaneous Translation](https://arxiv.org/pdf/2012.12465.pdf). AAAI 2021 **<font color=red>Oral</font>** (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng, Liangyou Li<br>
[![paper](https://img.shields.io/badge/AAAI_2021-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2012.12465)<br><br>

[ICT’s System for AutoSimTrans 2021: Robust Char-Level Simultaneous Translation](https://aclanthology.org/2021.autosimtrans-1.1.pdf). AutoSimTrans@NAACL 2021 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; [![paper](https://img.shields.io/badge/NAACL_2021-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2021.autosimtrans-1.1)<br><br>


# 🏆 Honors and Awards
- [2022]	ICT's Special Scholarship (Xia Peisu Award) (计算所 所长特别奖(夏培肃奖)) [Highest award in ICT/CAS, **<font color=red>Top 2</font>**]
- [2022]	National Scholarship (国家奖学金)
- [2021]	First place in the streaming track of AutoSimTrans 2021 (organized by Baidu/Huawei/Google)
- [2020]	Beijing Outstanding Graduates Award (北京市优秀毕业生)
- [2018]	Beijing Merit Student (北京市三好学生)
- [2017]	National Scholarship (国家奖学金)

# 👏 Services
- **Area Chair** of ACL/EACL/NAACL ARR 2023 
- **Reviewer** of ACL/EMNLP/COLING/NAACL/EACL/NeurIPS, Computing Survey
- **Session Chair** of Student Seminar in [CCL 2024](http://cips-cl.org/static/CCL2024/index.html)
- **Session Chair** of Student Seminar in [YSSNLP 2024](https://liip.kust.edu.cn/yssnlp/yssnlp.html)
- 中国中文信息学会青年工作委员会 **学生执委会主任** 2020-2024
- **Programming Chair** of [CSSNLP](https://conference.cipsc.org.cn/cssnlp/) 2020/2021/2023

# 📖 Educations
- *2020.06 - now*: Ph.D. Candidate. Nature language processing. [Key Laboratory of Intelligent Information Processing](http://iip.ict.ac.cn/), [Institute of Computing Technology](https://www.cas.cn/), [Chinese Academy of Sciences](https://www.cas.cn/).
- *2016.09 - 2020.06*: Bachelor's degree. Computer science and technology. [Beijing University of Posts and Telecommunications](http://www.bupt.edu.cn/).

# 💬 Invited Talks
- "大模型时代的科研选题和实践分享" on MLNLP Academic Seminar [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/MLNLP_%E5%A4%A7%E6%A8%A1%E5%9E%8B%E6%97%B6%E4%BB%A3%E7%9A%84%E7%A7%91%E7%A0%94%E9%80%89%E9%A2%98%E5%92%8C%E5%AE%9E%E8%B7%B5%E5%88%86%E4%BA%AB_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "跨语言对齐增强大模型——百聆" on AI TIME 大模型嘉年华 [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/AI-Time%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%98%89%E5%B9%B4%E5%8D%8E_%E8%B7%A8%E8%AF%AD%E8%A8%80%E5%AF%B9%E9%BD%90%E5%A4%A7%E6%A8%A1%E5%9E%8B_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://www.bilibili.com/video/BV1yt4y1Z7Ck/?spm_id_from=333.999.0.0)]
- "如何在大模型时代找到科研切入点？" on CCMT 2023 [[Slides](https://zhangshaolei1998.github.io/slides/CCMT%E5%AD%A6%E7%94%9F%E8%AE%BA%E5%9D%9B_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://www.bilibili.com/video/BV1TW4y1F7uD/)]
- "从机器翻译到同声传译：挑战与进展" on MLNLP Academic Seminar [[Slides](https://zhangshaolei1998.github.io/slides/MLNLP%E5%AD%A6%E6%9C%AF%E7%A0%94%E8%AE%A8%E4%BC%9A_%E5%90%8C%E5%A3%B0%E4%BC%A0%E8%AF%91%E7%BB%BC%E8%BF%B0_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://link.zhihu.com/?target=http%3A//www.bilibili.com/video/BV1dr4y1W7E9)]
- AI Time Youth Talk for ICLR 2023 [[Video](https://www.bilibili.com/video/BV1Wk4y1W7yr/?spm_id_from=333.999.0.0&vd_source=c899334e93a187eda3344c9e3cbb3c9a)]
- Share talk in ByteDance, Huawei, Tencent, Li Auto

# 💻 Internships
- *2019.12 - 2021.12*, Huawei Noah's Ark Lab, industry-university-research collaboration project, China.

<a href='https://clustrmaps.com/site/1bx1j'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=300&t=tt&d=f6ObyrbVLY65qa_IZr0teL9UER09Q1bLih8TUF5yekA'/></a>
