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

**<font color=black>Shaolei Zhang</font>** (**<font color=black>张绍磊</font>**) is a fifth-year Ph.D. candidate (2020-2025) in [Key Laboratory of Intelligent Information Processing](http://iip.ict.ac.cn/), [Institute of Computing Technology](https://www.cas.cn/), [Chinese Academy of Sciences](https://www.cas.cn/) (中国科学院计算技术研究所), advised by professor [Yang Feng (冯洋)](https://people.ucas.edu.cn/~yangfeng?language=en). He received his bachelor's degree from [Beijing University of Posts and Telecommunications](http://www.bupt.edu.cn/) in 2020, majoring in computer science and technology (北京邮电大学计算机科学与技术实验班). 

His research interests include nature language processing, <font color=red>simultaneous model of text/speech</font> and <font color=blue>large language model</font>. He has published over **20 papers** at the top international AI/NLP conferences such as ACL, NeurIPS, ICLR, AAAI. He won the first place in the streaming transcription track of AutoSimTrans 2021. He has served as Area Chair of ACL/EACL/NAACL ARR 2023 and Reviewer of Top AI/NLP conferences.

> I'm willing to communicate and share my research, and interested in opportunities in the industry, academia or postdoc. If you would like to connect with me, please feel free to reach out via Email `zhangshaolei20z@ict.ac.cn` or WeChat `zhangshaolei0331`.


# 🔥 News
- *2024.05*: &nbsp;🎉	<font color=red>1 paper</font> is accepted by AAAI 2025!
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
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Multilingual LLM</div><img src='images/bayling.png' alt="sym" width="100%">

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

- BayLing (百聆) is a LLM equipped with advanced language alignments.
- BayLing is the first research to <font color=blue>use language alignments to enhance LLM's multilingual capabilities</font>.
- BayLing is selected for inclusion in the [2022-2023 Top 100 Opensource achievements: <font color=red>Open100 (2022-2023)</font>](https://www.benchcouncil.org/evaluation/opencs/annual.html), launched by the International Open Benchmark Council (BenchCouncil).
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Vision</div><img src='images/llava_mini.png' alt="sym" width="100%">

<details>
<summary>Demo</summary>
  <img src="images/llava_mini.gif" alt="img" width="100%" />
</details>

</div>
</div>
<div class='paper-box-text' markdown="1">

[LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One Vision Token](https://arxiv.org/abs/2501.03895) \\
**Shaolei Zhang**, Qingkai Fang, Zhe Yang, Yang Feng

[![arXiv](https://img.shields.io/badge/Paper-Preprint_2025-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2501.03895) [![model](https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-Models-blue.svg)](https://huggingface.co/ICTNLP/llava-mini-llama-3.1-8b) [![](https://img.shields.io/github/stars/ictnlp/LLaVA-Mini?style=social&label=Code+Stars)](https://github.com/ictnlp/StreamSpeech)

- LLaVA-Mini is a <font color=red>unified large multimodal model</font> that can support the understanding of images, high-resolution images, and videos in <font color=red>an efficient manner</font>.
- LLaVA-Mini only requires 1 token to represent each image, which improves the efficiency of image and video understanding, including:
  - **Computational effort**: <font color=blue>77% FLOPs</font> reduction;
  - **Response latency**: reduce from 100 milliseconds to <font color=blue>40 milliseconds</font>;
  - **VRAM memory usage**: reduce from 360 MB/image to <font color=blue>0.6 MB/image</font>, support <font color=blue>3-hour video processing</font>;
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
- StreamSpeech can present intermediate results (i.e., ASR or translation results) during simultaneous translation, offering a more comprehensive <font color=blue>low-latency communication experience</font> .
- Get over <font color=red>500 reposts</font> and <font color=red>300K views</font> on [Twitter](https://x.com/search?q=StreamSpeech)!
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Trustworthy LLM</div><img src='images/truthx.png' alt="sym" width="100%">

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
- TruthX can control LLMs to <font color=blue>generate truthful or hallucinatory responses by editing only a vector in truthful space.
- On [TruthfulQA benchmark](https://paperswithcode.com/sota/question-answering-on-truthfulqa), TruthX yields an average enhancement of 20% in truthfulness across 13 LLMs.  <font color=red>#Ranked 2 behind GPT-4</font>.
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

## 2025

- [LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One Vision Token](https://arxiv.org/pdf/2501.03895). &nbsp; Preprint 2025.<br>
Tian Yu, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_Preprint_2025-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2501.03895) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/LLaVA-Mini) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/llava-mini-llama-3.1-8b)<br>

- [Large Language Models Are Read/Write Policy-Makers for Simultaneous Generation](https://arxiv.org/pdf/2501.00868). &nbsp; AAAI 2025. (<font color=red>CCF-A</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Zhengrui Ma, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_AAAI_2025-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2501.00868) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/LSG)<br>


## 2024

- [Auto-RAG: Autonomous Retrieval-Augmented Generation for Large Language Models](https://arxiv.org/pdf/2411.19443). &nbsp; Preprint 2024.<br>
Tian Yu, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_Preprint_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2411.19443) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Auto-RAG) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/Auto-RAG-Llama-3-8B-Instruct)<br>

- [BayLing 2: A Multilingual Large Language Model with Efficient Language Alignment](https://arxiv.org/pdf/2411.16300). &nbsp; Preprint 2024.<br>
**Shaolei Zhang**, Kehao Zhang, Qingkai Fang, Shoutao Guo, Yan Zhou, Xiaodong Liu, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_Preprint_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2411.16300) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BayLing) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://aicloud.oneainexus.cn:30013/bayling2/#/bayling2) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/bayling-2-llama-3-8b)<br>

- [LLaMA-Omni: Seamless Speech Interaction with Large Language Models](https://arxiv.org/pdf/2409.06666). &nbsp; Preprint 2024.<br>
Qingkai Fang, Shoutao Guo, Yan Zhou, Zhengrui Ma, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_Preprint_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2409.06666) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/LLaMA-Omni) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/Llama-3.1-8B-Omni)<br>

- [TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space](https://arxiv.org/pdf/2402.17811.pdf). &nbsp; ACL 2024 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Tian Yu, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2402.17811) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/TruthX) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://ictnlp.github.io/TruthX-site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/Llama-2-7b-chat-TruthX) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/101796-truthx-alleviating-hallucinations-by-editing-large-language-models-in-truthful-space)<br>

- [StreamSpeech: Simultaneous Speech-to-Speech Translation with Multi-task Learning](https://arxiv.org/pdf/2406.03049). &nbsp; ACL 2024 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Qingkai Fang, Shoutao Guo, Zhengrui Ma, Min Zhang, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2406.03049) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/StreamSpeech) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://ictnlp.github.io/StreamSpeech-site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/StreamSpeech_Models) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/102738-streamspeech-simultaneous-speech-to-speech-translation-with-multi-task-learning)<br>

- [Truth-Aware Context Selection: Mitigating Hallucinations of Large Language Models Being Misled by Untruthful Contexts](https://arxiv.org/pdf/2403.07556.pdf). &nbsp; ACL 2024 findings (<font color=red>CCF-A</font>).<br>
Tian Yu, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2403.07556) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/TACS) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/TACS_Truth_Detection_Classifiers) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/102020-truth-aware-context-selection-mitigating-hallucinations-of-large-language-models-being-misled-by-untruthful-contexts)<br>

