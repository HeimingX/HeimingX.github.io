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

I am currently a Postdoctoral Research Fellow at the <a href="https://www.adelaide.edu.au/aiml/">Australian Institute for Machine Learning (AIML)</a> at The University of Adelaide, working under the supervision of <a href="https://lingqiao-adelaide.github.io/lingqiaoliu.github.io/">Prof. Lingqiao Liu</a>. Prior to that, I earned my Ph.D. degree in Computer Science from The University of Adelaide in 2022. Before coming to Adelaide, I completed my M.S. degree in Computer Science in 2018 at the <a href="https://palm.seu.edu.cn/">PAttern Learning and Mining (PALM) Lab</a>, Southeast University, China in 2018, where I was supervised by <a href="https://palm.seu.edu.cn/hxue/">Prof. Hui Xue</a>. My B.S. degree in Computer Science was awarded by China University of Mining and Technology in 2015.

I am interested in general ML and CV research problems, such as Multimodal Large Language Models (MLLMs), Semi-supervised Learning (SSL) for Multiple Domains (e.g., 2D image/3D point-cloud segmentation and text classification), Pretrained Foundation Models for Various Applications (e.g., few-shot segmentation and class-agnostic counting).


# 🔥 News
- *2024.12*: &nbsp;🎉 The code and OCG benchmark for our <a href="https://github.com/HeimingX/TAG">TAG</a> work (AAAI 2025) are now open-sourced. Feel free to explore and give it a try!
- *2024.12*: &nbsp;🎉 Our paper is accepted to AAAI 2025. Topic: Vision-based GUI Grounding
- *2024.10*: &nbsp;🎉 Our paper is accepted to WACV 2025. Topic: Class-agnostic Counting
- *2024.02*: &nbsp;🎉 Our paper is accepted to CVPR 2024. Topic: Few-shot Semantic Segmentation
- *2023.07*: &nbsp; Three papers are accepted to ICCV 2023. Topic: SSL with Pretrained Models; KD for DETR Models; Point Cloud Segmentation
- *2023.02*: &nbsp; Our paper is accepted to CVPR 2023. Topic: Domain Generalization for 3D Detection in BEV
- *2022.10*: &nbsp; Our paper is accepted to BMVC 2022. Topic: Open-Set Panoptic Segmentation
- *2022.09*: &nbsp; Our paper is accepted to NeurIPS 2022. Topic: Semi-supervised Semantic Segmentation
- *2022.07*: &nbsp; Our paper is accepted to ECCV 2022. Topic: FGVR with Few Data
- *2022.04*: &nbsp; Our paper is accepted to NAACL 2022. Topic: Semi-supervised Text Classification

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/2025_tag.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Attention-driven GUI Grounding: Leveraging Pretrained Multimodal Large Language Models without Fine-Tuning](https://arxiv.org/abs/2412.10840)

<strong>Hai-Ming Xu</strong>, Qi Chen, Lei Wang, Lingqiao Liu

The 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025)

