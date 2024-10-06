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

I am currently a senior researcher at Huawei Noah’s Ark Lab in Hong Kong, working on LLMs, MLLMs, and generative models. I obtained my Ph.D. from National University of Singapore in 2018, receiving [National Semiconductor Gold Medal](https://cde.nus.edu.sg/isem/awards-student/nsgoldmedalprize/#:~:text=Donated%20in%201994%20by%20the,award%20of%20another%20gold%20medal.). Prior to that, I received my bachelor's degree from Shanghai Jiao Tong University in 2014.

My group focuses on building generalizable AI systems from a data-centric perspective. Our mission is to understand the power and limitations of existing models, explore their corner cases, and propose efficient next-generation models and algorithms. Representative projects include:

- **Omi-modal Large Language Model**: [EMOVA](https://emova-ollm.github.io/)
- **Alignment of LLMs and MLLMs**: [Mistake Analysis](https://arxiv.org/abs/2310.10477), [CoSafe](https://arxiv.org/abs/2406.17626), [ECSO](https://gyhdog99.github.io/projects/ecso/)
- **Corner Case Understanding and Generation in Self-Driving**: [MagicDrive](https://gaoruiyuan.com/magicdrive/), [GeoDiffusion](https://kaichen1998.github.io/projects/geodiffusion/), [CODA]( https://coda-dataset.github.io/index.html)
- **Generalization of Deep Learning Models**: [OOD-Bench](https://arxiv.org/abs/2106.03721), [Continual Self-Supervised Learning](https://arxiv.org/abs/2104.12081), [MixedAE](https://arxiv.org/abs/2303.17152)

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 We have released [EMOVA](https://emova-ollm.github.io/), a novel end-to-end omni-modal model with SoTA vision-language and speech capabilities, further supporting emotional dialogue. Stay tuned for more details!
- *2024.09*: We hosted the ECCV Workshop "Multimodal Perception and Comprehension of Corner Cases in Autonomous Driving: Towards Next-Generation Solutions" ([W-CODA]( https://coda-dataset.github.io/w-coda2024/)) in Milan, Italy!
- *2024.09*: Two papers accepted by NeurIPS 2024!
- *2024.09*: One paper accepted by EMNLP 2024!
- *2024.08*: One paper accepted by COLM 2024!
- *2024.07*: Two papers accepted by ECCV 2024!
- *2024.06*: &nbsp;🎉🎉 [MagicDrive](https://gaoruiyuan.com/magicdrive/), as a core feature of [PanGu Large Model 5.0](https://www.huaweicloud.com/news/2024/20240621000945888.html), was unveiled at Huawei Developer Conference 2024 ([HDC 2024](https://developer.huawei.com/home/en/hdc/hdc2024.html))! [[see details](https://gaoruiyuan.com/news/hdc2024/)]
- *2024.02*: Two papers accepted by CVPR 2024!
- *2024.01*: Three papers accepted by ICLR 2024! See you in Vienna!

# ✨ Selected Projects
## Omi-modal Large Language Model (2024)

- Proposeed EMOVA, a novel end-to-end omni-modal LLM that can see, hear and speak. Weuseacontinuous vision encoder and a semantic-acoustic disentangled speech tokenizer for seamless omni-modal alignment and diverse speech style controllability. 
- Introduced an efficient text-centric omni-modal alignment which can further improve the vision-language and speech capabilities, even compared with the corresponding bi-modal aligned counterparts (i.e., image-text only and speech-text only alignment). 
- For the first time, EMOVA achieve state-of-the-art comparable performance on both the vision-language and speech benchmarks simultaneously, while supporting flexible spoken dialogues with vivid emotions.

## Alignment of LLMs and MLLMs (2023-2024)

- Proposed LLMs and MLLMs self-alignment framework [Mistake Analysis](https://arxiv.org/abs/2310.10477) (ICLR) and [ECSO](https://gyhdog99.github.io/projects/ecso/) (ECCV), enhancing large models' safety pass rates by over 20% while maintaining the model performance;
- Established [CoSafe](https://arxiv.org/abs/2406.17626) (EMNLP), a benchmark for evaluating LLM's safety in multi-turn dialogues, which systematically assesses large models' safety performance across multiple dialogue rounds.
- Featured in [QbitAI](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247701019&idx=5&sn=de7b3deaa9b55932507b285621e2beed&chksm=e8df6569dfa8ec7fc1f6db67506e1b7e7e4885340c9d1b77129e301b322151d4bf9c31607ca3&mpshare=1&srcid=10263crC46GFKRte2livXBtI&sharer_shareinfo=533163a6a0ac6a5bc6454af2a2051185&sharer_shareinfo_first=78063bf217476908c2020d891dad1935&from=timeline&scene=2&subscene=2&sessionid=1728183113&clicktime=1728199181&enterid=1728199181&ascene=45&fasttmpl_type=0&fasttmpl_fullversion=7404777-zh_CN-zip&fasttmpl_flag=0&realreporttime=1728199181972&devicetype=android-31&version=28003339&nettype=WIFI&abtest_cookie=AAACAA%3D%3D&lang=zh_CN&countrycode=CN&exportkey=n_ChQIAhIQdoN%2F7TbFsoQt3X6dRcOXfxL2AQIE97dBBAEAAAAAAA3UGp0KtNcAAAAOpnltbLcz9gKNyK89dVj0q%2Bc3BqqUsOzi0BBwt4xxbwhtw8aCgKLedEsn0TLUF0EitXmN%2BpsDJU9i3aNW5i7%2Bvhu830mNk0INWbG%2B%2FMhDSSBvBrSE7PMqIE4J6ODXZDV7bKklOYVMliSExUhDXuRQhN5AN0aP%2BobgaENxZbPRBoesCVve9Dhbljr7CDY8LMsOveIzYpE%2B8enAEk53Zxq%2FnpV628QOX4nNkuM89z2zmdq%2BhFG0AR50ATGc8Vg9erlXyLuFIl9OPsdf8B1tt6aIIgJeKDppAIL0uuYu3KTcQw%3D%3D&pass_ticket=XRpGkaLVP0TDhIqvLI2Vzr3jyeFwS%2FivS2QvymUetIpaAAtlIDWlQ6zvkc8U0IVg&wx_header=3); supported the [PanGu Large Model](https://m.yicai.com/news/101848233.html)'s compliance with the National Cyberspace Administration's AIGC Large Model Regulatory Filing.

## Corner Case Understanding and Generation in Self-Driving (2021-2023)

- Established a controlable video generation framework for corner cases in autonomous driving by integrating physical laws, featuring works such as [GeoDiffusion](https://kaichen1998.github.io/projects/geodiffusion/) (ICLR), [MagicDrive](https://gaoruiyuan.com/magicdrive/) (ICLR), and [DetDiffusion](https://arxiv.org/abs/2403.13304) (CVPR), addressing challenges in cross-view and cross-frame spatiotemporal consistency video generation.
- Developed [CODA](https://coda-dataset.github.io/index.html) (ECCV) and [CODA-LM](https://coda-dataset.github.io/coda-lm/index.html), autonomous driving corner case datasets, covering over 5000 rare scenes; these significantly reduced model perception and understanding performance (including GPT-4V), effectively evaluating and pinpointing model weaknesses in autonomous driving corner cases.
- Received coverage by [QbitAI](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652391793&idx=5&sn=356b7dd1e5e1c74933d3214b4bdb88a7&chksm=f12b3d80c65cb49637be329fe2b1c6e059c09548520e764c54be0e5a8394aada613e8a83f286&mpshare=1&srcid=1017ZpBWozjmNebv1PgwnSOb&sharer_shareinfo=6483570165361b75b2be6287ad0a7c9d&sharer_shareinfo_first=79ed3ae9dc384ff6b855d4b72a069de0&from=timeline&scene=2&subscene=2&sessionid=1728183113&clicktime=1728201777&enterid=1728201777&ascene=45&fasttmpl_type=0&fasttmpl_fullversion=7404777-zh_CN-zip&fasttmpl_flag=0&realreporttime=1728201777018#rd) and other public channels; implemented in Huawei vehicles and highlighted as a core feature of the [PanGu Large Model 5.0](https://www.huaweicloud.com/news/2024/20240621000945888.html) at the Huawei [HDC 2024](https://developer.huawei.com/home/en/hdc/hdc2024.html) [[see details](https://gaoruiyuan.com/news/hdc2024/)].

## Generalization of Deep Learning Models (2019-2021)

-	Proposed a multi-dimensional out-of-distribution (OOD) generalization benchmark, addressing OOD generalization challenges across three dimensions: training data, paradigms, and model architectures. Published works include [OOD-Bench](https://arxiv.org/abs/2106.03721) (CVPR Oral), [NAS-OOD](https://arxiv.org/abs/2109.02038) (ICCV), and [DecAug](https://arxiv.org/abs/2012.09382) (AAAI), among others.
-	Explored improving model generalization through self-supervised learning (SSL), with methods such as [MultiSiam](https://arxiv.org/abs/2108.12178) (ICCV) and [MixedAE](https://arxiv.org/abs/2303.17152) (CVPR) for complex multi-instance scenarios, [MoCE](https://arxiv.org/abs/2402.05382) (ICLR Spotlight) for task-customized SSL, [Continual SSL](https://arxiv.org/abs/2104.12081) (ICLR), and [SADE](https://arxiv.org/abs/2107.09249) (NeurIPS) for SSL multi-expert integration.
-	Widely cited by prominent researchers, including [Kaiming He](https://arxiv.org/abs/2401.14404) and [Percy Liang](https://arxiv.org/abs/2108.07258); featured by Synced ([OOD-Bench](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650818480&idx=3&sn=966e38608a44d7bff2385fb123f2f4d1&chksm=84e583ceb3920ad8e7706ce5aecd16f1107d4d0449f5768e5e777a90bd35c10553d4b47e74e7&mpshare=1&srcid=06154vepfHcp3nOMPgKQrAvz&sharer_sharetime=1623737761076&sharer_shareid=c877ebbbbffdb92f47cbc52b0ab90504&from=timeline&scene=2&subscene=2&sessionid=1728183113&clicktime=1728189719&enterid=1728189719&ascene=45&fasttmpl_type=0&fasttmpl_fullversion=7404777-zh_CN-zip&fasttmpl_flag=0&realreporttime=1728189719008&devicetype=android-31&version=28003339&nettype=WIFI&abtest_cookie=AAACAA%3D%3D&lang=zh_CN&countrycode=CN&exportkey=n_ChQIAhIQmp%2BlfJ7lEbkLXvCwYaF00hL2AQIE97dBBAEAAAAAALwbN3ljyRAAAAAOpnltbLcz9gKNyK89dVj0fd9oBYskpMoE0zOkx%2FwkaGTAvF%2FV%2BAhqJigCPYKDz8D2%2BTV6%2BnqUjhvVJPPIDJ0Ujregzd4Fx3f6lTqGIKYbAxdTUhj%2FoPwvr6pb%2FbVDPsAsBLwg%2FJJlYtEYRM8YI2drtf2H0fiMlCuU1WN51dK2YFmN%2FA7L4Vvd7ZPp1T%2FdLbuVJ9YikYE3b1vLycarE1S7U8MTS5zvf3FpddWSq%2B3%2ByPJ%2Bd%2FYducYfK6Wj%2F5fUNtTW5JU0UB%2FUcd%2B8f5xxgoghDzG8urqz9QM370pucn9Xjg%3D%3D&pass_ticket=KMJrvpVCFNTuxEFzJDlaA%2BDi%2BZLaKFI8gdkj1QbaypnzXQ4Wtaqo68gWI%2BkNlVkG&wx_header=3), [SADE](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650862111&idx=4&sn=b7564e668dbb69ff1a3e02a9295ef5e4&chksm=84e53661b392bf77ecb7b3b245a49d22b67410312a0dece8f79531df1c12a4acdb190427e8c1&mpshare=1&srcid=1126qwnPSEDNWsMDF9abXvE5&sharer_sharetime=1669442577223&sharer_shareid=18b556012d29d75d3ea40b2bdbb06025&from=timeline&scene=2&subscene=2&sessionid=1728183113&clicktime=1728189649&enterid=1728189649&ascene=45&fasttmpl_type=0&fasttmpl_fullversion=7404777-zh_CN-zip&fasttmpl_flag=0&realreporttime=1728189649063&devicetype=android-31&version=28003339&nettype=WIFI&abtest_cookie=AAACAA%3D%3D&lang=zh_CN&countrycode=CN&exportkey=n_ChQIAhIQzoYe5KPyyKeHyxDRWC7HWxL2AQIE97dBBAEAAAAAAHsPMecq8HEAAAAOpnltbLcz9gKNyK89dVj0%2FB8WxWr0vsQU4ce7cCcKj9x5UcWbRHTNX2MRjeCiVUHoMr9RWtsCGsFbGwVa5RbKQaE3aJjmdqhGh%2BdF%2BLQ08Wak8OiPEIASqcB1cKCWFXkv50kFssLK%2FRztFYP%2BemPyyJ%2F1pQAdjtbG7NAFOntiYXeM5sgVMnWEuoh3MOWkKNFhjVg8nvUFcT4nx6x5Qb%2FGz550fplEUHjkbCbzz0txM3aVEBTQ7i9H7xh4sIXgGXrNsRTYUBDdTWjSWH6gCyVGEyJckRsxPb0cqCqN5EUo2Q%3D%3D&pass_ticket=pbiYoFUwi%2FgomjjOq9G8MIxsk60%2FCCeEb4HzWJBLtua2YcJvVbZsaiuiTEAv3qvk&wx_header=3)) and AI Era ([DecAug](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652106632&idx=4&sn=c417156e8c09f92d32815f0294846967&chksm=f1209b79c657126fb7901d2a63930ffee1771d719e3f81fa0a84c0e5d45833ff9736655347cf&mpshare=1&scene=24&srcid=0414aQBwW5F5x2kDK5HGGsVq&sharer_sharetime=1623338055173&sharer_shareid=c877ebbbbffdb92f47cbc52b0ab90504&ascene=14&devicetype=android-31&version=28003339&nettype=WIFI&abtest_cookie=AAACAA%3D%3D&lang=zh_CN&countrycode=CN&exportkey=n_ChQIAhIQT0sIGbFS%2FDHknnFEDqifUBLiAQIE97dBBAEAAAAAAJ6NGugGU80AAAAOpnltbLcz9gKNyK89dVj0cERWLSu8cFaUkZhfe7t3y94dbTUlfOsg9iMf0l9EmmkWW5%2FOweexnycLeJ947z2KKmhC9vGjO4B07oYH4FJrvqKsl84%2FrJrtflwGNSSrujtiJ7rRNL5apgLwLigr3tf%2FbB%2BET71tR4%2FwTuEosiXl2SEnaOEtwnZMnzMdm0NXOxnDcAkV2iw58a1h5Agw7wYFJaaqmIyMaCv2W4HUAE44LtUYE91CgJsKXsSULoHnM5FAJLwZVwvJTbIrKFc%3D&pass_ticket=%2FRLHYt3bAB39iOmiYNbtJLgb7KFo30tPuTCa5AmUlyCqbmH1t13YhRrN8Y5lj3Wk&wx_header=3)). Algorithms applied in Huawei Music to decouple irrelevant user features, effectively reducing the "Matthew Effect" in recommendation systems.

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

**<span style="color:black;">• CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration</span>**

<span style="color:black;">Jiahui Gao, Renjie Pi, Tianyang Han, Han Wu, Lanqing Hong, Lingpeng Kong, Xin Jiang, Zhenguo Li</span>

<span style="color:black;"> Conference on Language Modeling (**COLM**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/pdf/2409.11365)

**<span style="color:black;">• Eyes Closed, Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation</span>**

<span style="color:black;">Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang</span>

<span style="color:black;">European Conference on Computer Vision (**ECCV**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2403.09572) [<span style="color:blue; text-decoration:underline;">Project</span>](https://gyhdog99.github.io/projects/ecso/)

**<span style="color:black;">• Implicit Concept Removal of Diffusion Models</span>**

<span style="color:black;">Zhili Liu, Kai Chen, Yifan Zhang, Jianhua Han, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, and James T. Kwok</span>

<span style="color:black;">European Conference on Computer Vision (**ECCV**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2310.05873)

**<span style="color:black;">• CVT-xRF: Contrastive In-Voxel Transformer for 3D Consistent Radiance Fields from Sparse Inputs</span>**

<span style="color:black;">Yingji Zhong, Lanqing Hong, Zhenguo Li, Dan Xu</span>

<span style="color:black;">Conference on Computer Vision and Pattern Recognition (**CVPR**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2403.16885)

**<span style="color:black;">• DetDiffusion: Synergizing Generative and Perceptive Models for Enhanced Data Generation and Perception</span>**

<span style="color:black;">Yibo Wang<sup>*</sup>, Ruiyuan Gao<sup>*</sup>, Kai Chen<sup>*</sup>, Kaiqiang Zhou, Yingjie Cai, Lanqing Hong, Zhenguo Li, Lihui Jiang, Dit-Yan Yeung, Qiang Xu, Kai Zhang</span>

<span style="color:black;">Conference on Computer Vision and Pattern Recognition (**CVPR**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/abs/2403.13304)

**<span style="color:black;">• Gaining Wisdom from Setbacks: Aligning Large Language Models via Mistake Analysis</span>**

<span style="color:black;">Kai Chen<sup>\*</sup>, Chunwei Wang<sup>\*</sup>, Kuo Yang, Jianhua Han, Lanqing Hong<sup>†</sup>, Fei Mi<sup>†</sup>, Hang Xu, Zhengying Liu, Wenyong Huang, Zhenguo Li, Dit-Yan Yeung, Lifeng Shang, Xin Jiang, Qun Liu</span>

<span style="color:black;">International Conference on Learning Representations (**ICLR**), 2024</span>

[<span style="color:blue; text-decoration:underline;">Paper</span>](https://arxiv.org/pdf/2310.10477)

**<span style="color:black;">• MagicDrive: Street View Generation with Diverse 3D Geometry Control</span>**

<span style="color:black;">Ruiyuan Gao<sup>\*</sup>, Kai Chen<sup>\*</sup>, Enze Xie, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung, Qiang Xu</span>

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
- [Kai CHEN]( https://kaichen1998.github.io/) (Hong Kong University of Science and Technology)
- [Ruiyuan GAO](https://gaoruiyuan.com/) (The Chinese University of Hong Kong)
- [Yunhao GOU](https://scholar.google.com/citations?user=RYDHIccAAAAJ&hl=zh-CN) (Hong Kong University of Science and Technology)
- [Runhui HUANG](https://scholar.google.com/citations?user=B5zcj4wAAAAJ&hl=zh-CN) (The University of Hong Kong)
- [Kaican LI](https://scholar.google.com/citations?hl=en&user=Mc-lzZMAAAAJ&view_op=list_works&sortby=pubdate) (Hong Kong University of Science and Technology)
- [Zhili LIU](https://scholar.google.com/citations?user=FdR09jsAAAAJ&hl=zh-CN) (Hong Kong University of Science and Technology)
- [Yingji ZHONG](https://github.com/zhongyingji) (Hong Kong University of Science and Technology)

## Former Interns
- [Haoyue BAI](https://haoyuebaizju.github.io/) (University of Wisconsin-Madison)
- [Shoukang HU](https://skhu101.github.io/) (Sony AI)
- [Haonan WANG](https://charles-haonan-wang.me/) (National University of Singapore)
- [Longhui YU]( https://yulonghui.github.io/) (Peking University)
- [Xinyun ZHANG](https://yxgnahz.github.io/) (The Chinese University of Hong Kong)
- [Kaichen ZHOU](https://www.cs.ox.ac.uk/people/kaichen.zhou/) (University of Oxford)
