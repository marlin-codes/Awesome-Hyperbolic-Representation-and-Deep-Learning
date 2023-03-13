## Introduction

Recently, hyperbolic spaces have emerged as a promising alternative for processing graph data with tree-like structure or power-law distribution, owing to its exponential growth property. Different from the Euclidean space which expands polynomially, the hyperbolic space grows exponentially which makes it gains natural advantages in abstracting tree-like or scale-free graphs with hierarchical organizations.  In this repository, we categorize papers related to hyperbolic representation learning into different types to facilitate researcher studies and to promote the development of the community. We will keep updating this repository with latest research developments. We are aware that there will inevitable be some mistakes and oversights, so if you have any questions and suggestions, please feel free to contact us (mlyang@link.cuhk.edu.hk). 


<table>
<tr><td colspan="2"><a href="#latest-update", p style="color:#B22222">1. Lastest Update</a></td></tr> 
<tr><td colspan="2"><a href="#surveys-books-tools-tutorials", p style="color:#B22222">2. Surveys, Books, Tools and Tutorials</a></td></tr>
<tr>
    <td>&ensp;<a href="#surveys">2.1 Surveys</a></td>
    <td>&ensp;<a href="#books">2.2  Books </a></td>
</tr>
<tr>
    <td>&ensp;<a href="#tools">2.3 Tools </a></td>
    <td>&ensp;<a href="#tutorials">2.4 Tutorials</a></td>
</tr>
<tr><td colspan="2"><a href="#methods", p style="color:#B22222">3. Methods</a></td></tr> 
<tr>
    <td>&ensp;<a href="#hyperbolic-shallow-model">3.1 Hyperbolic Shallow Model</a></td>
    <td>&ensp;<a href="#hyperbolic-neural-network">3.2 Hyperbolic Neural Network</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#hyperbolic-graph-neural-network">3.3 Hyperbolic Graph Neural Network</a></td>
    <td>&ensp;<a href="#mixed-curvature-learning">3.4 Mixed Curvature Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#ultrahyperbolic-learning">3.5 Ultrahyperbolic Learning</a></td>
    <td>&ensp;<a href="#hyperbolic-operations">3.6 Hyperbolic Operations</a></td>
</tr> 
<tr><td colspan="2"><a href="#applications", p style="color:#B22222">4. Applications</a></td></tr> 

<tr>
    <td>&ensp;<a href="#recommender-systems">4.1 Recommender Systems</a></td>
    <td>&ensp;<a href="#knowledge-graphs">4.2 Knowledge Graphs</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#molecular-learning">4.3 Molecular Learning </a></td>
    <td>&ensp;<a href="#dynamic-graphs">4.4 Dynamic Graphs</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#code-representation">4.4 Code Representation</a></td>
    <td>&ensp;<a href="#graph-embeddings">4.5 Graph Embedding</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#word-embeddings">4.6 Word Embedding</a></td>
    <td>&ensp;<a href="#multi-label-learning">4.7 Multi-label Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#computer-vision">4.8 Computer Vision</a></td>
    <td>&ensp;<a href="#natural-language-processing">4.9 Natural Language Processing</a></td>
</tr>
</table>

Hyperbolic Machine Learning Groups:
- Slack: https://join.slack.com/t/hyperboliclearning/shared_invite/zt-1qcqgtwfr-HpsRSzDhvkAEal6dOnKDvA


## [Latest update](#content)

