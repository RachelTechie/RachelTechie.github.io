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

# 💬 About Me

I am currently a senior researcher at Huawei Noah’s Ark Lab in Hong Kong. I obtained my Ph.D. from the National University of Singapore in 2018, receiving the [National Semiconductor Gold Medal](https://cde.nus.edu.sg/isem/awards-student/nsgoldmedalprize/#:~:text=Donated%20in%201994%20by%20the,award%20of%20another%20gold%20medal.) under the supervision of Dr. [Ye Zhisheng](https://cde.nus.edu.sg/isem/staff/ye-zhisheng/). Prior to that, I received my bachelor's degree from Shanghai Jiao Tong University in 2014.

My group focuses on Machine Learning and Artificial Intelligence, aiming to build generalizable AI systems from a data-centric perspective. Our mission is to understand the power and limitations of existing models, explore their corner cases, and develop efficient next-generation models and algorithms. Representative projects include:

- **Omi-modal Large Language Model**: [EMOVA](https://emova-ollm.github.io/)
- **Alignment of LLMs and MLLMs**: [Mistake Analysis]( https://arxiv.org/abs/2310.10477), [CoSafe]( https://arxiv.org/abs/2406.17626), [ECSO]( https://gyhdog99.github.io/projects/ecso/)
- **Corner Case Perception and Generation**: [GeoDiffusion]( https://kaichen1998.github.io/projects/geodiffusion/), [MagicDrive]( https://gaoruiyuan.com/magicdrive/), [DetDiffusion]( https://arxiv.org/abs/2403.13304), [CODA]( https://coda-dataset.github.io/index.html)
- **Out-of-distribution Generalization**: [OOD-Bench](https://arxiv.org/abs/2106.03721), [Continual Self-Supervised Learning]( https://arxiv.org/abs/2104.12081), [MixedAE]( https://arxiv.org/abs/2303.17152), [MultiSiam](https://arxiv.org/abs/2108.12178)

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 We have released [EMOVA](https://emova-ollm.github.io/), a novel end-to-end omni-modal model with SoTA vision-language and speech capabilities, further supporting emotional dialogue. Stay tuned for more details!
- *2024.09*: We hosted the Workshop on Multimodal Perception and Comprehension of Corner Cases in Autonomous Driving: Towards Next-Generation Solutions ([W-CODA]( https://coda-dataset.github.io/w-coda2024/)) at ECCV 2024 in Milan, Italy!
- *2024.09*: Two papers accepted by NeurIPS 2024!
- *2024.09*: One paper accepted by EMNLP 2024!
- *2024.07*: Two papers accepted by ECCV 2024!
- *2024.02*: Two papers accepted by CVPR 2024!
- *2024.02*: Code and checkpoints of [GeoDiffusion]( https://kaichen1998.github.io/projects/geodiffusion/) and [MagicDrive](https://gaoruiyuan.com/magicdrive/) have been released. Welcome to try!
- *2024.01*: Three papers accepted by ICLR 2024! See you in Vienna!

# ✨ Selected Projects

# 📝 Recent Publications
The full publication list can be found on [Google Scholar](https://scholar.google.com.sg/citations?user=2p7x6OUAAAAJ&hl=en).
## Preprint:
**<span style="color:black;">• EMOVA: Empowering Language Models to See, Hear and Speak with Vivid Emotions</span>**

<span style="color:black;">Kai Chen<sup>\*</sup>, Yunhao Gou<sup>\*</sup>, Runhui Huang<sup>\*</sup>, Zhili Liu<sup>\*</sup>, Daxin Tan<sup>\*</sup>, Jing Xu, Chunwei Wang, Yi Zhu, Yihan Zeng, Kuo Yang, Dingdong Wang, Kun Xiang, Haoyuan Li, Haoli Bai, Jianhua Han, Xiaohui Li, Weike Jin, Nian Xie, Yu Zhang, James T. Kwok, Hengshuang Zhao, Xiaodan Liang, Dit-Yan Yeung, Xiao Chen, Zhenguo Li, Wei Zhang, Qun Liu, Lanqing Hong<sup>†</sup>, Lu Hou<sup>†</sup>, Hang Xu<sup>†</sup></span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2409.18042) [<span style="color:blue; text-decoration:underline;">Project</span>](https://emova-ollm.github.io/)

**<span style="color:black;">• MagicDrive3D: Controllable 3D Generation for Any-View Rendering in Street Scenes</span>**

<span style="color:black;">Ruiyuan Gao, Kai Chen, Zhihao Li, Lanqing Hong<sup>†</sup>, Zhenguo Li, Qiang Xu<sup>†</sup></span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2405.14475) [<span style="color:blue; text-decoration:underline;">Project</span>](https://gaoruiyuan.com/magicdrive3d/)

**<span style="color:black;">• Automated Evaluation of Large Vision-Language Models on Self-Driving Corner Cases</span>**

<span style="color:black;">Kai Chen<sup>\*</sup>, Yanze Li<sup>\*</sup>, Wenhua Zhang<sup>\*</sup>, Yanxin Liu, Pengxiang Li, Ruiyuan Gao, Lanqing Hong<sup>†</sup>, Meng Tian, Xinhai Zhao, Zhenguo Li, Dit-Yan Yeung, Huchuan Lu, Xu Jia<sup>†</sup></span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2404.10595)

**<span style="color:black;">• Mixture of Cluster-conditional LoRA Experts for Vision-language Instruction Tuning</span>**

<span style="color:black;">Yunhao Gou, Zhili Liu, Kai Chen, Lanqing Hong, Hang Xu, Aoxue Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2312.12379)

## 2024
**<span style="color:black;">• CoSafe: Evaluating Large Language Model Safety in Multi-Turn Dialogue Coreference</span>**

<span style="color:black;">Erxin Yu, Jing Li, Ming Liao, Siqi Wang, Zuchen Gao, Fei Mi, Lanqing Hong</span>

<span style="color:black;">Empirical Methods in Natural Language Processing (**EMNLP**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2406.17626)

**<span style="color:black;">• Eyes Closed, Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation</span>**

<span style="color:black;">Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang</span>

<span style="color:black;">European Conference on Computer Vision (**ECCV**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2403.09572) [<span style="color:blue; text-decoration:underline;">Project</span>](https://gyhdog99.github.io/projects/ecso/)

**<span style="color:black;">• Implicit Concept Removal of Diffusion Models</span>**

<span style="color:black;">Zhili Liu, Kai Chen, Yifan Zhang, Jianhua Han, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, and James T. Kwok</span>

<span style="color:black;">European Conference on Computer Vision (**ECCV**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2310.05873)

**<span style="color:black;">• Gaining Wisdom from Setbacks: Aligning Large Language Models via Mistake Analysis</span>**

<span style="color:black;">Kai Chen<sup>\*</sup>, Chunwei Wang<sup>\*</sup>, Kuo Yang, Jianhua Han, Lanqing Hong<sup>†</sup>, Fei Mi<sup>†</sup>, Hang Xu, Zhengying Liu, Wenyong Huang, Zhenguo Li, Dit-Yan Yeung, Lifeng Shang, Xin Jiang, Qun Liu</span>

<span style="color:black;">International Conference on Learning Representations (**ICLR**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/pdf/2310.10477)

**<span style="color:black;">• MagicDrive: Street View Generation with Diverse 3D Geometry Control</span>**

<span style="color:black;">Ruiyuan Gao, Kai Chen, Enze Xie, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung, Qiang Xu</span>

<span style="color:black;">International Conference on Learning Representations (**ICLR**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/pdf/2310.02601) [<span style="color:blue; text-decoration:underline;">Project</span>](https://gaoruiyuan.com/magicdrive/)

**<span style="color:black;">• GeoDiffusion: Text-Prompted Geometric Control for Object Detection Data Generation</span>**

<span style="color:black;">Kai Chen<sup>\*</sup>, Enze Xie<sup>\*</sup>, Zhe Chen, Yibo Wang, Lanqing Hong<sup>†</sup>, Zhenguo Li, Dit-Yan Yeung</span>

<span style="color:black;">International Conference on Learning Representations (**ICLR**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/pdf/2306.04607) [<span style="color:blue; text-decoration:underline;">Project</span>](https://kaichen1998.github.io/projects/geodiffusion/)

# 🎖 Professional Services
- Industrial Chair of [3DV 2025]( https://3dvconf.github.io/2025/people/)
- Senior Program Committee Members of IJCAI [2023]( https://ijcai-23.org/spc-member-list/), 2024
- Organizer of ECCV Workshop [W-CODA]( https://coda-dataset.github.io/w-coda2024/)
- Reviewer of TPAMI, ICLR, NeurIPS, CVPR, ECCV, ICCV, etc.

# 🌐 Internship Opportunities
We are now recruiting self-motivated interns/full-time researchers. If you are interested in, please directly send your CV to my email.

## Current Interns
- [Kai CHEN]( https://kaichen1998.github.io/) (HKUST)
- [Ruiyuan GAO](https://gaoruiyuan.com/) (CUHK)
- [Yunhao GOU](https://scholar.google.com/citations?user=RYDHIccAAAAJ&hl=zh-CN) (HKUST)
- [Runhui HUANG](https://scholar.google.com/citations?user=B5zcj4wAAAAJ&hl=zh-CN) (HKU)
- [Kaican LI](https://scholar.google.com/citations?hl=en&user=Mc-lzZMAAAAJ&view_op=list_works&sortby=pubdate) (HKUST)
- [Zhili LIU](https://scholar.google.com/citations?user=FdR09jsAAAAJ&hl=zh-CN) (HKUST)
- [Yingji ZHONG](https://github.com/zhongyingji) (HKUST)

## Former Interns
- [Haoyue BAI](https://haoyuebaizju.github.io/) (University of Wisconsin-Madison)
- [Shoukang HU](https://skhu101.github.io/) (Sony AI)
- [Longhui YU]( https://yulonghui.github.io/) (Peking University)
- [Xinyun ZHANG](https://yxgnahz.github.io/) (CUHK)
- [Kaichen ZHOU](https://www.cs.ox.ac.uk/people/kaichen.zhou/) (University of Oxford)
