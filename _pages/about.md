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

I am currently a Ph.D. candidate at [**USSLab**](https://usslab.org), Zhejiang University, co-supervised by [Prof. Wenyuan Xu](https://sites.google.com/view/xuwenyuan/main) and [Prof. Xiaoyu Ji](https://sites.google.com/site/xiaoyuijh/home). I received my B.S. degree in Automation at College of EE, Zhejiang University in 2022.

My research interests include: (1) Speech security and privacy, particularly focusing on speech anonymization and voice deepfake detection;
(2) Sensor security and privacy, which focuses on physical signal attacks and defense against sensors in cyber-physical systems (CPS) and sensor-based privacy protecion.

# 🔥 News
- *2025.08*: &nbsp; 🎉 Our paper "SoK: Understanding the Fundamentals and Implications of Sensor Out-of-band Vulnerabilities" got accepted by **NDSS 2026**!
- *2025.08*: &nbsp; 🎉 Our paper "Exploring the Robustness of Vision-Language-Action Models 
  against Sensor Attacks" got accepted by **CCS-LAMPS 2025** ! 
- *2024.06*: &nbsp; 🎉 Our paper "IoT Data Privacy Protection by Birth" got accepted by **Nature Review Electrical Engineering**!
- *2023.12*: &nbsp; 🔥 I attended the ACM CCS 2023 and present our work "MicPro" in person.
- *2023.05*: &nbsp; 🎉 Our paper "MicPro: Microphone-based Voice Privacy Protection" got accepted by **CCS 2023**!
- *2023.03*: &nbsp; 🎉 Our paper "Volttack: Control IoT Devices by Manipulating Power Supply Voltage" got accepted by **S&P 2023**!
- *2022.12*: &nbsp; 🎉 Our paper "Private Eye: On the Limits of Textual Screen Peeking via Eyeglass Reflections in Video Conferencing" got accepted by **S&P 2023**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2026</div><img src='images/SOK2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SoK: Understanding the Fundamentals and Implications of Sensor Out-of-band Vulnerabilities](https://dx.doi.org/10.14722/ndss.2026.230450)

**Shilin Xiao**, Wenjun Zhu, Yan Jiang, Kai Wang, Peiwang Wang, Chen Yan, Xiaoyu Ji, Wenyuan Xu.
To appear in **NDSS 2026 (CCF-A, Big4)**.

We provide a systematic analysis on sensor out-of-band vulnerabilities. We identify the physical principles and limitations that contribute to OOB vulnerabilities, categorize known attacks and evaluate their practicality, and analyze how CPS features such as sensor fusion, closed-loop control, and intelligent perception impact the exposure and mitigation of OOB threats. Our findings offer a foundational understanding of sensor hardware security and provide guidance and future directions for sensor designers, security researchers, and system developers aiming to build more secure sensors and CPS.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2023</div><img src='images/MicPro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MicPro: Microphone-based Voice Pirvacy Protecion](https://doi.org/10.1145/3576915.3616616) [[Paper](docs/pubs/MicPro.pdf)] [[Slide](docs/pubs/MicPro-v5-1124.pdf)] [[Code](https://github.com/USSLab/MicPro)] 

**Shilin Xiao**, Xiaoyu Ji, Chen Yan, Zhicong Zheng, Wenyuan Xu. **CCS 2023 (CCF-A, Big4)**

We propose the first privacy-enhanced microphone module (i.e., MicPro) that can produce anonymous audio recordings with biometric information suppressed while preserving speech quality for human perception or linguistic content for speech recognition. MicPro transforms formants, which are distinct for each person due to the unique physiological structure of the vocal organs, and formant transformations are done by modifying the linear spectrum frequencies (LSFs) provided by a popular codec (i.e., CELP) in low-latency communications.
</div>
</div>

+ [Exploring the Robustness of Vision-Language-Action Models against Sensor Attacks]().

  Xuancun Lu, Jiaxiang Chen, **Shilin Xiao**, Zizhi Jin, Ruochen Zhou, Xiaoyu Ji, Wenyuan Xu. To appear in **CCS-LAMPS 2025**.
  
+ [IoT Data Privacy Protection by Birth](https://doi.org/10.1038/s44287-024-00073-2).

  Xiaoyu Ji, Wenjun Zhu, **Shilin Xiao**, Wenyuan Xu. **Nature Review Electrical Engineering 2024**.

+ [Volttack: Control IoT Devices by Manipulating Power Supply Voltage](https://10.1109/sp46215.2023.10179340).
  
  Kai Wang, **Shilin Xiao**, Xiaoyu Ji, Chen Yan, Chaohao Li, Wenyuan Xu. **S&P 2023 (CCF-A, Big4)**
  
+ [Private Eye: On the Limits of Textual Screen Peeking via Eyeglass Reflections in Video Conferencing](https://doi.org/10.1109/sp46215.2023.10179423).
  
  Yan Long, Chen Yan, **Shilin Xiao**, Shivan Prasad, Wenyuan Xu, Kevin Fu. **S&P 2023 (CCF-A, Big4)**

# 🎖 Honors and Award

# 📖 Educations
- *2022.09 - Present*, Ph.D., USSLAB, Zhejiang University, Hangzhou. 
- *2018.09 - 2022.06*, Undergraduate, College of Electrical Engineering, Zhejiang University, Hangzhou. 

# 💬 Invited Talks
+ *2023.12*, ACM CCS 2023 at Copenhagen, Denmark.

# 🗺️ Visitor Map
<div style="width:25%; max-width:600px;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=GLPDlLbX1cPZm8KLm_XgXodCr9GtyJ7mqVJyXZjRBDY"></script>
</div>
