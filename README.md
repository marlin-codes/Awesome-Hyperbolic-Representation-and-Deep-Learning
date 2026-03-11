
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/marlin-codes/Awesome-Hyperbolic-Graph-Representation-Learning?color=yellow)  ![Forks](https://img.shields.io/github/forks/marlin-codes/Awesome-Hyperbolic-Graph-Representation-Learning?color=blue&label=Fork)

## Introduction

Recently, hyperbolic spaces have emerged as a promising alternative for processing data with a tree-like structure or power-law distribution, owing to its exponential growth property and tree-likeness prior. Different from the Euclidean space, which expands polynomially, the hyperbolic space grows exponentially which makes it gain natural advantages in abstracting tree-like or scale-free data with hierarchical organizations. In this repository, we organize papers into core methods, domain applications, and cross-domain task settings to make the taxonomy easier to navigate. We will keep updating this repository with the latest research developments. We are aware that there will inevitably be some mistakes and oversights, so if you have any questions or suggestions, please feel free to contact us (menglin.yang[@]outlook.com).

<table>
<tr><td colspan="2"><a href="#latest-update" style="color:#B22222">1. Latest Update</a></td></tr> 
<tr><td colspan="2"><a href="papers.md#2-core-methods-and-geometry" style="color:#B22222">2. Core Methods and Geometry</a></td></tr>
<tr>
    <td>&ensp;<a href="papers.md#21-hyperbolic-shallow-models-and-embeddings">2.1 Hyperbolic Shallow Models and Embeddings</a></td>
    <td>&ensp;<a href="papers.md#22-hyperbolic-neural-networks">2.2 Hyperbolic Neural Networks</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="papers.md#23-hyperbolic-graph-neural-networks">2.3 Hyperbolic Graph Neural Networks</a></td>
    <td>&ensp;<a href="papers.md#24-attention-transformers-and-sequence-models">2.4 Attention, Transformers, and Sequence Models</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#25-theory-analysis-and-numerical-stability">2.5 Theory, Analysis, and Numerical Stability</a></td>
    <td>&ensp;<a href="papers.md#26-hierarchy-and-tree-modeling">2.6 Hierarchy and Tree Modeling</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="papers.md#27-mixed-curvature-and-alternative-geometries">2.7 Mixed-Curvature and Alternative Geometries</a></td>
    <td>&ensp;<a href="papers.md#28-hyperbolic-generative-models">2.8 Hyperbolic Generative Models</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#29-hyperbolic-classifiers-and-decision-models">2.9 Hyperbolic Classifiers and Decision Models</a></td>
    <td>&ensp;<a href="papers.md#210-hyperbolic-operations-and-representation-utilities">2.10 Hyperbolic Operations and Representation Utilities</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#211-llms-and-foundation-models">2.11 LLMs and Foundation Models</a></td>
    <td></td>
</tr>
<tr><td colspan="2"><a href="papers.md#3-domain-applications" style="color:#B22222">3. Domain Applications</a></td></tr>
<tr>
    <td>&ensp;<a href="papers.md#31-language-and-text-applications">3.1 Language and Text Applications</a></td>
    <td>&ensp;<a href="papers.md#32-computer-vision-graphics-and-robotics">3.2 Computer Vision, Graphics, and Robotics</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#33-graphs-and-networked-data">3.3 Graphs and Networked Data</a></td>
    <td>&ensp;<a href="papers.md#34-recommender-systems">3.4 Recommender Systems</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#35-knowledge-graphs">3.5 Knowledge Graphs</a></td>
    <td>&ensp;<a href="papers.md#36-biology-and-molecular-learning">3.6 Biology and Molecular Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#37-code-representation">3.7 Code Representation</a></td>
    <td></td>
</tr>
<tr><td colspan="2"><a href="papers.md#4-task-oriented-settings" style="color:#B22222">4. Task-Oriented Settings</a></td></tr>
<tr>
    <td>&ensp;<a href="papers.md#41-multi-label-and-hierarchical-classification">4.1 Multi-label and Hierarchical Classification</a></td>
    <td>&ensp;<a href="papers.md#42-metric-learning-retrieval-and-clustering">4.2 Metric Learning, Retrieval, and Clustering</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#43-data-driven-geometry-learning-and-adaptation">4.3 Data-Driven Geometry Learning and Adaptation</a></td>
    <td>&ensp;<a href="papers.md#44-few-shot-and-low-data-learning">4.4 Few-Shot and Low-Data Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#45-open-vocabulary-zero-shot-and-category-discovery">4.5 Open-Vocabulary, Zero-Shot, and Category Discovery</a></td>
    <td>&ensp;<a href="papers.md#46-safety-robustness-and-privacy">4.6 Safety, Robustness, and Privacy</a></td>
</tr>
<tr>
    <td>&ensp;<a href="papers.md#47-environmental-monitoring">4.7 Environmental Monitoring</a></td>
    <td>&ensp;<a href="papers.md#48-multi-criteria-learning">4.8 Multi-Criteria Learning</a></td>
</tr>
</table>




**Hyperbolic Slack Group**
- Slack: https://join.slack.com/t/hyperboliclearning/shared_invite/zt-1qcqgtwfr-HpsRSzDhvkAEal6dOnKDvA
- Website: https://hyperboliclearning.github.io/collection


## [Latest Update](#content)
- March 11, 2026: add EMNLP 2025, WSDM 2025, RecSys 2025, AISTATS 2025, LoG 2025 papers 🔥
- March 7, 2026: add ICLR 2026, CVPR 2026 papers 🔥
- December 17, 2025: add NeurIPS 2025, AAAI 2026 papers 
- August 17, 2025: add ICCV 2025 papers
- Jun 10, 2025 : add ICML 2025, ICML 2024 papers
- Jun  7, 2025 : update CVPR 2025, SIGIR 2025, ACL 2025 paper
- Feb 26, 2025 : update ICLR 2025 papers 
- Dec 29, 2024 : update NeurIPS 2024 papers 
- Dec 16, 2024 : add NeurIPS 2024 papers
- Sept 8, 2024 : add ICML 2024, KDD 2024, WWW 2024, SIGIR 2024, ICDE 2024, CVPR 2024 papers
 


**CVPR 2026**
1. [Hyperbolic Prototype Learning with Uncertainty-Aware Consistency for Continual Test-Time Segmentation](https://www.linkedin.com/posts/sdivakarbhat_two-accepted-cvpr-activity-7431711068017582080-zvj2), CVPR 2026 \
*Siddhant Gole, Akash Pal, Amit More, Srinivasa Divakar Bhat, Subhasis Chaudhuri, Biplab Banerjee*

1. [GeoWorld: Geometric World Models](https://arxiv.org/abs/2602.23058), CVPR 2026 \
*Zeyu Zhang, Danning Li, Ian Reid, Richard Hartley*

1. [HiTag: Hierarchical Image Tagging with Hyperbolic Vision-Language Modeling](https://bjxdw.github.io/), CVPR 2026 \
*Yi Yang, Ziyue Peng, Kang Zhang, Xincheng Tan, Fan Lu, Jingting Ding, Kecheng Zheng, Minfeng Zhu, Wei Chen*

1. [HypeVPR: Exploring Hyperbolic Space for Perspective to Equirectangular Visual Place Recognition](https://arxiv.org/abs/2506.04764), CVPR 2026 \
*Suhan Woo, Seongwon Lee, Jinwoo Jang, Euntai Kim*

**ICLR 2026**
1. [Understanding and Improving Hyperbolic Deep Reinforcement Learning](https://openreview.net/forum?id=7rfdenlP1L), ICLR 2026 Poster \
*Timo Klein, Thomas Lang, Andrii Shkabrii, Alexander Sturm, Kevin Sidak, Lukas Miklautz, Claudia Plant, Yllka Velaj, Sebastian Tschiatschek*

1. [PoinnCARE: Hyperbolic Multi-Modal Learning for Enzyme Classification](https://openreview.net/forum?id=dGxAYNK6JU), ICLR 2026 Poster \
*Kun Xie, Peng Zhou, Xingyi Zhang, Wei Liu, Peilin Zhao, Sibo Wang, Biaobin Jiang*

1. [The Natural Geometry of Code: Hyperbolic Representation Learning for Program Reasoning](https://openreview.net/forum?id=oq4jXWaFyH), ICLR 2026 Poster \
*Weilin Zhou*

**NeurIPS 2025**
1. [HELM: Hyperbolic Large Language Models via Mixture-of-Curvature Experts](https://arxiv.org/abs/2505.24722), NeurIPS 2025 \
*Neil He, Rishabh Anand, Hiren Madhu, Ali Maatouk, Smita Krishnaswamy, Leandros Tassiulas, Menglin Yang, Rex Ying*

1. [Hyperbolic Fine-Tuning for Large Language Models](https://neurips.cc/virtual/2025/poster/117823), NeurIPS 2025 (Spotlight) \
*Menglin Yang, Ram Samarth B B, Aosong Feng, Bo Xiong, Jiahong Liu, Irwin King, Rex Ying*

1. [HyperET: Efficient Training in Hyperbolic Space for Multi-modal Large Language Models](https://neurips.cc/virtual/2025/poster/118372), NeurIPS 2025 (Oral) \
*Zelin Peng, Zhengqin Xu, Qingyang Liu, Xiaokang Yang, Wei Shen*

1. [Hyperbolic Dataset Distillation](https://arxiv.org/abs/2505.24623), [Code](https://github.com/Guang000/HDD), NeurIPS 2025 \
*Wenyuan Li, Guang Li, Keisuke Maeda, Takahiro Ogawa, Miki Haseyama*

1. [Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically Aware Sign Language Translation](https://arxiv.org/abs/2506.00129), [Code](https://github.com/ed-fish/geo-sign), NeurIPS 2025 \
*Edward Fish, Richard Bowden*

**NeurIPS 2025 Workshop**
1. [Hyperbolic Multimodal Representation Learning for Biological Taxonomies](https://arxiv.org/abs/2508.16744), NeurIPS 2025 Workshop on Imageomics \
*ZeMing Gong, Chuanqi Tang, Xiaoliang Huo, Nicholas Pellegrino, Austin T. Wang, Graham W. Taylor, Angel X. Chang, Scott C. Lowe, Joakim Bruslund Haurum*

1. [Hyperbolic Few-Shot Learning for Taxonomic Plant Classification](https://openreview.net/forum?id=7F9ObzcT7I), NeurIPS 2025 Workshop on Imageomics \
*Mithil Shah*

**AAAI 2026**
1. [Hyperbolic Hierarchical Alignment Reasoning Network for Text-3D Retrieval](https://arxiv.org/abs/2511.11045), AAAI 2026 \
*Wenrui Li, Yidan Lu, Yeyu Chai, Rui Zhao, Hengyu Man, Xiaopeng Fan*

**EMNLP 2025**
1. [HyperKGR: Knowledge Graph Reasoning in Hyperbolic Space with Graph Neural Network Encoding Symbolic Path](https://aclanthology.org/2025.emnlp-main.1279/), EMNLP 2025 \
*Lihui Liu*

**EMNLP Findings 2025**
1. [Exploring Hyperbolic Hierarchical Structure for Multimodal Rumor Detection](https://aclanthology.org/2025.findings-emnlp.8/), Findings of EMNLP 2025 \
*Md Mahbubur Rahman, Shufeng Hao, Chongyang Shi, An Lao, Jinyan Liu*

1. [Human-Inspired Obfuscation for Model Unlearning: Local and Global Strategies with Hyperbolic Representations](https://aclanthology.org/2025.findings-emnlp.774/), Findings of EMNLP 2025 \
*Zekun Wang, Jingjie Zeng, Yingxu Li, Liang Yang, Hongfei Lin*

**WSDM 2025**
1. [Review-Based Hyperbolic Cross-Domain Recommendation](https://www.wsdm-conference.org/2025/accepted-papers/), WSDM 2025 \
*Yoonhyuk Choi, Jiho Choi, Taewook Ko*

**RecSys 2025**
1. [Learning geometry-aware recommender systems with manifold regularization](https://recsys.acm.org/recsys25/accepted-contributions/), RecSys 2025 (LBR) \
*Zaira Zainulabidova, Julia Borisova, Alexander Hvatov*

1. [Leveraging Geometric Insights in Hyperbolic Triplet Loss for Improved Recommendations](https://recsys.acm.org/recsys25/accepted-contributions/), RecSys 2025 (LBR) \
*Viacheslav Yusupov, Maxim Rakhuba, Evgeny Frolov*

**AISTATS 2025**
1. [Knowledge Graph Completion with Mixed Geometry Tensor Factorization](https://proceedings.mlr.press/v258/yusupov25a.html), AISTATS 2025 \
*Viacheslav Yusupov, Maxim Rakhuba, Evgeny Frolov*

1. [Hyperbolic Prototypical Entailment Cones for Image Classification](https://proceedings.mlr.press/v258/fonio25a.html), AISTATS 2025 \
*Samuele Fonio, Roberto Esposito, Marco Aldinucci*

1. [Hyperboloid GPLVM for Discovering Continuous Hierarchies via Nonparametric Estimation](https://proceedings.mlr.press/v258/watanabe25a.html), AISTATS 2025 \
*Koshi Watanabe, Keisuke Maeda, Takahiro Ogawa, Miki Haseyama*

1. [Variational Combinatorial Sequential Monte Carlo for Bayesian Phylogenetics in Hyperbolic Space](https://proceedings.mlr.press/v258/chen25f.html), AISTATS 2025 \
*Alex Chen, Philippe Chlenski, Kenneth Munyuza, Antonio Khalil Moretti, Christian A. Naesseth, Itsik Pe'er*

**LoG 2025**
1. [Hyperbolic Kernel Convolution: A Generic Framework](https://proceedings.mlr.press/v269/qu25a.html), LoG 2025 \
*Eric Qu, Lige Zhang, Habib Debaya, Yue Wu, Dongmian Zou*

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
1. [Rethinking Generalizable Face Anti-spoofing via Hierarchical Prototype-guided Distribution Refinement in Hyperbolic Space](https://openaccess.thecvf.com/content/CVPR2024/papers/Hu_Rethinking_Generalizable_Face_Anti-spoofing_via_Hierarchical_Prototype-guided_Distribution_Refinement_in_CVPR_2024_paper.pdf), CVPR 2024 \
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
