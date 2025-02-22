---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Bio

My name is Ge Chunjiang. I am currently a fifth year PhD candidate in Tsinghua University. My research interest lies in Computer Vision and Multimodal Foundation Models, and the ultimate goals are towards enabling machine learning models to understand the open world, interact with the open world. I am now a Ph.D candidate of Department of Automation, Tsinghua University, advised by Prof. [Gao huang](http://www.gaohuang.net/). Before coming to Department of Automation, I received B.S. in Department of Physics, Tsinghua University. **I am actively seeking postdoctoral positions and industrial opportunities.**

我是葛春江，目前是清华大学五年级的博士生。我兴趣是计算机视觉和多模态基础模型，最终目标是使机器学习模型可以理解开放世界，并和开放世界交互。我目前就读于清华大学自动化系。我在清华大学物理系获得数理基础科学学位。我在寻求**博士后和工业界**的机会。

My research interests include:

1. **Multimodal Foundation Models**. I think the foundation models should build on physical world. Hence, to understand the real world, vision is essential. My work focuses on improving the foundation's visual capabilities, e.g., on high resolution images ([ConvLLaVA](https://arxiv.org/abs/2405.15738), [LLaVA-UHD](https://arxiv.org/abs/2403.11703)), long videos~([OVO-bench](https://arxiv.org/abs/2501.05510),[T2Vid](https://arxiv.org/abs/2411.19951)). I also interested in integrate visual understanding and generation.
2. **Computer Vision Architectures**. My research interests include building efficient and effective vision architectures, e.g., convolution neural networks, self-attention, linear attention, to accelerate inference speed and reduce model size. My work includes integration of self-attention and convolution ([ACMix](https://arxiv.org/abs/2111.14556)), efficient linear attention ([MILA](https://arxiv.org/abs/2405.16605)).
3. **Learning Robust and Generalizable Representations**. I am interested in learning robust and generalizable representations through, e.g., domain adaptation ([DAPrompt](https://arxiv.org/abs/2202.06687)), causal prediction ([SEAD](https://ojs.aaai.org/index.php/AAAI/article/view/25142)). Besides, making models' behavior more controllable is also my interest ([D3PO](https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Using_Human_Feedback_to_Fine-tune_Diffusion_Models_without_Any_Reward_CVPR_2024_paper.pdf)).

If you're interested in my work or personal development, feel free to contact me. I can arrange 30 minutes per week to communicate with you. You can contact me by email.

我每周可以安排30分钟的时间和同学们交流，可以给我发邮件联系。如果你有微信，可以 [微信](https://github.com/John-Ge/John-Ge.github.io/blob/master/images/wechat.jpg) 联系。

# Survices

- Conference: CVPR, NIPS, ICCV, ICML, ECCV;
- Journal: TIP, TCSVT;


# News

- [2024/05] I am excited to announce that our project and paper, [ConvLLaVA](https://arxiv.org/abs/2405.15738), has been released. We employ a hierarchical backbone for High resolution understanding, which is efficient and effective. Welcome cooperation!
<!-- - [2023/08] I become a contributor of project [OpenRLHF](https://github.com/OpenLLMAI/OpenRLHF/tree/main).  -->
- [2023/06] I establish a github repo for collecting papers on [foundation models](https://github.com/John-Ge/awesome-foundation-models). Welcome pull requests and collaboration。

# Selected Publications

**ConvLLaVA: Hierarchical Backbones as Visual Encoder for Large Multimodal Models**\
**Chunjiang Ge**, Sijie Cheng, Ziming Wang, Jiale Yuan, Yuan Gao, Jun Song, Shiji Song, Gao Huang, Bo Zheng \
**TL; DR:** We propose to employ a five stage ConvNeXt as the visual encoder of LMM to compress visual tokens, greatly improves performance on high resolution benchmarks and efficiency.\
<a href="http://arxiv.org/abs/2405.15738"> 
    <img src="https://img.shields.io/badge/arXiv-2405.15738-b31b1b.svg?logo=arXiv">
</a>
<a href="https://github.com/alibaba/conv-llava"> 
    <img src="https://img.shields.io/badge/Github-ConvLLaVA-181717.svg?logo=GitHub">
</a>
<a href="https://huggingface.co/collections/ConvLLaVA/convllava-66519ef0ccdee62544bd19bf"> 
    <img src="https://img.shields.io/badge/🤗%20Hugging%20Face-Models-ffd21e">
</a>
<a href="https://modelscope.cn/organization/ConvLLaVA?tab=model"> 
    <img src="https://img.shields.io/badge/🤖%20ModelScope-Models-5f4cf2.svg">
</a>
<a href="https://github.com/alibaba/conv-llava/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/alibaba/conv-llava?color=ccf" />
</a>

**Domain Adaptation via Prompt Learning**\
**Chunjiang Ge**, Rui Huang, Mixue Xie, Zihang Lai, Shiji Song, Shuang Li, Gao Huang.  \
**TL; DR:** We propose a novel domain adaptation method, DAPrompt, which learns a set of domain-specific prompts to avoid information loss resulted from domain alignment.\
<a href="https://arxiv.org/abs/2202.06687"> 
    <img src="https://img.shields.io/badge/arXiv-2202.06687-b31b1b.svg?logo=arXiv">
</a>
  <a href="https://github.com/LeapLabTHU/DAPrompt"> 
    <img src="https://img.shields.io/badge/Github-DAPrompt-181717.svg?logo=GitHub">
</a>
<a href="https://github.com/LeapLabTHU/DAPrompt/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/LeapLabTHU/DAPrompt?color=ccf" />
</a>

**On the Integration of Self-Attention and Convolution**\
Pan, Xuran, **Chunjiang Ge**, Rui Lu, Shiji Song, Guanfu Chen, Zeyi Huang, and Gao Huang.  \
**TL; DR:** We propose an operator, ACMix, which integrates convolution and self-attention with most compute sharing.\
<a href="(https://arxiv.org/abs/2111.14556"> 
    <img src="https://img.shields.io/badge/arXiv-2111.14556-b31b1b.svg?logo=arXiv">
</a>
  <a href="https://github.com/LeapLabTHU/ACmix"> 
    <img src="https://img.shields.io/badge/Github-ACmix-181717.svg?logo=GitHub">
</a>
<a href="https://github.com/LeapLabTHU/ACmix/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/LeapLabTHU/ACmix?color=ccf" />
</a>

---

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=5fymzl2m77g&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
