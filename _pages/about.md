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

I am a second-year Ph.D. student at the <a href='https://www.mpu.edu.mo/'>**Macao Polytechnic University (MPU), Faculty of Applied Sciences**</a>. My research focuses on protein–peptide interactions and computational peptide design. I am supervised by <a href='https://cbbio.online/shirleysiu/'>**Shirley W. I. Siu**</a> , and I am a member of the <a href='https://cbbio.online/'>**Computational Biology and Bioinformatics (CBBio) Lab**</a>.

For more information about our research, please visit our group website.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
- *2025.10*: &nbsp;🎉🎉 A paper is submitted to **ChemRxiv**.
- *2025.08*: &nbsp;🎉🎉 A paper is accepted by **Digital Discovery** [<span style="color:red">IF:5.6, JCR Q1</span>]
- *2025.07*: &nbsp;🎉🎉 A conference paper is accepted by **the 2025 International Conference on Intelligent Computing [ICIC 2025, <span style="color:red">CCF-C</span>]**
- *2025.03*: &nbsp;🎉🎉 A paper **[Liu et al., 2025]** is accepted by **Cell Reports Physical Science (CRPS)** [<span style="color:red">IF:7.3, JCR Q1</span>]

# 📝 Publications 
Selected publications are listed below, focusing on some research tasks: Drug-target interaction prediction, anticancer peptide prediction....

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><em>Digital Discovery</em></div><img src='images/MAARDTI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAARDTI: A multi-perspective attention aggregating model for the prediction of drug-target interactions,](https://pubs.rsc.org/en/content/articlelanding/2025/dd/d5dd00311c) [<span style="color:red">**doi:10.1039/D5DD00311C**</span>]((https://doi.org/10.1039/D5DD00311C))

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

- Tiantao Liu. [Data-driven revolution of enzyme catalysis from the perspective of reactions, pathways, and enzymes](https://www.cell.com/cell-reports-physical-science/fulltext/S2666-3864(25)00065-7), <em>**Cell Reports Physical Science (CRPS)**</em>, 2025.

# 🎖 Honors and Awards
- *2024.08*, Half-scholarship of the Macao Polytechnic University (2024-2027).
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - (now)*, Ph.D. Macao Polytechnic University, Macau, China.
- *2019.09 - 2021.01*, M.S. Xijing University, Xi'an, Shaanxi, China.
- *2014.09 - 2018.06*, B.S. Hubei Polytechnic University, Huangshi, Hubei, China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Fundings
- *2022.01 - 2023.12*, Natural Science Basic Research Program of Shaanxi: Prediction of drug-target interactions based on complex networks.