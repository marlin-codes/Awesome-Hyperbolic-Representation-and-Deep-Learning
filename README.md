
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/marlin-codes/Awesome-Hyperbolic-Graph-Representation-Learning?color=yellow)  ![Forks](https://img.shields.io/github/forks/marlin-codes/Awesome-Hyperbolic-Graph-Representation-Learning?color=blue&label=Fork)

## Introduction

Recently, hyperbolic spaces have emerged as a promising alternative for processing data with a tree-like structure or power-law distribution, owing to its exponential growth property and tree-likeness prior. Different from the Euclidean space, which expands polynomially, the hyperbolic space grows exponentially which makes it gain natural advantages in abstracting tree-like or scale-free data with hierarchical organizations.  In this repository, we categorize papers related to hyperbolic representation learning into different types to facilitate researcher studies and to promote the development of the community. We will keep updating this repository with the latest research developments. We are aware that there will inevitably be some mistakes and oversights, so if you have any questions or suggestions, please feel free to contact us (menglin.yang[@]outlook.com).

<table>
<tr><td colspan="2"><a href="#latest-update" style="color:#B22222">1. Latest Update</a></td></tr> 
<tr><td colspan="2"><a href="papers.md#2-methods-and-models" style="color:#B22222">2. Methods and Models</a></td></tr> 
<tr>
    <td>&ensp;<a href="papers.md#21-hyperbolic-shallow-model">2.1 Hyperbolic Shallow Model</a></td>
    <td>&ensp;<a href="papers.md#22-hyperbolic-neural-network">2.2 Hyperbolic Neural Network</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="papers.md#23-hyperbolic-graph-neural-network">2.3 Hyperbolic Graph Neural Network</a></td>
    <td>&ensp;<a href="papers.md#24-hyperbolic-transformer">2.4 Hyperbolic Transformer</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#29-mixed-curvature-learning">2.5 Mixed Curvature Learning</a></td>
    <td>&ensp;<a href="papers.md#210-semi-riemannian-learning">2.6 Semi-Riemannian Learning</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="papers.md#211-hyperbolic-generative-models">2.7 Hyperbolic Generative Models</a></td>
    <td>&ensp;<a href="papers.md#213-hyperbolic-operations">2.8 Hyperbolic Operations</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#214-llm-and-hyperbolic-space">2.9 LLM && Hyperbolic Space</a></td>
    <td>&ensp;<a href="papers.md#26-analysis">2.10 Analysis</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#27-numerical-problems">2.11 Numerical Problems</a></td>
    <td>&ensp;<a href="papers.md#28-explicitly-tree-embedding">2.12 Explicitly Tree Embedding</a></td>
</tr>
<tr><td colspan="2"><a href="papers.md#3-applications" style="color:#B22222">3. Applications</a></td></tr> 
<tr>
    <td>&ensp;<a href="papers.md#31-natural-language-processing">3.1 Natural Language Processing</a></td>
    <td>&ensp;<a href="papers.md#32-computer-vision">3.2 Computer Vision</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#33-graph-embeddings">3.3 Graph Embedding</a></td>
    <td>&ensp;<a href="papers.md#34-recommender-systems">3.4 Recommender Systems</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#35-knowledge-graphs">3.5 Knowledge Graphs</a></td>
    <td>&ensp;<a href="papers.md#36-molecular-learning">3.6 Molecular Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#37-code-representation">3.7 Code Representation</a></td>
    <td>&ensp;<a href="papers.md#38-multi-label-learning">3.8 Multi-label Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#39-hyperbolic-metric-learning">3.9 Hyperbolic Metric Learning</a></td>
    <td>&ensp;<a href="papers.md#310-data-driven-geometry-learning">3.10 Data-driven Geometry Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#311-few-shot-learning">3.11 Few-Shot Learning</a></td>
    <td>&ensp;<a href="papers.md#312-open-vocabulary-learning">3.12 Open-Vocabulary Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#313-safety-and-robustness">3.13 Safety and Robustness</a></td>
    <td>&ensp;<a href="papers.md#314-environmental-monitoring">3.14 Environmental Monitoring</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#315-category-discovery">3.15 Category Discovery</a></td>
    <td>&ensp;<a href="papers.md#316-multi-criteria-learning">3.16 Multi-Criteria Learning</a></td>
</tr>
</table>




**Hyperbolic Slack Group**
- Slack: https://join.slack.com/t/hyperboliclearning/shared_invite/zt-1qcqgtwfr-HpsRSzDhvkAEal6dOnKDvA
- Website: https://hyperboliclearning.github.io/collection


## [Latest Update](#content)
- August 17, 2025: add ICCV 2025 papers 🔥
- Jun 10, 2025 : add ICML 2025, ICML 2024 papers
- Jun  7, 2025 : update CVPR 2025, SIGIR 2025, ACL 2025 paper
- Feb 26, 2025 : update ICLR 2025 papers 
- Dec 29, 2024 : update NeurIPS 2024 papers 
- Dec 16, 2024 : add NeurIPS 2024 papers
- Sept 8, 2024 : add ICML 2024, KDD 2024, WWW 2024, SIGIR 2024, ICDE 2024, CVPR 2024 papers
 


> 🔥: [HELM: Hyperbolic Large Language Models via Mixture-of-Curvature Experts](https://arxiv.org/abs/2505.24722) by Neil He, Rishabh Anand, Hiren Madhu, Ali Maatouk, Smita Krishnaswamy, Leandros Tassiulas, Menglin Yang, Rex Ying

**KDD 2025**
1. [Understanding and Mitigating Hyperbolic Dimensional Collapse in Graph Contrastive Learning](https://dl.acm.org/doi/abs/10.1145/3690624.3709249), KDD 2025 \
*Yifei Zhang, Hao Zhu, Menglin Yang, Jiahong Liu, Rex Ying, Irwin King, Piotr Koniusz*

1. [Lorentzian Residual Neural Networks](https://dl.acm.org/doi/10.1145/3690624.3709292), KDD 2025 \
  *Neil He, Menglin Yang, Rex Ying*

1. [Hyperbolic Deep Learning for Foundation Models: A Survey](https://arxiv.org/abs/2507.17787), KDD 2025 \
  *Neil He, Hiren Madhu, Ngoc Bui, Menglin Yang, Rex Ying*

**ICCV 2025**

1. [Enhancing Partially Relevant Video Retrieval with Hyperbolic Learning](https://arxiv.org/pdf/2507.17402),  [Code](https://github.com/lijun2005/ICCV25-HLFormer), ICCV 2025, \
*Jun Li, Jinpeng Wang, Chaolei Tan, Niu Lian, Long Chen, Yaowei Wang, Min Zhang, Shu-Tao Xia, Bin Chen*

1. [HypDAE: Hyperbolic Diffusion Autoencoders for Hierarchical Few-shot Image Generation](https://arxiv.org/abs/2411.17784), ICCV 2025 \
*Lingxiao Li, Kaixuan Fan, Boqing Gong, Xiangyu Yue*

1. [Learning Visual Hierarchies in Hyperbolic Space for Image Retrieval](https://arxiv.org/abs/2411.17490), ICCV 2025 \
*Ziwei Wang, Sameera Ramasinghe, Chenchen Xu, Julien Monteil, Loris Bazzani, Thalaiyasingam Ajanthan*

1. [Riemannian-Geometric Fingerprints of Generative Models](https://arxiv.org/abs/2506.22802), ICCV 2025 \
*Hae Jin Song, Laurent Itti*

**ICML 2025**
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



