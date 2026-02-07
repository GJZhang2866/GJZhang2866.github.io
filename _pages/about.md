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

I am pursuing my PhD degree (2022~) at [Shanxi University](https://www.sxu.edu.cn/), supervised by Prof. [Hu Zhang](https://cs.sxu.edu.cn/faculty/professor/3367/index.htm). Before that, I received a B.S. degree from Shanxi University in 2020, majoring in computer science and technology. 

My research interests include Information Extraction, Knowledge Graphs and Language Models.
I have published some academic papers at the top international conferences like ACL, AAAI, EMNLP, COLING, ICASSP, ICONLP, IJCNN and journals like *Journal of Peking University*, *Journal of Chinese Information Processing*, *Information Science* and TALLIP. Additionally, I participated in natural language processing evaluations related to MRC and won the national seconde prize (CAIL 2021) and  the national third prize (CAIL 2020).

Be free to contact me by <a href="mailto:zgj2866@gmail.com">email</a> if you are interested in discussing or collaborating with me.
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script> 


# 🔥 News
- *2026.01*: &nbsp; 🎉 One paper on Explainable Question Answering is accepted by IPM. (CCF-B)
- *2026.01*: &nbsp; 🎉 One paper on Few-shot Relation Extraction is accepted by ICASSP 2026.  (CCF-B)
- *2025.11*: &nbsp; 🎉 One paper on Event Extraction is accepted by AAAI 2026 (Thanks to **Ya Su**'s prayers!!!). [\[Code\]](https://github.com/GJZhang2866/GenExtract).(CCF-A)
- *2025.11*: &nbsp; 🎨 We presented a poster (by our junior labmate **Ya Su**) and gave an oral presentation (by our junior labmate **Boxiang Ma**)  at EMNLP 2025 in Suzhou, China.
- *2025.08*: &nbsp; 🎉 One paper on Event Causality Identification is accepted by [EMNLP 2025](https://aclanthology.org/2025.emnlp-main.616/).  (CCF-B)
- *2024.12*: &nbsp; 🎉 One paper on Explainable Question Answering is accepted by [Information Science](https://www.sciencedirect.com/science/article/abs/pii/S0020025524016773). (CCF-B)
- *2024.11*: &nbsp; 🎉 One paper on Event Causality Identification is accepted by [COLING 2025](https://aclanthology.org/2025.coling-main.495/). (CCF-B)
- *2024.08*: &nbsp; 🎉 One paper on Event Extraction is accepted by TALLIP.(CCF-C)
- *2024.05*: &nbsp; 🎉 One paper on Event Extraction is accepted in [ACL 2024 Main Coference](https://2024.aclweb.org/). [\[Code\]](https://github.com/GJZhang2866/HMPEAE). (CCF-A)
- *2024.04*: &nbsp; 🎉 One paper on Graph Representation Learning is accepted in IJCNN 2024. (CCF-C)
- *2023.10*: &nbsp; 🎉 We share our Outstanding Paper report on [CCKS 2023](https://sigkg.cn/ccks2023/program/).
- *2023.08*: &nbsp; 🎉 Two papers on [Text Summarization](https://link.springer.com/chapter/10.1007/978-981-99-8148-9_16) and [Relation Extraction](https://link.springer.com/chapter/10.1007/978-981-99-8148-9_17) are accepted in ICONLP 
- *2023.08*: &nbsp; 🎉 One Journal paper on Named Entity Recognition is accepted to the Journal of Chinese Information Processing.
- *2023.08*: &nbsp; 🎉 One Journal paper on Named Entity Recognition is accepted to the Journal of Peking University.


# 📝 Main Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IPM</div><img src='images/SRCR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SRCR: Faithful structured reasoning with curriculum reinforcement learning for explainable question answering

Yue Fan, Hu Zhang, Ru Li, **Guangjun Zhang**, Yujie Wang, Hongye Tan, Yuanlong Wang, Xiaoli Li, Jiye Liang, 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2026</div><img src='images/ICASSP-26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

QUERY-GUIDED PROTOTYPICAL LEARNING FOR FEW-SHOT DOCUMENT-LEVEL RELATION EXTRACTION

Hu Zhang, Yazhou Han, **Guangjun Zhang**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/AAAI-26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Learning to Generate and Extract: A Multi-Agent Collaboration Framework For Zero-shot Document-level Event Arguments Extraction

**Guangjun Zhang**, Hu Zhang, Yazhou Han, Yue Fan, Yuhang Shao, Ru Li, Hongye Tan
[**Project**](https://github.com/GJZhang2866/GenExtract) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a Multi-Agent Collaboration Framework for Zero-shot EAE.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/eci.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Energy-Based Contrastive Learning with Multi-Stage Knowledge Verification for Event Causality Identification](https://aclanthology.org/2025.emnlp-main.616/).

Ya Su, Hu Zhang, Yue Fan,  **Guangjun Zhang**, YuJie Wang, Ru Li, Hongye Tan
- We propose the ECI method enhanced by Dynamic Energy-Based Contrastive Learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2025</div><img src='images/LKCER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Event Causality Identification with LLM Knowledge and Concept-Level Event Relations](https://aclanthology.org/2025.coling-main.495/)

Ya Su,Hu Zhang, **Guangjun Zhang**, Yujie Wang, Yu Fan, Ru Li, Yuanlong Wang
- We propose the ECI method enhanced by LLM Knowledge and Concept-Level Event Relations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Infromation Science</div><img src='images/WSQG.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Weakly-supervised explainable question answering via question aware contrastive learning and adaptive gate mechanism](https://www.sciencedirect.com/science/article/abs/pii/S0020025524016773)

Yue Fan, Hu Zhang, Ru Li, Yujie Wang, **Guangjun Zhang**, Hongye Tan, Jiye Liang
- We propose a  weakly supervised XQA method, which automatically captures effective remotely supervised signals and mines evidence coupled with answers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/HPN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hyperspherical Multi-Prototype with Optimal Transport for Event Argument Extraction](https://aclanthology.org/2024.acl-long.502/)

**Guangjun Zhang**, Hu Zhang, Yujie Wang, Ru Li, Hongye Tan and Jiye Liang.

[**Project**](https://github.com/GJZhang2866/HMPEAE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel approach HMPEAE, guiding the model in learning argument representations. 
</div>
</div>


# 🎖 Honors and Awards
- *2025.06* The Second Class Award Scholarship of the Graduate School, Shanxi University, in 2025.
- *2024.06* The First Class Award Scholarship of the Graduate School, Shanxi University, in 2024.
- *2023.06* The Second Class Award Scholarship of the Graduate School, Shanxi University, in 2023.
- *2022.06* The Third Class Award Scholarship of the Graduate School, Shanxi University, in 2022.
- *2021.10* CAIL 2021 Machine Reading Comprehension, Second Prize.
- *2021.06* The Second Class Award Scholarship of the Graduate School, Shanxi University, in 2021.
- *2020.10* CAIL 2020 Machine Reading Comprehension, Third  Prize.


# 📖 Educations
- *2022.09 -*, School of Computer and Information Technology, Shanxi University. Ph.D. Student.
- *2020.09 - 2022.06*, School of Computer and Information Technology, Shanxi University. Master Student.
- *2016.09 - 2020.06*, School of Computer and Information Technology, Shanxi University. Undergraduate.
- *2013.09 - 2016.06*, No.2 Middle School of Hengshui. High school student.



