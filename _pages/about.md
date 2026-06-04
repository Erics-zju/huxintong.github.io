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

I am an incoming Ph.D. student of [Prof. Tao Yu](https://taoyds.github.io/) at [XLANG Lab](https://xlang.ai/), The University of Hong Kong, and a research intern at the Qwen Team, Alibaba Group. My research interest focuses on <span style="color:red">Embodied AI (VLA and WAM)</span>. I received my B.S. in [Computer Science and Technology](http://www.cs.zju.edu.cn/) from Zhejiang University, where I was fortunate to be advised by [Prof. Zhou Zhao](https://scholar.google.com/citations?hl=zh-CN&user=IIoFY90AAAAJ). Feel free to reach out if you are interested in my work or have any questions to discuss!




<span class='anchor' id='news'></span>

# 🔥 News
- *2026.05*: &nbsp; 🎉🎉 "FineVLA: Fine-Grained Instruction Alignment for Steerable Vision-Language-Action Policies" is released on arXiv.
- *2026.05*: &nbsp; 🎉🎉 "Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments" is released on arXiv.
- *2025.09*: &nbsp; 🎉🎉 "MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations" is accepted by NeurIPS2025.
- *2025.09*: &nbsp; 🎉🎉 "Tree of Preferences for Diversified Recommendation" is accepted by NeurIPS2025.
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='publications'></span>

# 📝 Publications 


<!-- paper: FineVLA -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Preprint 2026</div>
      <img src='images/FineVLA-main.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [FineVLA: Fine-Grained Instruction Alignment for Steerable Vision-Language-Action Policies](https://arxiv.org/abs/2605.27284)

  **Xintong Hu**<sup>*</sup>, Xuhong Huang<sup>*</sup>, Jinyu Zhang, Yutong Yao, Yuchong Sun, Qiuyue Wang, Mingsheng Li, Sicheng Xie, Yitao Liu, Junhao Chen, Yixuan Chen, Yingming Zheng, Shuai Bai, Tao Yu

  [🌐 **Project Page**](https://finevla.xlang.ai/)
  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://github.com/xlang-ai/FineVLA)
  [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="20px" style="vertical-align: middle; margin-right: 5px;"> **RoboFine-VLM**](https://huggingface.co/xlangai/RoboFine-VLM-397B-A17B)
  [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="20px" style="vertical-align: middle; margin-right: 5px;"> **Benchmark**](https://huggingface.co/datasets/xlangai/RoboFine-bench)

  An open framework for fine-grained VLA supervision, including: (1) **FineVLA-Data And Pipeline** that unifies 972K trajectories from 10 robot datasets into 47K human-verified fine-grained trajectories; (2) **RoboFine-Bench**, a 500-video benchmark with 10K+ atomic facts and 1K VQA questions; (3) **RoboFine-VLM**, a robotics-specialized VLM annotator for scalable trajectory annotation; (4) **FineVLA-Policy**, a steerable VLA policy achieving 86.8%/82.5% in RoboTwin and 62.7/100 in real-world dual-arm manipulation.
  </div>
</div>


<!-- paper: Qwen-VLA -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Preprint 2026</div>
      <img src='images/qwen-vla-main.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments](https://arxiv.org/abs/2605.30280)

  Qwen Team (**Xintong Hu** is a **core contributor**)

  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://github.com/QwenLM/Qwen-VLA) <img src="https://img.shields.io/github/stars/QwenLM/Qwen-VLA?style=social" alt="GitHub stars" style="vertical-align: middle; margin-left: 5px;">
  [🌐 **Project Page**](https://qwen.ai/blog?id=qwenvla)

  - A unified embodied foundation model extending Qwen's VL stack to action and trajectory generation via a DiT-based decoder, unifying manipulation, navigation, and trajectory prediction.
  <br>
  - Achieves 97.9% on LIBERO, 86.1%/87.2% on RoboTwin, 69.0% OSR on R2R, 76.9% OOD success on real-world ALOHA.
  </div>
</div>


<!-- paper1 ： MRSAudio  -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025 Poster</div>
      <img src='images/MRSAudio.jpg' alt="sym" width="100%" style="margin-bottom: 10px;">
      <img src='images/MRSAudio-2.jpg' alt="sym" width="100%">
      </div>
    </div>
  <div class='paper-box-text' markdown="1">
  [MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations](https://openreview.net/forum?id=p2pRiDwjDa&noteId=TmGqB9RN30)

  Wenxiang Guo<sup>*</sup>, Changhao Pan<sup>*</sup>, Zhiyuan Zhu<sup>*</sup>, **Xintong Hu**<sup>*</sup>, Yu Zhang<sup>*</sup>, Li Tang, Rui Yang, Han Wang, Zongbao Zhang, Yuhan Wang, Yixuan Chen, Hankun Xu, Ke Xu, Pengfei Fan, Zhetao Chen, Yanhao Yu, Qiange Huang, Fei Wu, Zhou Zhao<sup>†</sup>


  [<img src='images/MRSAudio-headImage.jpg' alt="demo" width="20px" style="vertical-align: middle; margin-right: 5px;"> **DemoPage**](https://mrsaudio.github.io/index.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://github.com/MRSAudio/MRSAudio_Main) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
  [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="20px" style="vertical-align: middle; margin-right: 5px;"> **Dataset**](https://huggingface.co/datasets/verstar/MRSAudio) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


  -Datasets: Establish MRSAudio, a 500-hour multimodal spatial audio dataset with ambisonic audio, synchronized video, motion trajectories, and fine-grained annotations (transcripts, lyrics, scores), covering 4 real-world scenarios (daily life/speech/singing/music).
  <br>
  -Benchmark: Unified benchmark for 5 spatial audio tasks (spatialization, text-to-speech, singing synthesis, music generation, sound localization) enabling 3D-aware audio modeling.
  </div>
</div>



<!-- paper2 ： Tree of Preference  -->
<div class='paper-box'>
  <div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Poster</div><img src='images/Tree_of_preference.jpg' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">

  [Tree of Preferences for Diversified Recommendation](https://openreview.net/forum?id=KlZUwDP0pR&noteId=vB7YeUWlGH)

  Hanyang Yuan,Ning Tang, Tongya Zheng, Jiarong Xu, **Xintong Hu**, Renhong Huang, Shunyu Liu, Jiacong Hu, Jiawei Chen, Mingli Song<sup>†</sup>

  [<i class="fab fa-github" style="font-size: 20px; margin-right: 5px;"></i>**Code**](https://anonymous.4open.science/r/TPRec-7047/README.md) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  -Abstract: With the help of the agent, complete the user information to improve the diversity of recommendations. Use Agent to help solve the Filter Bubble problem in traditional recommendation algorithms.
  </div>
</div>


<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
- *2025.10* **National Scholarship(Top 1%)**.
- *2024.10* **National Scholarship(Top 1%)**.
- *2025.06* 2025 IEEE ASRU AudioMos Challenge **Second Prize**.
- *2024.11* Zhejiang Province "Shangde Scholar" Award (Single Recipient).
- *2024.11* Zhejiang University CS ”Campus Star” Honor (Top 10 Students).
- *2025.09* Zhejiang University First-Class Scholarship (Top 3%).
- *2024.09* Zhejiang University First-Class Scholarship(Top 3%).
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2022.09 - Now*, *B.S.* Zhejiang University, School of Computer Science and Technology. 
<!-- - *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span class='anchor' id='internships'></span>

# 💻 Internships

**Alibaba Group, Qwen Team (Hangzhou)**
*Research Intern* (01/2026 -- Present)  
Advisor: Shuai Bai  
Research Topic: **Vision-Language-Action (VLA)**

**[XLANG NLP Lab, The University of Hong Kong](https://xlang.ai) (Hong Kong)**
*Research Assistant* (06/2025 -- Present)  
Advisor: Prof. Tao Yu  
Research Topic: **Embodied AI**

**YiWise Lab, Zhejiang University (Hangzhou)**
*Research Assistant* (02/2025 -- 06/2025)  
Advisor: Prof. Zhou Zhao  
Research Topic: **Spatial Audio**

**[VIPA Lab, Zhejiang University](https://www.vipazoo.cn/) (Hangzhou)**
*Research Assistant* (07/2024 -- 02/2025)  
Advisor: Prof. Mingli Song  
Research Topic: **Recommendation**

