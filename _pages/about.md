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

# 👋 Welcome! 
I am an incoming PhD student in the Department of Electrical and Computer Engineering at the University of Southern California, supervised by Prof. [C.-C. Jay Kuo](https://viterbi.usc.edu/directory/faculty/Kuo/Chung-Chieh). 

Previously, I was a Visiting Research Student in the Department of Radiology at Harvard Medical School & Massachusetts General Hospital supervised by Prof. [Jonghye Woo](https://researchers.mgh.harvard.edu/profile/12882709/Jonghye-Woo), and in the Department of Orthopaedics and Traumatology at The University of Hong Kong supervised by Prof. [Chun Man Lawrence Lau](https://www.ortho.hku.hk/biography/lau-chun-man-lawrence/).

I received my M.S. degree from the Graduate Institute of Biomedical Electronics and Bioinformatics, National Taiwan University, where I was co-supervised by Prof. [Chung-Ping Chen](https://www.ee.ntu.edu.tw/profile1.php?teacher_id=943008) and Prof. [Wen-Shiang Chen](https://www.ntuh.gov.tw/PMR/Vcard.action?q_type=-1&q_itemCode=246). 

Before that, I earned dual B.S. degrees in Electronics and Electrical Engineering and in Digital Healthcare from National Yang Ming Chiao Tung University.

My research interests include Medical AI, Computer Vision, Bioengineering, and Bioinformatics.

You can find my CV here: <a href="../assets/CV.pdf" target="_blank" style="background-color: #e0e7ff; color: #3730a3; padding: 3px 10px; border-radius: 4px; font-size: 0.95em; font-weight: 500; text-decoration: none;">📄 Jyun-Ping Kao's Curriculum Vitae</a>

If you are interested in my work, please feel free to drop me an email: <a href="mailto:jjpkao@gmail.com" style="background-color: #ffedd5; color: #9a3412; padding: 3px 10px; border-radius: 4px; font-size: 0.95em; font-weight: 500; text-decoration: none;">📧 jjpkao@gmail.com</a>

<hr style="margin: 2rem 0; border: none; border-top: 1px solid #e2e8f0;">

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
    <a href="https://doi.org/10.1109/ISBI61048.2026.11515951" target="_blank" style="text-decoration: none; border: 1px solid #d1d5db; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; color: #374151; transition: background-color 0.2s;">
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








# 🎓 Educations
- *2026.08 - Present*, PhD in Electrical and Computer Engineering, University of Southern California, United States
- *2023.08 - 2026.01*, MS in Biomedical Electronics and Bioinformatics, National Taiwan University, Taiwan
  - **GPA: 4.3/4.3 (Program Ranked: 1/62)**
  - **Awards: Outstanding Paper Award**
- *2019.09 - 2023.08*, BS in Electronics and Electrical Engineering (Double Major) &  BS in Digital Healthcare (Double Major), National Yang Ming Chiao Tung University, Taiwan
  - **Awards: Phi Tau Phi Awards (Top 1 % student in the school)**



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

<div class="academic-service-section" style="margin-top: 1rem;">

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(230px, 1fr)); gap: 12px; margin-bottom: 1.25rem;">

  <div style="background: linear-gradient(135deg, #f8fafc, #eef2ff); border: 1px solid #e2e8f0; border-radius: 14px; padding: 1rem 1.15rem;">
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 12px; align-items: center;">
      <div>
        <div style="font-size: 1.45em; font-weight: 700; color: #1e293b; margin-bottom: 2px;">9+</div>
        <div style="font-size: 0.9em; color: #64748b;">Journal reviewer roles</div>
      </div>
      <div style="border-left: 1px solid #c7d2fe; padding-left: 12px;">
        <div style="font-size: 1.45em; font-weight: 700; color: #1e293b; margin-bottom: 2px;">80+</div>
        <div style="font-size: 0.9em; color: #64748b;">Journal papers reviewed</div>
      </div>
    </div>
  </div>

  <div style="background: linear-gradient(135deg, #f8fafc, #ecfdf5); border: 1px solid #e2e8f0; border-radius: 14px; padding: 1rem 1.15rem;">
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 12px; align-items: center;">
      <div>
        <div style="font-size: 1.45em; font-weight: 700; color: #1e293b; margin-bottom: 2px;">7+</div>
        <div style="font-size: 0.9em; color: #64748b;">Conference reviewer roles</div>
      </div>
      <div style="border-left: 1px solid #bbf7d0; padding-left: 12px;">
        <div style="font-size: 1.45em; font-weight: 700; color: #1e293b; margin-bottom: 2px;">20+</div>
        <div style="font-size: 0.9em; color: #64748b;">Conference papers reviewed</div>
      </div>
    </div>
  </div>

</div>


  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 16px;">

    <div style="background: #ffffff; border: 1px solid #e2e8f0; border-radius: 16px; padding: 1.15rem 1.25rem; box-shadow: 0 8px 24px rgba(15, 23, 42, 0.04);">
      <div style="display: flex; align-items: center; gap: 8px; margin-bottom: 12px;">
        <span style="font-size: 1.25em;">📚</span>
        <div>
          <div style="font-size: 1.02em; font-weight: 700; color: #1e293b;">Journal Reviewer</div>
          <div style="font-size: 0.82em; color: #94a3b8;">Medical AI · Imaging · Informatics</div>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 8px; line-height: 1.5;">
        <a href="https://www.embs.org/jbhi/" target="_blank" style="text-decoration: none; background: #eef2ff; color: #3730a3; border: 1px solid #c7d2fe; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IEEE JBHI</a>
        <a href="https://www.sciencedirect.com/journal/artificial-intelligence-in-medicine" target="_blank" style="text-decoration: none; background: #f0fdf4; color: #166534; border: 1px solid #bbf7d0; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">AI in Medicine</a>
        <a href="https://www.sciencedirect.com/journal/computerized-medical-imaging-and-graphics" target="_blank" style="text-decoration: none; background: #f0f9ff; color: #075985; border: 1px solid #bae6fd; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">CMIG</a>
        <a href="https://www.sciencedirect.com/journal/international-journal-of-medical-informatics" target="_blank" style="text-decoration: none; background: #f8fafc; color: #334155; border: 1px solid #cbd5e1; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IJMI</a>
        <a href="https://www.sciencedirect.com/journal/biomedical-signal-processing-and-control" target="_blank" style="text-decoration: none; background: #fefce8; color: #854d0e; border: 1px solid #fde68a; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">BSPC</a>
        <a href="https://link.springer.com/journal/10278" target="_blank" style="text-decoration: none; background: #fff7ed; color: #9a3412; border: 1px solid #fed7aa; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">JIIM</a>
        <a href="https://www.cell.com/heliyon/home" target="_blank" style="text-decoration: none; background: #fdf2f8; color: #9d174d; border: 1px solid #fbcfe8; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">Heliyon</a>
        <a href="https://www.nowpublishers.com/SIP" target="_blank" style="text-decoration: none; background: #f5f3ff; color: #5b21b6; border: 1px solid #ddd6fe; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">APSIPA TSIP</a>
        <a href="https://www.clinicalradiologyonline.net/" target="_blank" style="text-decoration: none; background: #f8fafc; color: #334155; border: 1px solid #cbd5e1; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">Clinical Radiology</a>
      </div>
    </div>

    <div style="background: #ffffff; border: 1px solid #e2e8f0; border-radius: 16px; padding: 1.15rem 1.25rem; box-shadow: 0 8px 24px rgba(15, 23, 42, 0.04);">
      <div style="display: flex; align-items: center; gap: 8px; margin-bottom: 12px;">
        <span style="font-size: 1.25em;">🗞️</span>
        <div>
          <div style="font-size: 1.02em; font-weight: 700; color: #1e293b;">Conference Reviewer</div>
          <div style="font-size: 0.82em; color: #94a3b8;">Biomedical imaging · Signal processing · Health informatics</div>
        </div>
      </div>

      <div style="display: flex; flex-wrap: wrap; gap: 8px; line-height: 1.5;">
        <a href="https://2026.ieeeicip.org/" target="_blank" style="text-decoration: none; background: #eef2ff; color: #3730a3; border: 1px solid #c7d2fe; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IEEE ICIP 2026</a>
        <a href="https://embc.embs.org/2026/" target="_blank" style="text-decoration: none; background: #f0fdf4; color: #166534; border: 1px solid #bbf7d0; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IEEE EMBC 2026</a>
        <a href="https://2026.midl.io/" target="_blank" style="text-decoration: none; background: #f0f9ff; color: #075985; border: 1px solid #bae6fd; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">MIDL 2026</a>
        <a href="https://biomedicalimaging.org/2026/" target="_blank" style="text-decoration: none; background: #fff7ed; color: #9a3412; border: 1px solid #fed7aa; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IEEE ISBI 2026</a>
        <a href="https://amia.org/education-events/amplify-informatics-conference" target="_blank" style="text-decoration: none; background: #fdf2f8; color: #9d174d; border: 1px solid #fbcfe8; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">AMIA 2026</a>
        <a href="https://embc.embs.org/2025/" target="_blank" style="text-decoration: none; background: #f8fafc; color: #334155; border: 1px solid #cbd5e1; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IEEE EMBC 2025</a>
        <a href="https://www.asprg.net/cms/conference.php?conf_id=c986860c-0552-4685-9c31-e54a3aaa96b1" target="_blank" style="text-decoration: none; background: #fefce8; color: #854d0e; border: 1px solid #fde68a; padding: 4px 9px; border-radius: 999px; font-size: 0.84em; font-weight: 500;">IEEE ICSPC 2025</a>
      </div>
    </div>

  </div>
</div>
# 🎖 Honors and Awards
<div style="margin-top: 1rem;">

<!-- 2025 = blue: #dbeafe / #1e40af | 2024 = purple: #ede9fe / #5b21b6 | 2023 = green: #dcfce7 / #166534 | 2022 = orange: #ffedd5 / #9a3412 -->

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dbeafe; color: #1e40af; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Oct 2025</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 National Taiwan University</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🏆 Outstanding Paper Award</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Thesis published in a journal ranked in the top 15% by JCR and awarded a $340 USD scholarship.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dbeafe; color: #1e40af; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Oct 2025</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 National Taiwan University</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">✈️ International Conference Travel Grant</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Received $550 USD to present at the Radiological Society of North America Annual Meeting (RSNA 2025).</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dbeafe; color: #1e40af; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Jun 2025</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 National Taiwan University</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🎓 Graduate Student Research Scholarship</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Awarded $1,200 USD to support AI in medical imaging research.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dbeafe; color: #1e40af; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">May 2025</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 Intel Greater Bay Area Innovation Center</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🥈 2025 Intel AI Innovation Application Competition — Semi-Finalist</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Recognized for Graph Neural Network application in decision making on Intel AI PCs.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #ede9fe; color: #5b21b6; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Nov 2024</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 National Science and Technology Council (NSTC), Taiwan</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">✈️ International Conference Travel Grant</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Received $1,250 USD to present at the 24th IEEE BIBE Conference.</div>
</div>

<div id="awards-extra" style="display:none;">

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #ede9fe; color: #5b21b6; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Aug 2024</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 The University of Hong Kong</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🔬 Summer Research Scholarship</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Awarded $2,570 USD for participation in the highly competitive 2024 HKU Summer Research Program.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dcfce7; color: #166534; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Jul 2023</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 Phi Tau Phi Scholastic Honor Society of the Republic of China</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🎓 Phi Tau Phi — Honorary Membership</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Awarded to the top 1% of graduating students for academic excellence.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dcfce7; color: #166534; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Jun 2023</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 Synopsys, Taiwan</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🥉 2023 Synopsys ARC AIoT Design Contest — Finalist</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Finalist for super-resolution imaging utilizing deep learning on Synopsys ARC EM9D Processors.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dcfce7; color: #166534; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Feb 2023</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 Ministry of Science and Technology (MOST), Taiwan</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">📚 Undergraduate Research Fellowship</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Awarded $1,510 USD research grant for generative AI in non-linear optical microscopy.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #dcfce7; color: #166534; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Feb 2023</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 Intel Corporation, Taiwan</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🥉 2022 Intel DevCup × OpenVINO Toolkit Award — Finalist</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Finalist for a deep learning project using Intel OpenVINO Toolkit for edge computing applications in microscopic image generation.</div>
</div>

<div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem 1.25rem; margin-bottom: 10px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px;">
    <span style="background: #ffedd5; color: #9a3412; font-size: 0.78em; font-weight: 600; padding: 2px 9px; border-radius: 5px;">Jan 2022</span>
    <span style="font-size: 0.78em; color: #94a3b8;">🏛 Intel Corporation, Taiwan</span>
  </div>
  <div style="font-size: 0.97em; font-weight: 600; color: #1e293b; margin-bottom: 4px;">🥈 2021 Intel DevCup × OpenVINO Toolkit Award — Second Place</div>
  <div style="font-size: 0.88em; color: #64748b; line-height: 1.6;">Secured 2nd place ($1,200 USD) for edge computing prediction of Hemochromatosis using ECG/GWAS data.</div>
</div>
</div>


<button onclick="var e=document.getElementById('awards-extra');var b=this;if(e.style.display==='none'){e.style.display='block';b.textContent='▲ Show less';}else{e.style.display='none';b.textContent='▼ Show 6 more awards';}" style="background: none; border: 1px solid #cbd5e1; border-radius: 6px; padding: 5px 14px; font-size: 0.85em; color: #475569; cursor: pointer; margin-top: 4px;">▼ Show 6 more awards</button>
</div>


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
