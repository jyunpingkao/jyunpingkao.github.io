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

# Welcome! 
I am an incoming PhD student in the Department of Electrical and Computer Engineering at the University of Southern California (USC), supervised by Prof. [C.-C. Jay Kuo](https://viterbi.usc.edu/directory/faculty/Kuo/Chung-Chieh). 

Previously, I was a Visiting Research Student in the Department of Radiology at Harvard Medical School & Massachusetts General Hospital supervised by Prof. [Jonghye Woo](https://researchers.mgh.harvard.edu/profile/12882709/Jonghye-Woo), and in the Department of Orthopaedics and Traumatology at The University of Hong Kong supervised by Prof. [Chun Man Lawrence Lau](https://www.ortho.hku.hk/biography/lau-chun-man-lawrence/).

I received my M.S. degree from the Graduate Institute of Biomedical Electronics and Bioinformatics, National Taiwan University, where I was co-supervised by Prof. [Chung-Ping Chen](https://www.ee.ntu.edu.tw/profile1.php?teacher_id=943008) and Prof. [Wen-Shiang Chen](https://www.ntuh.gov.tw/PMR/Vcard.action?q_type=-1&q_itemCode=246). 

My research interests include Medical AI, Computer Vision, Bioengineering, and Bioinformatics.

You can find my CV here: [Jyun Ping Kao's Curriculum Vitae](../assets/CV.pdf). If you are interested in my work, please feel free to drop me an [email](mailto:jjpkao@gmail.com) **(jjpkao@gmail.com)**.


# 🔥 News
- *2026.04*: &nbsp;New Journal Paper **[Interpretable and backpropagation-free Green Learning for efficient multi-task echocardiographic segmentation and classification](https://arxiv.org/abs/2601.19743)** Accepted by **APSIPA Transactions on Signal and Information Processing**.
- *2026.04*: &nbsp;New Conference Paper **Entity-Preserving Biomedical Abstract Augmentation via Constraint-Driven Distillation** Accepted by **The Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC) 2026**.
- *2026.01*: &nbsp;New Conference Paper **[Cross-Modal Fine-Tuning of 3D Convolutional Foundation Models for ADHD Classification with Low-Rank Adaptation](https://ieeexplore.ieee.org/abstract/document/11515951)** Accepted by **IEEE International Symposium on Biomedical Imaging (ISBI) 2026**.
- *2025.11*: &nbsp;New Journal Paper **[A Novel Deep Learning Based Automatic Ultrasonic Posterior Cruciate Ligament Clinical Assessment Tool](https://www.nature.com/articles/s44387-025-00058-y)** Accepted by **npj Artificial Intelligence**.
- *2025.10*: &nbsp;I received the **Outstanding Paper Award** from the Graduate Institute of Biomedical Electronics and Bioinformatics, National Taiwan University.
- *2025.07*: &nbsp;New Conference Paper **MULTI-IMAGE MUSCULOSKELETAL ULTRASOUND INTERPRETATION USING A LARGE LANGUAGE MODEL** Accepted by **Radiological Society of North America Annual Meeting (RSNA 2025)**.
- *2025.06*: &nbsp;New Journal Paper **[LoRA-Enhanced RT-DETR: First Low-Rank Adaptation Based DETR for Real-Time Full Body Anatomical Structures Identification in Musculoskeletal Ultrasound](https://www.sciencedirect.com/science/article/abs/pii/S0895611125000928)** Accepted by **Computerized Medical Imaging and Graphics**.






# 📝 Publications 

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    Cross-Modal Fine-Tuning of 3D Convolutional Foundation Models for ADHD Classification with Low-Rank Adaptation
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    <b>Jyun-Ping Kao</b>, Shinyeong Rho, Shahar Lazarev, Hyun-Hae Cho, Fangxu Xing, Taehoon Shin, C.-C. Jay Kuo, Jonghye Woo
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    2026 IEEE International Symposium on Biomedical Imaging (ISBI)
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #ffedd5; color: #9a3412; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Conference Paper
    </span>
    <a href="https://ieeexplore.ieee.org/abstract/document/11515951" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      DOI 🔗
    </a>
  </div>
</div>


<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    A novel deep learning based automatic ultrasonic posterior cruciate ligament clinical assessment tool
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    <b>Jyun-Ping Kao</b>, Jiajing Zhang, Wei-Ning Lee, Chung-Ping Chen, Lawrence Chun-Man Lau
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    npj Artificial Intelligence, 2026
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #e0e7ff; color: #3730a3; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Journal Paper
    </span>
    <a href="https://doi.org/10.1038/s44387-025-00058-y" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      DOI 🔗
    </a>
  </div>
</div>

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    LoRA-Enhanced RT-DETR: First Low-Rank Adaptation based DETR for real-time full body anatomical structures identification in musculoskeletal ultrasound
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    <b>Jyun-Ping Kao</b>, Yu-Ching Chung, Hao-Yu Hung, Chung-Ping Chen, Wen-Shiang Chen
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    Computerized Medical Imaging and Graphics, 2025
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #e0e7ff; color: #3730a3; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Journal Paper
    </span>
    <a href="https://doi.org/10.1016/j.compmedimag.2025.102583" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      DOI 🔗
    </a>
  </div>
</div>

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    Transformer Based Real Time Musculoskeletal Anatomical Structure Detection in Clinical Use
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    <b>Jyun-Ping Kao</b>, Hao-Yu Hung, Ping-Xuan Chen, Chung-Ping Chen, Wen-Shiang Chen
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    2024 IEEE 24th International Conference on Bioinformatics and Bioengineering (BIBE)
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #ffedd5; color: #9a3412; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Conference Paper
    </span>
    <a href="https://doi.org/10.1109/BIBE63649.2024.10820491" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      DOI 🔗
    </a>
  </div>
</div>

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    Real time musculoskeletal ultrasound image annotations
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    Hao-Yu Hung, <b>Jyun-Ping Kao</b>, Hsin-Yuan Chu, Chung-Ping Chen, Wen-Shiang Chen
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    Proc. SPIE 13487, Optics and Photonics International Congress 2024
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #ffedd5; color: #9a3412; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Conference Paper
    </span>
    <a href="https://doi.org/10.1117/12.3052319" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      DOI 🔗
    </a>
  </div>
</div>

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    Enhancing Multi-Object Detection in Ultrasound Images Through Semi-Supervised Learning, Focal Loss and Relation of Frame
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    Hsin-Yuan Chu, Chueh-Hung Wu, Ping-Xuan Chen, Hao-Yu Hung, <b>Jyun-Ping Kao</b>, Chung-Ping Chen, Wen-Shiang Chen
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    Ultrasound in Medicine & Biology, 2024
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #e0e7ff; color: #3730a3; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Journal Paper
    </span>
    <a href="https://doi.org/10.1016/j.ultrasmedbio.2024.08.012" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      DOI 🔗
    </a>
  </div>
</div>

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    Deep-Learning-Enabled Third-Harmonic-Generation Imaging for Skin Virtual Biopsy from Reflectance Scanning Microscope
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    <b>Jyun-Ping Kao</b>, Xin Lin, You-Yang Zhang, Connie Liu, Shih-Hsuan Chia
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    2023 Optics & Photonics Taiwan International Conference (OPTIC)
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #ffedd5; color: #9a3412; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Conference Paper
    </span>
    <a href="https://optic2023.conf.tw/site/order/1495/SessionDetail.aspx?sid=1495&lang=en&snid=F&rmid=F04&rowid=6" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      Link 🔗
    </a>
  </div>
</div>

<div class='publication-item' style="margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid #eaeaea;">
  <div style="font-size: 1.15em; font-weight: 600; color: #2c3e50; line-height: 1.4; margin-bottom: 4px;">
    Optical design and realization of nonlinear mesoscope
  </div>
  <div style="color: #4b5563; font-size: 0.95em; margin-bottom: 4px;">
    <b>Jyun-Ping Kao</b>, Chu-Qiao Yu, Wei-Zhong Lin, Bo-Hsien Pan, Je-Chi Jang, Tien-Ching Tsai, Shih-Hsuan Chia
  </div>
  <div style="color: #059669; font-style: italic; font-size: 0.95em; margin-bottom: 12px;">
    2022 Optics & Photonics Taiwan International Conference (OPTIC)
  </div>
  <div style="display: flex; gap: 8px; flex-wrap: wrap;">
    <span style="background-color: #ffedd5; color: #9a3412; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 500;">
      Conference Paper
    </span>
    <a href="https://optic2022.conf.tw/site/order/1443/SessionDetail.aspx?sid=1443&lang=en&snid=F&rmid=F11&rowid=3" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
      Link 🔗
    </a>
  </div>
</div>








# 📖 Educations
- *2026.08 - Present*, PnD in Electrical and Computer Engineering, University of Southern California, United States
- *2023.08 - 2026.01*, MS in Biomedical Electronics and Bioinformatics, National Taiwan University, Taiwan
  - **GPA: 4.3/4.3 (Program Ranked: 1/62)**
  - **Awards: Outstanding Paper Award (Published in a JCR Top 15% journal)**
- *2019.09 - 2023.08*, BS in Electronics and Electrical Engineering (Double Major) &  BS in Digital Healthcare (Double Major), National Yang Ming Chiao Tung University, Taiwan
  - **Awards : Phi Tau Phi Awards (Top 1 % student in the school)**


# 🔬 Research Experience

**Harvard Medical School (HMS) and Massachusetts General Hospital (MGH) · Department of Radiology | Visiting Research Student**
- Advised by Prof. [Jonghye Woo](https://researchers.mgh.harvard.edu/profile/12882709/Jonghye-Woo)
- July 2025 - Jan 2026

**National Taiwan University Hospital (NTUH) · Department of Physical Medicine and Rehabilitation | Research Assistant**
- Advised by Prof. [Wen-Shiang Chen](https://www.researchgate.net/profile/Wen-Shiang-Chen)
- July 2023 - June 2025


**The University of Hong Kong (HKU) · Department of Orthopaedics and Traumatology | Visiting Research Student**
- Advised by Prof. [Chun Man Lawrence Lau](https://www.ortho.hku.hk/biography/lau-chun-man-lawrence/)
- June 2024 - Aug 2024


**National Yang Ming Chiao Tung University (NYCU) · Institute of Biophotonics | Undergraduate Research Student**
- Advised by Prof. [Shih-Hsuan Chia](https://bioph.nycu.edu.tw/faculty/%E9%83%AD%E6%96%87%E5%A8%9F-%E6%95%99%E6%8E%88-%E6%89%80%E9%95%B7%E3%80%80dr-wen-chuan-kuo-professor-director/dr-shih-hsuan-chia-associate-professor/)
- July 2020 - July 2023


# 📄 Academic Service

**Journal Reviewer**:  **[IEEE Journal of Biomedical and Health Informatics](https://www.embs.org/jbhi/)**, **[Artificial Intelligence In Medicine](https://www.sciencedirect.com/journal/artificial-intelligence-in-medicine)**, **[Computerized Medical Imaging and Graphics](https://www.sciencedirect.com/journal/computerized-medical-imaging-and-graphics)**, **[International Journal of Medical Informatics](https://www.sciencedirect.com/journal/international-journal-of-medical-informatics)**, **[Biomedical Signal Processing and Control](https://www.sciencedirect.com/journal/biomedical-signal-processing-and-control)**, **[Journal of Imaging Informatics in Medicine](https://link.springer.com/journal/10278)**, **[Heliyon](https://www.cell.com/heliyon/home)**, **[APSIPA Transactions on Signal and Information Processing](https://www.nowpublishers.com/SIP)**, **[Clinical Radiology](https://www.clinicalradiologyonline.net/)**.

**Conference Reviewer**: **[IEEE ICIP 2026](https://2026.ieeeicip.org/)** ,**[IEEE EMBC 2026](https://embc.embs.org/2026/?gad_source=1&gad_campaignid=14079357780&gbraid=0AAAAABPRV5S374lGfOI7xANIQE-g0CSHa&gclid=Cj0KCQjwlerQBhDMARIsAB16H-XFsYsNZYs05pSEHcR-TwYLipIyjZ5ShTPqn9firy5z4C-nUXdNYIEaAnwbEALw_wcB)**, **[MIDL 2026](https://2026.midl.io/)**, **[IEEE ISBI 2026](https://biomedicalimaging.org/2026/)**, **[AMIA 2026](https://amia.org/education-events/amplify-informatics-conference)**, **[IEEE EMBC 2025](https://embc.embs.org/2025/)**, **[IEEE ICSPC 2025](https://www.asprg.net/cms/conference.php?conf_id=c986860c-0552-4685-9c31-e54a3aaa96b1)**.  

# 🎖 Honors and Awards
- *2025.10* Outstanding Paper Award
- *2025.05* 2025 Intel Artificial Intelligence Innovation Application Competition - Semi-Finalist
- *2023.06* The Phi Tau Phi Scholastic Honor Society of the Republic of China Honorary Membership (Top 1% in the school during undergraduate)
- *2023.06* 2023 Synopsys ARC AIoT Design Contest Award – Finalist
- *2023.02* Undergraduate Research Fellowship
- *2023.01* 2022 Intel DevCup x OpenVINO Toolkit Award – Finalist
- *2022.01* 2021 Intel DevCup x OpenVINO Toolkit Award –  Second Place

# 🌏 Web visitors
<!-- Visitor map (inside body) -->
<div style="margin: 2rem 0; text-align:center;">
  <script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=c3cYIFJomLQjROqgCVr_4Zc-bcy6OA3OvHYUNLJu3I8&cl=ffffff&w=a"></script>
  <noscript>
    <a href="https://mapmyvisitors.com/web/1c0m7" title="Visit tracker">
      <img src="https://mapmyvisitors.com/map.png?d=c3cYIFJomLQjROqgCVr_4Zc-bcy6OA3OvHYUNLJu3I8&cl=ffffff" alt="Visit tracker">
    </a>
  </noscript>
</div>



------

<p align="center">
  <i>The grass withers and the flower fades, But the word of our God will stand forever. Isaiah40:8</i>
</p>
