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
{% assign url = gsDataBaseUrl | append: "gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Senior Researcher at Tencent Hunyuan, leading a research team focused on **AI 3D Pipeline**. 
Our team is dedicated to reimagining the traditional 3D art pipeline using 3D generative models.
Our research primarily covers: **Artistic Mesh Generation**, **Unified 3D Multimodal Models**, **Auto UV Unwrapping**, **Auto Animation**, etc. Welcome to explore our AI models at [Hunyuan3D HomePage](https://3d.hunyuan.tencent.com/) or [Hunyuan3D Studio](https://3d.hunyuan.tencent.com/studio).

🔥🔥🔥<span style="color: #ee0909; font-weight: bold;">We are constantly recruiting both full-time members and interns.</span>🔥🔥🔥 If you are seeking any form of academic cooperation, please feel free to contact me via email <img src='./images/email.png' style="width: 1.0em;">  <span style="color: #0e159e; font-weight: bold;">zhuooochen@tencent.com</span> or WeChat <img src='./images/wechat-logo.png' style="width: 1.0em;"> <span style="color: #228315; font-weight: bold;">czxytg</span> (To expedite the process, please include basic information, such as your name, school, and research focus.).


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Three papers are accepted by CVPR 2026.
- *2026.01*: &nbsp;🎉🎉 Three papers are accepted by ICLR 2026.
- *2025.09*: &nbsp;🎉🎉 Two papers are accepted by NeurIPS 2025.
- *2025.04*: &nbsp;🎉🎉 One paper is accepted by ICML 2025.
- *2025.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2025.
- *2022.04*: &nbsp;🎉🎉 One paper is accepted by ICML 2022.
- *2020.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2020.
- *2019.11*: &nbsp;🎉🎉 One paper is accepted by AAAI 2020.
- *2019.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2019.


# 📝 Publications 

## Technical Reports

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technique Report 2025</div><img src='images/publications/report_hunyuan3Dstudio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hunyuan3D Studio: End-to-End AI Pipeline for Game-Ready 3D Asset Generation](https://arxiv.org/abs/2509.12815)

**Zhuo Chen** is project leader.

[**Paper**](https://arxiv.org/pdf/2509.12815) \| [**Studio**](https://3d.hunyuan.tencent.com/studio) 

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technique Report 2025</div><img src='images/publications/report_hunyuan3D2.0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hunyuan3D 2.0: Scaling Diffusion Models for High Resolution Textured 3D Assets Generation](https://arxiv.org/abs/2501.12202)

**Zhuo Chen** is project leader of the studio part.

[**Project**](https://3d-models.hunyuan.tencent.com) [**Paper**](https://arxiv.org/pdf/2501.12202) [**Code**](https://github.com/Tencent/Hunyuan3D-2) [**Studio**](https://3d.hunyuan.tencent.com/studio) 

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technique Report 2024</div><img src='images/publications/report_hunyuan3D1.0.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hunyuan3D 1.0: A Unified Framework for Text-to-3D and Image-to-3D Generation](https://arxiv.org/abs/2411.02293)

**Zhuo Chen** is project leader of the Multi-view Generation part.

[**Project**](https://3d-models.hunyuan.tencent.com) [**Paper**](https://arxiv.org/pdf/2411.02293) [**Code**](https://github.com/Tencent-Hunyuan/Hunyuan3D-1) 

</div>
</div>



## Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/publications/cvpr2026_meshpro.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mesh-Pro: Asynchronous Advantage-guided Ranking Preference Optimization for Artist-style Quadrilateral Mesh Generation](https://arxiv.org/abs/2603.00526)

**Zhuo Chen** is project leader.

[**Paper**](https://arxiv.org/pdf/2603.00526) [**Studio**](https://3d.hunyuan.tencent.com/studio/creation/role/poly)

- A novel 3D-aware RL algorithm named Advantage-guided Ranking Preference Optimization (ARPO).

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/publications/cvpr2026_xpart.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[X-Part: High Fidelity And Structure Coherent Shape Decomposition And Completion](https://arxiv.org/abs/2509.08643)

**Zhuo Chen** is project leader.

[**Project**](https://yanxinhao.github.io/Projects/X-Part/) [**Paper**](https://arxiv.org/pdf/2509.08643) [**Code**](https://github.com/Tencent-Hunyuan/Hunyuan3D-Part/tree/main/XPart) [**Studio**](https://3d.hunyuan.tencent.com/studio/creation/role/poly)

- A controllable generative model designed to decompose a holistic 3D object into semantically meaningful and structurally coherent parts with high geometric fidelity.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/publications/cvpr2026_matpedia.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MatPedia: A Universal Generative Foundation for High-Fidelity Material Synthesis](https://arxiv.org/abs/2511.16957)

**Zhuo Chen** is project leader.

[**Paper**](https://arxiv.org/pdf/2511.16957)

- A unified framework handling multiple material tasks—text-to-material, image-tomaterial, and intrinsic decomposition.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publications/iclr2026_partxmllm.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Part-X-MLLM: Part-aware 3D Multimodal Large Language Model](https://arxiv.org/abs/2511.13647)

**Zhuo Chen** is project leader.

[**Project**](https://chunshi.wang/Part-X-MLLM/) [**Paper**](https://arxiv.org/pdf/2511.13647) [**Code**](https://github.com/AiEson/Part-X-MLLM) [**Demo**](https://chunshi.wang/Part-X-MLLM/#playground)

- A native 3D multimodal large language model that unifies diverse 3D tasks by formulating them as programs in a structured, executable grammar.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publications/iclr2026_quadgpt.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[QuadGPT: Native Quadrilateral Mesh Generation with Autoregressive Models](https://arxiv.org/abs/2509.21420)

**Zhuo Chen** is project leader.

[**Paper**](https://arxiv.org/pdf/2509.21420) 

- The first autoregressive framework for generating quadrilateral meshes in an end-to-end manner.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publications/iclr2026_artuv.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ArtUV: Artist-style UV Unwrapping](https://arxiv.org/abs/2509.20710)

**Zhuo Chen** is project leader.

[**Paper**](https://arxiv.org/pdf/2509.20710) 

- A fully automated, end-to-end method for generating artist-style UV unwrapping.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/publications/neurips2025_autoconnect.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Auto-Connect: Connectivity-Preserving RigFormer with Direct Preference Optimization](https://arxiv.org/abs/2506.11430)

**Zhuo Chen** is project leader.

[**Project**](https://autoconnectrig.github.io/) [**Paper**](https://arxiv.org/pdf/2506.11430) 

- A novel approach for automatic rigging that explicitly preserves skeletal connectivity through a connectivity-preserving tokenization scheme.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/publications/neurips2025_meshrft.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mesh-RFT: Enhancing Mesh Generation via Fine-grained Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.16761)

**Zhuo Chen** is project leader.

[**Project**](https://hitcslj.github.io/mesh-rft/) [**Paper**](https://arxiv.org/pdf/2505.16761) 

- A novel fine-grained reinforcement finetuning framework that employs Masked Direct Preference Optimization (M-DPO)
to enable localized refinement 3D mesh generation.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/publications/icml2025_freemesh.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FreeMesh: Boosting Mesh Generation with Coordinates Merging](https://arxiv.org/abs/2505.13573)

**Zhuo Chen** is project leader.

[**Project**](https://hitcslj.github.io/mesh-rft/) [**Paper**](https://arxiv.org/pdf/2505.13573) 

- A mathematical framework, PTME, to evaluate existing mesh tokenizers without
any training.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/publications/cvpr2025_bpt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BPT: Scaling Mesh Generation via Compressive Tokenization](https://arxiv.org/abs/2411.07025)

[**Project**](https://whaohan.github.io/bpt/) [**Paper**](https://arxiv.org/pdf/2411.07025) [**Code**](https://github.com/whaohan/bpt)

- A compressive yet efficient mesh representation called Blocked and Patchified Tokenization.

</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.