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

I received my Master degree from [Yale University](https://www.yale.edu/) in 2024, under the supervision of [Prof. Hongyu Zhao]([https://www.ece.pku.edu.cn/en/info/1095/1323.htm](https://ysph.yale.edu/profile/hongyu-zhao/)). I obtained my Bachelor degree from [Southern University of Science and Technology](https://www.sustech.edu.cn/en/) in 2022, advised by [Prof. xxx](#FIXME). For now, my research realm focuses on **#FIXME**.  
E-mail: #FIXME

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->
 
# 📖 Educations
- *2022.08 - 2024.06*, Master of Science (IS THIS RIGHT?), Yale University.
- *2018.09 - 2022.06*, Bachelor of Engineering (IS THIS RIGHT?), Southern University of Science and Technology.

# 🎖 Honors and Awards
- *2022* Excellent Graduate Award, Southern University of Science and Technology
- *2020* **National Scholarship**, Ministry of Education of the PRC (The highest scholarship for Chinese undergraduates)
- *2019* The First Prize of Outstanding Students in SUSTech (**Top 5%** in SUSTech)

# 🔥 News
- *2024.08*: Starting my PhD journey — wish me luck🍀!
- *2024.04*: &nbsp;🎉🎉 Our paper "SoftAct: A High-Precision Softmax Architecture for Transformers with Nonlinear Functions Support" has been accepted by IEEE TCSVT!
- *2024.02*: &nbsp;🎉🎉 Our paper "Adjustable Multi-Stream Block-Wise Farthest Point Sampling Acceleration in Point Cloud Analysis" has been accepted by IEEE TCAS-II!
- *2023.10*: &nbsp;🎉🎉 Yuzhe Fu presents [the work](https://youtu.be/3Yw3-jFeRaE) on 3D Point Cloud Neural Network Accelerator at IEEE/ACM ICCAD 2023!
- *2023.08*: &nbsp;🎉🎉 Our paper "Sagitta: An Energy-Efficient Sparse 3D-CNN Accelerator for Real-Time 3D Understanding" has been accepted by IEEE IOTJ!
- *2023.07*: &nbsp;🎉🎉 Our paper "An Energy-Efficient 3D Point Cloud Neural Network Accelerator with Efficient Filter Pruning, MLP Fusion, and Dual-Stream Sampling" has been accepted by IEEE/ACM ICCAD 2023!

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/SoftAct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SoftAct: A High-Precision Softmax Architecture for Transformers Supporting Nonlinear Functions](https://ieeexplore.ieee.org/document/10495359)

**Yuzhe Fu**, Changchun Zhou, Tianling Huang, Eryi Han, Yifan He, Hailong Jiao.

**2024**, *IEEE Transactions on Circuits and Systems for Video Technology*
[[pdf](../papers/TCSVT.pdf)]
<details>
<summary>Abstract</summary>
  Transformer-based deep learning networks are revolutionizing our society. The convolution and attention co-designed (CAC) Transformers have demonstrated superior performance compared to the conventional Transformer-based networks. However, CAC Transformer networks contain various nonlinear functions, such as softmax and complex activation functions, which require high precision hardware design yet typically with significant cost in area and power consumption. To address these challenges, SoftAct, a compact and high-precision algorithm-hardware co-designed architecture, is proposed to implement both softmax and nonlinear activation functions in CAC Transformer accelerators. An improved softmax algorithm with penalties is proposed to maintain precision in hardware. A stage-wise full zero detection method is developed to skip redundant computation in softmax. A compact and reconfigurable architecture with a symmetrically designed linear fitting module is proposed to achieve nonlinear functions. The SoftAct architecture is designed in an industrial 28-nm CMOS technology with the MobileViT-xxs network as the benchmark. Compared with the state of the art, SoftAct improves up to 5.87% network accuracy, 153.2× area efficiency, and 1435× overall efficiency.
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-II</div><img src='images/TCASII.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adjustable Multi-Stream Block-Wise Farthest Point Sampling Acceleration in Point Cloud Analysis](https://ieeexplore.ieee.org/document/10430381)

Changchun Zhou#, **Yuzhe Fu**#, Yanzhe Ma, Eryi Han, Yifan He, Hailong Jiao.

**2024**, *IEEE Transactions on Circuits and Systems II: Express Briefs* (# with equal contribution)
[[pdf](../papers/TCAS-II.pdf)]
<details>
<summary>Abstract</summary>
  Point cloud is increasingly used in a variety of applications. Farthest Point Sampling (FPS) is typically employed for down-sampling to reduce the size of point cloud and enhance the representational capability by preserving contour points in point cloud analysis. However, due to low parallelism and high computational complexity, high energy consumption and long latency are caused, which becomes a bottleneck of hardware acceleration. In this brief, we propose an adjustable multi-stream block-wise FPS algorithm, adjusted by four configurable parameters, according to hardware and accuracy requirements. A unified hardware architecture with one parameter is designed to implement the adjustable multi-stream block-wise FPS algorithm. Furthermore, we present a rapid searching algorithm to select the optimal configuration of the five parameters. Designed in an industrial 28-nm CMOS technology, the proposed hardware architecture achieves a latency of 0.005 (1.401) ms and a frame energy consumption of 0.09 (27.265) µJ/frame for 1 k (24 k) input points at 200 MHz and 0.9 V supply voltage. Compared to the state of the art, the proposed hardware architecture reduces the latency by up to 99.9%, saves the energy consumption by up to 99.5%, and improves the network accuracy by up to 9.34%.
</details>
</div>
</div>

# 📃 Patent
- Hailong Jiao, **Yuzhe Fu**, A high-precision approximate calculation device for softmax function, **2024**, *CN Patent*.
- Fengwei An, **Yuzhe Fu** *et al*., [Low-power-consumption stereo matching system and method for acquiring depth information](https://worldwide.espacenet.com/patent/search/family/073657313/publication/CN112070821A?q=CN112070821A), **2020**, *CN Patent*, CN112070821A / WO2022021912A1

# 🍀 Tape Out
- An energy-efficient pipelined and configurable 3D point cloud-based neural network accelerator is being designed in TSMC 28-nm HPC technology with an area of 2.0 mm×1.5 mm and is taped out in July 2023.
- A 4.5 TOPS/W sparse 3D-CNN accelerator for real-time 3D understanding was fabricated in UMC 55-nm low-power CMOS technology with an area of 4.2 mm×3.6 mm in August 2020.

# 🚀 Skills
- Familiar with Verilog HDL, PyTorch, Intel Distiller (Model Compression), Cadence (Genus and NCSim), Vivado.
- Knowledgeable in Python, JAVA, MATLAB, Shell, Makefile.

# ![0D4D876E](https://github.com/Yuzhe-Fu/Yuzhe-Fu.github.io/assets/54790390/34cd68b3-1087-400d-9c3a-1ea97768f74c) About Me: 
- I am a easy-going and spirited individual with a passion for life. My enthusiasm not only drives my own life but also positively influences those around me.
- Interests and Hobbies: fitness, jogging, swimming, photography, traveling. (Here is a short [📸 video](https://www.bilibili.com/video/BV19q4y1H716/?vd_source=5c9e9ee79e4910700f06815b0fd41bf3) about my graduation trip in 2021.)


<!-- 

# 🔥 News
- Proficient in digital integrated circuit (IC) front-end development, neural network model compression and FPGA development. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2020.07 - 2020.08*, algorithm-hardware development position, National Technology Company[nationstech](https://github.com/), China.
 -->
