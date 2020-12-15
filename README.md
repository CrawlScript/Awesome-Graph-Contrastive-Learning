# Awesome-Graph-Contrastive-Learning
Collection of resources related with Graph Contrastive Learning.




## Contents

- [Papers](#papers)
  - [2019](#2019)
  - [2020](#2020)
- [Library](#library)


<a name="papers" />

## Papers

<a name="2019" />

### 2019

1. **Deep Graph Infomax** *Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, & R Devon Hjelm.* ICLR 2019. 
    + __Paper:__ [*OpenReview*](https://openreview.net/pdf?id=rklz9iAcKQ) | __Code:__ [*PyTorch*](https://github.com/PetarV-/DGI), [*tf_geometric*](https://github.com/CrawlScript/tf_geometric/blob/master/demo/demo_dgi.py)
    + __Method(*DGI*):__ Local-Global Mutual Information Maximization
    + __Experiment:__ 
        + __Task:__ *Transductive Node Classification* | __Datasets:__ *Cora, Citeseer, Pubmed.* | __Baselines:__ *Raw features, Label Propagation, DeepWalk, DeepWalk + features, GCN, Planetoid.*
        + __Task:__ *Inductive Node Classification* | __Datasets:__ *Reddit, PPI.* | __Baselines:__ *Raw features; DeepWalk; DeepWalk + features; GraphSAGE-GCN; GraphSAGE-mean; GraphSAGE-LSTM; GraphSAGE-pool; FastGCN; Avg. pooling.*



<a name="2020" />

### 2020

1. **InfoGraph: Unsupervised and Semi-supervised Graph-Level Representation Learning via Mutual Information Maximization** *Fan-Yun Sun, Jordan Hoffmann, Vikas Verma, Jian Tang.* ICLR 2020.
    + __Paper:__ [*OpenReview*](https://openreview.net/pdf/af171fb8c60fa180c4dcf349ccc51ff006211216.pdf) | __Code:__ [*PyTorch*](https://github.com/fanyun-sun/InfoGraph) 
    + __Method:__ Local-Global Mutual Information Maximization (Batch-wise Negative Sampling, Multi-scale), GIN
    + __Experiment:__ 
        + __Task:__ *Graph Classification* | __Datasets:__ *MUTAG, PTC-MR, RDT-B, RDT-M5K, IMDB-B, IMDB-M.* | __Baselines:__ *RandomWalk, Shortest Path Kernel, Graphlet Kernel, Weisfeiler-Lehman Sub-tree Kernel, Deep Graph Kernels, Multi-Scale Laplacian Kernel, node2vec, sub2vec, graph2vec.*
        + __Task:__ *Semi-supervised Molecular Property Prediction* | __Datasets:__ *QM9.* | __Baselines:__ *Mean-Teachers.*


1. **Contrastive Multi-View Representation Learning on Graphs** *Kaveh Hassani, Amir Hosein Khas Ahmadi.* ICML 2020.
    + __Paper:__ [*MLR*](http://proceedings.mlr.press/v119/hassani20a/hassani20a.pdf) | __Code:__ [*PyTorch*](https://github.com/kavehhassani/mvgrl)
    + __Method(*MVGRL*):__ Multi-View Local-Global Mutual Information Maximization
    + __Experiment:__ 
        + __Task:__ *Node Classification* | __Datasets:__ *Cora, Citeseer, Pubmed.* | __Baselines:__ *MLP, Iterative Classification Algorithm, Label Propagation, ManiReg, SemiEmb, Planetoid, Chebyshev, GCN, MoNet, JKNet, GAT, Linear, DeepWalk, GAE, VERSE, DGI.*
        + __Task:__ *Node Clustering* | __Datasets:__ *Cora, Citeseer, Pubmed.* | __Baselines:__ *VGAE, MGAE, ARGA, ARVGA, GALA.*
        + __Task:__ *Graph Classification* | __Datasets:__ *MUTAG, PTC-MR, IMDB-BIN, IMDB-MULTI, REDDIT-BIN.* | __Baselines:__ *Shortest Path Kernel, Graphlet kernel, Weisfeiler-Lehman Sub-tree Kernel, Deep Graph Kernels, Multi-scale Laplacian Kernel, GraphSAGE, GIN-0, GIN-ε, GAT, RandomWalk, node2vec, sub2vec, graph2vec, InfoGraph.*



<a name="library" />

## Library



