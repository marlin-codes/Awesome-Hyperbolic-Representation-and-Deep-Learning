# Awesome hyperbolic graph neural network papers (keep update)

Graph neural networks generalize conventional neural networks to graph-structured data and have received widespread attention due to their impressive representation ability. In spite of the remarkable achievements, the performance of Euclidean models in graph-related learning is still bounded and limited by the representation ability of Euclidean geometry, especially for datasets with highly non-Euclidean latent anatomy. Recently, hyperbolic space has gained increasing popularity in processing graph data with tree-like structure and power-law distribution, owing to its exponential growth property.  In this survey, we comprehensively revisit the technical details of the current hyperbolic graph neural networks https://github.com/marlin-codes/HGNNs , unifying them into a general framework and summarizing the variants of each component. More importantly, we present various HGNN-related applications. For reader convenience, we also list the non-HGNN research. If there are some typos or you have any question, just feel free to contact us (menglin.yang@outlook.com).


| Hyperbolic Manifolds |
| :--------: |
|![](https://i.imgur.com/M3iOEam.png) |


## 1. Survey and Book

[Hyperbolic Graph Neural Networks: A Review of Methods and Application](https://arxiv.org/abs/2202.13852), 2022 [GitHub](https://github.com/marlin-codes/HGNNs) \
Menglin Yang, Min Zhou, Zhihao Li, Jiahong Liu, Lujia Pan, Hui Xiong, Irwin King

[Hyperbolic Deep Neural Networks: A Survey](https://arxiv.org/abs/2101.04562), TPAMI 2022. [GitHub](https://github.com/xiaoiker/Awesome-Hyperbolic-NeuralNetworks) \
Wei Peng, Tuomas Varanka, Abdelrahman Mostafa, Henglin Shi, Guoying Zhao

[Hyperbolic Geometry](https://arxiv.org/abs/2003.11180), Arxiv 2020 TextBook. \
Brice Loustau



## 2. Hyperbolic Models w/o GNN
### 2.1 Hyperbolic Shallow Model

[Poincaré Embeddings for Learning Hierarchical Representations](https://arxiv.org/abs/1705.08039), NeurIPS 2017 \
Maximilian Nickel, Douwe Kiela

[Learning Continuous Hierarchies in the Lorentz Model of Hyperbolic Geometry](https://arxiv.org/abs/1806.03417), ICML 2018 \
Maximilian Nickel, Douwe Kiela

 
### 2.2 Hyperbolic Neural Network

[Hyperbolic Neural Networks](https://arxiv.org/abs/1805.09112), NeurIPS 2018 \
Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann

[Hyperbolic Attention Networks](https://arxiv.org/abs/1805.09786), ICLR 2019 \
Caglar Gulcehre, Misha Denil, Mateusz Malinowski, Ali Razavi, Razvan Pascanu, Karl Moritz Hermann, Peter Battaglia, Victor Bapst, David Raposo, Adam Santoro, Nando de Freitas

[Hyperbolic Neural Network++](https://arxiv.org/abs/2006.08210), ICLR 2021 \
Ryohei Shimizu, Yusuke Mukuta, Tatsuya Harada

[Fully Hyperbolic Neural Networks](https://arxiv.org/abs/2105.14686), ACL 2022 \
Weize Chen, Xu Han, Yankai Lin, Hexu Zhao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou



## 3. HGNN


[Hyperbolic Graph Convolutional Neural Networks](https://arxiv.org/abs/1910.12933), NeurIPS 2019 \
Ines Chami, Rex Ying, Christopher Ré, Jure Leskovec

[Hyperbolic Graph Neural Network](https://arxiv.org/abs/1910.12892), NeurIPS 2019  \
Qi Liu, Maximilian Nickel, Douwe Kiela

[Lorentzian Graph Convolutional Networks](https://arxiv.org/abs/2104.07477), WWW 2021 \
Yiding Zhang, Xiao Wang, Chuan Shi, Nian Liu, Guojie Song

[A Hyperbolic-to-Hyperbolic Graph Convolutional Network](https://arxiv.org/abs/2104.06942), CVPR 2021 \
Jindou Dai, Yuwei Wu, Zhi Gao, Yunde Jia

[Hyperbolic Graph Attention Network](https://arxiv.org/abs/1912.03046), Transcations on Big Data 2021 \
Yiding Zhang, Xiao Wang, Xunqiang Jiang, Chuan Shi, Yanfang Ye



[Unsupervised Hyperbolic Representation Learning via Message Passing Auto-Encoders](https://arxiv.org/abs/2103.16046), CVPR 2021 \
Jiwoong Park, Junho Cho, Hyung Jin Chang, Jin Young Choi


### 3.1 Mixed/Multiple Curvature Space + GNN
[Geometry Interaction Learning](https://arxiv.org/abs/2010.12135), NeurIPS 2020 \
Shichao Zhu, Shirui Pan, Chuan Zhou, Jia Wu, Yanan Cao, Bin Wang

[Constant Curvature Graph Convolutional Networks](https://arxiv.org/abs/1911.05076), ICML 2020 \
Gregor Bachmann, Gary Bécigneul, Octavian-Eugen Ganea

[Enhancing Hyperbolic Graph Embeddings via Contrastive Learning](https://arxiv.org/abs/2201.08554), NeurIPS 2021 SSL Workshop \
Jiahong Liu, Menglin Yang, Min Zhou, Shanshan Feng, Philippe Fournier-Viger

[A Self-supervised Mixed-curvature Graph Neural Network](https://arxiv.org/abs/2112.05393), AAAI 2022 \
Li Sun, Zhongbao Zhang, Junda Ye, Hao Peng, Jiawei Zhang, Sen Su, Philip S. Yu

### 3.2 UnltraHyperblic/Semi-Riemannian + GNN
[Ultrahyperbolic Neural Networks](https://openreview.net/forum?id=sf2BxJNXC3K), NeurIPS 2021 \
Marc T Law

[Ultrahyperbolic Representation Learning](https://arxiv.org/abs/2007.00211), NeurIPS 2020 \
Marc T. Law, Jos Stam


[Semi-Riemannian Graph Convolutional Networks](https://arxiv.org/abs/2106.03134), arxiv 2021 \
Bo Xiong, Shichao Zhu, Nico Potyka, Shirui Pan, Chuan Zhou, Steffen Staab

### 3.3 Scalable HGNNs
[HyLa: Hyperbolic Laplacian Features For Graph Learning](https://arxiv.org/abs/2202.06854), arxiv 2022 \
Tao Yu, Christopher De Sa

### 3.4 Equivariant HGNNs

[An Efficient Lorentz Equivariant Graph Neural Network for Jet Tagging](https://arxiv.org/pdf/2201.08187.pdf), arxiv 2022 \
Shiqi Gonga, Qi Meng, Jue Zhang, Huilin Qu, Congqiao Li, Sitian Qian, Weitao, Du, Zhi-Ming Ma, Tie-Yan Liu

## 4. Applications

### 4.1 Hyperbolic Models for Recommender System

#### 4.1.1 HGNN Research

[HRCF: Enhancing Collaborative Filtering via Hyperbolic Geometric Regularization](https://arxiv.org/abs/2204.08176), WWW 2022 \
Menglin Yang, Min Zhou, Jiahong Liu, Defu Lian, Irwin King

[HAKG: Hierarchy-Aware Knowledge Gated Network for Recommendation](https://arxiv.org/abs/2204.04959), SIGIR 2022 \
Yuntao Du, Xinjun Zhu, Lu Chen, Baihua Zheng, and Yunjun Gao

[Geometric Inductive Matrix Completion: A Hyperbolic Approach with Unified Message Passing](https://dl.acm.org/doi/abs/10.1145/3488560.3498402), WSDM 2022 \
Chengkun Zhang , Hongxu Chen , Sixiao Zhang , Guandong Xu , Junbin Gao

[Modeling Scale-free Graphs with Hyperbolic Geometry for Knowledge-aware Recommendation](https://arxiv.org/abs/2108.06468), WSDM 2022 \
Yankai Chen, Menglin Yang, Yingxue Zhang, Mengchen Zhao, Ziqiao Meng, Jianye Hao, Irwin King

[HGCF: Hyperbolic Graph Convolution Networks for Collaborative Filtering](https://www.cs.toronto.edu/~mvolkovs/www2021_hgcf.pdf), WWW 2021 \
Jianing Sun,Zhaoyue Cheng,Saba Zuberi,Felipe Perez,Maksims Volkovs

[Hypersorec: Exploiting hyperbolic user and item representations with multiple aspects for social-aware recommendation](http://home.ustc.edu.cn/~wanghao3/papers/haowang_TOIS2021.pdf), TOIS 2021 \
Hao Wang, Defu Lian, Hanghang Tong, Qi Liu, Zhenya Huang and Enhong Chen

[Knowledge Based Hyperbolic Propagation](http://dl.acm.org/doi/abs/10.1145/3404835.3462980), SIGIR short paper 2021 \
Chang-You Tai, Chien-Kun Huang, Liang-Ying Huang, Lun-Wei Ku

[HSR: hyperbolic social recommender](https://arxiv.org/abs/2102.09389), Information Sciences 2022 \
Anchen Li, Bo Yang
 
[HCGR: Hyperbolic Contrastive Graph Representation Learning for Session-based Recommendation](https://arxiv.org/abs/2107.05366), arxiv 2021 \
Naicheng Guo, Xiaolei Liu, Shaoshuai Li, Qiongxu Ma, Yunan Zhao, Bing Han, Lin Zheng, Kaixin Gao, Xiaobo Guo

[Hyperbolic Hypergraphs for Sequential Recommendation](https://arxiv.org/abs/2108.08134), CIKM 2021 \
Yicong Li, Hongxu Chen, Xiangguo Sun, Zhenchao Sun, Lin Li, Lizhen Cui, Philip S. Yu, Guandong Xu

#### 4.1.2 Hyperbolic Non-GNN Research

[Learning Feature Interactions with Lorentzian Factorization Machine](https://arxiv.org/abs/1911.09821), AAAI 2020 \
Canran Xu, Ming Wu

[HyperML: A Boosting Metric Learning Approach in Hyperbolic Space for Recommender Systems](https://arxiv.org/abs/1809.01703), WSDM 2020 \
Lucas Vinh Tran, Yi Tay, Shuai Zhang, Gao Cong, Xiaoli Li

[Scalable Hyperbolic Recommender Systems](https://arxiv.org/abs/1902.08648), WSDM 2020 \
Benjamin Paul Chamberlain, Stephen R. Hardwick, David R. Wardrope, Fabon Dzogang, Fabio Daolio, Saúl Vargas

[A hyperbolic metric embedding approach for next-poi recommendation](https://dl.acm.org/doi/10.1145/3397271.3401049), SIGIR 2020 \
Shanshan Feng , Lucas Vinh Tran , Gao Cong , Lisi Chen , Jing Li , Fan Li

[Node2LV: Squared Lorentzian Representations for Node Proximity](https://ieeexplore.ieee.org/document/9458940)， ICDE 2021 \
Shanshan Feng, Lisi Chen, Kaiqi Zhao, Wei Wei, Fan Li, Shuo Shang

### 4.2 Hyperbolic Moldes for Knowledge Graph

#### 4.2.1 HGNN Research
[Knowledge Association with Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2010.02162), EMNLP 2020 \
Zequn Sun, Muhao Chen, Wei Hu, Chengming Wang, Jian Dai, Wei Zhang

[Knowledge Graph Representation via Hierarchical Hyperbolic Neural Graph Embedding](https://ieeexplore.ieee.org/document/9671651), IEEE Big Data \
Shen Wang, Xiaokai Wei, Cicero Nogueira Dos Santos, Zhiguo Wang, Ramesh Nallapati, Andrew Arnold, Philip S. Yu

[Mixed-Curvature Multi-relational Graph Neural Network for Knowledge Graph Completion](https://assets.amazon.science/0c/9d/51d98f1040b1bfa7dc52d1015750/mixed-curvature-multi-relational-graph-neural-network-for-knowledge-graph-completion.pdf), WWW 2021 \
Shen Wang , Xiaokai Wei , Cicero Nogueira Nogueira dos Santos , Zhiguo Wang , Ramesh Nallapati , Andrew Arnold , Bing Xiang , Philip S. Yu , Isabel F. Cruz

#### 4.2.2 Hyperbolic Non-GNN Research

[Low-Dimensional Hyperbolic Knowledge Graph Embeddings](https://arxiv.org/abs/2005.00545), ACL 2019 \
Ines Chami, Adva Wolf, Da-Cheng Juan, Frederic Sala, Sujith Ravi, Christopher Ré

[Multi-relational Poincaré Graph Embeddings](https://arxiv.org/abs/1905.09791), NeurIPS 2019 \
Ivana Balažević, Carl Allen, Timothy Hospedales

[Modeling Heterogeneous Hierarchies with Relation-specific Hyperbolic Cones](https://arxiv.org/abs/2110.14923)， NeurIPS 2021 \
Yushi Bai, Rex Ying, Hongyu Ren, Jure Leskovec

[Hyperbolic Temporal Knowledge Graph Embeddings with Relational and Time Curvatures](https://arxiv.org/abs/2106.04311), ACL 2021 \
Sebastien Montella, Lina Rojas-Barahona, Johannes Heinecke

[Self-supervised hyperboloid representations from logical queries over knowledge graphs](https://arxiv.org/abs/2012.13023), WWW 2021 \
Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy


[HyperKG: Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion](https://arxiv.org/abs/1908.04895), arxiv \
Prodromos Kolyvakis, Alexandros Kalousis, Dimitris Kiritsis

[Hyperbolic Hierarchy-Aware Knowledge Graph Embedding for Link Prediction](https://aclanthology.org/2021.findings-emnlp.251/). EMNLP findings 2021 \
Zhe Pan, Peng Wang

### 4.3 Hyperbolic models for Molecular

#### 4.3.1 HGNN Research

[Hyperbolic relational graph convolution networks plus: a simple but highly efficient QSAR-modeling method](https://academic.oup.com/bib/article-abstract/22/5/bbab112/6235968?redirectedFrom=fulltext), Briefings in Bioinformatics 2021 \
Zhenxing Wu, Dejun Jiang, Chang-Yu Hsieh, Guangyong Chen, Ben Liao, Dongsheng Cao, Tingjun Hou

[Semi-supervised  hierarchical  drug  embedding  inhyperbolic space](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00681), J. Chem. Inf. Model 2020 \
Ke Yu*, Shyam Visweswaran*, and Kayhan Batmanghelich

#### 4.3.2 Hyperbolic Non-GNN Research

[HiG2Vec: hierarchical representations of Gene Ontology and genes in the Poincaré ball](https://academic.oup.com/bioinformatics/article/37/18/2971/6184857?login=false), Bioinformatics, 2021 \
Jaesik Kim, Dokyoon Kim, Kyung-Ah Sohn

### 4.4 HGNN for Dynamic Graph

[Discrete-time Temporal Network Embedding via Implicit Hierarchical Learning in Hyperbolic Space](https://arxiv.org/abs/2107.03767),  KDD 2021 \
Menglin Yang, Min Zhou, Marcus Kalander, Zengfeng Huang, Irwin King

[Hyperbolic Variational Graph Neural Network for Modeling Dynamic Graphs](https://arxiv.org/abs/2104.02228), AAAI 2021 \
Li Sun, Zhongbao Zhang, Jiawei Zhang, Feiyang Wang, Hao Peng, Sen Su, Philip S. Yu

[Exploring the Scale-Free Nature of Stock Markets: Hyperbolic Graph Learning for Algorithmic Trading](https://dl.acm.org/doi/10.1145/3442381.3450095),  WWW 2021 \
Ramit Sawhney , Shivam Agarwal , Arnav Wadhwa , Rajiv Shah


---
Note: The following research works not limited to HGNNs but higly related to hyperbolic geometry.

---

## 5 Hyperbolic Embeddings
### 5.1 Hyperbolic Geometry for Heterogeneous Network Embedding
[Hyperbolic Heterogeneous Information Network Embedding](https://ojs.aaai.org/index.php/AAAI/article/view/4471),  AAAI 2020 \
Xiao Wang, Yiding Zhang, Chuan Shi

[Embedding Heterogeneous Information Network in Hyperbolic Spaces](https://dl.acm.org/doi/abs/10.1145/3468674?sid=SCITRUS), TKDD 2022 \
Yiding Zhang, Xiao Wang, Nian Liu, Chuan Shi


### 5.2 Hyperbolic Geometry for Directed Graph Embedding
[Hyperbolic Disk Embeddings for Directed Acyclic Graphs](https://arxiv.org/pdf/1902.04335.pdf)，ICML 2019 \
Ryota Suzuki, Ryusuke Takahama, Shun Onoda

[A hyperbolic Embedding Model for Directed Networks](https://arxiv.org/abs/1906.03597) \
Zongning Wu, Zengru Di, Ying Fan (this paper includes many errors)

### 5.3 Hyperbolic Geometry for Signed Graph Embedding
[Hyperbolic Node Embedding for Signed Networks](https://arxiv.org/abs/1910.13090), Neurcomputing 2021 \
Wenzhuo Song, Hongxu Chen, Xueyan Liu, Hongzhe Jiang, Shengsheng Wang

### 5.4 Hyperbolic Geometry for Attributed Graph Embedding
[HEAT: Hyperbolic Embedding of Attributed Networks](https://arxiv.org/abs/1903.03036), IDEAL 2020 \
David McDonald, Shan He

### 5.5 Hyperbolic Geometry for Word Embedding
[Poincare Glove: Hyperbolic Word Embeddings](https://arxiv.org/abs/1810.06546), ICLR 2019 \
Alexandru Tifrea and Gary Becigneul and Octavian-Eugen Gane

[Skip-gram word embeddings in hyperbolic space](https://arxiv.org/abs/1809.01498), ACL 2018 \
Matthias Leimeister, Benjamin J. Wilson

[Embedding text in hyperbolic spaces](https://arxiv.org/abs/1806.04313), ACL 2018 \
Bhuwan Dhingra, Christopher J. Shallue, Mohammad Norouzi, Andrew M. Dai, George E. Dahl

[Representation Tradeoffs for Hyperbolic Embeddings](https://arxiv.org/abs/1804.03329), ICML 2018 \
Christopher De Sa, Albert Gu, Christopher Ré, Frederic Sala

[Hyperbolic entailment cones for learning hierarchical embeddings](https://arxiv.org/abs/1804.01882), ICML 2018 \
Octavian-Eugen Ganea, Gary Bécigneul, Thomas Hofmann

[Low-rank approximations of hyperbolic embeddings](https://arxiv.org/abs/1903.07307) \
Pratik Jawanpuria, Mayank Meghwanshi, Bamdev Mishra

[Hyperbolic Multiplex Network Embedding with Maps of Random Walk](https://arxiv.org/abs/1912.08927) \
Peiyuan Sun

### 5.6 Hyperbolic Geometry for Multi-label Classification

[Hyperbolic interaction model for hierarchical multi-label classification](https://ojs.aaai.org/index.php/AAAI/article/view/6247), AAAI 2021 \
Boli Chen, Xin Huang, Lin Xiao, Zixin Cai, Liping Jing

[Hyperbolic Capsule Networks for Multi-Label Classification](https://aclanthology.org/2020.acl-main.283/), ACL 2020 \
Boli Chen, Xin Huang, Lin Xiao, Liping Jing

[Joint Learning of Hyperbolic Label Embeddings for Hierarchical Multi-label Classification](https://arxiv.org/abs/2101.04997), EACL 2021 \
Soumya Chatterjee, Ayush Maheshwari, Ganesh Ramakrishnan, Saketha Nath Jagaralpudi

[Hyperbolic Embeddings for Hierarchical Multi-label Classification](https://link.springer.com/chapter/10.1007/978-3-030-59491-6_7), 2020 \
Tomaž StepišnikEmail, Dragi Kocev

[A Fully Hyperbolic Neural Model for Hierarchical Multi-Class Classification](https://arxiv.org/abs/2010.02053), EMNLP findings \
Federico López, Michael Strube

## 6 Hyperbolic Baisc Operations

[Latent Variable Modelling with Hyperbolic Normalizing Flows](https://arxiv.org/abs/2002.06336), ICML 2020  \
Avishek Joey Bose, Ariella Smofsky, Renjie Liao, Prakash Panangaden, William L. Hamilton

## 7 Hyperbolic Geometry for CV

[Hyperbolic Image Segmentation](https://arxiv.org/abs/2203.05898), cvpr 2022 \
Mina GhadimiAtigh, Julian Schoep, Erman Acar, Nanne van Noord, Pascal Mettes


[Mix Dimension in Poincaré Geometry for 3D Skeleton-based Action Recognition](https://dl.acm.org/doi/abs/10.1145/3394171.3413910), ACM MM 2020 \
Wei Peng, Jingang Shi, Zhaoqiang Xia, Guoying Zhao

[Curvature Generation in Curved Spaces for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Curvature_Generation_in_Curved_Spaces_for_Few-Shot_Learning_ICCV_2021_paper.pdf), ICCV 2021 \
Zhi Gao, Yuwei Wu*, Yunde Jia, Mehrtash Harandi

[Unsupervised Discovery of the Long-Tail in Instance Segmentation Using Hierarchical Self-Supervision](https://arxiv.org/abs/2104.01257), CVPR 2021 \
Zhenzhen Weng, Mehmet Giray Ogut, Shai Limonchik, Serena Yeung

[Hyperbolic Image Embedding](https://arxiv.org/abs/1904.02239), CVPR 2020 \
Valentin Khrulkov, Leyla Mirvakhabova, Evgeniya Ustinova, Ivan Oseledets, Victor Lempitsky

[Meta Hyperbolic Networks for Zero-Shot Learning](https://www.sciencedirect.com/science/article/pii/S0925231222003344), Neurocomputing \
Yan Xu, Lifu Mu, ZhongJi, Xiyao Liu, JungongHan

## 8 Hyperbolic Geometry for NLP

[Medical Triage Chatbot Diagnosis Improvement via Multi-relational Hyperbolic Graph Neural Network](https://dl.acm.org/doi/abs/10.1145/3404835.3463095). SIGIR short paper 2021 \
Zheng Liu , Xiaohan Li , Zeyu You , Tao Yang , Wei Fan , Philip Yu



## 9 Hyperbolic Metric Learning

[Hyperbolic Busemann Learning with Ideal Prototypes](https://proceedings.neurips.cc/paper/2021/file/01259a0cb2431834302abe2df60a1327-Paper.pdf), NeurIPS 2021 \
Mina Ghadimi Atigh, Martin Keller-Ressel, Pascal Mettes


[Unsupervised Hyperbolic Metric Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_Unsupervised_Hyperbolic_Metric_Learning_CVPR_2021_paper.pdf), CVPR 2021 \
Jiexi Yan, Lei Luo, Cheng Deng, Heng Huang

## Tools

[GraphZoo: A Development Toolkit for Graph Neural Networks with Hyperbolic Geometries](https://people.cs.vt.edu/~reddy/papers/WWW22d.pdf) WWW 2022 \
Anoushka Vyas, Nurendra Choudhary, Mehrdad Khatir, Chandan K. Reddy

https://github.com/AnoushkaVyas/GraphZoo

### TBA

HYPMIX: Hyperbolic Interpolative Data Augmentation

ANTHEM: Attentive Hyperbolic Entity Model for Product Search, WSDM 2022

HoroPCA: Hyperbolic Dimensionality Reduction via Horospherical Projections, ICML 2021
http://proceedings.mlr.press/v139/chami21a/chami21a.pdf

Ines Chami* Albert Gu* Dat Nguyen* Christopher Re´

ANTHEM: Attentive Hyperbolic Entity Model for Product Search, WSDM 2022
https://dl.acm.org/doi/10.1145/3488560.3498456

Nurendra Choudhary , Nikhil Rao , Sumeet Katariya , Karthik Subbian , Chandan K. Reddy
