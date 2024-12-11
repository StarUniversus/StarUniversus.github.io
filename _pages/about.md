---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======

I graduated from Northeastern University and have been working in the university's Computer Vision Laboratory since 2019, focusing on medical image analysis, multimodal large models, and agent-based systems.

Publications
======

You can also find a list of my published work on <a href="https://scholar.google.com/citations?user=JpQ3YxkAAAAJ&hl" target="_blank">Google Scholar</a>.
### Medical Image Analysis
1. *Global contrast-masked autoencoders are powerful pathological representation learners* <br/>
Hao Quan<sup>\*</sup>, **Xingyu Li**<sup>\*</sup> (co-first author), Weixing Chen, Qun Bai, Mingchen Zou, Ruijie Yang, Tingting Zheng, Ruiqun Qi, Xinghua Gao, Xiaoyu Cui<br/>
*<a href="https://www.sciencedirect.com/science/article/abs/pii/S0031320324004965" target="_blank">Pattern Recognition (PR)(2024)</a>.*
[<a href="{{base.url}}/files/gcmae.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/gcmae.bib" target="_blank">BibTeX</a>] 
[<a href="https://github.com/StarUniversus/gcmae" target="_blank">Source Code</a>]

1. *Decoding Expertise from Pathologists’ Diagnostic Processes on Whole Slide Images*  
*Nature Communications (revision submission)*
[<a href="{{base.url}}/files/PEAN.pdf" target="_blank">PDF</a>] 
[<a href="https://github.com/MasyerN/PEAN" target="_blank">Source Code</a>]

1. *Discriminating Chromophobe RCC from Oncocytoma: A Transformer-based Approach Leveraging the Subtleties of Nuclear Structures within Kidney Tumors*<br/>
Jing Yang, **Xingyu Li**, Hongjiu Ren, Yanmei Zhu, Qimin Wang, Ruiqun Qi, Xiaoyu Cui and Huamao Jiang <br/>
[<a href="{{base.url}}/files/Kidney.pdf" target="_blank">PDF</a>] 

1. *MedConvMamba: Enhancing Medical Image Classification by Integrating Convolutional Neural Networks with Mamba for Local Feature Extraction and Global Context Awareness* <br/>
Hui Qu, Jiaxi Liu, Mingchen Zou, **Xingyu Li**, Canwei Dong, Xiaoyu Cui. <br/>
*IEEE Journal of Biomedical and Health Informatics (under review) (JBHI) (2024)*
[<a href="{{base.url}}/files/MedConvMamba.pdf" target="_blank">PDF</a>] 

1. *Attention-based Feature Distillation MultiInstance Learning for Pathological Image
Classification* <br/>
Tianh Nan, **Xy Li**, H Quan, K Yang, Xy Cui, <br/>
*IEEE Journal of Biomedical and Health Informatics (under review) (JBHI) (2024)*
[<a href="{{base.url}}/files/AFD-MIL.pdf" target="_blank">PDF</a>] 
[<a href="https://github.com/MasyerN/AFD-MIL" target="_blank">Source Code</a>]


### MLLM&Agents
1. *CorrectFlow: On-the-Spot Correction for Multimodal Reasoning with
Multi-Agent Collaboration* <br/>
Xiao Dong, Pan Zhou, **Xingyu Li**, Zheng Chong, Yuhao Cheng, Jianxing Yu, Jian Yin, Xiaodan Liang <br/>
*CVPR2025 (submission)*
[<a href="{{base.url}}/files/CorrectFlow.pdf" target="_blank">PDF</a>] 


1. *ACTIONFILLER: FILL-IN-THE-BLANK PROMPTING FOR OS AGENTS* <br/>
Xiao Dong, Zijun Zhang, **Xingyu Li**, Yuhao Cheng, Jianxing Yu, Jian Yin, Pan Zhou, Xiaodan Liang <br/>
*ICLR 2025 (submission)*
[<a href="{{base.url}}/files/ActionFiller.pdf" target="_blank">PDF</a>] 

Projects
======
{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}
## <a href='{{base.url}}/projects/ep'>AI Pathology Image Analysis System</a>
The AI Pathology Image Analysis System is an intelligent pathology imaging tool integrated with eye-tracking technology. It efficiently processes and analyzes pathology slide images. <br/><img src='/images/ep.svg' alt='EP' width='980' height='735'>



Competitions&Awards
======
* <a href='{{base.url}}/images/bmedesign.png'>National Undergraduate Biomedical Engineering Innovation Design Competition -- National Second Prize</a>

* <a href='{{base.url}}/images/isicdm2023.png'>ISICDM 2023 Chest X-ray Posture Assessment Competition: The Second Prize</a>

* <a href='{{base.url}}/images/neu.png'>Northeastern University Technology Innovation Individual</a>

Invention Patent
======
* A Method for Analyzing and Evaluating Medical Imaging Interpretation Skills
<img src='/images/patent.png' alt='EP' width='400' height='200'>