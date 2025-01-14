# Awesome Self-Interpretable Neural Network

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

A professionally curated list of awesome literature on **Self-Interpretable Neural Network** (SINN), which is the first work to comprehensively and systematically summarize the recent advances of machine learning models designed to have inherent interpretability. We focus on collecting and reviewing SINN-related papers published in leading AI-related conferences and journals, including but not limited to NeurIPS, ICML, ICLR, AAAI, CVPR, ACL, KDD, WWW, IJCAI, TAPMI, JMLR, TKDE, TOIS, and Nature-related journals, as well as influential works from the broader research community. 

# Attribution-based methods

The following table explains the abbreviations used in this section:

| Abbreviation | Full Name                         |
|--------------|------------------------------------|
| `GCA`        | Generalized Coefficient Attribution |
| `ASA`        | Additive Score Attribution |
| `HFA`        | Hybrid Feature Attribution |


| title                                                                                                                    |   year | subsubsections      | source                          |
|:-------------------------------------------------------------------------------------------------------------------------|-------:|:--------------------|:--------------------------------|
| A value for n-person games                                                                                               |   1953 | `ASA`               | Contrib. Theory Games           |
| Neural Machine Translation by Jointly Learning to Align and Translate                                                    |   2015 | `GCA`               | ICLR                            |
| Rationalizing Neural Predictions                                                                                         |   2016 | `GCA`               | EMNLP                           |
| From softmax to sparsemax: A sparse model of attention and multi-label classification                                    |   2016 | `GCA`               | ICML                            |
| A unified approach to interpreting model predictions                                                                     |   2017 | `ASA`               | NeurIPS                         |
| Generalized additive models                                                                                              |   2017 | `ASA`               | Statistical models in S         |
| Attention is all you need                                                                                                |   2017 | `GCA`               | NeurIPS                         |
| Categorical Reparameterization with {Gumbel-Softmax}                                                                     |   2017 | `GCA`               | ICLR                            |
| Neural interaction transparency (nit): Disentangling learned interactions for improved interpretability                  |   2018 | `ASA`               | NeurIPS                         |
| INVASE: Instance-wise variable selection using neural networks                                                           |   2018 | `GCA`               | ICLR                            |
| Learning to explain: An information-theoretic perspective on model interpretation                                        |   2018 | `GCA`               | ICML                            |
| Approximating CNNs with Bag-of-local-Features models works surprisingly well on ImageNet                                 |   2018 | `ASA`               | ICLR                            |
| Towards robust interpretability with self-explaining neural networks                                                     |   2018 | `GCA`, `HFA`        | NeurIPS                         |
| Beyond Polarity: Interpretable Financial Sentiment Analysis with Hierarchical Query-driven Attention                     |   2018 | `GCA`               | IJCAI                           |
| Reparameterizable subset sampling via continuous relaxations                                                             |   2019 | `GCA`               | IJCAI                           |
| Interpretable multi-task learning for product quality prediction with attention mechanism                                |   2019 | `GCA`               | IEEE ICDE                       |
| Adaptively Sparse Transformers                                                                                           |   2019 | `GCA`               | EMNLP                           |
| Exploiting kernel sparsity and entropy for interpretable CNN compression                                                 |   2019 | `GCA`               | CVPR                            |
| Learning representations for neural network-based classification using the information bottleneck principle              |   2019 | `GCA`               | IEEE TPAMI                      |
| Interpretable predictive modeling for climate variables with weighted lasso                                              |   2019 | `GCA`, `HFA`        | AAAI                            |
| Attention is not not Explanation                                                                                         |   2019 | `GCA`               | EMNLP-IJCNLP                    |
| Is Attention Interpretable?                                                                                              |   2019 | `GCA`               | ACL                             |
| Concrete autoencoders: Differentiable feature selection and reconstruction                                               |   2019 | `GCA`               | ICML                            |
| Deepcoda: personalized interpretability for compositional health data                                                    |   2020 | `GCA`, `HFA`        | ICML                            |
| Graph Information Bottleneck for Subgraph Recognition                                                                    |   2020 | `GCA`               | ICLR                            |
| Sparse shrunk additive models                                                                                            |   2020 | `ASA`               | ICML                            |
| MRI reconstruction with interpretable pixel-wise operations using reinforcement learning                                 |   2020 | `GCA`               | AAAI                            |
| Attention is Not Only a Weight: Analyzing Transformers with Vector Norms                                                 |   2020 | `GCA`               | EMNLP                           |
| Modeling users' behavior sequences with hierarchical explainable network for cross-domain fraud detection                |   2020 | `GCA`               | ACM WWW                         |
| Feature selection using stochastic gates                                                                                 |   2020 | `GCA`               | ICML                            |
| On Identifiability in Transformers                                                                                       |   2020 | `GCA`               | ICLR                            |
| Consistent feature selection for analytic deep neural networks                                                           |   2020 | `GCA`               | NeurIPS                         |
| Towards Transparent and Explainable Attention Models                                                                     |   2020 | `GCA`               | ACL                             |
| Learning to Deceive with Attention-Based Explanations                                                                    |   2020 | `GCA`               | ACL                             |
| Timeshap: Explaining recurrent models through sequence perturbations                                                     |   2021 | `ASA`               | ACM SIGKDD                      |
| GAMI-Net: An explainable neural network based on generalized additive models with structured interactions                |   2021 | `ASA`, `HFA`        | Pattern Recognit.               |
| Shapley Explanation Networks                                                                                             |   2021 | `ASA`               | ICLR                            |
| Market-oriented job skill valuation with cooperative composition neural network                                          |   2021 | `HFA`               | Nat. Commun.                    |
| Neural additive models: Interpretable machine learning with neural nets                                                  |   2021 | `ASA`, `HFA`        | NeurIPS                         |
| Is Sparse Attention more Interpretable?                                                                                  |   2021 | `GCA`               | ACL-IJCNLP                      |
| Edge: Explaining deep reinforcement learning policies                                                                    |   2021 | `GCA`, `HFA`        | NeurIPS                         |
| Why attentions may not be interpretable?                                                                                 |   2021 | `GCA`               | ACM SIGKDD                      |
| Attention-based interpretability with concept transformers                                                               |   2021 | `GCA`               | ICLR                            |
| Effective Attention Sheds Light On Interpretability                                                                      |   2021 | `GCA`               | ACL-IJCNLP                      |
| Self-Interpretable Model with Transformation Equivariant Interpretation                                                  |   2021 | `GCA`, `HFA`        | NeurIPS                         |
| Towards rigorous interpretations: a formalisation of feature attribution                                                 |   2021 | `GCA`               | ICML                            |
| Discerning decision-making process of deep neural networks with hierarchical voting transformation                       |   2021 | `HFA`               | NeurIPS                         |
| Recognizing predictive substructures with subgraph information bottleneck                                                |   2021 | `GCA`               | IEEE TPAMI                      |
| Tabnet: Attentive interpretable tabular learning                                                                         |   2021 | `GCA`               | AAAI                            |
| Lassonet: A neural network with feature sparsity                                                                         |   2021 | `GCA`               | J. Mach. Learn. Res.            |
| Convolutional dynamic alignment networks for interpretable classifications                                               |   2021 | `GCA`               | IEEE CVPR                       |
| Have We Learned to Explain?: How Interpretability Methods Can Learn to Encode Predictions in their Interpretations       |   2021 | `GCA`               | AISTATS                         |
| Evidence-aware hierarchical interactive attention networks for explainable claim verification                            |   2021 | `GCA`               | IJCAI                           |
| Towards improved and interpretable deep metric learning via attentive grouping                                           |   2022 | `GCA`               | IEEE TPAMI                      |
| Supervising model attention with human explanations for robust natural language inference                                |   2022 | `GCA`               | AAAI                            |
| Deep Variational Information Bottleneck                                                                                  |   2022 | `GCA`               | ICLR                            |
| Locally sparse neural networks for tabular biomedical data                                                               |   2022 | `GCA`               | ICML                            |
| Self-explaining deep models with logic rule reasoning                                                                    |   2022 | `GCA`               | NeurIPS                         |
| Is attention explanation? an introduction to the debate                                                                  |   2022 | `GCA`               | ACL                             |
| Puregam: Learning an inherently pure additive model                                                                      |   2022 | `ASA`               | KDD                             |
| Query and attention augmentation for knowledge-based explainable reasoning                                               |   2022 | `GCA`               | IEEE CVPR                       |
| A diversified attention model for interpretable multiple clusterings                                                     |   2022 | `GCA`               | IEEE Trans. Knowl. Data Eng.    |
| Interpretable and generalizable graph learning via stochastic attention mechanism                                        |   2022 | `GCA`               | ICML                            |
| Neural basis models for interpretability                                                                                 |   2022 | `ASA`, `HFA`        | NeurIPS                         |
| B-cos networks: Alignment is all we need for interpretability                                                            |   2022 | `GCA`               | CVPR                            |
| Sparse interaction additive networks via feature interaction detection and sparse selection                              |   2022 | `ASA`, `HFA`        | NeurIPS                         |
| Scalable interpretability via polynomials                                                                                |   2022 | `ASA`               | NeurIPS                         |
| Seat: stable and explainable attention                                                                                   |   2023 | `GCA`               | AAAI                            |
| Interpretable bilinear attention network with domain adaptation improves drug--target prediction                         |   2023 | `GCA`               | Nat. Mach. Intell.              |
| Extractive explanations for interpretable text ranking                                                                   |   2023 | `GCA`               | ACM Trans. Inf. Syst.           |
| Improving interpretability via explicit word interaction graph layer                                                     |   2023 | `GCA`               | AAAI                            |
| Interpretable Geometric Deep Learning via Learnable Randomness Injection                                                 |   2023 | `GCA`               | ICLR                            |
| N$\text{A}^\text{2}$Q: Neural Attention Additive Model for Interpretable Multi-Agent Q-Learning                          |   2023 | `ASA`               | ICML                            |
| Towards Faithful Neural Network Intrinsic Interpretation with Shapley Additive Self-Attribution                          |   2023 | `GCA`, `ASA`, `HFA` | arXiv preprint arXiv:2309.15559 |
| The contextual lasso: Sparse linear models via deep neural networks                                                      |   2023 | `GCA`               | NeurIPS                         |
| Learning Faithful Attention for Interpretable Classification of Crisis-Related Microblogs under Constrained Human Budget |   2023 | `GCA`               | ACM WWW                         |
| Improving Neural Additive Models with Bayesian Principles                                                                |   2023 | `ASA`               | ICML                            |
| Sparse Neural Additive Model: Interpretable Deep Learning with Feature Selection via Group Sparsity                      |   2023 | `ASA`, `HFA`        | ICLR                            |
| CAT: Interpretable Concept-based Taylor Additive Models                                                                  |   2024 | `ASA`               | KDD                             |
| B-cos Alignment for Inherently Interpretable CNNs and Vision Transformers                                                |   2024 | `GCA`               | IEEE TPAMI                      |
| Kan: Kolmogorov-arnold networks                                                                                          |   2024 | `HFA`               | arXiv preprint arXiv:2404.19756 |
| ProtoGate: Prototype-based Neural Networks with Global-to-local Feature Selection for Tabular Biomedical Data            |   2024 | `GCA`               | ICML                            |
| InterpreTabNet: Distilling Predictive Signals from Tabular Data by Salient Feature Interpretation                        |   2024 | `GCA`               | ICML                            |
| Interpretable prototype-based graph information bottleneck                                                               |   2024 | `GCA`               | NeurIPS                         |
| Exgc: Bridging efficiency and explainability in graph condensation                                                       |   2024 | `GCA`               | ACM WWW                         |
| Towards self-interpretable graph-level anomaly detection                                                                 |   2024 | `GCA`               | NeurIPS                         |
| Tempme: Towards the explainability of temporal graph neural networks via motif discovery                                 |   2024 | `GCA`               | NeurIPS                         |
| NODE-GAM: Neural Generalized Additive Model for Interpretable Deep Learning                                              |   2024 | `ASA`               | ICLR                            |
| GRAND-SLAMIN'Interpretable Additive Modeling with Structural Constraints                                                 |   2024 | `ASA`               | NeurIPS                         |
| Propagation Structure-Aware Graph Transformer for Robust and Interpretable Fake News Detection                           |   2024 | `GCA`               | KDD                             |
| NAISR: A 3D Neural Additive Model for Interpretable Shape Representation                                                 |   2024 | `ASA`               | ICLR                            |
| Comprehensive Attribution: Inherently Explainable Vision Model with Feature Detector                                     |   2025 | `GCA`               | ECCV                            |

