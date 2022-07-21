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


<!--
### Hi there 👋
**zhangzjn/zhangzjn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

https://www.emojiall.com/zh-hans/categories/F
-->

I am pursuing my Ph.D. degree (2020.04 - Now⚡) in College of Control Science and Engineering, Zhejiang University, Hangzhou, China, under the supervision of [Prof. Yong Liu](https://april.zju.edu.cn/our-team/). My major is Computer Vision and my research interests include: 
- 🌱 Generative Adversarial Network (GAN), e.g., image/audio-guided face reenactment, face swapping, video generation, etc.
- 🌱 Neural Architecture Design (NAD), e.g., transformer-based architecture improvement, light-wight vision model, etc.
- 🌱 Semantic/Instance Segmentation, Point Could Reconstruction/Sampling, Anomaly Detection, Person Re-Identification, etc.

💬 Feel free to drop me emails (186368@zju.edu.cn) if you have interests, and remote cooperations are welcomed.

💖 I love 📷photography, 🍲cooking, and 🌏traveling, enjoy together!!!!!!

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2022.07*: &nbsp;🎉🎉🎉 One of five finalists for the IJIRA Best Paper Award 2022. <span style="color:red">(Person Re-Identification and Robotic Navigation)</span>
- *2022.07*: &nbsp;🎉🎉🎉 Three papers are accepted by ECCV 2022. <span style="color:red">(Face Reenactment/Swapping | Point Cloud Sampling/Reconstruction)</span>
- *2022.06*: &nbsp;🎉🎉🎉 One paper is accepted by TCSVT. <span style="color:red">(Video Object Detection)</span>
- *2022.03*: &nbsp;🎉🎉🎉 One paper is accepted by CVPR 2022. <span style="color:red">(Face Swapping)</span>
- *2021.12*: &nbsp;🎉🎉🎉 One paper is accepted by AAAI 2022. <span style="color:red">(Image Colorization and Super-Resolution)</span>
- *2021.09*: &nbsp;🎉🎉🎉 One paper is accepted by NeurIPS 2021. <span style="color:red">(Transformer Architecture Design)</span>
- *2020.12*: &nbsp;🎉🎉🎉 Research intern in YouTu Lab, Tencent, mentored by Researcher Jian Li, Researcher Yabiao Wang, and [Dr. Ying Tai](https://tyshiwo.github.io/).
- *2020.07*: &nbsp;🎉🎉🎉 One paper is accepted by ECCV 2020 as spotlight presentation. <span style="color:red">(Time-Lapse Video Generation)</span>
- *2020.04*: &nbsp;🎉🎉🎉 From master to docker, pursuing Ph.D. in Zhejiang University, Hangzhou, China.🔭🔭🔭
- *2020.02*: &nbsp;🎉🎉🎉 Two papers are accepted by CVPR 2022. <span style="color:red">(Face Reenactment | Unsupervised Optical Flow Estimation)</span>

# 📝 Publications 

## Conference 
<ul>

<li><strong>ECCV 2022</strong> <a href="https://arxiv.org">Designing One Unified Framework for High-Fidelity Face Reenactment and Swapping</a>, Chao Xu*, <strong>Jiangning Zhang</strong>*, Yue Han, Guanzhong Tian, Xianfang Zeng, Ying Tai, Yabiao Wang, Chengjie Wang, and Yong Liu | <a href="https://github.com/xc-csc101/UniFace">Code</a> </li>

<li><strong>ECCV 2022</strong> <a href="https://arxiv.org">Resolution-free Point Cloud Sampling Network with Data Distillation</a>, Tianxin Huang*, <strong>Jiangning Zhang</strong>*, Jun Chen, Yuang Liu, and Yong Liu | <a href="https://github.com/Tianxinhuang/PCDNet">Code</a> </li>

<li><strong>ECCV 2022</strong> <a href="https://arxiv.org">Learning to Train a Point Cloud Reconstruction Network without Matching</a>, Tianxin Huang, Xuemeng Yang, <strong>Jiangning Zhang</strong>, Jinhao Cui, Hao Zou, Jun Chen, Xiangrui Zhao, and Yong Liu | <a href="https://github.com/Tianxinhuang/PCLossNet">Code</a> </li>

<li><strong>CVPR 2022</strong> <a href="https://ieeexplore.ieee.org/abstract/document/9552566">Region-Aware Face Swapping</a>, Chao Xu*, <strong>Jiangning Zhang</strong>*, Miao Hua, Qian He, Zili Yi, and Yong Liu </li>

<li><strong>AAAI 2022</strong> <a href="https://ojs.aaai.org/index.php/AAAI/article/view/20236">SCSNet: An Efficient Paradigm for Learning Simultaneously Image Colorization and Super-Resolution</a>, <strong>Jiangning Zhang</strong>, Chao Xu, Jian Li, Yue Han, Yabiao Wang, Ying Tai, and Yong Liu </li>

<li><strong>NeurIPS 2021</strong> <a href="https://proceedings.neurips.cc/paper/2021/hash/e02e27e04fdff967ba7d76fb24b8069d-Abstract.html">Analogous to Evolutionary Algorithm: Designing a Unified Sequence Model</a>, <strong>Jiangning Zhang</strong>, Chao Xu, Jian Li, Wenzhou Chen, Yabiao Wang, Ying Tai, Shuo Chen, Chengjie Wang, Feiyue Huang, and Yong Liu | <a href="https://github.com/TencentYoutuResearch/BaseArchitecture-EAT">Code</a> </li>

<li><strong>ECCV 2020</strong> <span style="color:red">(Spotlight)</span> <a href="https://link.springer.com/chapter/10.1007/978-3-030-58558-7_18">DTVNet: Dynamic Time-Lapse Video Generation via Single Still Image</a>, <strong>Jiangning Zhang</strong>*, Chao Xu*, Liang Liu, Mengmeng Wang, Xia Wu, Yong Liu, and Yunliang Jiang | <a href="https://github.com/zhangzjn/DTVNet">Code</a> </li>

<li><strong>CVPR 2020</strong> <a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_FReeNet_Multi-Identity_Face_Reenactment_CVPR_2020_paper.html">FReeNet: Multi-Identity Face Reenactment</a>, <strong>Jiangning Zhang</strong>, Xianfang Zeng, Mengmeng Wang, Yusu Pan, Liang Liu, Yong Liu, Yu Ding, and Changjie Fan | <a href="https://github.com/zhangzjn/FReeNet">Code</a> </li>

<li><strong>CVPR 2020</strong> <a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Learning_by_Analogy_Reliable_Supervision_From_Transformations_for_Unsupervised_Optical_CVPR_2020_paper.html">Learning by Analogy: Reliable Supervision From Transformations for Unsupervised Optical Flow Estimation</a>, Liang Liu, <strong>Jiangning Zhang</strong>, Ruifei He, Yong Liu, Yabiao Wang, Ying Tai, Donghao Luo, Chengjie Wang, Jilin Li, and Feiyue Huang | <a href="https://github.com/lliuz/ARFlow">Code</a> </li>

<li><strong>ICASSP 2020</strong> <a href="https://ieeexplore.ieee.org/abstract/document/9052977">APB2FACE: Audio-Guided Face Reenactment with Auxiliary Pose and Blink Signals</a>, <strong>Jiangning Zhang</strong>, Liang Liu, Zhucun Xue, and Yong Liu | <a href="https://github.com/zhangzjn/APB2Face">Code</a> </li>

</ul>

## Journal
<ul>

<li><strong>TCSVT 2022</strong> <a href="https://ieeexplore.ieee.org/abstract/document/9797768">Multi-Level Spatial-Temporal Feature Aggregation for Video Object Detection</a>, Chao Xu, <strong>Jiangning Zhang</strong>, Mengmeng Wang, Guanzhong Tian, and Yong Liu </li>

<li><strong>IJIRA 2022</strong> <span style="color:red">(Best Paper Reward Nomination)</span> <a href="https://link.springer.com/article/10.1007/s41315-021-00167-2">Learning Hierarchical and Efficient Person Re-Identification for Robotic Navigation</a>, <strong>Jiangning Zhang</strong>, Chao Xu, Xiangrui Zhao, Liang Liu, Yong Liu, Jinqiang Yao, and Zaisheng Pan </li>

<li><strong>SPL 2022 </strong> <a href="https://ieeexplore.ieee.org/abstract/document/9552566">Real-Time Audio-Guided Multi-Face Reenactment</a>, <strong>Jiangning Zhang</strong>, Xianfang Zeng, Chao Xu, and Yong Liu | <a href="https://github.com/zhangzjn/APB2FaceV2">Code</a> </li>

<li><strong>TIE 2018</strong> <a href="https://ieeexplore.ieee.org/abstract/document/8566182">Learning-Based Hand Motion Capture and Understanding in Assembly Process</a>, Liang Liu, Yong Liu, and <strong>Jiangning Zhang</strong> </li>

</ul>

## ArXiv

<ul>

<li><strong>arXiv 2022 </strong> <a href="https://arxiv.org/abs/2206.09325">EATFormer: Improving Vision Transformer Inspired by Evolutionary Algorithm</a>, <strong>Jiangning Zhang</strong>, Xiangtai Li, Yabiao Wang, Chengjie Wang, Yibo Yang, Yong Liu, and Dacheng Tao | <a href="https://https://github.com/zhangzjn/EATFormer">Code</a> </li>

<li><strong>arXiv 2022 </strong> <a href="https://arxiv.org/abs/2207.04415v1">SFNet: Faster, Accurate, and Domain Agnostic Semantic Segmentation via Semantic Flow</a>, Xiangtai Li, <strong>Jiangning Zhang</strong>, Yibo Yang, Guangliang Cheng, Kuiyuan Yang, Yunhai Tong, and Dacheng Tao | <a href="https://github.com/lxtGH/SFSegNets">Code</a> </li>

<li><strong>arXiv 2022 </strong> <a href="https://arxiv.org/abs/2203.00259">Omni-frequency Channel-selection Representations for Unsupervised Anomaly Detection</a>, Yufei Liang*, <strong>Jiangning Zhang</strong>*, Shiwei Zhao, Runze Wu, Yong Liu, and Shuwen Pan | <a href="https://github.com/zhangzjn/OCR-GAN">Code</a> </li>

<li><strong>arXiv 2021 </strong> <a href="https://arxiv.org/abs/2112.10683">SelFSR: Self-Conditioned Face Super-Resolution in the Wild via Flow Field Degradation Network</a>, Xianfang Zeng*, <strong>Jiangning Zhang</strong>*, Liang Liu, Guangzhong Tian, and Yong Liu </li>

</ul>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2020.04 - Now*, From master to docker, pursuing Ph.D. in Zhejiang University, Hangzhou, China. 
- *2017.09 - 2020.04*, Pursuing M.D. in Zhejiang University, Hangzhou, China.
- *2013.09 - 2017.06*, Obtained B.S. in Wuhan University, Wuhan, China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2020.12 - Now*, YouTu Lab, Tencent, Shanghai, mentored by Researcher Jian Li, Researcher Yabiao Wang, and [Dr. Ying Tai](https://tyshiwo.github.io/).
