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

I am a second-year Ph.D. student at the <a href='https://www.mpu.edu.mo/'>**Macao Polytechnic University (MPU), Faculty of Applied Sciences,**</a> supervised by <a href='https://cbbio.online/shirleysiu/'>**Associate Professor Shirley W. I. Siu**</a>. My research focuses on protein–peptide interactions and computational peptide design. I was lucky to have opportunities to collaborate with <a href='https://teacher.nwpu.edu.cn/zhuhongyou.html'>**Prof. Zhuhong You**</a> and <a href='https://teacher.nwpu.edu.cn/yuanhuang.html'>**Prof. Yu-An Huang**</a>. 

For more information about our research, please visit our group web-<a href='https://cbbio.online/'>**Computational Biology and Bioinformatics (CBBio) Lab**</a>.

**Feel free to reach out to me if you have an interest in the relevant topics.**


# 🔥🔥 News

## 2026

- *2026.09*：&nbsp;🎉🎉 A paper **[Shaolong Lin et al., 2026]** is accepted by **Chemical Science** [<span style="color:red">IF:8.1, JCR Q1</span>]
- *2026.08*：&nbsp;🎉🎉 A paper **[Zhan Xinke et al., 2026]** is accepted by **Communications Chemistry** [<span style="color:red">IF:6.9, JCR Q1</span>]
- *2026.08*：&nbsp;🎉🎉 A paper **[Zang Jieying et al., 2026]** is accepted by **Wiley Interdisciplinary Reviews-Computational Molecular Science** [<span style="color:red">IF:10.85, JCR Q1</span>]
- *2026.05*: &nbsp;🎉🎉 A paper **[Liu Dongqi et al., 2026]** is published by **Journal of Chemical Information and Modeling (JCIM)** [<span style="color:red">IF:6.3, JCR Q1</span>]
- *2026.02*: &nbsp;🎉🎉 A paper **[Liu Tiantao et al., 2026]** is published by **Journal of Cheminformatics (JC)** [<span style="color:red">IF:5.7, JCR Q1</span>]
- *2026.01*: &nbsp;🎉🎉 A paper **[Ma Xiangyu  et al., 2025]** is published by **Engineering Applications of Artificial Intelligence (EAAI)** [<span style="color:red">IF:8.0, JCR Q1</span>]

## 2025

- *2025.10*: &nbsp;🎉🎉 A paper is submitted to **ChemRxiv**.
- *2025.08*: &nbsp;🎉🎉 A paper **[Zhan Xinke  et al., 2025]** is accepted by **Digital Discovery** [<span style="color:red">IF:7.1, JCR Q1</span>]
- *2025.07*: &nbsp;🎉🎉 A conference paper is accepted by **the 2025 International Conference on Intelligent Computing (ICIC)** [<span style="color:red">CCF-C</span>]
- *2025.03*: &nbsp;🎉🎉 A paper **[Liu Tiantao et al., 2025]** is accepted by **Cell Reports Physical Science (CRPS)** [<span style="color:red">IF:7.3, JCR Q1</span>]

# 📝 Publications 
Selected publications are listed below, focusing on some research tasks: Drug-target interaction prediction, anticancer peptide prediction....

## 2026

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><em>Communications Chemistry</em></div><img src='images/PepInter.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A sequence-based deep learning framework (PepInter) for protein–peptide interaction representation learning with pretrained protein language models](https://www.nature.com/articles/s42004-026-02168-3) [<span style="color:red">**https://doi.org/10.1038/s42004-026-02168-3**</span>](https://doi.org/10.1038/s42004-026-02168-3)

**Xinke Zhan**, Silong Zhai, Tiantao Liu, Shaolong Lin, Tao Bi, Bingwen Zhu, Shirley W. I. Siu

