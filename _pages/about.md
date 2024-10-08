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

大家好，我是电子科技大学计算机学院，计算机科学与工程专业的博士二年级学生，导师是[宋井宽](https://jingkuansong.github.io/)教授和[高联丽](https://lianligao.github.io/)教授。
我本科就读于西南石油大学的安全工程专业。
之后，我于 2020 年考入电子科技大学攻读计算机硕士学位，导师为高联丽教授。
并于 2022 年经过硕博连读考核，转为博士研究生，目前的导师为宋井宽教授。 

我的研究兴趣包括计算机视觉中的持续学习, 计算机视觉，多模态学习。
现在，我的研究重点主要是研究多模态大模型在持续学习范式中的表现。

<span class='anchor' id='-news'></span>

# 🔥 消息
- *2024.10*: 🎉 一篇论文被NeurIPS 2024接收.
- *2023.10*: 🎉 获得国家奖学金.
- *2023.07*: 🎉 一篇论文被ACM Multimedia 2023接收.
- *2022.07*: 🎉 一篇论文被IEEE Transactions on Image Processing (TIP)接收.
- *2022.07*: 🎉 一篇论文被ACM Multimedia 2022接收.

<span class='anchor' id='-xl'></span>

# 🎓 教育经历
- *2022.09 - Now*,     博士研究生, <a href="https://en.uestc.edu.cn/"><img class="png" src="/images/UESTC_logo.png" width="20pt"></a> 电子科技大学, 计算机科学与工程学院, 计算机科学与技术, 中国成都
- *2020.09 - 2022.06*, 硕士研究生, <a href="https://en.uestc.edu.cn/"><img class="png" src="/images/UESTC_logo.png" width="20pt"></a> 电子科技大学, 计算机科学与工程学院, 计算机科学与技术, 中国成都
- *2010.09 - 2014.06*, 本科, <a href="https://www.swpu.edu.cn/"><img class="png" src="/images/SWPU_logo.png" width="23pt"></a> 
西南石油大学, 化学化工学院, 安全工程, 中国成都.
 
<span class='anchor' id='-lwzl'></span>

# 📝 论文
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS</div><img src='images/CoIN_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoIN: A Benchmark of Continual Instruction tuNing for Multimodel Large Language Model](https://arxiv.org/abs/2403.08350)

`Cheng Chen`, Junchen Zhu, Xu Luo, Hengtao Shen, Lianli Gao, Jingkuan Song. 

NeurIPS 2024 Datasets and Benchmarks

Keywords: Continual Learning, Instruction Tuning, Multimodel Large Language Model

[[Arxiv]](https://arxiv.org/abs/2403.08350) [[Dataset]](https://huggingface.co/datasets/Zacks-Chen/CoIN) [[Github]](https://github.com/zackschen/CoIN)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/IBM_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Redundancy-Free Sub-networks in Continual Learning](https://arxiv.org/abs/2312.00840)

`Cheng Chen`, Jingkuan Song, LianLi Gao, Heng Tao Shen 

Arxiv 2023

Keywords: Continual Learning, Information Bottleneck, SVD

[[Arxiv]](https://arxiv.org/abs/2312.00840) [[Github]](https://github.com/zackschen/IBM-Net)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2023</div><img src='images/CUCL_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CUCL: Codebook for Unsupervised Continual Learning](https://arxiv.org/abs/2311.14911)

`Cheng Chen`, Jingkuan Song, Xiaosu Zhu, Junchen Zhu, Lianli Gao, Hengtao Shen

ACM Multimedia 2023

Keywords: Continual Learning, Unsupervised Learning, Vector Quantization

[[Arxiv]](https://arxiv.org/abs/2311.14911) [[Github]](https://github.com/zackschen/CUCL)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2022</div><img src='images/DMM_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Continual Referring Expression Comprehension via Dual Modular Memorization](https://arxiv.org/abs/2311.14909)

Heng Tao Shen, `Cheng Chen`, Peng Wang, Lianli Gao, Meng Wang, Jingkuan Song

IEEE Transactions on Image Processing

Keywords: Continual Learning, Visual Grounding, Rehearsal

[[Arxiv]](https://arxiv.org/abs/2311.14909) [[Github]](github.com/zackschen/DMM)

</div>
</div> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2022</div><img src='images/CGP_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Class Gradient Projection For Continual Learning](https://arxiv.org/abs/2311.14909)

`Cheng Chen`, Ji Zhang, Jingkuan Song, Lianli Gao

ACM Multimedia 2022

Keywords: Continual Learning, Gradient Porjection, SVD

[[Arxiv]](https://arxiv.org/abs/2311.14909) [[Github]]([github.com/zackschen/DMM](https://github.com/zackschen/CGP))

</div>
</div> 

<span class='anchor' id='-ryjx'></span>

# 🥇 获奖情况
- *2023* 国家奖学金, 电子科技大学
- *2023* 优秀研究生, 电子科技大学 
- *2023* 学位一等奖学金, 电子科技大学
- *2022* 学位二等奖学金, 电子科技大学
- *2021* 学位二等奖学金, 电子科技大学