---
title: "Collections of Awesome Hyperbolic Representation and Deep Learning"
layout: page
permlink: /
---

<link rel="stylesheet" href="/style.css">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/marlin-codes/Awesome-Hyperbolic-Graph-Representation-Learning?color=yellow)  ![Forks](https://img.shields.io/github/forks/marlin-codes/Awesome-Hyperbolic-Graph-Representation-Learning?color=blue&label=Fork)

## Introduction

Recently, hyperbolic spaces have emerged as a promising alternative for processing data with a tree-like structure or power-law distribution, owing to its exponential growth property and tree-likeness prior. Different from the Euclidean space, which expands polynomially, the hyperbolic space grows exponentially which makes it gain natural advantages in abstracting tree-like or scale-free data with hierarchical organizations.  In this repository, we categorize papers related to hyperbolic representation learning into different types to facilitate researcher studies and to promote the development of the community. We will keep updating this repository with the latest research developments. We are aware that there will inevitably be some mistakes and oversights, so if you have any questions or suggestions, please feel free to contact us (menglin.yang[@]outlook.com).

<table>
<tr><td colspan="2"><a href="#latest-update" style="color:#B22222">1. Latest Update</a></td></tr> 
<tr><td colspan="2"><a href="#surveys-books-tools-tutorials" style="color:#B22222">2. Surveys, Books, Tools and Tutorials</a></td></tr>
<tr>
    <td>&ensp;<a href="#surveys">2.1 Surveys</a></td>
    <td>&ensp;<a href="#books">2.2 Books</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#tools">2.3 Tools</a></td>
    <td>&ensp;<a href="#tutorials">2.4 Tutorials</a></td>
</tr>
<tr><td colspan="2"><a href="#methods-and-models" style="color:#B22222">3. Methods and Models</a></td></tr> 
<tr>
    <td>&ensp;<a href="#hyperbolic-shallow-model">3.1 Hyperbolic Shallow Model</a></td>
    <td>&ensp;<a href="#hyperbolic-neural-network">3.2 Hyperbolic Neural Network</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#hyperbolic-graph-neural-network">3.3 Hyperbolic Graph Neural Network</a></td>
    <td>&ensp;<a href="#hyperbolic-transformer">3.4 Hyperbolic Transformer</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#mixed-curvature-learning">3.5 Mixed Curvature Learning</a></td>
    <td>&ensp;<a href="#semi-riemannian-learning">3.6 Semi-Riemannian Learning</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#hyperbolic-generative-models">3.7 Hyperbolic Generative Models</a></td>
    <td>&ensp;<a href="#hyperbolic-operations">3.8 Hyperbolic Operations</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#llm-and-hyperbolic-space">3.9 LLM && Hyperbolic Space</a></td>
    <td>&ensp;<a href="#analysis">3.10 Analysis</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#numerical-problems">3.11 Numerical Problems</a></td>
    <td>&ensp;<a href="#explicitly-tree-embedding">3.12 Explicitly Tree Embedding</a></td>
</tr>
<tr><td colspan="2"><a href="#applications" style="color:#B22222">4. Applications</a></td></tr> 
<tr>
    <td>&ensp;<a href="#natural-language-processing">4.1 Natural Language Processing</a></td>
    <td>&ensp;<a href="#computer-vision">4.2 Computer Vision</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#graph-embeddings">4.3 Graph Embedding</a></td>
    <td>&ensp;<a href="#recommender-systems">4.4 Recommender Systems</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#knowledge-graphs">4.5 Knowledge Graphs</a></td>
    <td>&ensp;<a href="#molecular-learning">4.6 Molecular Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#code-representation">4.7 Code Representation</a></td>
    <td>&ensp;<a href="#multi-label-learning">4.8 Multi-label Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#hyperbolic-metric-learning">4.9 Hyperbolic Metric Learning</a></td>
    <td>&ensp;<a href="#data-driven-geometry-learning">4.10 Data-driven Geometry Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#few-shot-learning">4.11 Few-Shot Learning</a></td>
    <td>&ensp;<a href="#open-vocabulary-learning">4.12 Open-Vocabulary Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#safety-and-robustness">4.13 Safety and Robustness</a></td>
    <td>&ensp;<a href="#environmental-monitoring">4.14 Environmental Monitoring</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#category-discovery">4.15 Category Discovery</a></td>
    <td>&ensp;<a href="#multi-criteria-learning">4.16 Multi-Criteria Learning</a></td>
</tr>
</table>





**Hyperbolic Slack Group**
- Slack: https://join.slack.com/t/hyperboliclearning/shared_invite/zt-1qcqgtwfr-HpsRSzDhvkAEal6dOnKDvA
- Website: https://hyperboliclearning.github.io/collection


## [Latest Update](#content)
- Jun 10, 2025 : add ICML 2025, ICML 2024 papers
- Jun  7, 2025 : update CVPR 2025, SIGIR 2025, ACL 2025 paper 🔥
- Feb 26, 2025 : update ICLR 2025 papers 
- Dec 29, 2024 : update NeurIPS 2024 papers 
- Dec 16, 2024 : add NeurIPS 2024 papers
- Sept 8, 2024 : add ICML 2024, KDD 2024, WWW 2024, SIGIR 2024, ICDE 2024, CVPR 2024 papers
 


> 🔥: [HELM: Hyperbolic Large Language Models via Mixture-of-Curvature Experts](https://arxiv.org/abs/2505.24722) by Neil He, Rishabh Anand, Hiren Madhu, Ali Maatouk, Smita Krishnaswamy, Leandros Tassiulas, Menglin Yang, Rex Ying

**ICML2025**
1. [Hyperbolic-PDE GNN: Spectral Graph Neural Networks in the Perspective of A System of Hyperbolic Partial Differential Equations](https://arxiv.org/abs/2505.23014), ICML 2025 \
*Juwei Yue, Haikuo Li, Jiawei Sheng, Xiaodong Li, Taoyu Su, Tingwen Liu, Li Guo*

1. [Sparse Spectral Training and Inference on Euclidean and Hyperbolic Neural Networks](https://arxiv.org/abs/2405.15481), ICML 2025 \
*Jialin Zhao, Yingtao Zhang, Xinghang Li, Huaping Liu, Carlo Cannistraci*

1. [Low-distortion and GPU-compatible Tree Embeddings in Hyperbolic Space](https://arxiv.org/abs/2502.17130), ICML 2025 \
*Max van Spengler, Pascal Mettes*

1. [Learning Along the Arrow of Time: Hyperbolic Geometry for Backward-Compatible Representation Learning](https://arxiv.org/abs/2506.05826), ICML 2025 \ 
*Ngoc Bui, Menglin Yang, Runjin Chen, Leonardo Neves, Mingxuan Ju, Zhitao Ying, Neil Shah, Tong Zhao*

1. [Hyperbolic Graph Transformer for Collaborative Filtering](https://arxiv.org/abs/2502.15693), ICML 2025 \
*Yang Xin, Xingrun Li, Heng Chang, Yang Jinze, Xihong Yang, Shengyu Tao, Maiko Shigeno, Ningkang Chang, Junfeng Wang, Dawei Yin, Erxue Min*

1. [Mixed-Curvature Decision Trees and Random Forests](https://arxiv.org/abs/2410.13879), ICML 2025 \
*Philippe Chlenski, Quentin Chu, Raiyan Khan, Kaizhu Du, Antonio Moretti, Itsik Pe'er*

1. [A Mixed-Curvature based Pre-training Paradigm for Multi-Task Vehicle Routing Solver](https://openreview.net/forum?id=JsPyLqCgks), ICML 2025 \
*Suyu Liu, Zhiguang Cao, Shanshan Feng, Yew Soon Ong*

1. [Curvature-aware Graph Attention for PDEs on Manifolds](https://xiucheng.org/assets/pdfs/icml25-curv-gt.pdf), ICML 2025 \
*Yunfeng Liao, Jiawen Guan, Xiucheng Li*

**CVPR2025**

1. [Hyperbolic Category Discovery](https://arxiv.org/abs/2504.06120), CVPR 2025 \
*Yuanpei Liu, Zhenqi He, Kai Han*

1. [Parameter-efficient Fine-tuning in Hyperspherical Space for Open-vocabulary Semantic Segmentation](https://arxiv.org/abs/2405.18840), CVPR 2025 \
*Zelin Peng, Zhengqin Xu, Zhilin Zeng, Changsong Wen, Yu Huang, Menglin Yang, Feilong Tang, Wei Shen*

1. [Hyperbolic Safety-Aware Vision-Language Models](https://arxiv.org/abs/2503.12127), CVPR 2025 \
*Tobia Poppi, Tejaswi Kasarla, Pascal Mettes, Lorenzo Baraldi, Rita Cucchiara*

1. [Hyperbolic Uncertainty-Aware Few-Shot Incremental Point Cloud Segmentation](https://cvpr.thecvf.com/virtual/2025/poster/34838), CVPR 2025 \
*Tanuj Sur, Samrat Mukherjee, Kaizer Rahaman, Subhasis Chaudhuri, Muhammad Haris Khan, Biplab Banerjee*

1. [Deep Change Monitoring: A Hyperbolic Representative Learning Framework and a Dataset for Long-term Fine-grained Tree Change Detection](https://arxiv.org/abs/2503.00643), CVPR 2025 \
*Yante Li, Hanwen Qi, Haoyu Chen, Liang Xinlian, Guoying Zhao*


**ACL Findings 2025**
1. [Enhancing Multi-Hop Reasoning for Question Answering with Hyperbolic Representations](https://2025.aclweb.org/program/find_papers/), ACL Findings 2025 \
*Simon Welz, Lucie Flek, Akbar Karimi*

**SIGIR 2025**
1. [VoRec: Enhancing Recommendation with Voronoi Diagram in Hyperbolic Space](https://sigir2025.dei.unipd.it/accepted-papers.html), SIGIR 2025 \
*Yong Chen, Li Li, Wei Peng, Songzhi Su*

1. [Large Language Models Enhanced Hyperbolic Space Recommender Systems](https://arxiv.org/abs/2504.05694), SIGIR 2025 \
*Wentao Cheng, Zhida Qin, Zexue Wu, Pengzhan Zhou, Tianyu Huang*

1. [Hyperbolic Multi-Criteria Rating Recommendation](https://sigir2025.dei.unipd.it/accepted-papers.html), SIGIR 2025 \
*Zhihao Guo, Ting Han, Peng Song, Chenjiao Feng, Kaixuan Yao, Jiye Liang*

---


**ICLR 2025**
1. [Compositional Entailment Learning for Hyperbolic Vision-Language Models](https://openreview.net/forum?id=3i13Gev2hV), ICLR 2025 \
   Avik Pal, Max van Spengler, Guido Maria D'Amely di Melendugno, Alessandro Flaborea, Fabio Galasso, Pascal Mettes

1. [Hyperbolic Genome Embeddings](https://openreview.net/forum?id=NkGDNM8LB0), ICLR 2025 \
   Raiyan R. Khan, Philippe Chlenski, Itsik Pe'er

1. [Tree-Wasserstein Distance for High Dimensional Data with a Latent Feature Hierarchy](https://openreview.net/forum?id=nYjAzwor9R), ICLR 2025 \
   Ya-Wei Eileen Lin, Ronald R. Coifman, Gal Mishne, Ronen Talmon

1. [Gyrogroup Batch Normalization](https://openreview.net/forum?id=d1NWq4PjJW), ICLR 2025 \
   Ziheng Chen, Yue Song, Xiaojun Wu, Nicu Sebe

1. [Spectro-Riemannian Graph Neural Networks](https://openreview.net/forum?id=2MLvV7fvAz), ICLR 2025 \
   Karish Grover, Haiyang Yu, Xiang song, Qi Zhu, Han Xie, Vassilis N. Ioannidis, Christos Faloutsos


**NeurIPS 2024**
1. [Learning Structured Representations with Hyperbolic Embeddings](https://arxiv.org/abs/2412.01023), NeurIPS 2024 \
Aditya Sinha, Siqi Zeng, Makoto Yamada, Han Zhao

1. [Hyperbolic Embeddings of Supervised Models](https://openreview.net/pdf/462449e98af15b416d5418ce67b4921a32541c11.pdf), NeurIPS 2024, [Slides](https://users.cecs.anu.edu.au/~rnock/docs/neurips24-nansw-slides.pdf) \
Richard Nock, Ehsan Amid, Frank Nielsen, Alexander Soen, Manfred Warmuth

1. [Language Models as Hierarchy Encoders](https://arxiv.org/abs/2401.11374), NeurIPS 2024 \
Yuan He, Zhangdie Yuan, Jiaoyan Chen, Ian Horrocks

1. [Non-Euclidean Mixture Model for Social Network Embedding](https://arxiv.org/pdf/2411.04876), NeurIPS 2024 \
Roshni G. Iyer, Yewen Wang, Wei Wang, Yizhou Sun


**ICML 2024**
1. [Hyperbolic Active Learning for Semantic Segmentation under Domain Shift](https://proceedings.mlr.press/v235/franco24a.html), ICML 2024 \
Luca Franco, Paolo Mandica, Konstantinos Kallidromitis, Devin Guillory, Yu-Teng Li, Trevor Darrell, Fabio Galasso

1. [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://proceedings.mlr.press/v235/fu24c.html), ICML 2024 \
Xingcheng Fu · Yisen Gao · Yuecen Wei · Qingyun Sun · Hao Peng · Jianxin Li · Xianxian Li

1. [Bringing Motion Taxonomies to Continuous Domains via GPLVM on Hyperbolic manifolds](https://proceedings.mlr.press/v235/jaquier24a.html), ICML 2024 \
Noémie Jaquier, Leonel Rozo, Miguel González-Duque, Viacheslav Borovitskiy, Tamim Asfour

1. [Hyperbolic Optimizer as a Dynamical System](https://proceedings.mlr.press/v235/alvarado24a.html), ICML 2024 \
Nico Alvarado, Hans Lobel

**KDD 2024**
1. [Hypformer: Exploring Efficient Hyperbolic Transformer Fully in Hyperbolic Space](https://arxiv.org/abs/2407.01290), KDD 2024 \
Menglin Yang, Harshit Verma, Delvin Ce Zhang, Jiahong Liu, Irwin King, Rex Ying

1. [Predicting Long-term Dynamics of Complex Networks via Identifying Skeleton in Hyperbolic Space](https://arxiv.org/abs/2408.09845), KDD 2024 \
Ruikun Li, Huandong Wang, Jinghua Piao, Qingmin Liao, Yong Li

1. [Improving Robustness of Hyperbolic Neural Networks by Lipschitz Analysis](https://dl.acm.org/doi/pdf/10.1145/3637528.3671875), KDD 2024 \
Yuekang Li*, Yidan Mao*, Yifei Yang, Dongmian Zou

**WWW 2024**
1. [An Efficient Automatic Meta-Path Selection for Social Event Detection via Hyperbolic Space](https://dl.acm.org/doi/10.1145/3589334.3645526), WWW 2024 \
Zitai Qiu. Congbo Ma, Jia Wu. Jian Yang

**ICLR 2024**
1. [Leveraging Hyperbolic Embeddings for Coarse-to-Fine Robot Design](https://arxiv.org/abs/2311.00462), ICLR 2024 \
*Heng Dong, Junyu Zhang, Chongjie Zhang*

1. [Fully Hyperbolic Convolutional Neural Networks for Computer Vision](https://arxiv.org/abs/2303.15919), ICLR 2024 \
*Ahmad Bdeir, Kristian Schwethelm, Niels Landwehr*

1. [Fast Hyperboloid Decision Tree Algorithms](https://arxiv.org/abs/2310.13841), ICLR 2024 \
*Philippe Chlenski, Ethan Turok, Antonio Moretti, Itsik Pe'er*

1. [Shadow Cones: A Generalized Framework for Partial Order Embeddings](https://arxiv.org/abs/2305.15215), ICLR 2024 \
*Tao Yu, Toni J.B. Liu, Albert Tseng, Christopher De Sa*

**SIGIR 2024**
1. [MetaHKG: Meta Hyperbolic Learning for Few-shot Temporal Reasonin](https://dl.acm.org/doi/10.1145/3626772.3657711), SIGIR 2024 \
Ruijie Wang, Yutong Zhang, Jinyang Li, Shengzhong Liu, Dachun Sun, Tianchen Wang, Tianshi Wang, Yizhuo Chen, Denizhan Kara and Tarek Abdelzaher

**ICDE 2024**
1. [Logical Relation Modeling and Mining in Hyperbolic Space for Recommendation](https://www.cs.emory.edu/~jyang71/files/logirec.pdf), ICDE 2024 \
Yanchao Tan, Hang Lv, Zihao Zhou, Wenzhong Guo, Bo Xiong, Weiming Liu, Chaochao Chen, Shiping Wang, Carl Yang

**CVPR 2024**
1. [Rethinking Generalizable Face Anti-spoofing via Hierarchical Prototype-guided Distribution Refinement in Hyperbolic Space](https://openaccess.thecvf.com//content/CVPR2024/papers/Hu_Rethinking_Generalizable_Face_Anti-spoofing_via_Hierarchical_Prototype-guided_Distribution_Refinement_in_CVPR_2024_paper.pdf), CVPR 2024 \
Chengyang Hu, Ke-Yue Zhang, Taiping Yao, Shouhong Ding, Lizhuang Ma

1. [Improving Visual Recognition with Hyperbolical Visual Hierarchy Mapping](https://arxiv.org/abs/2404.00974), CVPR 2024 \
Hyeongjun Kwon, Jinhyun Jang, Jin Kim, Kwonyoung Kim, Kwanghoon Sohn

1. [Hyperbolic Learning with Synthetic Captions for Open-World Detection](https://arxiv.org/abs/2404.05016), CVPR 2024 \
Fanjie Kong, Yanbei Chen, Jiarui Cai, Davide Modolo

1. [Hyperbolic Anomaly Detection](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Hyperbolic_Anomaly_Detection_CVPR_2024_paper.pdf), CVPR 2024 \
Huimin Li, Zhentao Chen, Yunhao Xu, Junlin Hu

1. [Accept the Modality Gap: An Exploration in the Hyperbolic Space](https://openaccess.thecvf.com/content/CVPR2024/papers/Ramasinghe_Accept_the_Modality_Gap_An_Exploration_in_the_Hyperbolic_Space_CVPR_2024_paper.pdf), CVPR 2024 \
Sameera Ramasinghe Violetta Shevchenko Gil Avraham Ajanthan Thalaiyasingam

1. [G^3-LQ: Marrying Hyperbolic Alignment with Explicit Semantic-Geometric Modeling for 3D Visual Grounding](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_G3-LQ_Marrying_Hyperbolic_Alignment_with_Explicit_Semantic-Geometric_Modeling_for_3D_CVPR_2024_paper.pdf), CVPR 2024 \
Yuan Wang, Yali Li, Shengjin Wang

## [Surveys, Books, Tools, Tutorials](#content)

### [Surveys](#content)

1. [Hyperbolic Deep Learning in Computer Vision: A Survey](https://arxiv.org/abs/2305.06611), arxiv 2023 \
   Pascal Mettes, Mina Ghadimi Atigh, Martin Keller-Ressel, Jeffrey Gu, Serena Yeung

1. [Hyperbolic Graph Neural Networks: A Review of Methods and Application](https://arxiv.org/abs/2202.13852), arxiv 2022.
[GitHub](https://github.com/marlin-codes/HGNNs) \
Menglin Yang, Min Zhou, Zhihao Li, Jiahong Liu, Lujia Pan, Hui Xiong, Irwin King

1. [Hyperbolic Deep Neural Networks: A Survey](https://arxiv.org/abs/2101.04562), TPAMI 2022.
[GitHub](https://github.com/xiaoiker/Awesome-Hyperbolic-NeuralNetworks) \
Wei Peng, Tuomas Varanka, Abdelrahman Mostafa, Henglin Shi, Guoying Zhao

1. [Hyperbolic Geometry in Computer Vision: A Survey](https://arxiv.org/pdf/2304.10764.pdf), arxiv 2023. \
   Pengfei Fang, Mehrtash Harandi, Trung Le, Dinh Phung


### [Books](#content)
1. [An Introduction to Geometric Topology](https://arxiv.org/pdf/1610.02592.pdf), 2022 \
Bruno Martelli

1. [Hyperbolic Geometry](https://arxiv.org/abs/2003.11180), 2020. \
Brice Loustau

1. [Manifolds and Differential Geometry](https://www.ams.org/books/gsm/107/gsm107-endmatter.pdf), 2009. \
Jeffrey M. Lee

1. [Introduction to Hyperbolic Geometry](https://link.springer.com/book/10.1007/978-1-4757-5585-5), 1995. \
A Ramsay, RD Richtmyer 


### [Tools](#content)

1. [Geoopt: Riemannian Adaptive Optimization Methods](https://github.com/geoopt/geoopt) ICLR 2019 \
Max Kochurov and Rasul Karimov and Serge Kozlukov

1. [Curvature Learning Framework](https://github.com/alibaba/Curvature-Learning-Framework) \
Alibaba

1. [GraphZoo: A Development Toolkit for Graph Neural Networks with Hyperbolic Geometries](https://github.com/AnoushkaVyas/GraphZoo) WWW 2022 \
Anoushka Vyas, Nurendra Choudhary, Mehrdad Khatir, Chandan K. Reddy

1. [HypLL: The Hyperbolic Learning Library](https://arxiv.org/abs/2306.06154), [GitHub](https://github.com/maxvanspengler/hyperbolic_learning_library) \
   Max van Spengler, Philipp Wirth, Pascal Mettes

1. [Geomstats](https://geomstats.github.io/), [Pymanopt](https://pymanopt.org/)

1. [Manify: A Python Library for Learning Non-Euclidean Representations](https://arxiv.org/abs/2503.09576) \
   Philippe Chlenski, Kaizhu Du, Dylan Satow, Itsik Pe'er

### [Tutorials](#content)

1. [Hyperbolic Deep Learning for Computer Vision](https://sites.google.com/view/hdlcv-cvpr23tutorial/homepage) \
   Pascal Mettes, Max van Spengler, Yunhui Guo, Stella Yu

1. [Hyperbolic networks: Theory, Architecture and Applications](https://nurendra.com/hyperbolic-networks-tutorial/) \
   Nurendra Choudhary, Nikhil Rao, Karthik Subbian, Srinivasan H. Sengamedu, Chandan Reddy

1. [Hyperbolic Graph Neural Networks: A Tutorial on Methods and Applications](https://hyperbolicgnn.github.io/), KDD 2023 \
    Min Zhou, Menglin Yang, Bo Xiong, Hui Xiong, Irwin King
   
1. [Hyperbolic Representation Learning for Computer Vision](https://sites.google.com/view/hyperbolic-tutorial-eccv22/homepage). Tutorial 2022 \
   Pascal Mettes, Mina Ghadimi Atigh, Martin Keller-Ressel, Jeffrey Gu, Serena Yeung@ECCV2022 \
   https://hyperbolic-representation-learning.readthedocs.io/en/latest/

1. [Hyperbolic Graph Representation Learning](https://hyperbolicgraphlearning.github.io/). Tutorial 2022 \
Min Zhou, Menglin Yang, Lujia Pan, Irwin King @ ECML-PKDD 2022

1. [Hyperbolic Neural Network](https://nurendra.me/hyperbolic-networks-tutorial/kdd-2022/). Tutorial 2022 \
Nurendra Choudhary, Nikhil Rao, Karthik Subbian, Srinivasan Sengamedu, Chandan Reddy @ KDD 2022

1. [Hyperbolic Hyperbolic embeddings in machine learning and deep learning](https://www.youtube.com/watch?v=-ksbWExpWis). Tutorial 2020 \
Octavian Ganea 2020.


## [Methods and Models](#content)

### [Hyperbolic Shallow Model](#content)

1. [Poincaré Embeddings for Learning Hierarchical Representations](https://arxiv.org/abs/1705.08039), NeurIPS 2017 \
Maximilian Nickel, Douwe Kiela

1. [Learning Continuous Hierarchies in the Lorentz Model of Hyperbolic Geometry](https://arxiv.org/abs/1806.03417), ICML 2018 \
Maximilian Nickel, Douwe Kiela

1. [Representation Tradeoffs for Hyperbolic Embeddings](https://arxiv.org/pdf/1804.03329.pdf), ICML 2018 \
   Frederic Sala, Christopher De Sa, Albert Gu, Christopher Re´

1. [Hyperbolic Entailment Cones for Learning Hierarchical Embeddings](https://arxiv.org/abs/1804.01882), ICML 2018 \
   Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann
   
1. [Lorentzian Distance Learning for Hyperbolic Representations](https://proceedings.mlr.press/v97/law19a/law19a.pdf), ICML 2019 \
   Marc T. Law, Renjie Liao, Jake Snell, Richard S. Zemel

1. [Hyperbolic Disk Embeddings for Directed Acyclic Graphs](https://arxiv.org/abs/1902.04335), ICML 2019 \
   Ryota Suzuki, Ryusuke Takahama, Shun Onoda

1. [The Dark Side of the Hyperbolic Moon](https://openreview.net/forum?id=zbKcFZ6Dbp), ICLR 2024 \
   Tao Yu, Toni J.B. Liu, Albert Tseng, Christopher De Sa
 
1.  [Tempered Calculus for ML: Application to Hyperbolic Model Embedding](https://arxiv.org/abs/2402.04163), arxiv 2024 \
   Richard Nock, Ehsan Amid, Frank Nielsen, Alexander Soen, Manfred K. Warmuth

### [Hyperbolic Neural Network](#content)

1. [Hyperbolic Neural Networks](https://arxiv.org/abs/1805.09112), NeurIPS 2018 \
Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann

1. [Hyperbolic Attention Networks](https://arxiv.org/abs/1805.09786), ICLR 2019 \
Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas

1. [Continuous Hierarchical Representations with Poincaré Variational Auto-Encoders](https://arxiv.org/abs/1901.06033), NeurIPS 2019 \
   Emile Mathieu, Charline Le Lan, Chris J. Maddison, Ryota Tomioka, Yee Whye Teh

1. [Hyperbolic Neural Network++](https://arxiv.org/abs/2006.08210), ICLR 2021 \
Ryohei Shimizu, Yusuke Mukuta, Tatsuya Harada

1. [Fully Hyperbolic Neural Networks](https://arxiv.org/abs/2105.14686), ACL 2022 \
Weize Chen, Xu Han, Yankai Lin, Hexu Zhao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou

1. [Poincaré ResNet](https://arxiv.org/abs/2303.14027), arxiv 2023 \
Max van Spengler, Erwin Berkhout, Pascal Mettes

1. [Lorentz ResNet](https://arxiv.org/abs/2412.14695), KDD 2025 \
Neil He, Menglin Yang, Rex Ying

1. [Riemannian Residual Neural Networks](https://arxiv.org/abs/2310.10013), arxiv 2023 \
   Isay Katsman, Eric Ming Chen, Sidhanth Holalkere, Anna Asch, Aaron Lou, Ser-Nam Lim, Christopher De Sa

1. [Nested Hyperbolic Spaces for Dimensionality Reduction and Hyperbolic NN Design](https://arxiv.org/abs/2112.03402), CVPR 2022 \
   Xiran Fan, Chun-Hao Yang, Baba C. Vemuri

1. [Fully Hyperbolic Convolutional Neural Networks for Computer Vision](https://openreview.net/forum?id=ekz1hN5QNh), ICLR 2024 \
   Ahmad Bdeir, Kristian Schwethelm, Niels Landwehr

1. [Hypformer: Exploring Efficient Hyperbolic Transformer Fully in Hyperbolic Space](https://arxiv.org/abs/2407.01290), KDD 2024 \
   Menglin Yang, Harshit Verma, Delvin Ce Zhang, Jiahong Liu, Irwin King, Rex Ying


### [Hyperbolic Graph Neural Network](#content)

1. [Hyperbolic Graph Convolutional Neural Networks](https://arxiv.org/abs/1910.12933), NeurIPS 2019 \
Ines Chami\*, Rex Ying\*, Christopher Ré, Jure Leskovec

1. [Hyperbolic Graph Neural Network](https://arxiv.org/abs/1910.12892), NeurIPS 2019  \
Qi Liu, Maximilian Nickel, Douwe Kiela

1. [Lorentzian Graph Convolutional Networks](https://arxiv.org/abs/2104.07477), WWW 2021 \
Yiding Zhang, Xiao Wang, Chuan Shi, Nian Liu, Guojie Song

1. [A Hyperbolic-to-Hyperbolic Graph Convolutional Network](https://arxiv.org/abs/2104.06942), CVPR 2021 \
Jindou Dai, Yuwei Wu, Zhi Gao, Yunde Jia

1. [Hyperbolic Graph Attention Network](https://arxiv.org/abs/1912.03046), Transcations on Big Data 2021 \
Yiding Zhang, Xiao Wang, Xunqiang Jiang, Chuan Shi, Yanfang Ye

1. [Unsupervised Hyperbolic Representation Learning via Message Passing Auto-Encoders](https://arxiv.org/abs/2103.16046), CVPR 2021 \
Jiwoong Park, Junho Cho, Hyung Jin Chang, Jin Young Choi

1. [$\kappa$HGCN: Tree-likeness Modeling via Continuous and Discrete Curvature Learning](https://arxiv.org/abs/2212.01793), KDD 2023 \
   Menglin Yang, Min Zhou, Lujia Pan, Irwin King
1. [Residual Hyperbolic Graph Convolution Networks](https://ojs.aaai.org/index.php/AAAI/article/view/29559), AAAI 2024 \
   Yangkai Xue, Jindou Dai, Zhipeng Lu, Yuwei Wu, Yunde Jia

1.  [Hyperbolic Graph Neural Networks at Scale: A Meta Learning Approach](https://arxiv.org/abs/2310.18918), NeurIPS 2023 \
   Nurendra Choudhary, Nikhil Rao, Chandan K. Reddy

### [Hyperbolic Transformer](#content)

1. [Hypformer: Exploring Efficient Transformer Fully in Hyperbolic Space](https://arxiv.org/abs/2407.01290), KDD 2024 \
   Menglin Yang, Harshit Verma, Delvin Ce Zhang, Jiahong Liu, Irwin King, Rex Ying

2. [Curve Your Attention: Mixed-Curvature Transformers for Graph Representation Learning](https://arxiv.org/abs/2309.04082), arxiv 2023 \
   Sungjun Cho, Seunghyuk Cho, Sungwoo Park, Hankook Lee, Honglak Lee, Moontae Lee

3. [Fully Hyperbolic Neural Networks](https://arxiv.org/abs/2105.14686), ACL 2022 \
Weize Chen, Xu Han, Yankai Lin, Hexu Zhao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou

1. [Hyperbolic Attention Networks](https://arxiv.org/abs/1805.09786), ICLR 2019 \
Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas

1. [Hyperbolic Neural Network++](https://arxiv.org/abs/2006.08210), ICLR 2021 \
   Ryohei Shimizu, Yusuke Mukuta, Tatsuya Harada

### [Theoretical Foundations](#content)
1. [Representation Tradeoffs for Hyperbolic Embeddings](https://arxiv.org/abs/1804.03329), ICML 2018 \
Christopher De Sa, Albert Gu, Christopher Ré, Frederic Sala

1. [Generalization Error Bound for Hyperbolic Ordinal Embedding](https://arxiv.org/abs/2105.10475), ICML 2021 \
   Atsushi Suzuki, Atsushi Nitanda, Jing Wang, Linchuan Xu, Marc Cavazza, Kenji Yamanishi

1. [Generalization Bounds for Graph Embedding Using Negative Sampling: Linear vs Hyperbolic](https://proceedings.neurips.cc/paper/2021/hash/09779bb7930c8a0a44360e12b538ae3c-Abstract.html), NeurIPS 2021 \
   Atsushi Suzuki, Atsushi Nitanda, jing wang, Linchuan Xu, Kenji Yamanishi, Marc Cavazza

### [Analysis](#content)

1. [The Numerical Stability of Hyperbolic Representation Learning](https://proceedings.mlr.press/v202/mishne23a.html), ICML 2023 \
   Gal Mishne, Zhengchao Wan, Yusu Wang, Sheng Yang
   
1. [Hyperbolic vs Euclidean Embeddings in Few-Shot Learning: Two Sides of the Same Coin](https://arxiv.org/abs/2309.10013) WACV \
   Gabriel Moreira, Manuel Marques, João Paulo Costeira, Alexander Hauptmann

1. [Where are we in embedding spaces? A Comprehensive Analysis on Network Embedding Approaches for Recommender Systems](https://arxiv.org/abs/2105.08908) KDD 2021 \
   Sixiao Zhang, Hongxu Chen, Xiao Ming, Lizhen Cui, Hongzhi Yin, Guandong Xu

1. [Improving Robustness of Hyperbolic Neural Networks by Lipschitz Analysis](https://dl.acm.org/doi/pdf/10.1145/3637528.3671875), KDD 2024 \
   Yuekang Li, Yidan Mao, Yifei Yang, Dongmian Zou

1. [Hyperbolicity Measures "Democracy" in Real-World Networks](https://arxiv.org/abs/1503.03061), Phys. Rev. E 2015
   Michele Borassi, Alessandro Chessa, and Guido Caldarelli

### [Numerical Problems](#content)
1. [The Numerical Stability of Hyperbolic Representation Learning](https://proceedings.mlr.press/v202/mishne23a.html), ICML 2023

1. [Representation Tradeoffs for Hyperbolic Embeddings](https://arxiv.org/pdf/1804.03329.pdf), ICML 2018 \
   Frederic Sala, Christopher De Sa, Albert Gu, Christopher Re´ 

### [Explicitly Tree Embedding](#content)
1. [Fast Hyperboloid Decision Tree Algorithms](https://openreview.net/forum?id=TTonmgTT9X), ICLR 2024 

1.  [Fitting trees to $\ell_1$-hyperbolic distances](https://openreview.net/forum?id=xo2lbfQE8I), NeurIPS 2023 \
   Joon-Hyeok Yim, Anna Gilbert

### [Mixed Curvature Learning](#content)

1. [Learning mixed-curvature representations in product spaces](https://openreview.net/forum?id=HJxeWnCcF7), ICLR 2019 \
   Albert Gu, Frederic Sala, Beliz Gunel, Christopher Ré

1. [Mixed-curvature variational autoencoders](), ICLR 2020 \
   Skopek, Ondrej, Octavian-Eugen Ganea, and Gary Bécigneul

1. [Constant Curvature Graph Convolutional Networks](https://arxiv.org/abs/1911.05076), ICML 2020 \
   Gregor Bachmann, Gary Bécigneul, Octavian-Eugen Ganea

1. [Mixed-curvature multi-relational graph neural network for knowledge graph completion](https://dl.acm.org/doi/abs/10.1145/3442381.3450118), WWW 2021 \
   Wang, Shen, Xiaokai Wei, Cicero Nogueira Nogueira dos Santos, Zhiguo Wang, Ramesh Nallapati, Andrew Arnold, Bing Xiang, Philip S. Yu, and Isabel F. Cruz.

1. [A Self-supervised Mixed-curvature Graph Neural Network](https://arxiv.org/abs/2112.05393), AAAI 2022 \
   Li Sun, Zhongbao Zhang, Junda Ye, Hao Peng, Jiawei Zhang, Sen Su, Philip S. Yu

1. [Enhancing Hyperbolic Graph Embeddings via Contrastive Learning](https://arxiv.org/abs/2201.08554), NeurIPS 2021 SSL Workshop \
   Jiahong Liu, Menglin Yang, Min Zhou, Shanshan Feng, Philippe Fournier-Viger

1. [Geometry Interaction Learning](https://arxiv.org/abs/2010.12135), NeurIPS 2020 \
   Shichao Zhu, Shirui Pan, Chuan Zhou, Jia Wu, Yanan Cao, Bin Wang

1. [FMGNN: Fused Manifold Graph Neural Network](https://arxiv.org/abs/2304.01081), TKDD 2023 \
   Cheng Deng, Fan Xu, Jiaxing Ding, Luoyi Fu, Weinan Zhang, Xinbing Wang

1. [Curve Your Attention: Mixed-Curvature Transformers for Graph Representation Learning](https://arxiv.org/abs/2309.04082), arxiv 2023 \
   Sungjun Cho, Seunghyuk Cho, Sungwoo Park, Hankook Lee, Honglak Lee, Moontae Lee
   
1. [Matrix Manifold Neural Networks++](https://openreview.net/forum?id=30aSE3FB3L), ICLR 2024 \
   Xuan Son Nguyen, Shuo Yang, Aymeric Histace

1. [Linear Classifiers in Product Space Forms](Puoya Tabaghi, Chao Pan, Eli Chien, Jianhao Peng, Olgica Milenkovic), arXiv 2022 \
   Puoya Tabaghi, Chao Pan, Eli Chien, Jianhao Peng, Olgica Milenkovic

1. [Principal Component Analysis in Space Forms](https://arxiv.org/abs/2301.02750), arXiv 2022 \
   Puoya Tabaghi, Michael Khanzadeh, Yusu Wang, Sivash Mirarab

1. [Mixed-Curvature Decision Trees and Random Forests](https://arxiv.org/abs/2410.13879), ICML 2025 \
   Philippe Chlenski, Quentin Chu, Raiyan R. Khan, Kaizhu Du, Antonio Khalil Moretti, Itsik Pe'er
   

### [Semi-Riemannian Learning](#content)

1. [Directed Graph Embeddings in Pseudo-Riemannian Manifolds](https://arxiv.org/abs/2106.08678), ICML 2021 \
   Aaron Sim, Maciej Wiatrak, Angus Brayne, Páidí Creed, Saee Paliwal

1. [Semi-Riemannian Graph Convolutional Networks](https://arxiv.org/abs/2106.03134), NeurIPS 2022 \
   Bo Xiong, Shichao Zhu, Nico Potyka, Shirui Pan, Chuan Zhou, Steffen Staab

1. [Ultrahyperbolic Neural Networks](https://openreview.net/forum?id=sf2BxJNXC3K), NeurIPS 2021 \
   Marc T Law

1. [Ultrahyperbolic Representation Learning](https://arxiv.org/abs/2007.00211), NeurIPS 2020 \
   Marc T. Law, Jos Stam


### [Hyperbolic Generative Models](#content)

1. [Latent Variable Modelling with Hyperbolic Normalizing Flows](https://arxiv.org/abs/2002.06336), ICML 2020  \
   Avishek Joey Bose, Ariella Smofsky, Renjie Liao, Prakash Panangaden, William L. Hamilton

1. [Hyperbolic Graph Diffusion Model](https://arxiv.org/abs/2306.07618), AAAI 2024 \
   Lingfeng Wen, Xuan Tang, Mingjie Ouyang, Xiangxiang Shen, Jian Yang, Daxin Zhu, Mingsong Chen, Xian Wei

1. [Hyperbolic VAE via Latent Gaussian Distributions](https://arxiv.org/abs/2209.15217), NeurIPS 2023 \
    Seunghyuk Cho, Juyong Lee, Dongwoo Kim

1. [Lorentzian fully hyperbolic generative adversarial network](https://arxiv.org/abs/2201.12825), arxiv 2022 \
   Eric Qu, Dongmian Zou

2. [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://arxiv.org/abs/2405.03188), ICML 2024 \
   Xingcheng Fu, Yisen Gao, Yuecen Wei, Qingyun Sun, Hao Peng, Jianxin Li, Xianxian Li

### [Hyperbolic Classifiers](#content)

**Support vector machines**
1. [Large-Margin Classification in Hyperbolic Space](https://arxiv.org/abs/1806.00437), AISTATS 2019\
   Hyunghoon Cho, Benjamin DeMeo, Jian Peng, Bonnie Berger

1. [Kernel Methods in Hyperbolic Spaces](https://openaccess.thecvf.com/content/ICCV2021/papers/Fang_Kernel_Methods_in_Hyperbolic_Spaces_ICCV_2021_paper.pdf), ICCV 2021 \
   Pengfei Fang, Mehrtash Harandi, Lars Petersson

1. [Robust Large-Margin Learning in Hyperbolic Space](https://arxiv.org/abs/2004.05465), NeurIPS 2020\
   Melanie Weber, Manzil Zaheer, Ankit Singh Rawat, Aditya Menon, Sanjiv Kumar

1. [Horospherical Decision Boundaries for Large Margin Classification in Hyperbolic Space](https://arxiv.org/abs/2302.06807), NeurIPS 2023 \
   Xiran Fan, Chun-Hao Yang, Baba C. Vemuri

**Random Forests**
1. [Hyperbolic Random Forests](https://arxiv.org/abs/2308.13279), TMLR 2024 \
   Lars Doorenbos, Pablo Márquez-Neila, Raphael Sznitman, Pascal Mettes

1. [Fast Hyperboloid Decision Tree Algorithms](https://arxiv.org/abs/2310.13841), ICLR 2024 \
   Philippe Chlenski, Ethan Turok, Antonio Moretti, Itsik Pe'er

1. [Mixed-Curvature Decision Trees and Random Forests](https://arxiv.org/abs/2410.13879), ICML 2025\
   Philippe Chlenski, Quentin Chu, Raiyan R. Khan, Kaizhu Du, Antonio Khalil Moretti, Itsik Pe'er

1. [Even Faster Hyperbolic Random Forests: A Beltrami-Klein Wrapper Approach](https://www.arxiv.org/abs/2506.04360), arXiv 2025 \
   Philippe Chlenski, Itsik Pe'er

### [Hyperbolic Operations](#content)

1. Mean Computation and BatchNorm \
[Differentiating through the Fréchet Mean](https://arxiv.org/abs/2003.00335), ICML 2020 \
Aaron Lou, Isay Katsman, Qingxuan Jiang, Serge Belongie, Ser-Nam Lim, Christopher De Sa

1. Sampling \
[A Wrapped Normal Distribution on Hyperbolic Space for Gradient-Based Learning](https://arxiv.org/abs/1902.02992), ICML 2019 \
Yoshihiro Nagano, Shoichiro Yamaguchi, Yasuhiro Fujita, Masanori Koyama

1. Sampling \
[Wrapped Distributions on homogeneous Riemannian manifolds](https://arxiv.org/abs/2204.09790), 2022 \
Fernando Galaz-Garcia, Marios Papamichalis, Kathryn Turnbull, Simon Lunagomez, Edoardo Airoldi

1. Sampling \
[A Rotated Hyperbolic Wrapped Normal Distribution for Hierarchical Representation Learning](https://arxiv.org/abs/2205.13371), NeurIPS 2022 \

1. MixUp and Data Augmentation \
[HYPMIX: Hyperbolic Interpolative Data Augmentation](https://aclanthology.org/2021.emnlp-main.776/), EMNLP 2021 \
Ramit Sawhney, Megh Thakkar, Shivam Agarwal, Di Jin, Diyi Yang, Lucie Flek

1. PCA \
[HoroPCA: Hyperbolic Dimensionality Reduction via Horospherical Projections](https://arxiv.org/abs/2106.03306), ICML 2021 \
Ines Chami\*, Albert Gu\*, Dat Nguyen, Christopher Ré*

1. TSNE \
 [Accelerating hyperbolic t-SNE](https://arxiv.org/abs/2401.13708), arxiv 2024 \
Martin Skrodzki, Hunter van Geffen, Nicolas F. Chaves-de-Plaza, Thomas Höllt, Elmar Eisemann, Klaus Hildebrandt

1. Hierarchical Clustering\
   [From Trees to Continuous Embeddings and Back: Hyperbolic Hierarchical Clustering](https://arxiv.org/abs/2010.00402) \
   Ines Chami, Albert Gu, Vaggos Chatziafratis, Christopher Ré
   

### [LLM and Hyperbolic Space](#content)

1. [HELM: Hyperbolic Large Language Models via Mixture-of-Curvature Experts](https://arxiv.org/abs/2505.24722) 🔥 \
Neil He, Rishabh Anand, Hiren Madhu, Ali Maatouk, Smita Krishnaswamy, Leandros Tassiulas, Menglin Yang, Rex Ying

1. [Large Language Models Enhanced Hyperbolic Space Recommender Systems](https://arxiv.org/abs/2504.05694), SIGIR 2025 \
*Wentao Cheng, Zhida Qin, Zexue Wu, Pengzhan Zhou, Tianyu Huang*

1. [Language Models as Hierarchy Encoders](https://arxiv.org/abs/2401.11374), NeurIPS 2024 \
Yuan He, Zhangdie Yuan, Jiaoyan Chen, Ian Horrocks

1. [HyperSDFusion: Bridging Hierarchical Structures in Language and Geometry for Enhanced 3D Text2Shape Generation](https://arxiv.org/pdf/2403.00372.pdf), arxiv 2024 \
   Zhiying Leng, Tolga Birdal, Xiaohui Liang, Federico Tombari

1. [LLMs are Good Action Recognizers](https://arxiv.org/html/2404.00532v1), arxiv 2024 \
   Haoxuan Qu, Yujun Cai, Jun Liu

## [Applications](#content)

### [Natural Language Processing](#content)

1. [Enhancing Multi-Hop Reasoning for Question Answering with Hyperbolic Representations](https://2025.aclweb.org/program/find_papers/), ACL Findings 2025 \
*Simon Welz, Lucie Flek, Akbar Karimi*

1. [Poincare Glove: Hyperbolic Word Embeddings](https://arxiv.org/abs/1810.06546), ICLR 2019 \
Alexandru Tifrea and Gary Becigneul and Octavian-Eugen Gane

1. [Skip-gram word embeddings in hyperbolic space](https://arxiv.org/abs/1809.01498), ACL 2018 \
Matthias Leimeister, Benjamin J. Wilson

1. [Embedding text in hyperbolic spaces](https://arxiv.org/abs/1806.04313), ACL 2018 \
Bhuwan Dhingra, Christopher J. Shallue, Mohammad Norouzi, Andrew M. Dai, George E. Dahl

1. [Hyperbolic entailment cones for learning hierarchical embeddings](https://arxiv.org/abs/1804.01882), ICML 2018 \
Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann

1. [Low-rank approximations of hyperbolic embeddings](https://arxiv.org/abs/1903.07307) \
Pratik Jawanpuria, Mayank Meghwanshi, Bamdev Mishra

1. [Inferring Concept Hierarchies from Text Corpora via Hyperbolic Embeddings](https://arxiv.org/pdf/1902.00913.pdf) \
Matt Le, Stephen Roller, Laetitia Papaxanthos, Douwe Kiela, Maximilian Nickel

1. [HISum: Hyperbolic Interaction Model for Extractive Multi-Document Summarization](https://dl.acm.org/doi/10.1145/3543507.3583197), WWW 2023 \
    Mingyang Song,  Yi Feng,  Liping Jing

1.  [Cross-lingual Word Embeddings in Hyperbolic Space](https://arxiv.org/abs/2205.01907) for word embedding, arxiv 2022
   Chandni Saxena, Mudit Chaudhary, Helen Meng


1.  [Public Wisdom Matters! Discourse-Aware Hyperbolic Fourier Co-Attention for Social-Text Classification](https://arxiv.org/abs/2209.13017),  NeurIPS 2022 Oral (Spotlight) \
K Grover, SM Angara, M Akhtar, T Chakraborty

1. [Probing BERT in Hyperbolic Spaces](https://arxiv.org/abs/2104.03869). ICLR 2021 \
   Boli Chen, Yao Fu, Guangwei Xu, Pengjun Xie, Chuanqi Tan, Mosha Chen, Liping Jing

1.  [Hyperbolic Relevance Matching for Neural Keyphrase Extraction](https://arxiv.org/abs/2205.02047) for key phrases matching, Naacl 2022 \
Mingyang Song, Yi Feng, Liping Jing

1. [Medical Triage Chatbot Diagnosis Improvement via Multi-relational Hyperbolic Graph Neural Network](https://dl.acm.org/doi/abs/10.1145/3404835.3463095). SIGIR short paper 2021 \
Zheng Liu , Xiaohan Li , Zeyu You , Tao Yang , Wei Fan , Philip Yu

1. [ANTHEM: Attentive Hyperbolic Entity Model for Product Search](https://dl.acm.org/doi/10.1145/3488560.3498456). WSDM 2022 \
Nurendra Choudhary , Nikhil Rao , Sumeet Katariya , Karthik Subbian , Chandan K. Reddy

1. [Leveraging Hierarchical Representations for Preserving Privacy and Utility in Text](https://arxiv.org/abs/1910.08917), ICDM 2019
   Oluwaseyi Feyisetan, Tom Diethe, Thomas Drake

1. [Hyperbolic Representation Learning for Fast and Efficient Neural Question Answering](https://dl.acm.org/doi/10.1145/3159652.3159664), WSDM 2018
   Yi Tay, Luu Anh Tuan, Siu Cheung Hui

### [Computer Vision](#content)

1. [Hyperbolic Category Discovery](https://arxiv.org/abs/2504.06120), CVPR 2025 \
*Yuanpei Liu, Zhenqi He, Kai Han*

1. [Parameter-efficient Fine-tuning in Hyperspherical Space for Open-vocabulary Semantic Segmentation](https://arxiv.org/abs/2405.18840), CVPR 2025 \
*Zelin Peng, Zhengqin Xu, Zhilin Zeng, Changsong Wen, Yu Huang, Menglin Yang, Feilong Tang, Wei Shen*

1. [Hyperbolic Safety-Aware Vision-Language Models](https://arxiv.org/abs/2503.12127), CVPR 2025 \
*Tobia Poppi, Tejaswi Kasarla, Pascal Mettes, Lorenzo Baraldi, Rita Cucchiara*

1. [Hyperbolic Uncertainty-Aware Few-Shot Incremental Point Cloud Segmentation](https://cvpr.thecvf.com/virtual/2025/poster/34838), CVPR 2025 \
*Tanuj Sur, Samrat Mukherjee, Kaizer Rahaman, Subhasis Chaudhuri, Muhammad Haris Khan, Biplab Banerjee*

1. [Deep Change Monitoring: A Hyperbolic Representative Learning Framework and a Dataset for Long-term Fine-grained Tree Change Detection](https://arxiv.org/abs/2503.00643), CVPR 2025 \
*Yante Li, Hanwen Qi, Haoyu Chen, Liang Xinlian, Guoying Zhao*

1. [Improving Visual Recognition with Hyperbolical Visual Hierarchy Mapping](https://arxiv.org/pdf/2404.00974.pdf), CVPR 2025
   Hyeongjun Kwon, Jinhyun Jang, Jin Kim, Kwonyoung Kim, Kwanghoon Sohn

1. [HyperSDFusion: Bridging Hierarchical Structures in Language and Geometry for Enhanced 3D Text2Shape Generation](https://arxiv.org/pdf/2403.00372.pdf), arxiv 2024 \
   Zhiying Leng, Tolga Birdal, Xiaohui Liang, Federico Tombari


1. [Hyperbolic Image Embedding](https://arxiv.org/abs/1904.02239), CVPR 2020 \
Valentin Khrulkov, Leyla Mirvakhabova, Evgeniya Ustinova, Ivan Oseledets, Victor Lempitsky

1. [Hyperbolic Image Segmentation](https://arxiv.org/abs/2203.05898), CVPR 2022 \
Mina GhadimiAtigh, Julian Schoep, Erman Acar, Nanne van Noord, Pascal Mettes

1. [Hyperbolic Vision Transformers: Combining Improvements in Metric Learning](https://arxiv.org/abs/2203.10833),CVPR 2022 \
Aleksandr Ermolov, Leyla Mirvakhabova, Valentin Khrulkov, Nicu Sebe, Ivan Oseledets

1. [Hyperbolic Image-Text Representations](https://arxiv.org/pdf/2304.09172.pdf), ICML 2023 \
   Karan Desai, Maximilian Nickel, Tanmay Rajpurohit, Justin Johnson, Ramakrishna Vedantam

2. [Hyperbolic Busemann Learning with Ideal Prototypes](https://openreview.net/forum?id=c_XcmuxwAY), NeurIPS 2021
   Mina Ghadimi Atigh, Martin Keller-Ressel, Pascal Mettes

3. [Rethinking the compositionality of point clouds through regularization in the hyperbolic space](https://arxiv.org/abs/2209.10318) (NeurIPS 2022) \
   Antonio Montanaro, Diego Valsesia, Enrico Magli

4. [HypLiLoc: Towards Effective LiDAR Pose Regression with Hyperbolic Fusion](https://arxiv.org/abs/2304.00932), CVPR 2023 \
Sijie Wang, Qiyu Kang, Rui She, Wei Wang, Kai Zhao, Yang Song, Wee Peng Tay


1. [Clipped Hyperbolic Classifiers Are Super-Hyperbolic Classifiers](https://arxiv.org/abs/2107.11472), CVPR 2022 \
Yunhui Guo, Xudong Wang, Yubei Chen, Stella X. Yu


1. [Capturing implicit hierarchical structure in 3D biomedical images with self-supervised hyperbolic representations](https://proceedings.neurips.cc/paper/2021/file/291d43c696d8c3704cdbe0a72ade5f6c-Paper.pdf) NeurIPS 2021 \
Joy Hsu, Jeffrey Gu, Gong-Her Wu, Wah Chiu, Serena Yeung

1. [Learning Hyperbolic Representations of Topological Features](https://arxiv.org/abs/2103.09273) ICLR 2021 \
Panagiotis Kyriakis, Iordanis Fostiropoulos, Paul Bogdan

1. [Curvature Generation in Curved Spaces for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf), ICCV 2021 \
Zhi\* Gao, Yuwei Wu\*, Yunde Jia, Mehrtash Harandi

1. [Unsupervised Discovery of the Long-Tail in Instance Segmentation Using Hierarchical Self-Supervision](https://arxiv.org/abs/2104.01257), CVPR 2021 \
Zhenzhen Weng, Mehmet Giray Ogut, Shai Limonchik, Serena Yeung

1. [Searching for Actions on the Hyperbole](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9157196), CVPR 2020 \
Teng Long, Pascal Mettes, Heng Tao Shen, Cees Snoek

1. [Mix Dimension in Poincaré Geometry for 3D Skeleton-based Action Recognition](https://dl.acm.org/doi/abs/10.1145/3394171.3413910), ACM MM 2020 \
Wei Peng, Jingang Shi, Zhaoqiang Xia, Guoying Zhao

1. [Meta Hyperbolic Networks for Zero-Shot Learning](https://www.sciencedirect.com/science/article/pii/S0925231222003344), Neurocomputing \
Yan Xu, Lifu Mu, ZhongJi, Xiyao Liu, JungongHan

1. [Poincaré ResNet](https://arxiv.org/abs/2303.14027), arxiv 2023 \
Max van Spengler, Erwin Berkhout, Pascal Mettes


**Robot Design**
1.  [Leveraging Hyperbolic Embeddings for Coarse-to-Fine Robot Design](https://arxiv.org/abs/2311.00462v2), arxiv 2023 \
    Heng Dong, Junyu Zhang, Chongjie Zhang

### [Graph Embeddings](#content)

**Directed Graphs**

1. [Hyperbolic Disk Embeddings for Directed Acyclic Graphs](https://arxiv.org/pdf/1902.04335.pdf)，ICML 2019 \
Ryota Suzuki, Ryusuke Takahama, Shun Onoda

1. [A hyperbolic Embedding Model for Directed Networks](https://arxiv.org/abs/1906.03597) \
Zongning Wu, Zengru Di, Ying Fan (this paper includes many errors)

**Signed Graphs**
1. [Hyperbolic Node Embedding for Signed Networks](https://arxiv.org/abs/1910.13090), Neurcomputing 2021 \
Wenzhuo Song, Hongxu Chen, Xueyan Liu, Hongzhe Jiang, Shengsheng Wang

**Heterogeneous Graphs**

1. [Hyperbolic Heterogeneous Information Network Embedding](https://ojs.aaai.org/index.php/AAAI/article/view/4471),  AAAI 2020 \
Xiao Wang, Yiding Zhang, Chuan Shi

1. [Embedding Heterogeneous Information Network in Hyperbolic Spaces](https://dl.acm.org/doi/abs/10.1145/3468674?sid=SCITRUS), TKDD 2022 \
Yiding Zhang, Xiao Wang, Nian Liu, Chuan Shi

**Attributed Graphs**
1. [HEAT: Hyperbolic Embedding of Attributed Networks](https://arxiv.org/abs/1903.03036), IDEAL 2020 \
David McDonald, Shan He

**Multigraphs**
1. [Hyperbolic Multiplex Network Embedding with Maps of Random Walk](https://arxiv.org/abs/1912.08927) \
Peiyuan Sun

**Multi-relational Graphs**
1. [Multi-relational Poincaré Graph Embeddings](https://arxiv.org/abs/1905.09791), NeurIPS 2019 \
Ivana Balažević, Carl Allen, Timothy Hospedales

**Dynamic Graphs**

1. [SINCERE: Sequential Interaction Networks representation learning on Co-Evolving RiEmannian manifolds](https://dl.acm.org/doi/abs/10.1145/3543507.3583353), WWW 2023 \
   Junda Ye, Zhongbao Zhang, Li Sun, Yang Yan, Feiyang Wang, Fuxin Ren

1. [Discrete-time Temporal Network Embedding via Implicit Hierarchical Learning in Hyperbolic Space](https://arxiv.org/abs/2107.03767),  KDD 2021 \
Menglin Yang, Min Zhou, Marcus Kalander, Zengfeng Huang, Irwin King

1. [Hyperbolic Variational Graph Neural Network for Modeling Dynamic Graphs](https://arxiv.org/abs/2104.02228), AAAI 2021 \
Li Sun, Zhongbao Zhang, Jiawei Zhang, Feiyang Wang, Hao Peng, Sen Su, Philip S. Yu

1. [Exploring the Scale-Free Nature of Stock Markets: Hyperbolic Graph Learning for Algorithmic Trading](https://dl.acm.org/doi/10.1145/3442381.3450095),  WWW 2021 \
Ramit Sawhney, Shivam Agarwal, Arnav Wadhwa , Rajiv Shah


### [Recommender Systems](#content)

1. [VoRec: Enhancing Recommendation with Voronoi Diagram in Hyperbolic Space](https://sigir2025.dei.unipd.it/accepted-papers.html), SIGIR 2025 \
*Yong Chen, Li Li, Wei Peng, Songzhi Su*

1. [Large Language Models Enhanced Hyperbolic Space Recommender Systems](https://arxiv.org/abs/2504.05694), SIGIR 2025 \
*Wentao Cheng, Zhida Qin, Zexue Wu, Pengzhan Zhou, Tianyu Huang*

1. [Hyperbolic Multi-Criteria Rating Recommendation](https://sigir2025.dei.unipd.it/accepted-papers.html), SIGIR 2025 \
*Zhihao Guo, Ting Han, Peng Song, Chenjiao Feng, Kaixuan Yao, Jiye Liang*

**Analysis**

1. [Where are we in embedding spaces? A Comprehensive Analysis on Network Embedding Approaches for Recommender Systems](https://arxiv.org/abs/2105.08908) KDD 2021 \
Sixiao Zhang, Hongxu Chen, Xiao Ming, Lizhen Cui, Hongzhi Yin, Guandong Xu

**Collaborative Filtering**
1. [HyperML: A Boosting Metric Learning Approach in Hyperbolic Space for Recommender Systems](https://arxiv.org/abs/1809.01703), WSDM 2020 \
Lucas Vinh Tran, Yi Tay, Shuai Zhang, Gao Cong, Xiaoli Li

1. [HICF: Hyperbolic Informative Collaborative Filtering](https://arxiv.org/abs/2207.09051), KDD 2022 \
Menglin Yang, Zhihao Li, Min Zhou, Jiahong Liu, Irwin King

1. [HRCF: Enhancing Collaborative Filtering via Hyperbolic Geometric Regularization](https://arxiv.org/abs/2204.08176), WWW 2022 \
Menglin Yang, Min Zhou, Jiahong Liu, Defu Lian, Irwin King

1. [HGCF: Hyperbolic Graph Convolution Networks for Collaborative Filtering](https://www.cs.toronto.edu/~mvolkovs/www2021_hgcf.pdf), WWW 2021 \
Jianing Sun,Zhaoyue Cheng,Saba Zuberi,Felipe Perez,Maksims Volkovs

1. [HGCC: Enhancing Hyperbolic Graph Convolution Networks on Heterogeneous Collaborative Graph for Recommendation](https://arxiv.org/abs/2304.02961), arxiv 2022 \
Lu Zhang, Ning Wu

1. [Hyperbolic Neural Collaborative Recommender](https://ieeexplore.ieee.org/abstract/document/9946432), TKDE 2022 \
   Anchen Li; Bo Yang; Huan Huo; Hongxu Chen; Guandong Xu; Zhen Wang

**KG-enhanced Recommender Systems**
1. [HAKG: Hierarchy-Aware Knowledge Gated Network for Recommendation](https://arxiv.org/abs/2204.04959), SIGIR 2022 \
Yuntao Du, Xinjun Zhu, Lu Chen, Baihua Zheng, and Yunjun Gao

1. [Modeling Scale-free Graphs with Hyperbolic Geometry for Knowledge-aware Recommendation](https://arxiv.org/abs/2108.06468), WSDM 2022 \
Yankai Chen, Menglin Yang, Yingxue Zhang, Mengchen Zhao, Ziqiao Meng, Jianye Hao, Irwin King

1. [Knowledge Based Hyperbolic Propagation](http://dl.acm.org/doi/abs/10.1145/3404835.3462980), SIGIR short paper 2021 \
Chang-You Tai, Chien-Kun Huang, Liang-Ying Huang, Lun-Wei Ku

1. [Lorentz Equivariant Model for Knowledge-Enhanced Collaborative Filtering](https://arxiv.org/abs/2302.04545), arxiv 2023 \
   Bosong Huang, Weihao Yu, Ruzhong Xie, Jing Xiao, Jin Huang

**Matrix Completion**
1. [Geometric Inductive Matrix Completion: A Hyperbolic Approach with Unified Message Passing](https://dl.acm.org/doi/abs/10.1145/3488560.3498402), WSDM 2022 \
Chengkun Zhang , Hongxu Chen , Sixiao Zhang , Guandong Xu , Junbin Gao

**Social-aware Recommender Systems**
1. [Hypersorec: Exploiting hyperbolic user and item representations with multiple aspects for social-aware recommendation](http://home.ustc.edu.cn/~wanghao3/papers/haowang_TOIS2021.pdf), TOIS 2021 \
Hao Wang, Defu Lian, Hanghang Tong, Qi Liu, Zhenya Huang and Enhong Chen

1. [HSR: hyperbolic social recommender](https://arxiv.org/abs/2102.09389), Information Sciences 2022 \
Anchen Li, Bo Yang

**Session-based Recommendation**
1. [Enhancing Hierarchy-Aware Graph Networks with Deep Dual Clustering for Session-based Recommendation](https://dl.acm.org/doi/abs/10.1145/3543507.3583247), WWW 2023 \
   Jiajie Su, Chaochao Chen, Weiming Liu, Fei Wu, Xiaolin Zheng, Haoming Lyu

1. [HCGR: Hyperbolic Contrastive Graph Representation Learning for Session-based Recommendation](https://arxiv.org/abs/2107.05366), arxiv 2021 \
Naicheng Guo, Xiaolei Liu, Shaoshuai Li, Qiongxu Ma, Yunan Zhao, Bing Han, Lin Zheng, Kaixin Gao, Xiaobo Guo

1. [Hyperbolic Hypergraphs for Sequential Recommendation](https://arxiv.org/abs/2108.08134), CIKM 2021 \
Yicong Li, Hongxu Chen, Xiangguo Sun, Zhenchao Sun, Lin Li, Lizhen Cui, Philip S. Yu, Guandong Xu

**FM**

1. [Learning Feature Interactions with Lorentzian Factorization Machine](https://arxiv.org/abs/1911.09821), AAAI 2020 \
Canran Xu, Ming Wu

1. [Scalable Hyperbolic Recommender Systems](https://arxiv.org/abs/1902.08648), WSDM 2020 \
Benjamin Paul Chamberlain, Stephen R. Hardwick, David R. Wardrope, Fabon Dzogang, Fabio Daolio, Saúl Vargas

1. [Node2LV: Squared Lorentzian Representations for Node Proximity](https://ieeexplore.ieee.org/document/9458940)， ICDE 2021 \
Shanshan Feng, Lisi Chen, Kaiqi Zhao, Wei Wei, Fan Li, Shuo Shang

**Next-Item Recommendation**

1. [A hyperbolic metric embedding approach for next-poi recommendation](https://dl.acm.org/doi/10.1145/3397271.3401049), SIGIR 2020 \
Shanshan Feng , Lucas Vinh Tran , Gao Cong , Lisi Chen , Jing Li , Fan Li

**Tag-related Recommendation**

2. [Enhancing Recommendation with Automated Tag Taxonomy Construction in Hyperbolic Space](https://ieeexplore.ieee.org/abstract/document/9835344), ICDE 2022 \
   Yanchao Tan; Carl Yang; Xiangyu Wei; Chaochao Chen; Longfei Li; Xiaolin Zheng
3. [Hyperbolic Personalized Tag Recommendation](https://link.springer.com/chapter/10.1007/978-3-031-00126-0_14), DASFAA 2022 \
   Weibin Zhao, Aoran Zhang, Lin Shang, Yonghong Yu, Li Zhang, Can Wang, Jiajun Chen & Hongzhi Yin 

### [Knowledge Graphs](#content)

2. [Low-Dimensional Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2005.00545), ACL 2019 \
Ines Chami, Adva Wolf, Da-Cheng Juan, Frederic Sala, Sujith Ravi, Christopher Ré

1. [Multi-relational Poincaré Graph Embeddings](https://arxiv.org/abs/1905.09791), NeurIPS 2019 \
Ivana Balažević, Carl Allen, Timothy Hospedales

1. [Hyperbolic Temporal Knowledge Graph Embeddings with Relational and Time Curvatures](https://arxiv.org/abs/2106.04311), ACL 2021 \
Sebastien Montella, Lina Rojas-Barahona, Johannes Heinecke

1. [Knowledge Association with Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2010.02162), EMNLP 2020 \
Zequn Sun, Muhao Chen, Wei Hu, Chengming Wang, Jian Dai, Wei Zhang

1. [Knowledge Graph Representation via Hierarchical Hyperbolic Neural Graph Embedding](https://ieeexplore.ieee.org/document/9671651), IEEE Big Data \
Shen Wang, Xiaokai Wei, Cicero Nogueira Dos Santos, Zhiguo Wang, Ramesh Nallapati, Andrew Arnold, Philip S. Yu


1. [Mixed-Curvature Multi-relational Graph Neural Network for Knowledge Graph Completion](https://assets.amazon.science/0c/9d/51d98f1040b1bfa7dc52d1015750/mixed-curvature-multi-relational-graph-neural-network-for-knowledge-graph-completion.pdf), WWW 2021 \
Shen Wang , Xiaokai Wei , Cicero Nogueira Nogueira dos Santos , Zhiguo Wang , Ramesh Nallapati , Andrew Arnold , Bing Xiang , Philip S. Yu , Isabel F. Cruz

1. [Geometry Interaction Knowledge Graph Embeddings](https://arxiv.org/abs/2206.12418) for KG embedding, AAAI 2022 \
   Zongsheng Cao, Qianqian Xu, Zhiyong Yang, Xiaochun Cao, Qingming Huang

1. [Modeling Heterogeneous Hierarchies with Relation-specific Hyperbolic Cones](https://arxiv.org/abs/2110.14923)， NeurIPS 2021 \
Yushi Bai, Rex Ying, Hongyu Ren, Jure Leskovec


1. [Self-supervised hyperboloid representations from logical queries over knowledge graphs](https://arxiv.org/abs/2012.13023), WWW 2021 \
Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy

1. [HyperKG: Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion](https://arxiv.org/abs/1908.04895), arxiv \
Prodromos Kolyvakis, Alexandros Kalousis, Dimitris Kiritsis

1. [Hyperbolic Hierarchy-Aware Knowledge Graph Embedding for Link Prediction](https://aclanthology.org/2021.findings-emnlp.251/). EMNLP findings 2021 \
Zhe Pan, Peng Wang

1. [FFHR: Fully and Flexible Hyperbolic Representation for Knowledge Graph Completion](https://arxiv.org/pdf/2302.04088.pdf),arxiv 2023 \
Wentao Shi, Junkang Wu, Xuezhi Cao, Jiawei Chen, Wenqiang Lei, Wei Wu, Xiangnan He

1. [Mixed Geometry Message and Trainable Convolutional Attention Network for Knowledge Graph Completion](https://ojs.aaai.org/index.php/AAAI/article/view/28745), AAAI 2024 \
   Bin Shang, Yinliang Zhao, Jun Liu, Di Wang

### [Molecular Learning](#content)

1. [Semi-supervised  hierarchical  drug  embedding  inhyperbolic space](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00681), J. Chem. Inf. Model 2020 \
Ke Yu\*, Shyam Visweswaran\*, and Kayhan Batmanghelich

1. [HiG2Vec: hierarchical representations of Gene Ontology and genes in the Poincaré ball](https://academic.oup.com/bioinformatics/article/37/18/2971/6184857?login=false), Bioinformatics, 2021 \
Jaesik Kim, Dokyoon Kim, Kyung-Ah Sohn

1. [Hyperbolic relational graph convolution networks plus: a simple but highly efficient QSAR-modeling method](https://academic.oup.com/bib/article-abstract/22/5/bbab112/6235968?redirectedFrom=fulltext), Briefings in Bioinformatics 2021 \
Zhenxing Wu, Dejun Jiang, Chang-Yu Hsieh, Guangyong Chen, Ben Liao, Dongsheng Cao, Tingjun Hou

1. [Contrastive Poincaré Maps for single-cell data analysis](https://openreview.net/pdf?id=zsUKE98bNu), ICLR workshop 2024 \
   Nithya Bhasker, Hattie Chung, Louis Boucherie, Vladislav Kim, Stefanie Speidel, Melanie Weber

1. [Hyperbolic Graph Diffusion Model](https://arxiv.org/abs/2306.07618), AAAI 2024 \
   Lingfeng Wen, Xuan Tang, Mingjie Ouyang, Xiangxiang Shen, Jian Yang, Daxin Zhu, Mingsong Chen, Xian Wei
   
1. [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://arxiv.org/abs/2405.03188), ICML 2024 \
   Xingcheng Fu, Yisen Gao, Yuecen Wei, Qingyun Sun, Hao Peng, Jianxin Li, Xianxian Li

1. [Deep generative model embedding of single-cell RNA-Seq profiles on hyperspheres and hyperbolic spaces](https://www.nature.com/articles/s41467-021-22851-4), Natur Communications 2021 \
   Jiarui Ding, Aviv Regev 
 

### [Code Representation](#content)

1. [Hyperbolic Representations of Source Code](https://assets.amazon.science/55/d9/58097f0d41b886269b30e5c68522/hyperbolic-representations-of-source-code.pdf) AAAI 2022 \
Raiyan Khan, Thanh V. Nguyen, Sengamedu H. Srinivasan


### [Multi-label Learning](#content)

1. [Hyperbolic interaction model for hierarchical multi-label classification](https://ojs.aaai.org/index.php/AAAI/article/view/6247), AAAI 2021 \
Boli Chen, Xin Huang, Lin Xiao, Zixin Cai, Liping Jing

1. [Hyperbolic Capsule Networks for Multi-Label Classification](https://aclanthology.org/2020.acl-main.283/), ACL 2020 \
Boli Chen, Xin Huang, Lin Xiao, Liping Jing

1. [Joint Learning of Hyperbolic Label Embeddings for Hierarchical Multi-label Classification](https://arxiv.org/abs/2101.04997), EACL 2021 \
Soumya Chatterjee, Ayush Maheshwari, Ganesh Ramakrishnan, Saketha Nath Jagaralpudi

1. [Hyperbolic Embeddings for Hierarchical Multi-label Classification](https://link.springer.com/chapter/10.1007/978-3-030-59491-6_7), 2020 \
Tomaž StepišnikEmail, Dragi Kocev

1. [A Fully Hyperbolic Neural Model for Hierarchical Multi-Class Classification](https://arxiv.org/abs/2010.02053), EMNLP findings \
Federico López, Michael Strube

1.  [Hyperbolic Space with Hierarchical Margin Boosts Fine-Grained Learning from Coarse Labels](https://arxiv.org/abs/2311.11019), NeurIPS, 2023 \
    Shu-Lin Xu, Yifan Sun, Faen Zhang, Anqi Xu, Xiu-Shen Wei, Yi Yang


### [Hyperbolic Metric Learning](#content)
1. [Contrastive Multi-view Hyperbolic Hierarchical Clustering](https://arxiv.org/abs/2205.02618) for clustering, IJCAI 2022 \
   Fangfei Lin, Bing Bai, Kun Bai, Yazhou Ren, Peng Zhao, Zenglin Xu

1. [Hyperbolic Busemann Learning with Ideal Prototypes](https://proceedings.neurips.cc/paper/2021/file/01259a0cb2431834302abe2df60a1327-Paper.pdf), NeurIPS 2021 \
Mina Ghadimi Atigh, Martin Keller-Ressel, Pascal Mettes

1. [Unsupervised Hyperbolic Metric Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_Unsupervised_Hyperbolic_Metric_Learning_CVPR_2021_paper.pdf), CVPR 2021 \
Jiexi Yan, Lei Luo, Cheng Deng, Heng Huang

1. [Hyperbolic Contrastive Learning](https://arxiv.org/abs/2302.01409), arxiv \
Yun Yue, Fangzhou Lin, Kazunori D Yamada, Ziming Zhang

1. [A Quadtree for Hyperbolic Space](https://arxiv.org/abs/2305.01356), arxiv 2023 \
    Sándor Kisfaludi-Bak, Geert van Wordragen

2.  [Alignment and Outer Shell Isotropy for Hyperbolic Graph Contrastive Learning](https://arxiv.org/abs/2310.18209v1), arxiv 2023 \
   Yifei Zhang, Hao Zhu, Jiahong Liu, Piotr Koniusz, Irwin King  

### [Data-driven Geometry Learning](#content)

1. [Dimensionality Selection for Hyperbolic Embeddings using Decomposed Normalized Maximum Likelihood Code-Length](https://www.researchsquare.com/article/rs-2550932/v1), arxiv 2023 \
Ryo Yuki, Yuichi Ike, Kenji Yamanishi
 
1. [CO-SNE: Dimensionality Reduction and Visualization for Hyperbolic Data](https://arxiv.org/abs/2111.15037) for embedding visualization, CVPR 2022 \
Yunhui Guo, Haoran Guo, Stella Yu
   
1. [Wrapped Distributions on homogeneous Riemannian manifolds](https://arxiv.org/abs/2204.09790)  for hyperbolic sampling, arxiv 2022 \
   Fernando Galaz-Garcia, Marios Papamichalis, Kathryn Turnbull, Simon Lunagomez, Edoardo Airoldi

2. [HyperAid: Denoising in hyperbolic spaces for tree-fitting and hierarchical clustering](https://arxiv.org/abs/2205.09721) for clustering, KDD 2022 \
Eli Chien, Puoya Tabaghi, Olgica Milenkovic

1. [Hyperbolic Feature Augmentation via Distribution Estimation and Infinite Sampling on Manifolds](https://openreview.net/forum?id=yoLGaLPEPo_) NeurIPS 2022 \
Zhi Gao, Yuwei Wu, Yunde Jia, Mehrtash Harandi

1. [Exploring Data Geometry for Continual Learning](https://arxiv.org/abs/2304.03931) CVPR 2023 \
Zhi Gao, Chen Xu, Feng Li, Yunde Jia, Mehrtash Harandi, Yuwei Wu

1. [Curvature-Adaptive Meta-Learning for Fast Adaptation to Manifold Data](https://ieeexplore.ieee.org/abstract/document/9749838), TPAMI 2023\
Zhi Gao, Yuwei Wu, Mehrtash Harandi, and Yunde Jia

### [Few-Shot Learning](#content)

1. [Hyperbolic Uncertainty-Aware Few-Shot Incremental Point Cloud Segmentation](https://cvpr.thecvf.com/virtual/2025/poster/34838), CVPR 2025 \
*Tanuj Sur, Samrat Mukherjee, Kaizer Rahaman, Subhasis Chaudhuri, Muhammad Haris Khan, Biplab Banerjee*

1. [Hyperbolic vs Euclidean Embeddings in Few-Shot Learning: Two Sides of the Same Coin](https://arxiv.org/abs/2309.10013) WACV \
   Gabriel Moreira, Manuel Marques, João Paulo Costeira, Alexander Hauptmann

1. [Curvature Generation in Curved Spaces for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf), ICCV 2021 \
Zhi\* Gao, Yuwei Wu\*, Yunde Jia, Mehrtash Harandi

### [Open-Vocabulary Learning](#content)

1. [Parameter-efficient Fine-tuning in Hyperspherical Space for Open-vocabulary Semantic Segmentation](https://arxiv.org/abs/2405.18840), CVPR 2025 \
*Zelin Peng, Zhengqin Xu, Zhilin Zeng, Changsong Wen, Yu Huang, Menglin Yang, Feilong Tang, Wei Shen*

1. [Hyperbolic Learning with Synthetic Captions for Open-World Detection](https://arxiv.org/abs/2404.05016), CVPR 2024 \
Fanjie Kong, Yanbei Chen, Jiarui Cai, Davide Modolo

### [Safety and Robustness](#content)

1. [Hyperbolic Safety-Aware Vision-Language Models](https://arxiv.org/abs/2503.12127), CVPR 2025 \
*Tobia Poppi, Tejaswi Kasarla, Pascal Mettes, Lorenzo Baraldi, Rita Cucchiara*

1. [Improving Robustness of Hyperbolic Neural Networks by Lipschitz Analysis](https://dl.acm.org/doi/pdf/10.1145/3637528.3671875), KDD 2024 \
Yuekang Li, Yidan Mao, Yifei Yang, Dongmian Zou

### [Environmental Monitoring](#content)

1. [Deep Change Monitoring: A Hyperbolic Representative Learning Framework and a Dataset for Long-term Fine-grained Tree Change Detection](https://arxiv.org/abs/2503.00643), CVPR 2025 \
*Yante Li, Hanwen Qi, Haoyu Chen, Liang Xinlian, Guoying Zhao*

### [Category Discovery](#content)

1. [Hyperbolic Category Discovery](https://arxiv.org/abs/2504.06120), CVPR 2025 \
*Yuanpei Liu, Zhenqi He, Kai Han*

### [Multi-Criteria Learning](#content)

1. [Hyperbolic Multi-Criteria Rating Recommendation](https://sigir2025.dei.unipd.it/accepted-papers.html), SIGIR 2025 \
*Zhihao Guo, Ting Han, Peng Song, Chenjiao Feng, Kaixuan Yao, Jiye Liang*

### [Biology](#content)

**Phylogenetics**

1. [Visualising very large phylogenetic trees in three dimensional hyperbolic space](https://pubmed.ncbi.nlm.nih.gov/15117420/), BMC Bioinformatics 2004\
   Timothy Hughes, Young Hyun, David A Liberles

1. [Novel metric for hyperbolic phylogenetic tree embeddings](https://www.biorxiv.org/content/10.1101/2020.10.09.334243v1.full), Biology Methods and Protocols 2021\
   Hirotaka Matsumoto, Takahiro Mimori, Tsukasa Fukunaga

1. [Learning Hyperbolic Embedding for Phylogenetic Tree Placement and Updates](https://www.mdpi.com/2079-7737/11/9/1256), Biology 2022\
   Yueyu Jiang, Puoya Tabaghi, Siavash Mirarab

1. [GeoPhy: Differentiable Phylogenetic Inference via Geometric Gradients of Tree Topologies], NeurIPS 2023\
   Takahiro Mimori, Michiaki Hamada

1. [Differentiable Phylogenetics via Hyperbolic Embeddings with Dodonaphy](https://arxiv.org/abs/2309.11732), Bioinformatics Advances 2024 \
   Matthew Macaulay and Mathieu Fourment

1. [Variational Combinatorial Sequential Monte Carlo for Bayesian Phylogenetics in Hyperbolic Space](https://arxiv.org/abs/2501.17965), AISTATS 2025 \
   Alex Chen, Philipe Chlenski, Kenneth Munyuza, Antonio Khalil Moretti, Christian A. Naesseth, Itsik Pe'er

**Genomics**
1. [Neural Distance Embeddings for Biological Sequences](https://arxiv.org/abs/2109.09740), NeurIPS 2021 \
   Gabriele Corso, Rex Ying, Michal Pándy, Petar Veličković, Jure Leskovec, Pietro Liò

1. [Deep generative model embedding of single-cell RNA-Seq profiles on hyperspheres and hyperbolic spaces](https://pubmed.ncbi.nlm.nih.gov/33953202/), Nature Communications 2021\
   Jiarui Ding, Aviv Regev

1. [Poincaré Maps for Analyzing Complex Hierarchies in Single-Cell Data](https://pubmed.ncbi.nlm.nih.gov/32528075/), Nature Communications 2020 \
   Anna Klimovskaia, David Lopez-Paz, Léon Bottou, Maximilian Nickel

1. [Hyperbolic Genome Embeddings](https://openreview.net/forum?id=NkGDNM8LB0), ICLR 2025 \
   Raiyan R. Khan, Philippe Chlenski, Itsik Pe'er

## Citation
To cite this repository:
```
@misc{hyperbolic-repo,
  author = {Menglin Yang, Min Zhou, Rex Ying},
  title = {{Hyperbolic Representation and Deep Learning: A Comprehensive Collection}},
  howpublished = {https://github.com/marlin-codes/Awesome-Hyperbolic-Representation-and-Deep-Learning},
  year = 2024,
  month = September
}
```