[[Code](https://github.com/HeimingX/TAG)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2025_wacv.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A Simple-but-effective Baseline for Training-free Class-Agnostic Counting](https://arxiv.org/abs/2403.01418)

Yuhao Lin<sup>+</sup>, <strong>Hai-Ming Xu<sup>+</sup></strong>, Lingqiao Liu, Javen Qinfeng Shi 

(<sup>+</sup>: Equal contribution)

IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2025)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2024_musebar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MuseBarControl: Enhancing Fine-Grained Control in Symbolic Music Generation through Pre-Training and Counterfactual Loss](https://arxiv.org/pdf/2407.04331)

Yangyang Shu, <strong>Hai-Ming Xu</strong>, Ziqin Zhou, Anton van den Hengel, Lingqiao Liu

[[Project](https://ganperf.github.io/musebarcontrol.github.io/musebarcontrol/)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2024_cvpr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Unlocking the Potential of Pre-trained Vision Transformers for Few-Shot Semantic Segmentation through Relationship Descriptors](https://openaccess.thecvf.com/content/CVPR2024/html/Zhou_Unlocking_the_Potential_of_Pre-trained_Vision_Transformers_for_Few-Shot_Semantic_CVPR_2024_paper.html)

Ziqin Zhou, <strong>Hai-Ming Xu</strong>, Yangyang Shu, Lingqiao Liu

IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024) 

[[Code](https://github.com/ZiqinZhou66/FewSegwithRD.git)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2024_aaai.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Revisiting Open-Set Panoptic Segmentation](https://ojs.aaai.org/index.php/AAAI/article/view/28498)

Yufei Yin, Hao Chen, Wengang Zhou, Jiajun Deng, <strong>Hai-Ming Xu</strong>, Houqiang Li

The 38th Annual AAAI Conference on Artificial Intelligence (AAAI 2024)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2023_iccvw.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Progressive Feature Adjustment for Semi-supervised Learning from Pretrained Models](https://openaccess.thecvf.com/content/ICCV2023W/VCL/html/Xu_Progressive_Feature_Adjustment_for_Semi-Supervised_Learning_from_Pretrained_Models_ICCVW_2023_paper.html)

<strong>Hai-Ming Xu</strong>, Lingqiao Liu, Hao Chen, Ehsan Abbasnejad, Rafael Felix

IEEE/CVF International Conference on Computer Vision Workshop (ICCVW 2023)

[[Code](https://github.com/HeimingX/PFA_SSL)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2023_iccv_detrdistill.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DETRDistill: A Universal Knowledge Distillation Framework for DETR-families](http://openaccess.thecvf.com/content/ICCV2023/papers/Chang_DETRDistill_A_Universal_Knowledge_Distillation_Framework_for_DETR-families_ICCV_2023_paper.pdf)

Jiahao Chang<sup>+</sup>, Shuo Wang<sup>+</sup>, <strong>Hai-Ming Xu<sup>+</sup></strong>, Zehui Chen, Chenhongyi Yang, Feng Zhao

(<sup>+</sup>: Equal contribution)

IEEE/CVF International Conference on Computer Vision (ICCV 2023)

[[Code](https://github.com/BIVLab-USTC/DETRDistill)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2023_iccv_proto.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ProtoTransfer: Cross-Modal Prototype Transfer for Point Cloud Segmentation](https://openaccess.thecvf.com/content/ICCV2023/papers/Tang_ProtoTransfer_Cross-Modal_Prototype_Transfer_for_Point_Cloud_Segmentation_ICCV_2023_paper.pdf)

Pin Tang, <strong>Hai-Ming Xu</strong>, Chao Ma

IEEE/CVF International Conference on Computer Vision (ICCV 2023)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2023_cvpr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Towards Domain Generalization for Multi-view 3D Object Detection in Bird-Eye-View](http://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Towards_Domain_Generalization_for_Multi-View_3D_Object_Detection_in_Bird-Eye-View_CVPR_2023_paper.pdf)

Shuo Wang, Xinhai Zhao, <strong>Hai-Ming Xu</strong>, Zehui Chen, Dameng Yu, Jiahao Chang, Zhen Yang, Feng Zhao

IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR 2023)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2022_bmvc.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Dual Decision Improves Open-Set Panoptic Segmentation](https://arxiv.org/pdf/2207.02504)

<strong>Hai-Ming Xu</strong>, Hao Chen, Lingqiao Liu, Yufei Yin

The 33rd British Machine Vision Conference (BMVC 2022) 

[[Code](https://github.com/HeimingX/OPS_dual_decision)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2022_nips.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Semi-supervised Semantic Segmentation with Prototype-based Consistency Regularization](https://proceedings.neurips.cc/paper_files/paper/2022/file/a70ee7ea485e4fd36abbfc4adf591c28-Paper-Conference.pdf)

<strong>Hai-Ming Xu</strong>, Lingqiao Liu, Qiuchen Bian, Zhen Yang

Thirty-sixth Conference on Neural Information Processing Systems (NeurIPS 2022)

[[Code](https://github.com/HeimingX/semi_seg_proto)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2022_eccv.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Improving Fine-Grained Visual Recognition in Low Data Regimes via Self-Boosting Attention Mechanism](https://arxiv.org/abs/2208.00617)

Yangyang Shu, Baosheng Yu, <strong>Hai-Ming Xu</strong>, Lingqiao Liu

Proceedings of the European Conference on Computer Vision (ECCV), 2022.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/2022_naacl.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Progressive Class Semantic Matching for Semi-supervised Text Classification](https://arxiv.org/pdf/2205.10189)

<strong>Hai-Ming Xu</strong>, Lingqiao Liu, Ehsan Abbasnejad

Annual Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2022), <span style="color:red">selected as Oral presentation</span>.
</div>
</div>


- `IJCAI 2017` [Multiple indefinite kernel learning for feature selection](https://palm.seu.edu.cn/hxue/publications/Multiple%20Indefinite%20Kernel%20Learning%20for%20Feature%20Selection%20Abstract.pdf), Hui Xue, Yu Song, <strong>Hai-Ming Xu</strong>

- ``AAAI 2017`` [Solving indefinite kernel support vector machine with difference of convex functions programming](https://ojs.aaai.org/index.php/AAAI/article/download/10889/10748), <strong>Hai-Ming Xu</strong>, Hui Xue, Xiao-Hong Chen, Yun-Yun Wang. \| [[Code](https://github.com/HeimingX/IKSVM-DC)]

# 🎖 Awards
- *2018-2022*: University of Adelaide Research Scholarships. 
- *2018*: Outstanding Graduates, Ministry of Education of P.R. China
- *2016*: National Scholarship, Ministry of Education of P.R. China (Graduate)
- *2013*: National Scholarship, Ministry of Education of P.R. China (Undergraduate)
- *2013*: Honorable Mention of 2013 International Mathematical Contest in Modeling (MCM)
- *2012*: Bronze Medal for Youth Group of The Sixth Olympic International Youth Calligraphy and Painting
Contest (Calligraphy)

# 💼 Employment
- *2023.06 - (now)*: Postdoc at AIML, The University of Adelaide, Australia. Working with Prof. <a href="https://lingqiao-adelaide.github.io/lingqiaoliu.github.io/">Lingqiao Liu</a>.
- *2021.03 - 2023.03*, Research intern at Noah’s Ark Lab, Huawei, China. Working with Dr. <a href="https://scholar.google.com.au/citations?user=FaOqRpcAAAAJ&hl=en">Hao Chen</a>

# 📜 Services
- Journal Reviewer: IEEE Transactions on Image Processing (TIP), IEEE Transactions on Neural
Networks and Learning Systems(TNNLS), Neural Networks, Pattern Recognition, Neurocomputing
- Conference Reviewer: ICLR, ICCV, ECCV, BMVC, ACCV, WACV, ACL, NAACL, EMNLP