[Github Code: [**PepInter**](https://github.com/zhanxinke/PepInter.git)]

- Protein-peptide interactions are crucial for cellular functions yet identifying them systematically is hindered by scarce experimental data. Here, the authors introduce PepInter, a deep learning framework that uses pretraining on pseudo protein-peptide pairs to enhance interaction6prediction.
  
</div>
</div>


## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><em>Digital Discovery</em></div><img src='images/MAARDTI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAARDTI: A multi-perspective attention aggregating model for the prediction of drug-target interactions](https://pubs.rsc.org/en/content/articlelanding/2025/dd/d5dd00311c) [<span style="color:red">**doi:10.1039/D5DD00311C**</span>]((https://doi.org/10.1039/D5DD00311C))

**Xinke Zhan**, Tiantao Liu, Changqing Yu, Yu-An Huang, Zhuhong You, Shirley W. I. Siu

[Github Code: [**MAARDTI**](https://github.com/TorchZhan/MAARDTI)] [Zenodo Website: [**MAARDTI**](https://zenodo.org/records/16936305)]

- MAAR module that providing a more comprehensive representation of the interactions between drugs and proteins.
- The superior prediction results of our method demonstrate the effectiveness of MAARDTI in predicting DTIs. 
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><em>The 2025 ICIC</em></div><img src='images/CALM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CALM-AcPEP:Predicting Anticancer Peptides Using Cross-Attention and Pre-Trained Language Model](https://link.springer.com/chapter/10.1007/978-981-95-0030-7_19)

**Xinke Zhan**, Tiantao Liu, Pratiti Bhadra, Yu-An Huang, Zhuhong You, Shirley W. I. Siu

- A deep learning framework based on the ACmix module,Evolutionary Scale Modeling 2 (ESM2) and cross-attention.
- The results of our proposed method shows improved performance in ACP prediction.
  
</div>
</div>

## 2026
- Shaolong Lin. Task-adaptive multimodal molecular representations forstructure-sensitive property prediction, <em>**Chemical Science**</em>, 2026.09.

- Jieying Zang. [Integrative Computational Strategies for Dynamic GPCR Landscapes: From Conformational Mechanisms to Drug Design](https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/wcms.70083), <em>**Wiley Interdisciplinary Reviews-Computational Molecular Science**</em>, 2026.08.

- Dongqi Liu. [MEGCAM: MEta-Graph and Causal Attention Method for Drug Repurposing on Heterogeneous Drug–Target–Disease Knowledge Network](https://doi.org/10.1021/acs.jcim.6c00440), <em>**Journal of Chemical Information and Modeling (JCIM)**</em>, 2026.05.

- Tiantao Liu. [Enzyformer: a two-stage pretrained model for enzymatic retrosynthesis](https://link.springer.com/article/10.1186/s13321-026-01164-y), <em>**Journal of Cheminformatics (JC)**</em>, 2026.02.

- Xiangyu MA. [CrossToGene: A bidirectional cross-modality interaction framework for predicting spatial gene expression from histopathological images](https://www.sciencedirect.com/science/article/pii/S0952197625037194),<em>**Engineering Applications of Artificial Intelligence (EAAI)**</em>, 2026.01.


## 2025
- Tiantao Liu. [Data-driven revolution of enzyme catalysis from the perspective of reactions, pathways, and enzymes](https://www.cell.com/cell-reports-physical-science/fulltext/S2666-3864(25)00065-7), <em>**Cell Reports Physical Science (CRPS)**</em>, 2025.03.


# 🎖 Honors and Awards
- *2024.08*, Half-scholarship of the Macao Polytechnic University (2024-2027).

# 📖 Educations
- *2024.09 - (now)*, Ph.D. in Artificial Intelligence Driven Drug Discovery (AIDD) in Macao Polytechnic University, Macau, China.
- *2018.09 - 2021.01*, M.S. in Control Engineering in Xijing University, Xi'an, Shaanxi, China.
- *2014.09 - 2018.06*, B.S. in Engineering in Electrical Engineering and Automation (EEA) in Hubei Polytechnic University, Huangshi, Hubei, China.


# 💻 Fundings
- *2022.01 - 2023.12*, Natural Science Basic Research Program of Shaanxi: Prediction of drug-target interactions based on complex networks.

# 👨🏻‍💻 Academic Services
- Journal Reviewer:
  - *Briefings in Bioinformatics*
  - *Journal of Cheminformatics*
  - *Journal of King Saud University Computer and Information Sciences*
  - *BMC bioinformatics*
  - *Molecular Diversity*
  - *npj Systems Biology and Applications*
  - *BMC Genomics*