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

I am currently a 4th year (2019-2023) Ph.D. student at [Medical Mechatronics Lab](http://www.labren.org/mm/) of the Department of Biomedical Engineering, [National University of Singapore]((https://www.nus.edu.sg/)), supervised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang). Before that, I worked with Dr. Tianyiyi  He, Dr. QiongFeng Shi and [Prof. Chengkuo Lee](https://www.ece.nus.edu.sg/stfpage/elelc/bio.html) in the [Department of Electrical and Computer Engineering](https://cde.nus.edu.sg/ece/), [National University of Singapore](https://www.nus.edu.sg/) and received my M.Sc. degree in 2019. From 2014 to 2018, I studied in [Soochow University](https://www.suda.edu.cn/) and received B.Eng. degree in Information Engineering. 

My research interests are mainly about Image-based Robotic Surgery Intelligence:
(1) AI-driven multi-sensory perception to achieve surgical task automation
(2) AI-powered large-scale data analysis to enhance surgical education
(3) AI model development with human-like continuous learning / domain adaptation ability
(4) Multi-Modal: Connecting Vision and Language to Actions
(5) Data-centric AI


# 🔥 News
- *2023.05*: one paper is early accepted by MICCAI.

# 📝 Journal Publications

**1. Self-powered glove-based intuitive interface for diversified control applications in real/cyber space**, He, Tianyiyi, Zhongda Sun, Qiongfeng Shi, Minglu Zhu, David Vera Anaya, **Mengya Xu**, Tao Chen, Mehmet Rasit Yuce, Aaron Voon-Yew Thean, and Chengkuo Lee. Nano Energy
[pdf](https://www.sciencedirect.com/science/article/pii/S2211285519300771)

**2. Stent Deployment Detection Using Radio Frequency‐Based Sensor and Convolutional Neural Networks**, **Mengya Xu**, Lalithkumar Seenivasan, Leonard Leong Litt Yeo, and Hongliang Ren. Advanced Intelligent Systems 2020
[pdf](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aisy.202000092) \| [code](https://github.com/XuMengyaAmy/Stent_Deployment_DL)

**3. SIRNet: Fine-Grained Surgical Interaction Recognition**, Li, Ling, Xiaojian Li, Shuai Ding, Zhao Fang, **Mengya Xu**, Hongliang Ren, and Shanlin Yang. IEEE Robotics and Automation Letters (RA-L) 2022. 
[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9705584) \| [code](https://github.com/cynerelee/SIRNet)

**4. Confidence-Aware Paced-Curriculum Learning by Label Smoothing for Surgical Scene Understanding**, **Mengya Xu**, Mobarakol Islam, Ben Glocker and Hongliang Ren. IEEE Transactions on Automation Science and Engineering (T-ASE), 2022
[pdf](https://ieeexplore.ieee.org/abstract/document/10138463) \| [code](https://github.com/XuMengyaAmy/P-CBLS)

**5. Rethinking Feature Extraction: Gradient-based Localized Feature Extraction for End-to-End Surgical Downstream Tasks**, Winnie Pang, Mobarakol Islam, Sai Mitheran, Lalithkumar Seenivasan, **Mengya Xu**, Hongliang Ren. IEEE Robotics and Automation Letters (RA-L), 2022
[pdf](https://doi.org/10.1109/LRA.2022.3221310) \| [code](https://github.com/PangWinnie0219/GradCAMDownstreamTask)
 
**6. Curriculum-Based Augmented Fourier Domain Adaptation for Robust Medical Image Segmentation**, An Wang\*, Mobarakol Islam\*, **Mengya Xu**\*(Co-first author) and Hongliang Ren\*\*. IEEE Transactions on Automation Science and Engineering (T-ASE), 2023.
[pdf](https://arxiv.org/pdf/2306.03511.pdf) \| [code](https://github.com/lofrienger/Curri-AFDA)

Under Review:
**6. Privacy-Preserving Synthetic Continual Semantic Segmentation for Robotic Surgery**, **Mengya Xu**, Mobarakol Islam, Long Bai and Hongliang Ren. IEEE Transactions on Medical Imaging (TMI), 2023, 2nd revision.

**7. Surgical Blender: A Synthetic Dataset Generator for Robot-Assisted Surgery**, **Mengya Xu**, Jieming Yu, Omer Raza, An Wang, Minghung Ma, Hongliang Ren. Medical Image Analysis (MIA), 2023, under review.

**8. A Lightweight MLP-based Point-guided Segmentation Network for Ore Images**,  Yuting Peng, **Mengya Xu**, An Wang, Yang Zhang, Hongliang Ren. IEEE Transactions on Industrial Informatics (TII), 2023, under review.

**9. MRAT: Exploring Continual Surgical Image Captioning under Domain Shifts**,  **Mengya Xu**, Hongliang Ren. International Journal of Computer Assisted Radiology and Surgery (IJCAR), 2023, under review.


# 📝 Conference Publications
     
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2021</div><img src='images/M2Transformer_DAN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**1. Learning domain adaptation with model calibration for surgical report generation in robotic surgery**

**Mengya Xu**, Mobarakol Islam, Chwee Ming Lim, and Hongliang Ren
  
IEEE International Conference on Robotics and Automation (ICRA) 2021 

[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9561569) \| [code](https://github.com/XuMengyaAmy/ReportDALS)

</div>
</div>
     
     
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2021</div><img src='images/CIDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2. Class-incremental domain adaptation with smoothing and calibration for surgical report generation**

**Mengya Xu**, Mobarakol Islam, Chwee Ming Lim, and Hongliang Ren
  
Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2021

[pdf](https://arxiv.org/pdf/2107.11091.pdf) \| [Code](https://github.com/XuMengyaAmy/CIDACaptioning) \| [Poster](https://github.com/XuMengyaAmy/XuMengyaAmy.github.io/blob/main/images/poster.png)

</div>
</div>
     

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/SwinMLP_TranCAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**3. Rethinking Surgical Captioning: End-to-End Window-Based MLP Transformer Using Patches**

**Mengya Xu**, Mobarakol Islam, and Hongliang Ren
  
Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2022

[pdf](https://arxiv.org/pdf/2207.00113.pdf)] \| [Code](https://github.com/XuMengyaAmy/SwinMLP_TranCAP)

</div>
</div>

  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/single_bg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**4. Rethinking Surgical Instrument Segmentation: A Background Image Can Be All You Need**

An Wang\*, Mobarakol Islam\*, **Mengya Xu**, and Hongliang Ren\*\*
  
Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2022

[pdf](https://arxiv.org/abs/2206.11804) \| [code](https://github.com/lofrienger/Single_SurgicalScene_For_Segmentation)

</div>
</div>

**5. S<sup>2</sup>ME: Spatial-Spectral Mutual Teaching and Ensemble Learning for Scribble-supervised Polyp Segmentation**

An Wang, **Mengya Xu**, Yang Zhang, Mobarakol Islam and Hongliang Ren

Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2023, early accpeted (top 14\% of 2253 submissions)

[pdf](https://arxiv.org/pdf/2306.00451.pdf) \| [code](https://github.com/lofrienger/S2ME)

**6 Rectifying Noisy Labels with Sequential Prior: Multi-Scale Temporal Feature Affinity Learning for Robust Video Segmentation**

Beilei Cui\*, Mingqing Zhang\*, **Mengya Xu\***(Co-first author), An Wang and Hongliang Ren\*\*

Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2023.

[pdf] (https://arxiv.org/pdf/2307.05898.pdf) \| [code] (https://github.com/BeileiCui/MS-TFAL)

[pdf](https://arxiv.org/pdf/2307.05898.pdf) \| [code](https://github.com/BeileiCui/MS-TFAL)

# 📖 Educations
- *2019.08 - now*, Ph.D., Biomedic Engineering, National University of Singapore, Singapore
- *2018.08 - 2019.06*, M.Sc., Electrical Engineering, National University of Singapore, Singapore
- *2014.09 - 2018.06*, B.Eng., Information Engineering, Soochow University, Suzhou, China  (Excellent Graduates)


# 📖 Services
- 2022.07.03 - as a reviewer for  Domain Adaptation and Representation Transfer (DART) 2022.


# 💬 Invited Talks
- 2022.08.30,  a joint workshop with Shandong University


# 🎖 Honors and Awards
- 2018.06, Excellent Graduates, Soochow University
- 2021.09, Top 3 for group project work at the UCL Medical Image Computing Summer School (MedICSS)


# 🎖 Internships
- *2021.09 - 2022.09*, Research Assistant, The Chinese University of Hong Kong