# Function-based methods

The following table explains the abbreviations used in this section:

| Abbreviation | Full Name                         |
|--------------|------------------------------------|
| `FD`        | Functional Decomposition. |
| `EL`        | Equation Learning. |


| title                                                                                                     |   year | subsubsections   | source                                |
|:----------------------------------------------------------------------------------------------------------|-------:|:-----------------|:--------------------------------------|
| Learning equations for extrapolation and control                                                          |   2018 | `EL`             | ICML                                  |
| Integration of neural network-based symbolic regression in deep learning for scientific discovery         |   2020 | `FD`, `EL`       | IEEE Trans. Neural Netw. Learn. Syst. |
| Discerning decision-making process of deep neural networks with hierarchical voting transformation        |   2021 | `FD`             | NeurIPS                               |
| Neural symbolic regression that scales                                                                    |   2021 | `FD`, `EL`       | ICML                                  |
| Symbolicgpt: A generative transformer model for symbolic regression                                       |   2021 | `FD`, `EL`       | arXiv preprint arXiv:2106.14131       |
| End-to-end symbolic regression with transformers                                                          |   2022 | `FD`, `EL`       | NeurIPS                               |
| A unified framework for deep symbolic regression                                                          |   2022 | `FD`, `EL`       | NeurIPS                               |
| Controllable neural symbolic regression                                                                   |   2023 | `FD`, `EL`       | ICML                                  |
| Deep Generative Symbolic Regression                                                                       |   2023 | `FD`, `EL`       | ICLR                                  |
| Kan: Kolmogorov-arnold networks                                                                           |   2024 | `FD`             | arXiv preprint arXiv:2404.19756       |
| GINN-LP: A Growing Interpretable Neural Network for Discovering Multivariate Laurent Polynomial Equations |   2024 | `FD`, `EL`       | AAAI                                  |