1. [Lorentz Equivariant Model for Knowledge-Enhanced Collaborative Filtering](https://arxiv.org/abs/2302.04545)

2. [FFHR: Fully and Flexible Hyperbolic
Representation for Knowledge Graph
Completion](https://arxiv.org/pdf/2302.04088.pdf)

3. [Dimensionality Selection for Hyperbolic Embeddings using Decomposed Normalized Maximum Likelihood Code-Length](https://www.researchsquare.com/article/rs-2550932/v1)

4. [Hyperbolic Contrastive Learning](https://arxiv.org/pdf/2302.01409.pdf)

5. [CO-SNE: Dimensionality Reduction and Visualization for Hyperbolic Data](https://arxiv.org/abs/2111.15037) for embedding visualization, CVPR 2022

6. [HICF: Hyperbolic Informative Collaborative Filtering](https://arxiv.org/abs/2207.09051) for recommender systems, KDD 2022

7. [HyperAid: Denoising in hyperbolic spaces for tree-fitting and hierarchical clustering](https://arxiv.org/abs/2205.09721) for clustering, KDD 2022

8. [Wrapped Distributions on homogeneous Riemannian manifolds](https://arxiv.org/abs/2204.09790)  for hyperbolic sampling, arxiv 2022

9. [Contrastive Multi-view Hyperbolic Hierarchical Clustering](https://arxiv.org/abs/2205.02618) for clustering, IJCAI 2022

10. [Hyperbolic Relevance Matching for Neural Keyphrase Extraction](https://arxiv.org/abs/2205.02047) for key phrases matching, Naacl 2022

11. [Cross-lingual Word Embeddings in Hyperbolic Space](https://arxiv.org/abs/2205.01907) for word embedding, arxiv 2022

12. [Geometry Interaction Knowledge Graph Embeddings](https://www.aaai.org/AAAI22Papers/AAAI-11284.CaoZ.pdf) for KG embedding, AAAI 2022


## [Surveys, Books, Tools, Tutorials](#content)

### [Surveys](#content)

1. [Hyperbolic Graph Neural Networks: A Review of Methods and Application](https://arxiv.org/abs/2202.13852), arxiv 2022.
[GitHub](https://github.com/marlin-codes/HGNNs) \
*Menglin Yang, Min Zhou, Zhihao Li, Jiahong Liu, Lujia Pan, Hui Xiong, Irwin King*

1. [Hyperbolic Deep Neural Networks: A Survey](https://arxiv.org/abs/2101.04562), TPAMI 2022.
[GitHub](https://github.com/xiaoiker/Awesome-Hyperbolic-NeuralNetworks) \
*Wei Peng, Tuomas Varanka, Abdelrahman Mostafa, Henglin Shi, Guoying Zhao*

### [Books](#content)

1. [Hyperbolic Geometry](https://arxiv.org/abs/2003.11180), 2020. \
Brice Loustau

1. [Manifolds and Differential Geometry](https://www.ams.org/books/gsm/107/gsm107-endmatter.pdf), 2009. \
*Jeffrey M. Lee*

### [Tools](#content)

1. [Geoopt: Riemannian Adaptive Optimization Methods](https://github.com/geoopt/geoopt) ICLR 2019 \
*Max Kochurov and Rasul Karimov and Serge Kozlukov*

1. [Curvature Learning Framework](https://github.com/alibaba/Curvature-Learning-Framework) \
Alibaba

1. [GraphZoo: A Development Toolkit for Graph Neural Networks with Hyperbolic Geometries](https://github.com/AnoushkaVyas/GraphZoo) WWW 2022 \
*Anoushka Vyas, Nurendra Choudhary, Mehrdad Khatir, Chandan K. Reddy*


### [Tutorials](#content)

1. [Hyperbolic Representation Learning for Computer Vision](https://sites.google.com/view/hyperbolic-tutorial-eccv22/homepage). Tutorial 2022 \
*Pascal Mettes, Mina Ghadimi Atigh, Martin Keller-Ressel, Jeffrey Gu, Serena Yeung@ECCV2022* \
https://hyperbolic-representation-learning.readthedocs.io/en/latest/

2. [Hyperbolic Graph Representation Learning](https://hyperbolicgraphlearning.github.io/). Tutorial 2022 \
*Min Zhou, Menglin Yang, Lujia Pan, Irwin King @ ECML-PKDD 2022*

1. [Hyperbolic Neural Network](https://nurendra.me/hyperbolic-networks-tutorial/kdd-2022/). Tutorial 2022 \
*Nurendra Choudhary, Nikhil Rao, Karthik Subbian, Srinivasan Sengamedu, Chandan Reddy @ KDD 2022*

1. [Hyperbolic Hyperbolic embeddings in machine learning and deep learning](https://www.youtube.com/watch?v=-ksbWExpWis). Tutorial 2020 \
*Octavian Ganea 2020.*


## [Methods](#content)

### [Hyperbolic Shallow Model](#content)

1. [Learning Continuous Hierarchies in the Lorentz Model of Hyperbolic Geometry](https://arxiv.org/abs/1806.03417), ICML 2018 \
*Maximilian Nickel, Douwe Kiela*

1. [Poincaré Embeddings for Learning Hierarchical Representations](https://arxiv.org/abs/1705.08039), NeurIPS 2017 \
*Maximilian Nickel, Douwe Kiela*

 
### [Hyperbolic Neural Network](#content)


1. [Fully Hyperbolic Neural Networks](https://arxiv.org/abs/2105.14686), ACL 2022 \
*Weize Chen, Xu Han, Yankai Lin, Hexu Zhao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou*

1. [Hyperbolic Neural Network++](https://arxiv.org/abs/2006.08210), ICLR 2021 \
*Ryohei Shimizu, Yusuke Mukuta, Tatsuya Harada*

1. [Hyperbolic Attention Networks](https://arxiv.org/abs/1805.09786), ICLR 2019 \
*Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas*

1. [Hyperbolic Neural Networks](https://arxiv.org/abs/1805.09112), NeurIPS 2018 \
*Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann*


### [Hyperbolic Graph Neural Network](#content)


1. [Hyperbolic Graph Convolutional Neural Networks](https://arxiv.org/abs/1910.12933), NeurIPS 2019 \
*Ines Chami\*, Rex Ying\*, Christopher Ré, Jure Leskovec*

1. [Hyperbolic Graph Neural Network](https://arxiv.org/abs/1910.12892), NeurIPS 2019  \
*Qi Liu, Maximilian Nickel, Douwe Kiela*

1. [Lorentzian Graph Convolutional Networks](https://arxiv.org/abs/2104.07477), WWW 2021 \
*Yiding Zhang, Xiao Wang, Chuan Shi, Nian Liu, Guojie Song*

1. [A Hyperbolic-to-Hyperbolic Graph Convolutional Network](https://arxiv.org/abs/2104.06942), CVPR 2021 \
*Jindou Dai, Yuwei Wu, Zhi Gao, Yunde Jia*

1. [Hyperbolic Graph Attention Network](https://arxiv.org/abs/1912.03046), Transcations on Big Data 2021 \
*Yiding Zhang, Xiao Wang, Xunqiang Jiang, Chuan Shi, Yanfang Ye*

1. [Unsupervised Hyperbolic Representation Learning via Message Passing Auto-Encoders](https://arxiv.org/abs/2103.16046), CVPR 2021 \
*Jiwoong Park, Junho Cho, Hyung Jin Chang, Jin Young Choi*


### [Mixed Curvature Learning](#content)

1. [A Self-supervised Mixed-curvature Graph Neural Network](https://arxiv.org/abs/2112.05393), AAAI 2022 \
*Li Sun, Zhongbao Zhang, Junda Ye, Hao Peng, Jiawei Zhang, Sen Su, Philip S. Yu*

1. [Enhancing Hyperbolic Graph Embeddings via Contrastive Learning](https://arxiv.org/abs/2201.08554), NeurIPS 2021 SSL Workshop \
*Jiahong Liu, Menglin Yang, Min Zhou, Shanshan Feng, Philippe Fournier-Viger*

1. [Geometry Interaction Learning](https://arxiv.org/abs/2010.12135), NeurIPS 2020 \
*Shichao Zhu, Shirui Pan, Chuan Zhou, Jia Wu, Yanan Cao, Bin Wang*

1. [Constant Curvature Graph Convolutional Networks](https://arxiv.org/abs/1911.05076), ICML 2020 \
*Gregor Bachmann, Gary Bécigneul, Octavian-Eugen Ganea*


### [Ultrahyperbolic Learning](#content)

1. [Semi-Riemannian Graph Convolutional Networks](https://arxiv.org/abs/2106.03134), NeurIPS 2022 \
*Bo Xiong, Shichao Zhu, Nico Potyka, Shirui Pan, Chuan Zhou, Steffen Staab*

1. [Ultrahyperbolic Neural Networks](https://openreview.net/forum?id=sf2BxJNXC3K), NeurIPS 2021 \
*Marc T Law*

1. [Ultrahyperbolic Representation Learning](https://arxiv.org/abs/2007.00211), NeurIPS 2020 \
*Marc T. Law, Jos Stam*

### [Hyperbolic Operations](#content)

1. Mean Computation and BatchNorm \
[Differentiating through the Fréchet Mean](https://arxiv.org/abs/2003.00335), ICML 2022 \
*Aaron Lou, Isay Katsman, Qingxuan Jiang, Serge Belongie, Ser-Nam Lim, Christopher De Sa*

1. Normalizing Flow \
[Latent Variable Modelling with Hyperbolic Normalizing Flows](https://arxiv.org/abs/2002.06336), ICML 2020  \
*Avishek Joey Bose, Ariella Smofsky, Renjie Liao, Prakash Panangaden, William L. Hamilton*

1. Sampling \
[Wrapped Distributions on homogeneous Riemannian manifolds](https://arxiv.org/abs/2204.09790), 2022 \
*Fernando Galaz-Garcia, Marios Papamichalis, Kathryn Turnbull, Simon Lunagomez, Edoardo Airoldi*

1. MixUp \
[HYPMIX: Hyperbolic Interpolative Data Augmentation](https://aclanthology.org/2021.emnlp-main.776/), EMNLP 2021 \
*Ramit Sawhney, Megh Thakkar, Shivam Agarwal, Di Jin, Diyi Yang, Lucie Flek*

1. PCA \
[HoroPCA: Hyperbolic Dimensionality Reduction via Horospherical Projections](https://arxiv.org/abs/2106.03306), ICML 2021 \
*Ines Chami\*, Albert Gu\*, Dat Nguyen, Christopher Ré*

## [Applications](#content)


### [Recommender Systems](#content)

#### [Hyperbolic Graph Neural Network for Recommender Systems](#content)

1. [HICF: Hyperbolic Informative Collaborative Filtering](https://arxiv.org/abs/2207.09051), KDD 2022 \
*Menglin Yang, Zhihao Li, Min Zhou, Jiahong Liu, Irwin King*

1. [HRCF: Enhancing Collaborative Filtering via Hyperbolic Geometric Regularization](https://arxiv.org/abs/2204.08176), WWW 2022 \
*Menglin Yang, Min Zhou, Jiahong Liu, Defu Lian, Irwin King*

1. [HAKG: Hierarchy-Aware Knowledge Gated Network for Recommendation](https://arxiv.org/abs/2204.04959), SIGIR 2022 \
*Yuntao Du, Xinjun Zhu, Lu Chen, Baihua Zheng, and Yunjun Gao*

1. [Geometric Inductive Matrix Completion: A Hyperbolic Approach with Unified Message Passing](https://dl.acm.org/doi/abs/10.1145/3488560.3498402), WSDM 2022 \
*Chengkun Zhang , Hongxu Chen , Sixiao Zhang , Guandong Xu , Junbin Gao*

1. [Modeling Scale-free Graphs with Hyperbolic Geometry for Knowledge-aware Recommendation](https://arxiv.org/abs/2108.06468), WSDM 2022 \
*Yankai Chen, Menglin Yang, Yingxue Zhang, Mengchen Zhao, Ziqiao Meng, Jianye Hao, Irwin King*

1. [HGCF: Hyperbolic Graph Convolution Networks for Collaborative Filtering](https://www.cs.toronto.edu/~mvolkovs/www2021_hgcf.pdf), WWW 2021 \
*Jianing Sun,Zhaoyue Cheng,Saba Zuberi,Felipe Perez,Maksims Volkovs*

1. [Hypersorec: Exploiting hyperbolic user and item representations with multiple aspects for social-aware recommendation](http://home.ustc.edu.cn/~wanghao3/papers/haowang_TOIS2021.pdf), TOIS 2021 \
*Hao Wang, Defu Lian, Hanghang Tong, Qi Liu, Zhenya Huang and Enhong Chen*

1. [Knowledge Based Hyperbolic Propagation](http://dl.acm.org/doi/abs/10.1145/3404835.3462980), SIGIR short paper 2021 \
*Chang-You Tai, Chien-Kun Huang, Liang-Ying Huang, Lun-Wei Ku*

1. [HSR: hyperbolic social recommender](https://arxiv.org/abs/2102.09389), Information Sciences 2022 \
*Anchen Li, Bo Yang*
 
1. [HCGR: Hyperbolic Contrastive Graph Representation Learning for Session-based Recommendation](https://arxiv.org/abs/2107.05366), arxiv 2021 \
*Naicheng Guo, Xiaolei Liu, Shaoshuai Li, Qiongxu Ma, Yunan Zhao, Bing Han, Lin Zheng, Kaixin Gao, Xiaobo Guo*

1. [Hyperbolic Hypergraphs for Sequential Recommendation](https://arxiv.org/abs/2108.08134), CIKM 2021 \
*Yicong Li, Hongxu Chen, Xiangguo Sun, Zhenchao Sun, Lin Li, Lizhen Cui, Philip S. Yu, Guandong Xu*

#### [Hyperbolic Neural Network for Recommender Systems](#content)

1. [Where are we in embedding spaces? A Comprehensive Analysis on Network Embedding Approaches for Recommender Systems](https://arxiv.org/abs/2105.08908) KDD 2021 \
*Sixiao Zhang, Hongxu Chen, Xiao Ming, Lizhen Cui, Hongzhi Yin, Guandong Xu*


1. [Learning Feature Interactions with Lorentzian Factorization Machine](https://arxiv.org/abs/1911.09821), AAAI 2020 \
*Canran Xu, Ming Wu*

1. [HyperML: A Boosting Metric Learning Approach in Hyperbolic Space for Recommender Systems](https://arxiv.org/abs/1809.01703), WSDM 2020 \
*Lucas Vinh Tran, Yi Tay, Shuai Zhang, Gao Cong, Xiaoli Li*

1. [Scalable Hyperbolic Recommender Systems](https://arxiv.org/abs/1902.08648), WSDM 2020 \
*Benjamin Paul Chamberlain, Stephen R. Hardwick, David R. Wardrope, Fabon Dzogang, Fabio Daolio, Saúl Vargas*

1. [A hyperbolic metric embedding approach for next-poi recommendation](https://dl.acm.org/doi/10.1145/3397271.3401049), SIGIR 2020 \
*Shanshan Feng , Lucas Vinh Tran , Gao Cong , Lisi Chen , Jing Li , Fan Li*

1. [Node2LV: Squared Lorentzian Representations for Node Proximity](https://ieeexplore.ieee.org/document/9458940)， ICDE 2021 \
*Shanshan Feng, Lisi Chen, Kaiqi Zhao, Wei Wei, Fan Li, Shuo Shang*

### [Knowledge Graphs](#content)

#### [Hyperbolic Graph Neural Network for Knowledge Graphs](#content)

1. [Knowledge Association with Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2010.02162), EMNLP 2020 \
*Zequn Sun, Muhao Chen, Wei Hu, Chengming Wang, Jian Dai, Wei Zhang*

1. [Knowledge Graph Representation via Hierarchical Hyperbolic Neural Graph Embedding](https://ieeexplore.ieee.org/document/9671651), IEEE Big Data \
*Shen Wang, Xiaokai Wei, Cicero Nogueira Dos Santos, Zhiguo Wang, Ramesh Nallapati, Andrew Arnold, Philip S. Yu*

1. [Mixed-Curvature Multi-relational Graph Neural Network for Knowledge Graph Completion](https://assets.amazon.science/0c/9d/51d98f1040b1bfa7dc52d1015750/mixed-curvature-multi-relational-graph-neural-network-for-knowledge-graph-completion.pdf), WWW 2021 \
*Shen Wang , Xiaokai Wei , Cicero Nogueira Nogueira dos Santos , Zhiguo Wang , Ramesh Nallapati , Andrew Arnold , Bing Xiang , Philip S. Yu , Isabel F. Cruz*

#### [Hyperbolic Translational Models for KG](#content)

1. [Low-Dimensional Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2005.00545), ACL 2019 \
*Ines Chami, Adva Wolf, Da-Cheng Juan, Frederic Sala, Sujith Ravi, Christopher Ré*

1. [Multi-relational Poincaré Graph Embeddings](https://arxiv.org/abs/1905.09791), NeurIPS 2019 \
*Ivana Balažević, Carl Allen, Timothy Hospedales*

1. [Modeling Heterogeneous Hierarchies with Relation-specific Hyperbolic Cones](https://arxiv.org/abs/2110.14923)， NeurIPS 2021 \
*Yushi Bai, Rex Ying, Hongyu Ren, Jure Leskovec*

1. [Hyperbolic Temporal Knowledge Graph Embeddings with Relational and Time Curvatures](https://arxiv.org/abs/2106.04311), ACL 2021 \
*Sebastien Montella, Lina Rojas-Barahona, Johannes Heinecke*

1. [Self-supervised hyperboloid representations from logical queries over knowledge graphs](https://arxiv.org/abs/2012.13023), WWW 2021 \
*Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy*


1. [HyperKG: Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion](https://arxiv.org/abs/1908.04895), arxiv \
*Prodromos Kolyvakis, Alexandros Kalousis, Dimitris Kiritsis*

1. [Hyperbolic Hierarchy-Aware Knowledge Graph Embedding for Link Prediction](https://aclanthology.org/2021.findings-emnlp.251/). EMNLP findings 2021 \
*Zhe Pan, Peng Wang*

### [Molecular Learning](#content)

#### [Hyperbolic Graph Neural Network for Molecular Learning](#content)

1. [Hyperbolic relational graph convolution networks plus: a simple but highly efficient QSAR-modeling method](https://academic.oup.com/bib/article-abstract/22/5/bbab112/6235968?redirectedFrom=fulltext), Briefings in Bioinformatics 2021 \
*Zhenxing Wu, Dejun Jiang, Chang-Yu Hsieh, Guangyong Chen, Ben Liao, Dongsheng Cao, Tingjun Hou*

1. [Semi-supervised  hierarchical  drug  embedding  inhyperbolic space](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00681), J. Chem. Inf. Model 2020 \
*Ke Yu\*, Shyam Visweswaran\*, and Kayhan Batmanghelich*

#### [Hyperbolic Neural Network models for Molecular Learning](#content)

1. [HiG2Vec: hierarchical representations of Gene Ontology and genes in the Poincaré ball](https://academic.oup.com/bioinformatics/article/37/18/2971/6184857?login=false), Bioinformatics, 2021 \
*Jaesik Kim, Dokyoon Kim, Kyung-Ah Sohn*

### [Dynamic Graphs](#content)

1. [Discrete-time Temporal Network Embedding via Implicit Hierarchical Learning in Hyperbolic Space](https://arxiv.org/abs/2107.03767),  KDD 2021 \
*Menglin Yang, Min Zhou, Marcus Kalander, Zengfeng Huang, Irwin King*

1. [Hyperbolic Variational Graph Neural Network for Modeling Dynamic Graphs](https://arxiv.org/abs/2104.02228), AAAI 2021 \
*Li Sun, Zhongbao Zhang, Jiawei Zhang, Feiyang Wang, Hao Peng, Sen Su, Philip S. Yu*

1. [Exploring the Scale-Free Nature of Stock Markets: Hyperbolic Graph Learning for Algorithmic Trading](https://dl.acm.org/doi/10.1145/3442381.3450095),  WWW 2021 \
*Ramit Sawhney , Shivam Agarwal , Arnav Wadhwa , Rajiv Shah*


### [Code Representation](#content)

1. [Hyperbolic Representations of Source Code](https://assets.amazon.science/55/d9/58097f0d41b886269b30e5c68522/hyperbolic-representations-of-source-code.pdf) AAAI 2022 \
*Raiyan Khan, Thanh V. Nguyen, Sengamedu H. Srinivasan*

### [Graph Embeddings](#content)

#### [Hyperbolic Geometry for Heterogeneous Network Embedding](#content)

1. [Hyperbolic Heterogeneous Information Network Embedding](https://ojs.aaai.org/index.php/AAAI/article/view/4471),  AAAI 2020 \
*Xiao Wang, Yiding Zhang, Chuan Shi*

1. [Embedding Heterogeneous Information Network in Hyperbolic Spaces](https://dl.acm.org/doi/abs/10.1145/3468674?sid=SCITRUS), TKDD 2022 \
*Yiding Zhang, Xiao Wang, Nian Liu, Chuan Shi*


#### [Hyperbolic Geometry for Directed Graph Embedding](#content)

1. [Hyperbolic Disk Embeddings for Directed Acyclic Graphs](https://arxiv.org/pdf/1902.04335.pdf)，ICML 2019 \
*Ryota Suzuki, Ryusuke Takahama, Shun Onoda*

1. [A hyperbolic Embedding Model for Directed Networks](https://arxiv.org/abs/1906.03597) \
*Zongning Wu, Zengru Di, Ying Fan* (this paper includes many errors)

#### [Hyperbolic Geometry for Signed Graph Embedding](#content)

1. [Hyperbolic Node Embedding for Signed Networks](https://arxiv.org/abs/1910.13090), Neurcomputing 2021 \
*Wenzhuo Song, Hongxu Chen, Xueyan Liu, Hongzhe Jiang, Shengsheng Wang*

#### [Hyperbolic Geometry for Attributed Graph Embedding](#content)

1. [HEAT: Hyperbolic Embedding of Attributed Networks](https://arxiv.org/abs/1903.03036), IDEAL 2020 \
*David McDonald, Shan He*

### [Word Embeddings](#content)

1. [Poincare Glove: Hyperbolic Word Embeddings](https://arxiv.org/abs/1810.06546), ICLR 2019 \
*Alexandru Tifrea and Gary Becigneul and Octavian-Eugen Gane*

1. [Skip-gram word embeddings in hyperbolic space](https://arxiv.org/abs/1809.01498), ACL 2018 \
*Matthias Leimeister, Benjamin J. Wilson*

1. [Embedding text in hyperbolic spaces](https://arxiv.org/abs/1806.04313), ACL 2018 \
*Bhuwan Dhingra, Christopher J. Shallue, Mohammad Norouzi, Andrew M. Dai, George E. Dahl*

1. [Representation Tradeoffs for Hyperbolic Embeddings](https://arxiv.org/abs/1804.03329), ICML 2018 \
*Christopher De Sa, Albert Gu, Christopher Ré, Frederic Sala*

1. [Hyperbolic entailment cones for learning hierarchical embeddings](https://arxiv.org/abs/1804.01882), ICML 2018 \
*Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann*

1. [Low-rank approximations of hyperbolic embeddings](https://arxiv.org/abs/1903.07307) \
*Pratik Jawanpuria, Mayank Meghwanshi, Bamdev Mishra*

1. [Hyperbolic Multiplex Network Embedding with Maps of Random Walk](https://arxiv.org/abs/1912.08927) \
*Peiyuan Sun*

### [Multi-label Learning](#content)

1. [Hyperbolic interaction model for hierarchical multi-label classification](https://ojs.aaai.org/index.php/AAAI/article/view/6247), AAAI 2021 \
*Boli Chen, Xin Huang, Lin Xiao, Zixin Cai, Liping Jing*

1. [Hyperbolic Capsule Networks for Multi-Label Classification](https://aclanthology.org/2020.acl-main.283/), ACL 2020 \
*Boli Chen, Xin Huang, Lin Xiao, Liping Jing*

1. [Joint Learning of Hyperbolic Label Embeddings for Hierarchical Multi-label Classification](https://arxiv.org/abs/2101.04997), EACL 2021 \
*Soumya Chatterjee, Ayush Maheshwari, Ganesh Ramakrishnan, Saketha Nath Jagaralpudi*

1. [Hyperbolic Embeddings for Hierarchical Multi-label Classification](https://link.springer.com/chapter/10.1007/978-3-030-59491-6_7), 2020 \
*Tomaž StepišnikEmail, Dragi Kocev*

1. [A Fully Hyperbolic Neural Model for Hierarchical Multi-Class Classification](https://arxiv.org/abs/2010.02053), EMNLP findings \
*Federico López, Michael Strube*


### [Computer Vision](#content)
1. [Hyperbolic Vision Transformers: Combining Improvements in Metric Learning](https://arxiv.org/abs/2203.10833),CVPR 2022 \
*Aleksandr Ermolov, Leyla Mirvakhabova, Valentin Khrulkov, Nicu Sebe, Ivan Oseledets*

1. [Clipped Hyperbolic Classifiers Are Super-Hyperbolic Classifiers](https://arxiv.org/abs/2107.11472), CVPR 2022 \
*Yunhui Guo, Xudong Wang, Yubei Chen, Stella X. Yu*

1. [Hyperbolic Image Segmentation](https://arxiv.org/abs/2203.05898), CVPR 2022 \
*Mina GhadimiAtigh, Julian Schoep, Erman Acar, Nanne van Noord, Pascal Mettes*

1. [Capturing implicit hierarchical structure in 3D biomedical images with self-supervised hyperbolic representations](https://proceedings.neurips.cc/paper/2021/file/291d43c696d8c3704cdbe0a72ade5f6c-Paper.pdf) NeurIPS 2021 \
*Joy Hsu, Jeffrey Gu, Gong-Her Wu, Wah Chiu, Serena Yeung*

1. [Learning Hyperbolic Representations of Topological Features](https://arxiv.org/abs/2103.09273) ICLR 2021 \
*Panagiotis Kyriakis, Iordanis Fostiropoulos, Paul Bogdan*

1. [Curvature Generation in Curved Spaces for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf), ICCV 2021 \
*Zhi\* Gao, Yuwei Wu\*, Yunde Jia, Mehrtash Harandi*

1. [Unsupervised Discovery of the Long-Tail in Instance Segmentation Using Hierarchical Self-Supervision](https://arxiv.org/abs/2104.01257), CVPR 2021 \
*Zhenzhen Weng, Mehmet Giray Ogut, Shai Limonchik, Serena Yeung*

1. [Searching for Actions on the Hyperbole](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9157196), CVPR 2020 \
Teng Long, Pascal Mettes, Heng Tao Shen, Cees Snoek

1. [Mix Dimension in Poincaré Geometry for 3D Skeleton-based Action Recognition](https://dl.acm.org/doi/abs/10.1145/3394171.3413910), ACM MM 2020 \
*Wei Peng, Jingang Shi, Zhaoqiang Xia, Guoying Zhao*

1. [Hyperbolic Image Embedding](https://arxiv.org/abs/1904.02239), CVPR 2020 \
*Valentin Khrulkov, Leyla Mirvakhabova, Evgeniya Ustinova, Ivan Oseledets, Victor Lempitsky*

1. [Meta Hyperbolic Networks for Zero-Shot Learning](https://www.sciencedirect.com/science/article/pii/S0925231222003344), Neurocomputing \
*Yan Xu, Lifu Mu, ZhongJi, Xiyao Liu, JungongHan*

### [Natural Language Processing](#content)

1. [Medical Triage Chatbot Diagnosis Improvement via Multi-relational Hyperbolic Graph Neural Network](https://dl.acm.org/doi/abs/10.1145/3404835.3463095). SIGIR short paper 2021 \
*Zheng Liu , Xiaohan Li , Zeyu You , Tao Yang , Wei Fan , Philip Yu*

1. [ANTHEM: Attentive Hyperbolic Entity Model for Product Search](https://dl.acm.org/doi/10.1145/3488560.3498456). WSDM 2022 \
*Nurendra Choudhary , Nikhil Rao , Sumeet Katariya , Karthik Subbian , Chandan K. Reddy*

### [Hyperbolic Metric Learning](#content)

1. [Hyperbolic Busemann Learning with Ideal Prototypes](https://proceedings.neurips.cc/paper/2021/file/01259a0cb2431834302abe2df60a1327-Paper.pdf), NeurIPS 2021 \
*Mina Ghadimi Atigh, Martin Keller-Ressel, Pascal Mettes*


1. [Unsupervised Hyperbolic Metric Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_Unsupervised_Hyperbolic_Metric_Learning_CVPR_2021_paper.pdf), CVPR 2021 \
*Jiexi Yan, Lei Luo, Cheng Deng, Heng Huang*

Contributed by: Menglin Yang, Min Zhou