- [Can We Achieve High-quality Direct Speech-to-Speech Translation Without Parallel Speech Data?](https://arxiv.org/pdf/2406.07289) &nbsp; ACL 2024 (<font color=red>CCF-A</font>).<br>
Qingkai Fang, **Shaolei Zhang**, Zhengrui Ma, Min Zhang, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2406.07289) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/ComSpeech) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://ictnlp.github.io/ComSpeech-Site/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/ComSpeech_Models) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/102717-can-we-achieve-high-quality-direct-speech-to-speech-translation-without-parallel-speech-dataquestion)<br>

- [Decoder-only Streaming Transformer for Simultaneous Translation](https://arxiv.org/pdf/2406.03878). &nbsp; ACL 2024 (<font color=red>CCF-A</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2406.03878) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/DST) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/DST) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/102737-decoder-only-streaming-transformer-for-simultaneous-translation)<br>

- [A Non-autoregressive Generation Framework for End-to-End Simultaneous Speech-to-Any Translation](https://arxiv.org/pdf/2406.06937). &nbsp; ACL 2024 (<font color=red>CCF-A</font>).<br>
Zhengrui Ma, Qingkai Fang, **Shaolei Zhang**, Shoutao Guo, Min Zhang, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2406.06937) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/NAST-S2x) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](https://nast-s2x.github.io/) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/NAST-S2X)<br>

- [Agent-SiMT: Agent-assisted Simultaneous Machine Translation with Large Language Models](https://arxiv.org/pdf/2406.06910). &nbsp; Preprint 2024.<br>
Shoutao Guo, **Shaolei Zhang**, Zhengrui Ma, Min Zhang, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_Preprint_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2406.06910) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/SiLLM)<br>