# Concept-based methods


The following table explains the abbreviations used in this section:

| Abbreviation | Full Name                         |
|--------------|------------------------------------|
| `CR`        | Concept Representation |
| `CO`        | Concept Organization |
| `CS`        | Concept Supervision |
| `GCM`        | Generative Concept Model |



| title                                                                                                              |   year | subsubsections   | source                          |
|:-------------------------------------------------------------------------------------------------------------------|-------:|:-----------------|:--------------------------------|
| beta-vae: Learning basic visual concepts with a constrained variational framework                                  |   2017 | `GCM`            | ICLR                            |
| Disentangling by factorising                                                                                       |   2018 | `GCM`            | ICML                            |
| Isolating sources of disentanglement in variational autoencoders                                                   |   2018 | `GCM`            | NeurIPS                         |
| Interfacegan: Interpreting the disentangled face representation learned by gans                                    |   2020 | `GCM`            | IEEE TPAMI                      |
| Concept bottleneck models                                                                                          |   2020 | `CR`             | ICML                            |
| Concept whitening for interpretable image recognition                                                              |   2020 | `CR`             | Nat. Mach. Intell.              |
| Attention-based interpretability with concept transformers                                                         |   2021 | `CR`             | ICLR                            |
| Explainable neural networks that simulate reasoning                                                                |   2021 | `CR`, `CO`       | Nat. Comput. Sci.               |
| Self-Interpretable Model with Transformation Equivariant Interpretation                                            |   2021 | `CR`             | NeurIPS                         |
| Post-hoc Concept Bottleneck Models                                                                                 |   2022 | `CR`, `CS`       | ICLR                            |
| Concept embedding models: Beyond the accuracy-explainability trade-off                                             |   2022 | `CR`             | NeurIPS                         |
| Addressing leakage in concept bottleneck models                                                                    |   2022 | `CR`, `CO`, `CS` | NeurIPS                         |
| Probabilistic Concept Bottleneck Models                                                                            |   2023 | `CR`             | ICML                            |
| Learning to Intervene on Concept Bottlenecks                                                                       |   2023 | `CO`, `CS`       | ICML                            |
| Interactive concept bottleneck models                                                                              |   2023 | `CS`             | AAAI                            |
| Label-free Concept Bottleneck Models                                                                               |   2023 | `CS`             | ICLR                            |
| Language in a bottle: Language model guided concept bottlenecks for interpretable image classification             |   2023 | `CS`             | CVPR                            |
| Towards Trustable Skin Cancer Diagnosis via Rewriting Model's Decision                                             |   2023 | `CS`             | CVPR                            |
| Pantypes: Diverse Representatives for Self-Explainable Models                                                      |   2024 | `GCM`            | AAAI                            |
| VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance                                          |   2024 | `CS`             | NeurIPS                         |
| Energy-based concept bottleneck models: unifying prediction, concept intervention, and conditional interpretations |   2024 | `CR`, `CS`       | arXiv preprint arXiv:2401.14142 |
| Mica: Towards explainable skin lesion diagnosis via multi-level image-concept alignment                            |   2024 | `CO`             | AAAI                            |
| Relational Concept Bottleneck Models                                                                               |   2024 | `CO`             | NeurIPS                         |
| Stochastic Concept Bottleneck Models                                                                               |   2024 | `CR`, `CS`       | NeurIPS                         |
| Learning to receive help: Intervention-aware concept embedding models                                              |   2024 | `CR`             | NeurIPS                         |
| Incremental residual concept bottleneck models                                                                     |   2024 | `CO`, `CS`       | CVPR                            |
| Understanding Inter-Concept Relationships in Concept-Based Models                                                  |   2024 | `CO`, `CS`       | ICML                            |
| Coarse-to-fine concept bottleneck models                                                                           |   2024 | `CO`             | NeurIPS                         |


