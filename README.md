# Awesome Self-Interpretable Neural Network

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

This repository is a curated collection of **Self-Interpretable Neural Network** (SINN) literature, offering a comprehensive and systematic summary of recent advancements in machine learning models designed with inherent interpretability. The focus is on papers related to SINNs, including **foundational theories**, **model designs**, and **interpretability evaluations or debates**. The curated works are sourced from leading AI conferences and journals, such as NeurIPS, ICML, ICLR, AAAI, CVPR, ACL, KDD, WWW, IJCAI, TAPMI, JMLR, TKDE, TOIS, and Nature-related journals, along with influential contributions from the broader research community.

We value your feedback! If you have any questions or suggestions, don’t hesitate to reach out to us. If you find this repository helpful, please consider citing our paper ([content](#citations); [reference](#citations)).

## Taxonomy of our paper

![Taxonomy](./Taxonomy.jpg)

## Self-Interpretation Methods
### Attribution-based 

| **Paper**                                                                                                                | **Year** | **Venue**          |
|--------------------------------------------------------------------------------------------------------------------------|:----------:|:---------------------:|
| [Rationalizing Neural Predictions](https://doi.org/10.18653/v1/d16-1011) | 2016 | EMNLP |
| [From softmax to sparsemax: A sparse model of attention and multi-label classification](http://proceedings.mlr.press/v48/martins16.html) | 2016 | ICML |
| [Neural interaction transparency (nit): Disentangling learned interactions for improved interpretability](https://proceedings.neurips.cc/paper/2018/hash/74378afe5e8b20910cf1f939e57f0480-Abstract.html) | 2018 | NeurIPS |
| [INVASE: Instance-wise variable selection using neural networks](https://openreview.net/forum?id=BJg_roAcK7) | 2018 | ICLR |
| [Learning to explain: An information-theoretic perspective on model interpretation](http://proceedings.mlr.press/v80/chen18j.html) | 2018 | ICML |
| [Approximating CNNs with Bag-of-local-Features models works surprisingly well on ImageNet](https://openreview.net/forum?id=SkfMWhAqYQ) | 2018 | ICLR |
| [Towards robust interpretability with self-explaining neural networks](https://proceedings.neurips.cc/paper/2018/hash/3e9f0fc9b2f89e043bc6233994dfcf76-Abstract.html) | 2018 | NeurIPS |
| [Beyond Polarity: Interpretable Financial Sentiment Analysis with Hierarchical Query-driven Attention](https://doi.org/10.24963/ijcai.2018/590) | 2018 | IJCAI |
| [Interpretable multi-task learning for product quality prediction with attention mechanism](https://doi.org/10.1109/ICDE.2019.00207) | 2019 | ICDE |
| [Adaptively Sparse Transformers](https://doi.org/10.18653/v1/D19-1223) | 2019 | EMNLP |
| [Exploiting kernel sparsity and entropy for interpretable CNN compression](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_Exploiting_Kernel_Sparsity_and_Entropy_for_Interpretable_CNN_Compression_CVPR_2019_paper.html) | 2019 | CVPR |
| [Learning representations for neural network-based classification using the information bottleneck principle](https://doi.org/10.1109/TPAMI.2019.2909031) | 2019 | TPAMI |
| [Interpretable predictive modeling for climate variables with weighted lasso](https://doi.org/10.1609/aaai.v33i01.33011385) | 2019 | AAAI |
| [Attention is not not Explanation](https://doi.org/10.18653/v1/n19-1357) | 2019 | EMNLP |
| [Is Attention Interpretable?](https://doi.org/10.18653/v1/p19-1282) | 2019 | ACL |
| [Concrete autoencoders: Differentiable feature selection and reconstruction](http://proceedings.mlr.press/v97/balin19a.html) | 2019 | ICML |
| [Deepcoda: personalized interpretability for compositional health data](http://proceedings.mlr.press/v119/quinn20a.html) | 2020 | ICML |
| [Graph Information Bottleneck for Subgraph Recognition](https://arxiv.org/abs/2010.05563) | 2020 | ICLR |
| [Sparse shrunk additive models](http://proceedings.mlr.press/v119/liu20b.html) | 2020 | ICML |
| [MRI reconstruction with interpretable pixel-wise operations using reinforcement learning](https://doi.org/10.1609/aaai.v34i01.5423) | 2020 | AAAI |
| [Attention is Not Only a Weight: Analyzing Transformers with Vector Norms](https://arxiv.org/abs/2004.10102) | 2020 | EMNLP |
| [Modeling users' behavior sequences with hierarchical explainable network for cross-domain fraud detection](https://doi.org/10.1145/3366423.3380172) | 2020 | WWW |
| [Feature selection using stochastic gates](http://proceedings.mlr.press/v119/yamada20a.html) | 2020 | ICML |
| [On Identifiability in Transformers](https://openreview.net/forum?id=BJg1f6EFDB) | 2020 | ICLR |
| [Consistent feature selection for analytic deep neural networks](https://proceedings.neurips.cc/paper/2020/hash/1959eb9d5a0f7ebc58ebde81d5df400d-Abstract.html) | 2020 | NeurIPS |
| [Towards Transparent and Explainable Attention Models](https://doi.org/10.18653/v1/2020.acl-main.387) | 2020 | ACL |
| [Learning to Deceive with Attention-Based Explanations](https://doi.org/10.18653/v1/2020.acl-main.432) | 2020 | ACL |
| [Timeshap: Explaining recurrent models through sequence perturbations](https://doi.org/10.1145/3447548.3467166) | 2021 | SIGKDD |
| [GAMI-Net: An explainable neural network based on generalized additive models with structured interactions](https://doi.org/10.1016/j.patcog.2021.108192) | 2021 | Pattern Recognition |
| [Shapley Explanation Networks](https://openreview.net/forum?id=vsU0efpivw) | 2021 | ICLR |
| [Market-oriented job skill valuation with cooperative composition neural network](https://www.nature.com/articles/s41467-021-22215-y) | 2021 | Nature Communications |
| [Neural additive models: Interpretable machine learning with neural nets](https://proceedings.neurips.cc/paper/2021/hash/251bd0442dfcc53b5a761e050f8022b8-Abstract.html) | 2021 | NeurIPS |
| [Is Sparse Attention more Interpretable?](https://doi.org/10.18653/v1/2021.acl-short.17) | 2021 | ACL |
| [Edge: Explaining deep reinforcement learning policies](https://proceedings.neurips.cc/paper/2021/hash/65c89f5a9501a04c073b354f03791b1f-Abstract.html) | 2021 | NeurIPS |
| [Why attentions may not be interpretable?](https://doi.org/10.1145/3447548.3467307) | 2021 | SIGKDD |
| [Attention-based interpretability with concept transformers](https://openreview.net/forum?id=kAa9eDS0RdO) | 2021 | ICLR |
| [Effective Attention Sheds Light On Interpretability](https://doi.org/10.18653/v1/2021.findings-acl.361) | 2021 | ACL |
| [Self-Interpretable Model with Transformation Equivariant Interpretation](https://proceedings.neurips.cc/paper/2021/hash/1387a00f03b4b423e63127b08c261bdc-Abstract.html) | 2021 | NeurIPS |
| [Towards rigorous interpretations: a formalisation of feature attribution](http://proceedings.mlr.press/v139/afchar21a.html) | 2021 | ICML |
| [Discerning decision-making process of deep neural networks with hierarchical voting transformation](https://proceedings.neurips.cc/paper/2021/hash/8f1fa0193ca2b5d2fa0695827d8270e9-Abstract.html) | 2021 | NeurIPS |
| [Recognizing predictive substructures with subgraph information bottleneck](https://arxiv.org/abs/2103.11155) | 2021 | TPAMI |
| [Tabnet: Attentive interpretable tabular learning](https://doi.org/10.1609/aaai.v35i8.16826) | 2021 | AAAI |
| [Lassonet: A neural network with feature sparsity](https://jmlr.org/papers/v22/20-848.html) | 2021 | JMLR |
| [Convolutional dynamic alignment networks for interpretable classifications](https://openaccess.thecvf.com/content/CVPR2021/html/Bohle_Convolutional_Dynamic_Alignment_Networks_for_Interpretable_Classifications_CVPR_2021_paper.html) | 2021 | CVPR |
| [Have We Learned to Explain?: How Interpretability Methods Can Learn to Encode Predictions in their Interpretations](http://proceedings.mlr.press/v130/jethani21a.html) | 2021 | AISTATS |
| [Evidence-aware hierarchical interactive attention networks for explainable claim verification](https://doi.org/10.24963/ijcai.2020/193) | 2021 | IJCAI |
| [Towards improved and interpretable deep metric learning via attentive grouping](https://arxiv.org/abs/2011.08877) | 2022 | TPAMI |
| [Supervising model attention with human explanations for robust natural language inference](https://doi.org/10.1609/aaai.v36i10.21386) | 2022 | AAAI |
| [Deep Variational Information Bottleneck](https://doi.org/10.3390/s23198093) | 2022 | ICLR |
| [Locally sparse neural networks for tabular biomedical data](https://proceedings.mlr.press/v162/yang22i.html) | 2022 | ICML |
| [Self-explaining deep models with logic rule reasoning](http://papers.nips.cc/paper_files/paper/2022/hash/1548d98b62d3a4382a31ba77d89186cd-Abstract-Conference.html) | 2022 | NeurIPS |
| [Is attention explanation? an introduction to the debate](https://aclanthology.org/2022.jeptalnrecital-taln.45) | 2022 | ACL |
| [Puregam: Learning an inherently pure additive model](https://doi.org/10.1145/3534678.3539256) | 2022 | KDD |
| [Query and attention augmentation for knowledge-based explainable reasoning](https://doi.org/10.1109/CVPR52688.2022.01513) | 2022 | CVPR |
| [A diversified attention model for interpretable multiple clusterings](https://doi.org/10.1109/TKDE.2022.3218693) | 2022 | TKDE |
| [Interpretable and generalizable graph learning via stochastic attention mechanism](https://proceedings.mlr.press/v162/miao22a.html) | 2022 | ICML |
| [Neural basis models for interpretability](http://papers.nips.cc/paper_files/paper/2022/hash/37da88965c016dca016514df0e420c72-Abstract-Conference.html) | 2022 | NeurIPS |
| [B-cos networks: Alignment is all we need for interpretability](https://doi.org/10.1109/CVPR52688.2022.01008) | 2022 | CVPR |
| [Sparse interaction additive networks via feature interaction detection and sparse selection](http://papers.nips.cc/paper_files/paper/2022/hash/5a3674849d6d6d23ac088b9a2552f323-Abstract-Conference.html) | 2022 | NeurIPS |
| [Scalable interpretability via polynomials](http://papers.nips.cc/paper_files/paper/2022/hash/ee81a23d6b83ac15fbeb5b7a30934e0b-Abstract-Conference.html) | 2022 | NeurIPS |
| [Seat: stable and explainable attention](https://doi.org/10.1609/aaai.v37i11.26517) | 2023 | AAAI |
| [Interpretable bilinear attention network with domain adaptation improves drug--target prediction](https://doi.org/10.1038/s42256-022-00605-1) | 2023 | Nature Machine Intelligence |
| [Extractive explanations for interpretable text ranking](https://doi.org/10.1145/3576924) | 2023 | TOIS |
| [Improving interpretability via explicit word interaction graph layer](https://doi.org/10.1609/aaai.v37i11.26586) | 2023 | AAAI |
| [Interpretable Geometric Deep Learning via Learnable Randomness Injection](https://openreview.net/forum?id=6u7mf9s2A9) | 2023 | ICLR |
| [N²AQ: Neural Attention Additive Model for Interpretable Multi-Agent Q-Learning](https://proceedings.mlr.press/v202/liu23be.html) | 2023 | ICML |
| [Towards Faithful Neural Network Intrinsic Interpretation with Shapley Additive Self-Attribution](https://doi.org/10.48550/arXiv.2309.15559) | 2023 | ArXiv |
| [The contextual lasso: Sparse linear models via deep neural networks](http://papers.nips.cc/paper_files/paper/2023/hash/3f226824426a4d6ae3d3efad8883fc53-Abstract-Conference.html) | 2023 | NeurIPS |
| [Learning Faithful Attention for Interpretable Classification of Crisis-Related Microblogs under Constrained Human Budget](https://doi.org/10.1145/3543507.3583861) | 2023 | WWW |
| [Improving Neural Additive Models with Bayesian Principles](https://openreview.net/forum?id=0pSTzCnEmi) | 2023 | ICML |
| [Sparse Neural Additive Model: Interpretable Deep Learning with Feature Selection via Group Sparsity](https://doi.org/10.1007/978-3-031-43418-1_21) | 2023 | ICLR |
| [CAT: Interpretable Concept-based Taylor Additive Models](https://doi.org/10.1145/3637528.3672020) | 2024 | KDD |
| [B-cos Alignment for Inherently Interpretable CNNs and Vision Transformers](https://doi.org/10.1109/TPAMI.2024.3355155) | 2024 | TPAMI |
| [ProtoGate: Prototype-based Neural Networks with Global-to-local Feature Selection for Tabular Biomedical Data](https://openreview.net/forum?id=07fSWltF6M) | 2024 | ICML |
| [InterpreTabNet: Distilling Predictive Signals from Tabular Data by Salient Feature Interpretation](https://openreview.net/forum?id=or8BQ4ohGb) | 2024 | ICML |
| [Interpretable prototype-based graph information bottleneck](http://papers.nips.cc/paper_files/paper/2023/hash/f224f056694bcfe465c5d84579785761-Abstract-Conference.html) | 2024 | NeurIPS |
| [Exgc: Bridging efficiency and explainability in graph condensation](https://doi.org/10.1145/3589334.3645551) | 2024 | WWW |
| [Towards self-interpretable graph-level anomaly detection](http://papers.nips.cc/paper_files/paper/2023/hash/1c6f06863df46de009a7a41b41c95cad-Abstract-Conference.html) | 2024 | NeurIPS |
| [Tempme: Towards the explainability of temporal graph neural networks via motif discovery](http://papers.nips.cc/paper_files/paper/2023/hash/5c5bc3553815adb4d1a8a5b8701e41a9-Abstract-Conference.html) | 2024 | NeurIPS |
| [NODE-GAM: Neural Generalized Additive Model for Interpretable Deep Learning](https://openreview.net/forum?id=g8NJR6fCCl8) | 2024 | ICLR |
| [GRAND-SLAMIN'Interpretable Additive Modeling with Structural Constraints](http://papers.nips.cc/paper_files/paper/2023/hash/c057cb81b8d3c67093427bf1c16a4e9f-Abstract-Conference.html) | 2024 | NeurIPS |
| [Propagation Structure-Aware Graph Transformer for Robust and Interpretable Fake News Detection](https://doi.org/10.1145/3637528.3672024) | 2024 | KDD |
| [NAISR: A 3D Neural Additive Model for Interpretable Shape Representation](https://openreview.net/forum?id=wg8NPfeMF9) | 2024 | ICLR |
| [Comprehensive Attribution: Inherently Explainable Vision Model with Feature Detector](https://doi.org/10.1007/978-3-031-73004-7_12) | 2025 | ECCV |


### Function-based 

| **Paper**                                                                                                 | **Year** | **Venue** |
|-----------------------------------------------------------------------------------------------------------|:----------:|:---------------------:|
| [Learning equations for extrapolation and control](http://proceedings.mlr.press/v80/sahoo18a.html) | 2018 | ICML |
| [Integration of neural network-based symbolic regression in deep learning for scientific discovery](https://doi.org/10.1109/TNNLS.2020.3017010) | 2020 | TNNLS |
| [Discerning decision-making process of deep neural networks with hierarchical voting transformation](https://proceedings.neurips.cc/paper/2021/hash/8f1fa0193ca2b5d2fa0695827d8270e9-Abstract.html) | 2021 | NeurIPS |
| [Neural symbolic regression that scales](http://proceedings.mlr.press/v139/biggio21a.html) | 2021 | ICML |
| [Symbolicgpt: A generative transformer model for symbolic regression](https://arxiv.org/abs/2106.14131) | 2021 | ArXiv |
| [End-to-end symbolic regression with transformers](http://papers.nips.cc/paper_files/paper/2022/hash/42eb37cdbefd7abae0835f4b67548c39-Abstract-Conference.html) | 2022 | NeurIPS |
| [A unified framework for deep symbolic regression](http://papers.nips.cc/paper_files/paper/2022/hash/dbca58f35bddc6e4003b2dd80e42f838-Abstract-Conference.html) | 2022 | NeurIPS |
| [Controllable neural symbolic regression](https://proceedings.mlr.press/v202/bendinelli23a.html) | 2023 | ICML |
| [Deep Generative Symbolic Regression](https://openreview.net/forum?id=o7koEEMA1bR) | 2023 | ICLR |
| [Kan: Kolmogorov-arnold networks](https://doi.org/10.48550/arXiv.2404.19756) | 2024 | ArXiv |
| [GINN-LP: A Growing Interpretable Neural Network for Discovering Multivariate Laurent Polynomial Equations](https://doi.org/10.1609/aaai.v38i13.29396) | 2024 | AAAI |


### Concept-based

| **Paper**                                                                                                          | **Year** | **Venue**          |
|--------------------------------------------------------------------------------------------------------------------|:----------:|:---------------------:|
| [Concept bottleneck models](https://doi.org/10.48550/arXiv.2411.16512) | 2020 | ICML |
| [Concept whitening for interpretable image recognition](https://doi.org/10.1038/s42256-020-00265-z) | 2020 | Nature Machine Intelligence |
| [Attention-based interpretability with concept transformers](https://openreview.net/forum?id=kAa9eDS0RdO) | 2021 | ICLR |
| [Explainable neural networks that simulate reasoning](https://doi.org/10.1038/s43588-021-00132-w) | 2021 | Nature Computational Science |
| [Self-Interpretable Model with Transformation Equivariant Interpretation](https://proceedings.neurips.cc/paper/2021/hash/1387a00f03b4b423e63127b08c261bdc-Abstract.html) | 2021 | NeurIPS |
| [Post-hoc Concept Bottleneck Models](https://doi.org/10.48550/arXiv.2205.15480) | 2022 | ICLR |
| [Concept embedding models: Beyond the accuracy-explainability trade-off](http://papers.nips.cc/paper_files/paper/2022/hash/867c06823281e506e8059f5c13a57f75-Abstract-Conference.html) | 2022 | NeurIPS |
| [Addressing leakage in concept bottleneck models](http://papers.nips.cc/paper_files/paper/2022/hash/944ecf65a46feb578a43abfd5cddd960-Abstract-Conference.html) | 2022 | NeurIPS |
| [Probabilistic Concept Bottleneck Models](https://proceedings.mlr.press/v202/kim23g.html) | 2023 | ICML |
| [Learning to Intervene on Concept Bottlenecks](https://doi.org/10.48550/arXiv.2308.13453) | 2023 | ICML |
| [Interactive concept bottleneck models](https://doi.org/10.1609/aaai.v37i5.25736) | 2023 | AAAI |
| [Label-free Concept Bottleneck Models](https://openreview.net/forum?id=FlCg47MNvBA) | 2023 | ICLR |
| [Language in a bottle: Language model guided concept bottlenecks for interpretable image classification](https://doi.org/10.1109/CVPR52729.2023.01839) | 2023 | CVPR |
| [Towards Trustable Skin Cancer Diagnosis via Rewriting Model's Decision](https://doi.org/10.1109/CVPR52729.2023.01113) | 2023 | CVPR |
| [Pantypes: Diverse Representatives for Self-Explainable Models](https://doi.org/10.1609/aaai.v38i12.29223) | 2024 | AAAI |
| [VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance](https://doi.org/10.48550/arXiv.2408.01432) | 2024 | NeurIPS |
| [Energy-based concept bottleneck models: unifying prediction, concept intervention, and conditional interpretations](https://doi.org/10.48550/arXiv.2401.14142) | 2024 | ArXiv |
| [Mica: Towards explainable skin lesion diagnosis via multi-level image-concept alignment](https://doi.org/10.1609/aaai.v38i2.27842) | 2024 | AAAI |
| [Relational Concept Bottleneck Models](https://lirias.kuleuven.be/retrieve/789506) | 2024 | NeurIPS |
| [Stochastic Concept Bottleneck Models](https://doi.org/10.48550/arXiv.2406.19272) | 2024 | NeurIPS |
| [Learning to receive help: Intervention-aware concept embedding models](http://papers.nips.cc/paper_files/paper/2023/hash/770cabd044c4eacb6dc5924d9a686dce-Abstract-Conference.html) | 2024 | NeurIPS |
| [Incremental residual concept bottleneck models](https://doi.org/10.1109/CVPR52733.2024.01049) | 2024 | CVPR |
| [Understanding Inter-Concept Relationships in Concept-Based Models](https://openreview.net/forum?id=JA6ThxAmth) | 2024 | ICML |
| [Coarse-to-fine concept bottleneck models](https://hal.science/hal-04709806/) | 2024 | NeurIPS |


### Prototype-based

| **Paper**                                                                                              | **Year** | **Venue** |
|--------------------------------------------------------------------------------------------------------|:----------:|:---------------------:|
| [This looks like that: deep learning for interpretable image recognition](https://proceedings.neurips.cc/paper/2019/hash/adf7ee2dcf142b0e11888e72b43fcb75-Abstract.html) | 2019 | NeurIPS |
| [Interpretable and steerable sequence learning via prototypes](https://doi.org/10.1145/3292500.3330908) | 2019 | SIGKDD |
| [Neural prototype trees for interpretable fine-grained image recognition](https://openaccess.thecvf.com/content/CVPR2021/html/Nauta_Neural_Prototype_Trees_for_Interpretable_Fine-Grained_Image_Recognition_CVPR_2021_paper.html) | 2021 | CVPR |
| [Interpretable image recognition by constructing transparent embedding space](https://doi.org/10.1109/ICCV48922.2021.00093) | 2021 | ICCV |
| [Protopshare: Prototypical parts sharing for similarity discovery in interpretable image classification](https://doi.org/10.1145/3447548.3467245) | 2021 | SIGKDD |
| [XProtoNet: diagnosis in chest radiography with global and local explanations](https://openaccess.thecvf.com/content/CVPR2021/html/Kim_XProtoNet_Diagnosis_in_Chest_Radiography_With_Global_and_Local_Explanations_CVPR_2021_paper.html) | 2021 | CVPR |
| [Proto2Proto: Can you recognize the car, the way I do?](https://doi.org/10.1109/CVPR52688.2022.00999) | 2022 | CVPR |
| [Interpretable image classification with differentiable prototypes assignment](https://doi.org/10.1007/978-3-031-19775-8_21) | 2022 | ECCV |
| [Protgnn: Towards self-explaining graph neural networks](https://doi.org/10.1609/aaai.v36i8.20898) | 2022 | AAAI |
| [Protovae: A trustworthy self-explainable prototypical variational model](http://papers.nips.cc/paper_files/paper/2022/hash/722f3f9298a961d2639eadd3f14a2816-Abstract-Conference.html) | 2022 | NeurIPS |
| [ProtoryNet-Interpretable Text Classification Via Prototype Trajectories](https://www.jmlr.org/papers/v24/21-0899.html) | 2023 | JMLR |
| [PIP-Net: Patch-Based Intuitive Prototypes for Interpretable Image Classification](https://doi.org/10.1109/CVPR52729.2023.00269) | 2023 | CVPR |
| [Towards interpretable deep reinforcement learning with human-friendly prototypes](https://openreview.net/forum?id=hWwY_Jq0xsN) | 2023 | ICLR |
| [Learning Support and Trivial Prototypes for Interpretable Image Classification](https://doi.org/10.1109/ICCV51070.2023.00197) | 2023 | ICCV |
| [Concept-level debugging of part-prototype networks](https://openreview.net/forum?id=oiwXWPDTyNk) | 2023 | ICLR |
| [Protoseg: Interpretable semantic segmentation with prototypical parts](https://doi.org/10.1109/WACV56688.2023.00153) | 2023 | WACV |
| [Interpretable prototype-based graph information bottleneck](http://papers.nips.cc/paper_files/paper/2023/hash/f224f056694bcfe465c5d84579785761-Abstract-Conference.html) | 2024 | NeurIPS |
| [Pantypes: Diverse Representatives for Self-Explainable Models](https://doi.org/10.1609/aaai.v38i12.29223) | 2024 | AAAI |
| [This looks like those: Illuminating prototypical concepts using multiple visualizations](http://papers.nips.cc/paper_files/paper/2023/hash/7b76eea0c3683e440c3d362620f578cd-Abstract-Conference.html) | 2024 | NeurIPS |
| [Market-aware Long-term Job Skill Recommendation with Explainable Deep Reinforcement Learning](https://dl.acm.org/doi/abs/10.1145/3704998) | 2024 | TOIS |


### Rule-based

| **Paper**                                                                                                     | **Year** | **Venue**      |
|---------------------------------------------------------------------------------------------------------------|:----------:|:---------------------:|
| [Logic Tensor Networks for Semantic Image Interpretation](https://doi.org/10.24963/ijcai.2017/221) | 2017 | IJCAI |
| [Deep neural decision trees](http://arxiv.org/abs/1806.06988) | 2018 | ArXiv |
| [Deep neural networks constrained by decision rules](https://doi.org/10.1609/aaai.v33i01.33012496) | 2019 | AAAI |
| [NBDT: Neural-Backed Decision Tree](https://arxiv.org/abs/2004.00221) | 2020 | ICLR |
| [Transparent classification with multilayer logical perceptrons and random binarization](https://doi.org/10.1609/aaai.v34i04.6102) | 2020 | AAAI |
| [Human-driven FOL explanations of deep learning](https://doi.org/10.24963/ijcai.2020/309) | 2020 | IJCAI |
| [A constraint-based approach to learning and explanation](https://doi.org/10.1609/aaai.v34i04.5774) | 2020 | AAAI |
| [Neural prototype trees for interpretable fine-grained image recognition](https://openaccess.thecvf.com/content/CVPR2021/html/Nauta_Neural_Prototype_Trees_for_Interpretable_Fine-Grained_Image_Recognition_CVPR_2021_paper.html) | 2021 | CVPR |
| [Learning accurate and interpretable decision rule sets from neural networks](https://doi.org/10.1609/aaai.v35i5.16555) | 2021 | AAAI |
| [Scalable rule-based representation learning for interpretable classification](https://proceedings.neurips.cc/paper/2021/hash/ffbd6cbb019a1413183c8d08f2929307-Abstract.html) | 2021 | NeurIPS |
| [Weakly Supervised Explainable Phrasal Reasoning with Neural Fuzzy Logic](https://arxiv.org/abs/2109.08927) | 2021 | ICLR |
| [Discerning decision-making process of deep neural networks with hierarchical voting transformation](https://proceedings.neurips.cc/paper/2021/hash/8f1fa0193ca2b5d2fa0695827d8270e9-Abstract.html) | 2021 | NeurIPS |
| [Analyzing differentiable fuzzy logic operators](https://doi.org/10.1016/j.artint.2021.103602) | 2022 | Artificial Intelligence |
| [Vit-net: Interpretable vision transformers with neural tree decoder](https://proceedings.mlr.press/v162/kim22g.html) | 2022 | ICML |
| [Self-explaining deep models with logic rule reasoning](http://papers.nips.cc/paper_files/paper/2022/hash/1548d98b62d3a4382a31ba77d89186cd-Abstract-Conference.html) | 2022 | NeurIPS |
| [Entropy-based logic explanations of neural networks](https://doi.org/10.1609/aaai.v36i6.20551) | 2022 | AAAI |
| [Extending Logic Explained Networks to Text Classification](https://doi.org/10.18653/v1/2022.emnlp-main.604) | 2022 | EMNLP |
| [Explainable Neural Rule Learning](https://doi.org/10.1145/3485447.3512023) | 2022 | WWW |
| [Deep differentiable logic gate networks](http://papers.nips.cc/paper_files/paper/2022/hash/0d3496dd0cec77a999c98d35003203ca-Abstract-Conference.html) | 2022 | NeurIPS |
| [Interpretable neural-symbolic concept reasoning](https://proceedings.mlr.press/v202/barbiero23a.html) | 2023 | ICML |
| [Learning to Binarize Continuous Features for Neuro-Rule Networks.](https://doi.org/10.24963/ijcai.2023/510) | 2023 | IJCAI |
| [Learning interpretable rules for scalable data representation and classification](https://doi.org/10.48550/arXiv.2310.14336) | 2023 | TPAMI |
| [FINRule: Feature Interactive Neural Rule Learning](https://doi.org/10.1145/3583780.3614884) | 2023 | CIKM |
| [Logic explained networks](https://doi.org/10.1016/j.artint.2022.103822) | 2023 | Artificial Intelligence |
| [Convolutional Differentiable Logic Gate Networks](https://doi.org/10.48550/arXiv.2411.04732) | 2024 | NeurIPS |
| [HyperLogic: Enhancing Diversity and Accuracy in Rule Learning with HyperNets](https://openreview.net/forum?id=gJbZyKGfd6) | 2024 | NeurIPS |
| [Interpretable prototype-based graph information bottleneck](http://papers.nips.cc/paper_files/paper/2023/hash/f224f056694bcfe465c5d84579785761-Abstract-Conference.html) | 2024 | NeurIPS |


## Applications
### Image Data

| **Paper** | **Year** | **Venue** |
|-------------|:----------:|:---------------------:|
| [Neural-symbolic VQA: Disentangling reasoning from vision and language understanding](https://proceedings.neurips.cc/paper/2018/hash/5e388103a391daabe3de1d76a6739ccd-Abstract.html) | 2018 | NeurIPS |
| [Pathologist-level interpretable whole-slide cancer diagnosis with deep learning](https://doi.org/10.1038/s42256-019-0052-1) | 2019 | Nature Machine Intelligence |
| [Training interpretable convolutional neural networks by differentiating class-specific filters](https://doi.org/10.1007/978-3-030-58536-5_37) | 2020 | ECCV |
| [Concept bottleneck models](https://doi.org/10.48550/arXiv.2411.16512) | 2020 | ICML |
| [Interpretable CNNs for object classification](https://doi.org/10.1109/TPAMI.2020.2982882) | 2020 | TPAMI |
| [Explainable object-induced action decision for autonomous vehicles](https://openaccess.thecvf.com/content_CVPR_2020/html/Xu_Explainable_Object-Induced_Action_Decision_for_Autonomous_Vehicles_CVPR_2020_paper.html) | 2020 | CVPR |
| [Neural prototype trees for interpretable fine-grained image recognition](https://openaccess.thecvf.com/content/CVPR2021/html/Nauta_Neural_Prototype_Trees_for_Interpretable_Fine-Grained_Image_Recognition_CVPR_2021_paper.html) | 2021 | CVPR |
| [Interpretable compositional convolutional neural networks](https://doi.org/10.24963/ijcai.2021/409) | 2021 | IJCAI |
| [Label-free Concept Bottleneck Models](https://openreview.net/forum?id=FlCg47MNvBA) | 2023 | ICLR |
| [Language in a bottle: Language model guided concept bottlenecks for interpretable image classification](https://doi.org/10.1109/CVPR52729.2023.01839) | 2023 | CVPR |
| [PIP-Net: Patch-Based Intuitive Prototypes for Interpretable Image Classification](https://doi.org/10.1109/CVPR52729.2023.00269) | 2023 | CVPR |
| [Concept embedding models: Beyond the accuracy-explainability trade-off](http://papers.nips.cc/paper_files/paper/2022/hash/867c06823281e506e8059f5c13a57f75-Abstract-Conference.html) | 2023 | NeurIPS |
| [Learning Support and Trivial Prototypes for Interpretable Image Classification](https://doi.org/10.1109/ICCV51070.2023.00197) | 2023 | ICCV |
| [Interpretable and Explainable Logical Policies via Neurally Guided Symbolic Abstraction](http://papers.nips.cc/paper_files/paper/2023/hash/9f42f06a54ce3b709ad78d34c73e4363-Abstract-Conference.html) | 2023 | ICLR |
| [PICNN: A Pathway towards Interpretable Convolutional Neural Networks](https://doi.org/10.1609/aaai.v38i3.27971) | 2024 | AAAI |

### Text Data

| Paper Title | Year | Venue |
|-------------|:----------:|:---------------------:|
| [Rationalizing Neural Predictions](https://doi.org/10.18653/v1/d16-1011) | 2016 | EMNLP |
| [Hierarchical attention networks for document classification](https://doi.org/10.18653/v1/n16-1174) | 2016 | NAACL |
| [Learning deep features for discriminative localization](https://doi.org/10.1109/CVPR.2016.319) | 2016 | CVPR |
| [Learning to explain entity relationships in knowledge graphs](https://doi.org/10.3115/v1/p15-1055) | 2016 | ACL |
| [Interpreting recurrent and attention-based neural models: a case study on natural language inference](https://aclanthology.org/D18-1537/) | 2018 | ACL |
| [SPINE: Sparse interpretable neural embeddings](https://doi.org/10.1609/aaai.v32i1.11935) | 2018 | AAAI |
| [Learning to explain: An information-theoretic perspective on model interpretation](http://proceedings.mlr.press/v80/chen18j.html) | 2018 | ICML |
| [Beyond Polarity: Interpretable Financial Sentiment Analysis with Hierarchical Query-driven Attention](https://doi.org/10.24963/ijcai.2018/590) | 2018 | IJCAI |
| [e-SNLI: Natural language inference with natural language explanations](https://proceedings.neurips.cc/paper/2018/hash/4c7a167bb329bd92580a99ce422d6fa6-Abstract.html) | 2018 | NeurIPS |
| [Towards Interpretable Natural Language Understanding with Explanations as Latent Variables](https://proceedings.neurips.cc/paper/2020/hash/4be2c8f27b8a420492f2d44463933eb6-Abstract.html) | 2018 | NeurIPS |
| [Interpretable and steerable sequence learning via prototypes](https://doi.org/10.1145/3292500.3330908) | 2019 | KDD |
| [Interpretable neural predictions with differentiable binary variables](https://doi.org/10.18653/v1/p19-1284) | 2019 | Artificial Intelligence |
| [Towards Explainable NLP: A Generative Explanation Framework for Text Classification](https://doi.org/10.18653/v1/p19-1560) | 2019 | ACL |
| [Learning credible deep neural networks with rationale regularization](https://doi.org/10.1109/ICDM.2019.00025) | 2019 | ICDM |
| [Explain Yourself! Leveraging Language Models for Commonsense Reasoning](https://doi.org/10.18653/v1/p19-1487) | 2019 | ACL |
| [Protoattend: Attention-based prototypical learning](https://jmlr.org/papers/v21/20-042.html) | 2020 | JMLR |
| [WT5?! Training Text-to-Text Models to Explain their Predictions](https://arxiv.org/abs/2004.14546) | 2020 | arXiv |
| [When Can Models Learn From Explanations? A Formal Framework for Understanding the Roles of Explanation Data](https://arxiv.org/abs/2102.02201) | 2022 | NeurIPS |
| [NILE: Natural Language Inference with Faithful Natural Language Explanations](https://doi.org/10.18653/v1/2020.acl-main.771) | 2022 | ACL |
| [Chain-of-thought prompting elicits reasoning in large language models](http://papers.nips.cc/paper_files/paper/2022/hash/9d5609613524ecf4f15af0f7b31abca4-Abstract-Conference.html) | 2022 | NeurIPS |
| [Few-Shot Self-Rationalization with Natural Language Prompts](https://doi.org/10.18653/v1/2022.findings-naacl.31) | 2022 | NAACL |
| [ProtoryNet: Interpretable Text Classification Via Prototype Trajectories](http://jmlr.org/papers/v24/21-0899.html) | 2023 | JMLR |
| [LIREx: Augmenting Language Inference with Relevant Explanation](https://doi.org/10.1609/aaai.v35i16.17708) | 2023 | AAAI |
| [Summarize-then-Answer: Generating Concise Explanations for Multi-hop Reading Comprehension](https://doi.org/10.18653/v1/2021.emnlp-main.490) | 2023 | EMNLP |
| [Tree of thoughts: Deliberate problem solving with large language models](http://papers.nips.cc/paper_files/paper/2023/hash/271db9922b8d1f4dd7aaef84ed5ac703-Abstract-Conference.html) | 2024 | NeurIPS |
| [On Behalf of the Stakeholders: Trends in NLP Model Interpretability in the Era of LLMs](https://doi.org/10.48550/arXiv.2407.19200) | 2024 | arXiv |
| [How interpretable are reasoning explanations from prompting large language models?](https://doi.org/10.18653/v1/2024.findings-naacl.138) | 2024 | ACL |
| [Are self-explanations from Large Language Models faithful?](https://doi.org/10.18653/v1/2024.findings-acl.19) | 2024 | ACL |


### Graph Data

| **Paper** | **Year** | **Venue** |
|-------------|:----------:|:---------------------:|
| [Multi-objective molecule generation using interpretable substructures](http://proceedings.mlr.press/v119/jin20b.html) | 2020 | ICML |
| [Explainable classification of brain networks via contrast subgraphs](https://doi.org/10.1145/3394486.3403383) | 2020 | KDD |
| [Towards self-explainable graph neural network](https://doi.org/10.1145/3459637.3482306) | 2021 | CIKM |
| [Graph Information Bottleneck for Subgraph Recognition](https://arxiv.org/abs/2010.05563) | 2021 | ICLR |
| [Interpretable and efficient heterogeneous graph convolutional network](https://arxiv.org/abs/2005.13183) | 2021 | TKDE |
| [Improving subgraph recognition with variational graph information bottleneck](https://doi.org/10.1109/CVPR52688.2022.01879) | 2022 | CVPR |
| [Protgnn: Towards self-explaining graph neural networks](https://doi.org/10.1609/aaai.v36i8.20898) | 2022 | AAAI |
| [Kergnns: Interpretable graph neural networks with graph kernels](https://doi.org/10.1609/aaai.v36i6.20615) | 2022 | AAAI |
| [Discovering Invariant Rationales for Graph Neural Networks](https://openreview.net/forum?id=hGXij5rfiHw) | 2022 | ICLR |
| [Interpretable and generalizable graph learning via stochastic attention mechanism](https://proceedings.mlr.press/v162/miao22a.html) | 2022 | ICML |
| [Train once and explain everywhere: Pre-training interpretable graph neural networks](http://papers.nips.cc/paper_files/paper/2023/hash/6ecd51685e2d765bc0ad32a2e73faf62-Abstract-Conference.html) | 2023 | NeurIPS |
| [Interpretable Geometric Deep Learning via Learnable Randomness Injection](https://openreview.net/forum?id=6u7mf9s2A9) | 2023 | ICLR |
| [TECHS: Temporal logical graph networks for explainable extrapolation reasoning](https://doi.org/10.18653/v1/2023.acl-long.71) | 2023 | ACL |
| [SIG: Efficient Self-Interpretable Graph Neural Network for Continuous-time Dynamic Graphs](https://doi.org/10.48550/arXiv.2405.19062) | 2023 | NeurIPS |
| [Propagation Structure-Aware Graph Transformer for Robust and Interpretable Fake News Detection](https://doi.org/10.1145/3637528.3672024) | 2024 | KDD |
| [Interpretable prototype-based graph information bottleneck](http://papers.nips.cc/paper_files/paper/2023/hash/f224f056694bcfe465c5d84579785761-Abstract-Conference.html) | 2024 | NeurIPS |
| [Towards self-interpretable graph-level anomaly detection](http://papers.nips.cc/paper_files/paper/2023/hash/1c6f06863df46de009a7a41b41c95cad-Abstract-Conference.html) | 2024 | NeurIPS |
| [Tempme: Towards the explainability of temporal graph neural networks via motif discovery](http://papers.nips.cc/paper_files/paper/2023/hash/5c5bc3553815adb4d1a8a5b8701e41a9-Abstract-Conference.html) | 2024 | NeurIPS |
| [How Interpretable Are Interpretable Graph Neural Networks?](https://openreview.net/forum?id=F3G2udCF3Q) | 2024 | ICML |
| [Globally Interpretable Graph Learning via Distribution Matching](https://doi.org/10.1145/3589334.3645674) | 2024 | WWW |
| [Unveiling Global Interactive Patterns across Graphs: Towards Interpretable Graph Neural Networks](https://doi.org/10.1145/3637528.3671838) | 2024 | KDD |
| [Interpretable graph networks formulate universal algebra conjectures](http://papers.nips.cc/paper_files/paper/2023/hash/2b2011a7d5396faf5899863d896a3c24-Abstract-Conference.html) | 2024 | NeurIPS |
| [SES: Bridging the Gap Between Explainability and Prediction of Graph Neural Networks](https://doi.org/10.1109/ICDE60146.2024.00229) | 2024 | ICDE |
| [Exgc: Bridging efficiency and explainability in graph condensation](https://doi.org/10.1145/3589334.3645551) | 2024 | WWW |
| [A Symbolic Rule Integration Framework with Logic Transformer for Inductive Relation Prediction](https://doi.org/10.1145/3589334.3645594) | 2024 | WWW |
| [MMGNN: A Molecular Merged Graph Neural Network for Explainable Solvation Free Energy Prediction](https://www.ijcai.org/proceedings/2024/642) | 2024 | IJCAI |


### Deep Reinforcement Learning

| **Paper** | **Year** | **Venue** |
|-------------|:----------:|:---------------------:|
| [Towards better interpretability in deep q-networks](https://doi.org/10.1609/aaai.v33i01.33014561) | 2019 | AAAI |
| [Towards interpretable reinforcement learning using attention augmented agents](https://proceedings.neurips.cc/paper/2019/hash/e9510081ac30ffa83f10b68cde1cac07-Abstract.html) | 2019 | NeurIPS |
| [Alphastock: A buying-winners-and-selling-losers investment strategy using interpretable deep reinforcement attention networks](https://doi.org/10.1145/3292500.3330647) | 2019 | KDD |
| [Self-supervised discovering of interpretable features for reinforcement learning](https://doi.org/10.1109/TPAMI.2020.3037898) | 2020 | TPAMI |
| [What did you think would happen? explaining agent behaviour through intended outcomes](https://proceedings.neurips.cc/paper/2020/hash/d5ab8dc7ef67ca92e41d730982c5c602-Abstract.html) | 2020 | NeurIPS |
| [Learning tree interpretation from object representation for deep reinforcement learning](https://proceedings.neurips.cc/paper/2021/hash/a35fe7f7fe8217b4369a0af4244d1fca-Abstract.html) | 2021 | NeurIPS |
| [Edge: Explaining deep reinforcement learning policies](https://proceedings.neurips.cc/paper/2021/hash/65c89f5a9501a04c073b354f03791b1f-Abstract.html) | 2021 | NeurIPS |
| [Differentiable logic policy for interpretable deep reinforcement learning](https://doi.org/10.1109/TPAMI.2023.3285634) | 2023 | TPAMI |
| [N²AQ: Neural Attention Additive Model for Interpretable Multi-Agent Q-Learning](https://proceedings.mlr.press/v202/liu23be.html) | 2023 | ICML |
| [Explainable reinforcement learning via a causal world model](https://doi.org/10.24963/ijcai.2023/505) | 2023 | IJCAI |
| [ProtoX: Explaining a Reinforcement Learning Agent via Prototyping](http://papers.nips.cc/paper_files/paper/2022/hash/ae5bf4f35236240c9460e761c60fa53d-Abstract-Conference.html) | 2023 | NeurIPS |
| [Towards interpretable deep reinforcement learning with human-friendly prototypes](https://openreview.net/forum?id=hWwY_Jq0xsN) | 2023 | ICLR |
| [Interpretable and Explainable Logical Policies via Neurally Guided Symbolic Abstraction](http://papers.nips.cc/paper_files/paper/2023/hash/9f42f06a54ce3b709ad78d34c73e4363-Abstract-Conference.html) | 2023 | ICLR |
| [Efficient Symbolic Policy Learning with Differentiable Symbolic Expression](http://papers.nips.cc/paper_files/paper/2023/hash/7207ffb9888068c0ee13ae3be023cada-Abstract-Conference.html) | 2023 | NeurIPS |
| [Interpretable reward redistribution in reinforcement learning: a causal approach](http://papers.nips.cc/paper_files/paper/2023/hash/402e12102d6ec3ea3df40ce1b23d423a-Abstract-Conference.html) | 2024 | NeurIPS |


## Evaluation Metrics

| **Paper** | **Year** | **Venue** |
|-------------|:----------:|:---------------------:|
| [On completeness-aware concept-based explanations in deep neural networks](https://proceedings.neurips.cc/paper/2020/hash/ecb287ff763c169694f682af52c1f309-Abstract.html) | 2018 | NeurIPS |
| [Towards robust interpretability with self-explaining neural networks](https://proceedings.neurips.cc/paper/2018/hash/3e9f0fc9b2f89e043bc6233994dfcf76-Abstract.html) | 2018 | NeurIPS |
| [Concept bottleneck models](https://doi.org/10.48550/arXiv.2411.16512) | 2020 | ICML |
| [Self-Interpretable Model with Transformation Equivariant Interpretation](https://proceedings.neurips.cc/paper/2021/hash/1387a00f03b4b423e63127b08c261bdc-Abstract.html) | 2021 | NeurIPS |
| [Protgnn: Towards self-explaining graph neural networks](https://doi.org/10.1609/aaai.v36i8.20898) | 2022 | AAAI |
| [Concept embedding models: Beyond the accuracy-explainability trade-off](http://papers.nips.cc/paper_files/paper/2022/hash/867c06823281e506e8059f5c13a57f75-Abstract-Conference.html) | 2022 | NeurIPS |
| [Language in a bottle: Language model guided concept bottlenecks for interpretable image classification](https://doi.org/10.1109/CVPR52729.2023.01839) | 2023 | CVPR |
| [Towards robust metrics for concept representation evaluation](https://doi.org/10.1609/aaai.v37i10.26392) | 2023 | AAAI |
| [Evaluation and improvement of interpretability for self-explainable part-prototype networks](https://doi.org/10.1109/ICCV51070.2023.00192) | 2023 | ICCV |
| [Towards human-centered explainable ai: A survey of user studies for model explanations](https://doi.org/10.1109/TPAMI.2023.3331846) | 2023 | TPAMI |
| [Market-aware Long-term Job Skill Recommendation with Explainable Deep Reinforcement Learning](https://dl.acm.org/doi/abs/10.1145/3704998) | 2024 | ACM TOIS |
| [Pixel-grounded prototypical part networks](https://doi.org/10.1109/WACV57701.2024.00470) | 2024 | WACV |
| [VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance](https://doi.org/10.48550/arXiv.2408.01432) | 2024 | NeurIPS |
| [Interpretability benchmark for evaluating spatial misalignment of prototypical parts explanations](https://doi.org/10.1609/aaai.v38i19.30154) | 2024 | AAAI |
| [Coarse-to-fine concept bottleneck models](https://hal.science/hal-04709806/) | 2024 | NeurIPS |
| [Learning to receive help: Intervention-aware concept embedding models](http://papers.nips.cc/paper_files/paper/2023/hash/770cabd044c4eacb6dc5924d9a686dce-Abstract-Conference.html) | 2024 | NeurIPS |
| [Towards Modeling Uncertainties of Self-Explaining Neural Networks via Conformal Prediction](https://doi.org/10.1609/aaai.v38i13.29382) | 2024 | AAAI |
| [Unveiling Global Interactive Patterns across Graphs: Towards Interpretable Graph Neural Networks](https://doi.org/10.1145/3637528.3671838) | 2024 | KDD |


## Citations
```
@article{jiyang2025sinn,
  title={A Comprehensive Survey on Self-Interpretable Neural Networks},
  author={Yang Ji and Ying Sun and Yuting Zhang and Zhigaoyuan Wang and Yuanxin Zhuang and Zheng Gong and Dazhong Shen and Chuan Qin and Hengshu Zhu and Hui Xiong},
  journal={arXiv preprint arXiv:2301.07854},
  year={2025},
  url={https://arxiv.org/abs/2301.07854}
}
```

## Other Resources

- [Awesome-XAI](https://github.com/altamiracorp/awesome-xai)
- [Awesome-Explainable-AI](https://github.com/wangyongjie-ntu/Awesome-explainable-AI)
- [Awesome-Graph-Explainability-Papers](https://github.com/flyingdoog/awesome-graph-explainability-papers)
- [Awesome-Explainable-Reinforcement-Learning](https://github.com/Plankson/awesome-explainable-reinforcement-learning)
- [Explainability-for-Large-Language-Models](https://github.com/hy-zhao23/Explainability-for-Large-Language-Models)


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yangji721/Awesome-Interpretable-Network&type=Date)](https://star-history.com/#yangji721/Awesome-Interpretable-Network&Date)
