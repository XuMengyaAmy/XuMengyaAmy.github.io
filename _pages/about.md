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
- *2022.10*: Two journal papers are accepted by T-ASE 2022 and RA-L 2022.

# 📝 Journal Publications

**1. Self-powered glove-based intuitive interface for diversified control applications in real/cyber space**, He, Tianyiyi, Zhongda Sun, Qiongfeng Shi, Minglu Zhu, David Vera Anaya, **Mengya Xu**, Tao Chen, Mehmet Rasit Yuce, Aaron Voon-Yew Thean, and Chengkuo Lee. Nano Energy
[pdf](https://www.sciencedirect.com/science/article/pii/S2211285519300771)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AIS 2020</div><img src='images/stentnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**2. Stent Deployment Detection Using Radio Frequency‐Based Sensor and Convolutional Neural Networks**

**Mengya Xu**, Lalithkumar Seenivasan, Leonard Leong Litt Yeo, and Hongliang Ren.
  
Advanced Intelligent Systems 2020
  
[pdf](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1002/aisy.202000092) \| [code](https://github.com/XuMengyaAmy/Stent_Deployment_DL)


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2022</div><img src='images/SIRNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
     
**3. SIRNet: Fine-Grained Surgical Interaction Recognition**

Li, Ling, Xiaojian Li, Shuai Ding, Zhao Fang, **Mengya Xu**, Hongliang Ren, and Shanlin Yang.  
     
IEEE Robotics and Automation Letters (RA-L) 2022. 
    
[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9705584) \| [code](https://github.com/cynerelee/SIRNet)
     
</div>
</div>

**4. Confidence-Aware Paced-Curriculum Learning by Label Smoothing for Surgical Scene Understanding**, **Mengya Xu**, Mobarakol Islam, Ben Glocker and Hongliang Ren. IEEE Transactions on Automation Science and Engineering (T-ASE), 2022

**5. Rethinking Feature Extraction: Gradient-based Localized Feature Extraction for End-to-End Surgical Downstream Tasks**, Winnie Pang, Mobarakol Islam, Sai Mitheran, Lalithkumar Seenivasan, **Mengya Xu**, Hongliang Ren. IEEE Robotics and Automation Letters (RA-L), 2022
  
# 📝 Conference Publications
     
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2021</div><img src='images/M2Transformer_DAN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**4. Learning domain adaptation with model calibration for surgical report generation in robotic surgery**

**Mengya Xu**, Mobarakol Islam, Chwee Ming Lim, and Hongliang Ren
  
IEEE International Conference on Robotics and Automation (ICRA) 2021 

[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9561569)] \| [code](https://github.com/XuMengyaAmy/ReportDALS)

</div>
</div>
     
     
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2021</div><img src='images/CIDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**5. Class-incremental domain adaptation with smoothing and calibration for surgical report generation**

**Mengya Xu**, Mobarakol Islam, Chwee Ming Lim, and Hongliang Ren
  
Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2021

[pdf](https://arxiv.org/pdf/2107.11091.pdf) \| [Code](https://github.com/XuMengyaAmy/CIDACaptioning) \| [Poster](https://github.com/XuMengyaAmy/XuMengyaAmy.github.io/blob/main/images/poster.png)

</div>
</div>
     

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/SwinMLP_TranCAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**6. Rethinking Surgical Captioning: End-to-End Window-Based MLP Transformer Using Patches**

**Mengya Xu**, Mobarakol Islam, and Hongliang Ren
  
Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2022

[pdf](https://arxiv.org/pdf/2207.00113.pdf)] \| [Code](https://github.com/XuMengyaAmy/SwinMLP_TranCAP)

</div>
</div>

  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/single_bg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**7. Rethinking Surgical Instrument Segmentation: A Background Image Can Be All You Need**

An Wang\*, Mobarakol Islam\*, **Mengya Xu**, and Hongliang Ren\*\*
  
Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2022

[pdf](https://arxiv.org/abs/2206.11804) \| [code](https://github.com/lofrienger/Single_SurgicalScene_For_Segmentation)

</div>
</div>

 
# 📖 Educations
- *2019.08 - now*, Ph.D., Biomedic Engineering, National University of Singapore, Singapore
- *2018.08 - 2019.06*, M.Sc., Electrical Engineering, National University of Singapore, Singapore
- *2014.09 - 2018.06*, B.Eng., Information Engineering, Soochow University, Suzhou, China  (Excellent Graduates)


# 📖 Services
- 2022.07.03 - as a reviewer for  Domain Adaptation and Representation Transfer (DART) 2022.


# 💬 Invited Talks
- 2022.08.30,  a joint workshop with Shandong Univeristy


# 🎖 Honors and Awards
- 2018.06, Excellent Graduates, Soochow University


# 🎖 Internships
- *2021.09 - 2022.09*, Research Assistant, The Chinese University of Hong Kong