# Prototype-based methods


The following table explains the abbreviations used in this section:

| Abbreviation | Full Name                         |
|--------------|------------------------------------|
| `PR`        | Prototype Representations. |
| `PA`        | Prototype Alignment. |




| title                                                                                                  |   year | subsubsections   | source                |
|:-------------------------------------------------------------------------------------------------------|-------:|:-----------------|:----------------------|
| This looks like that: deep learning for interpretable image recognition                                |   2019 | `PA`             | NeurIPS               |
| Interpretable and steerable sequence learning via prototypes                                           |   2019 | `PA`             | ACM SIGKDD            |
| Neural prototype trees for interpretable fine-grained image recognition                                |   2021 | `PR`             | IEEE CVPR             |
| Interpretable image recognition by constructing transparent embedding space                            |   2021 | `PR`             | IEEE ICCV             |
| Protopshare: Prototypical parts sharing for similarity discovery in interpretable image classification |   2021 | `PA`             | ACM SIGKDD            |
| XProtoNet: diagnosis in chest radiography with global and local explanations                           |   2021 | `PR`             | IEEE CVPR             |
| Proto2Proto: Can you recognize the car, the way I do?                                                  |   2022 | `PR`             | IEEE CVPR             |
| Interpretable image classification with differentiable prototypes assignment                           |   2022 | `PR`             | ECCV                  |
| Protgnn: Towards self-explaining graph neural networks                                                 |   2022 | `PA`             | AAAI                  |
| Protovae: A trustworthy self-explainable prototypical variational model                                |   2022 | `PR`             | NeurIPS               |
| ProtoryNet-Interpretable Text Classification Via Prototype Trajectories                                |   2023 | `PR`             | J. Mach. Learn. Res.  |
| PIP-Net: Patch-Based Intuitive Prototypes for Interpretable Image Classification                       |   2023 | `PR`, `PA`       | IEEE CVPR             |
| Towards interpretable deep reinforcement learning with human-friendly prototypes                       |   2023 | `PA`             | ICLR                  |
| Learning Support and Trivial Prototypes for Interpretable Image Classification                         |   2023 | `PR`             | IEEE ICCV             |
| Concept-level debugging of part-prototype networks                                                     |   2023 | `PA`             | ICLR                  |
| Protoseg: Interpretable semantic segmentation with prototypical parts                                  |   2023 | `PR`             | IEEE WACV             |
| Interpretable prototype-based graph information bottleneck                                             |   2024 | `PR`, `PA`       | NeurIPS               |
| Pantypes: Diverse Representatives for Self-Explainable Models                                          |   2024 | `PR`             | AAAI                  |
| This looks like those: Illuminating prototypical concepts using multiple visualizations                |   2024 | `PR`             | NeurIPS               |
| Market-aware Long-term Job Skill Recommendation with Explainable Deep Reinforcement Learning           |   2024 | `PA`             | ACM Trans. Inf. Syst. |