- [Glancing Future for Simultaneous Machine Translation](https://arxiv.org/pdf/2309.06179.pdf). &nbsp; ICASSP 2024 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ICASSP_2024-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2309.06179) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Glance-SiMT)<br>


## 2023
- [BayLing: Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models](https://arxiv.org/abs/2306.10968).  &nbsp; Preprint 2023.<br>
**Shaolei Zhang**, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_Preprint_2023-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2306.10968) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BayLing) [![project](https://img.shields.io/badge/Project-darkblue.svg?style=plastic&logo=google-home)](http://nlp.ict.ac.cn/bayling) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://huggingface.co/ICTNLP/bayling-13b-v1.1)<br>

- [Unified Segment-to-Segment Framework for Simultaneous Sequence Generation](https://openreview.net/pdf?id=GuErIOGLie). &nbsp; NeurIPS 2023 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_NeurIPS_2023-b31b1b.svg?style=plastic)](https://openreview.net/pdf?id=GuErIOGLie) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Seg2Seg) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://nips.cc/virtual/2023/poster/72184)<br>

- [Non-autoregressive Streaming Transformer for Simultaneous Translation](https://aclanthology.org/2023.emnlp-main.314.pdf). &nbsp; EMNLP 2023 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
Zhengrui Ma, **Shaolei Zhang**, Shoutao Guo, Chenze Shao, Min Zhang, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2023-b31b1b.svg?style=plastic)](https://aclanthology.org/2023.emnlp-main.314) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/NAST) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/88640-non-autoregressive-streaming-transformer-for-simultaneous-translation)<br>

- [Simultaneous Machine Translation with Tailored Reference](https://aclanthology.org/2023.findings-emnlp.202.pdf). &nbsp; EMNLP 2023 findings (<font color=red>CCF-B</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2023-b31b1b.svg?style=plastic)](https://aclanthology.org/2023.findings-emnlp.202) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Tailored-Ref) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/89518-simultaneous-machine-translation-with-tailored-reference)<br>

- [End-to-End Simultaneous Speech Translation with Differentiable Segmentation](https://aclanthology.org/2023.findings-acl.485.pdf). &nbsp; ACL 2023 findings (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2023-b31b1b.svg?style=plastic)](https://aclanthology.org/2023.findings-acl.485) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/DiSeg)<br>

- [Learning Optimal Policy for Simultaneous Machine Translation via Binary Search](https://aclanthology.org/2023.acl-long.130.pdf). &nbsp; ACL 2023 (<font color=red>CCF-A</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2023-b31b1b.svg?style=plastic)](https://aclanthology.org/2023.acl-long.130) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/BS-SiMT) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/76669-learning-optimal-policy-for-simultaneous-machine-translation-via-binary-search)<br>

- [Hidden Markov Transformer for Simultaneous Machine Translation](https://openreview.net/pdf?id=9y0HFvaAYD6). &nbsp; ICLR 2023 **<font color=red>Spotlight</font>**.<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ICLR_2023-b31b1b.svg?style=plastic)](https://openreview.net/pdf?id=9y0HFvaAYD6) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/HMT) [![model](https://img.shields.io/badge/%F0%9F%A4%97_Models-orange.svg?style=plastic)](https://github.com/ictnlp/HMT) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://iclr.cc/virtual/2023/poster/11939)<br>

## 2022
- [Information-Transport-based Policy for Simultaneous Translation](https://aclanthology.org/2022.emnlp-main.65.pdf). &nbsp; EMNLP 2022 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2022-b31b1b.svg?style=plastic)](https://aclanthology.org/2022.emnlp-main.65) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/ITST) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/65316-information-transport-based-policy-for-simultaneous-translation)<br>

- [Wait-info Policy: Balancing Source and Target at Information Level for Simultaneous Machine Translation](https://aclanthology.org/2022.findings-emnlp.166.pdf). &nbsp; EMNLP 2022 findings (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Shoutao Guo, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2022-b31b1b.svg?style=plastic)](https://aclanthology.org/2022.findings-emnlp.166) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Wait-info) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/65319-wait-info-policy-balancing-source-and-target-at-information-level-for-simultaneous-machine-translation)<br>

- [Turning Fixed to Adaptive: Integrating Post-Evaluation into Simultaneous Machine Translation](https://aclanthology.org/2022.findings-emnlp.167.pdf). &nbsp; EMNLP 2022 findings (<font color=red>CCF-B</font>).<br>
Shoutao Guo, **Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2022-b31b1b.svg?style=plastic)](https://aclanthology.org/2022.findings-emnlp.167) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/PED-SiMT) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/65320-turning-fixed-to-adaptive-integrating-post-evaluation-into-simultaneous-machine-translation)<br>

- [Modeling Dual Read/Write Paths for Simultaneous Machine Translation](https://aclanthology.org/2022.acl-long.176.pdf). &nbsp; ACL 2022 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2022-b31b1b.svg?style=plastic)](https://aclanthology.org/2022.acl-long.176) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/Dual-Path) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/50503-modeling-dual-readdashwrite-paths-for-simultaneous-machine-translation)<br>

- [Reducing Position Bias in Simultaneous Machine Translation with Length-Aware Framework](https://aclanthology.org/2022.acl-long.467.pdf). &nbsp; ACL 2022 (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2022-b31b1b.svg?style=plastic)](https://aclanthology.org/2022.acl-long.467) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/50584-reducing-position-bias-in-simultaneous-machine-translation-with-length-aware-framework)<br>

- [Gaussian Multi-head Attention for Simultaneous Machine Translation](https://aclanthology.org/2022.findings-acl.238.pdf). &nbsp; ACL 2022 findings (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_ACL_2022-b31b1b.svg?style=plastic)](https://aclanthology.org/2022.findings-acl.238) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/GMA) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/50061-gaussian-multi-head-attention-for-simultaneous-machine-translation)<br>

## 2021
- [Universal Simultaneous Machine Translation with Mixture-of-Experts Wait-k Policy](https://aclanthology.org/2021.emnlp-main.581.pdf). &nbsp; EMNLP 2021 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2021-b31b1b.svg?style=plastic)](https://aclanthology.org/2021.emnlp-main.581) [![github](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/ictnlp/MoE-Waitk) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/37449-universal-simultaneous-machine-translation-with-mixture-of-experts-wait-k-policy)<br>

- [Modeling Concentrated Cross-Attention for Neural Machine Translation with Gaussian Mixture Model](https://aclanthology.org/2021.findings-emnlp.121.pdf). &nbsp; EMNLP 2021 findings (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_EMNLP_2021-b31b1b.svg?style=plastic)](https://aclanthology.org/2021.findings-emnlp.121) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://underline.io/lecture/38411-modeling-concentrated-cross-attention-for-neural-machine-translation-with-gaussian-mixture-model)<br>

- [Future-Guided Incremental Transformer for Simultaneous Translation](https://arxiv.org/pdf/2012.12465.pdf). &nbsp; AAAI 2021 **<font color=red>Oral</font>** (<font color=red>CCF-A</font>).<br>
**Shaolei Zhang**, Yang Feng, Liangyou Li  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_AAAI_2021-b31b1b.svg?style=plastic)](https://arxiv.org/pdf/2012.12465) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://slideslive.com/38948467/futureguided-incremental-transformer-for-simultaneous-translation?ref=account-79851-presentations)<br>

- [ICT's System for AutoSimTrans 2021: Robust Char-Level Simultaneous Translation](https://aclanthology.org/2021.autosimtrans-1.1.pdf). &nbsp; AutoSimTrans@NAACL 2021 **<font color=red>Oral</font>** (<font color=red>CCF-B</font>).<br>
**Shaolei Zhang**, Yang Feng  &nbsp; <br>[![paper](https://img.shields.io/badge/%F0%9F%93%84_NAACL_2021-b31b1b.svg?style=plastic)](https://aclanthology.org/2021.autosimtrans-1.1) [![github](https://img.shields.io/badge/Docker-skyblue.svg?style=plastic&logo=docker)](https://hub.docker.com/repository/docker/zhangshaolei1998/auto_simtrans2021_final/general) [![pre](https://img.shields.io/badge/%F0%9F%8E%9E_Presentation-darkgreen.svg?style=plastic)](https://autosimtrans.github.io/2021/assets/docs/slides2021/ict_ZhangShaolei_AutoSimTrans_Slides.pdf)<br>


# 🏆 Honors and Awards
- [2022]	ICT's Special Scholarship (Xia Peisu Award) (计算所 所长特别奖(夏培肃奖)) [Highest award in ICT/CAS, **<font color=red>Top 2</font>**]
- [2022]	National Scholarship (国家奖学金)
- [2021]	**<font color=red>First place</font>** in the streaming track of [AutoSimTrans 2021](https://autosimtrans.github.io/2021/program.html) (organized by Baidu/Huawei/Google)
- [2020]	Beijing Outstanding Graduates Award (北京市优秀毕业生)
- [2018]	Beijing Merit Student (北京市三好学生)
- [2017]	National Scholarship (国家奖学金)

# 👏 Services
- **Area Chair** of ACL/EACL/NAACL ARR 2023 
- **Reviewer** of ACL/EMNLP/COLING/NAACL/EACL/NeurIPS/ICLR/ICML, Computing Survey
- **Session Chair** of Student Seminar in [CCL 2024](http://cips-cl.org/static/CCL2024/index.html)
- **Session Chair** of Student Seminar in [YSSNLP 2024](https://liip.kust.edu.cn/yssnlp/yssnlp.html)
- 中国中文信息学会青年工作委员会 **学生执委会主任** 2020-2024
- **Programming Chair** of [CSSNLP](https://conference.cipsc.org.cn/cssnlp/) 2020/2021/2023

# 📖 Educations
- *2020.06 - 2025.06*: Ph.D. Candidate. Nature language processing. [Key Laboratory of Intelligent Information Processing](http://iip.ict.ac.cn/), [Institute of Computing Technology](https://www.cas.cn/), [Chinese Academy of Sciences](https://www.cas.cn/).
- *2016.09 - 2020.06*: Bachelor's degree. Computer science and technology. [Beijing University of Posts and Telecommunications](http://www.bupt.edu.cn/).

# 💬 Invited Talks
- "浅谈大模型时代的研究转变：选题和实践" on ASCII-116 [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/ASCII116_%E6%B5%85%E8%B0%88%E5%A4%A7%E6%A8%A1%E5%9E%8B%E6%97%B6%E4%BB%A3%E7%9A%84%E7%A0%94%E7%A9%B6%E8%BD%AC%E5%8F%98_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "如何在大模型技术迭代中把握科研节奏" on IMLIP 2024 [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/IMLIP2024_%E5%A6%82%E4%BD%95%E5%9C%A8%E5%A4%A7%E6%A8%A1%E5%9E%8B%E6%8A%80%E6%9C%AF%E8%BF%AD%E4%BB%A3%E4%B8%AD%E6%8A%8A%E6%8F%A1%E7%A7%91%E7%A0%94%E8%8A%82%E5%A5%8F_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "流式翻译进展分享" share talk in Li Auto [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/%E7%90%86%E6%83%B3%E5%88%86%E4%BA%AB_%E6%B5%81%E5%BC%8F%E7%BF%BB%E8%AF%91%E8%BF%9B%E5%B1%95%E5%88%86%E4%BA%AB_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "缓解大语言模型幻觉：从内部表示视角" share talk in Tencent [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/%E8%85%BE%E8%AE%AF%E5%88%86%E4%BA%AB_%E7%BC%93%E8%A7%A3%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E5%B9%BB%E8%A7%89_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "大模型时代的科研选题和实践分享" on MLNLP Academic Seminar [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/MLNLP_%E5%A4%A7%E6%A8%A1%E5%9E%8B%E6%97%B6%E4%BB%A3%E7%9A%84%E7%A7%91%E7%A0%94%E9%80%89%E9%A2%98%E5%92%8C%E5%AE%9E%E8%B7%B5%E5%88%86%E4%BA%AB_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)]
- "跨语言对齐增强大模型——百聆" on AI TIME 大模型嘉年华 [[Slides](https://github.com/zhangshaolei1998/zhangshaolei1998.github.io/blob/main/slides/AI-Time%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%98%89%E5%B9%B4%E5%8D%8E_%E8%B7%A8%E8%AF%AD%E8%A8%80%E5%AF%B9%E9%BD%90%E5%A4%A7%E6%A8%A1%E5%9E%8B_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://www.bilibili.com/video/BV1yt4y1Z7Ck/?spm_id_from=333.999.0.0)]
- "如何在大模型时代找到科研切入点？" on CCMT 2023 [[Slides](https://zhangshaolei1998.github.io/slides/CCMT%E5%AD%A6%E7%94%9F%E8%AE%BA%E5%9D%9B_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://www.bilibili.com/video/BV1TW4y1F7uD/)]
- "从机器翻译到同声传译：挑战与进展" on MLNLP Academic Seminar [[Slides](https://zhangshaolei1998.github.io/slides/MLNLP%E5%AD%A6%E6%9C%AF%E7%A0%94%E8%AE%A8%E4%BC%9A_%E5%90%8C%E5%A3%B0%E4%BC%A0%E8%AF%91%E7%BB%BC%E8%BF%B0_%E5%BC%A0%E7%BB%8D%E7%A3%8A.pdf)] [[Video](https://link.zhihu.com/?target=http%3A//www.bilibili.com/video/BV1dr4y1W7E9)]
- AI Time Youth Talk for ICLR 2023 [[Video](https://www.bilibili.com/video/BV1Wk4y1W7yr/?spm_id_from=333.999.0.0&vd_source=c899334e93a187eda3344c9e3cbb3c9a)]
- Internal share talks in ByteDance, Huawei, Tencent, Li Auto

# 💻 Internships
- *2019.12 - 2021.12*, Huawei Noah's Ark Lab, industry-university-research collaboration project, China.

<a href='https://clustrmaps.com/site/1bx1j'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=300&t=tt&d=f6ObyrbVLY65qa_IZr0teL9UER09Q1bLih8TUF5yekA'/></a>