# Rule-based methods

The following table explains the abbreviations used in this section:

| Abbreviation | Full Name                         |
|--------------|------------------------------------|
| `LOAN`        | Logical Operators as Neurons |
| `LC`        | Logic-Inspired Constraints |
| `RGN`        | Rule Generation Network |
| `INT`        | Interpretable Neural Tree |
| `AC`        | Attribution-Prototype Composition |
| `DC`        | Distribution-Concept Composition |
| `CC`        | Concept-Rule Composition |
| `FF`        | Function-Concept Fusion |
| `PF`        | Prototype-Rule Fusion |
| `GAI`        | Global-Local Attribution Integration |


| title                                                                                                         |   year | subsubsections   | source                          |
|:--------------------------------------------------------------------------------------------------------------|-------:|:-----------------|:--------------------------------|
| Logic Tensor Networks for Semantic Image Interpretation                                                       |   2017 | `LOAN`           | IJCAI                           |
| Deep neural decision trees                                                                                    |   2018 | `INT`            | arXiv preprint arXiv:1806.06988 |
| Deep neural networks constrained by decision rules                                                            |   2019 | `RGN`            | AAAI                            |
| NBDT: Neural-Backed Decision Tree                                                                             |   2020 | `INT`            | ICLR                            |
| Transparent classification with multilayer logical perceptrons and random binarization                        |   2020 | `LOAN`           | AAAI                            |
| Human-driven FOL explanations of deep learning                                                                |   2020 | `LC`             | IJCAI                           |
| A constraint-based approach to learning and explanation                                                       |   2020 | `LC`             | AAAI                            |
| Neural prototype trees for interpretable fine-grained image recognition                                       |   2021 | `INT`, `PF`      | IEEE CVPR                       |
| Learning accurate and interpretable decision rule sets from neural networks                                   |   2021 | `LOAN`           | AAAI                            |
| Scalable rule-based representation learning for interpretable classification                                  |   2021 | `LOAN`           | NeurIPS                         |
| Weakly Supervised Explainable Phrasal Reasoning with Neural Fuzzy Logic                                       |   2021 | `RGN`            | ICLR                            |
| Discerning decision-making process of deep neural networks with hierarchical voting transformation            |   2021 | `FF`             | NeurIPS                         |
| Analyzing differentiable fuzzy logic operators                                                                |   2022 | `LOAN`           | Artif. Intell.                  |
| Vit-net: Interpretable vision transformers with neural tree decoder                                           |   2022 | `INT`, `GAI`     | ICML                            |
| Self-explaining deep models with logic rule reasoning                                                         |   2022 | `RGN`            | NeurIPS                         |
| Entropy-based logic explanations of neural networks                                                           |   2022 | `LC`             | AAAI                            |
| Extending Logic Explained Networks to Text Classification                                                     |   2022 | `LC`             | EMNLP                           |
| Explainable Neural Rule Learning                                                                              |   2022 | `LOAN`           | WWW                             |
| Deep differentiable logic gate networks                                                                       |   2022 | `LOAN`           | NeurIPS                         |
| Interpretable neural-symbolic concept reasoning                                                               |   2023 | `LC`, `CC`       | ICML                            |
| Learning to Binarize Continuous Features for Neuro-Rule Networks.                                             |   2023 | `LOAN`           | IJCAI                           |
| Learning interpretable rules for scalable data representation and classification                              |   2023 | `LOAN`           | IEEE TPAMI                      |
| FINRule: Feature Interactive Neural Rule Learning                                                             |   2023 | `LOAN`           | CIKM                            |
| Probabilistic Concept Bottleneck Models                                                                       |   2023 | `DC`             | ICML                            |
| Logic explained networks                                                                                      |   2023 | `LC`             | Artif. Intell.                  |
| Convolutional Differentiable Logic Gate Networks                                                              |   2024 | `LOAN`           | NeurIPS                         |
| HyperLogic: Enhancing Diversity and Accuracy in Rule Learning with HyperNets                                  |   2024 | `LOAN`           | NeurIPS                         |
| Interpretable prototype-based graph information bottleneck                                                    |   2024 | `AC`             | NeurIPS                         |
| Stochastic Concept Bottleneck Models                                                                          |   2024 | `DC`             | NeurIPS                         |
| ProtoGate: Prototype-based Neural Networks with Global-to-local Feature Selection for Tabular Biomedical Data |   2024 | `GAI`            | ICML                            |
