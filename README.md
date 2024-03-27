# Antibody-Prediction-Methods  
## Description
Here is a paper list containing all kinds of deep learning-based prediction of antibody. If you have a paper or resource you'd like to add, please submit a pull request or open an issue.

抗体可开发性预测：
Biophysical cartography of the native and human-engineered antibody landscapes quantifies the plasticity of antibody developability
超过 200 万个天然和人工工程单链抗体序列的 40 个基于序列的 DP 和 46 个基于结构的 DP

抗体性质预测
AbPROP: Language and Graph Deep Learning for Antibody Property Prediction
图神经网络性质预测 GVP GAT

抗体序列生成：
设计
语言模型
Reprogramming Pretrained Language Models for Antibody Sequence Infilling
ReprogBert BERT重编程

抗体亲和力预测：
Antibody optimization enabled by artificial intelligence predictions of binding affinity and naturalness
遗传算法同时最大化自然度和亲和力

抗体序列+结构预测（关注模型设计）：
ABDIFFUSER: FULL-ATOM GENERATION OF INVITRO FUNCTIONING ANTIBODIES
等变+扩散模型

抗体优化：
Optimization of therapeutic antibodies by predicting antigen specificity from antibody sequence via deep learning

抗体序列+结构预测+亲和力优化：（提到抗体数据库，关注模型设计）
Conditional Antibody Design as 3D Equivariant Graph Translation
图等变模型

抗体序列+亲和力预测：
De novo generation of antibody CDRH3 with a pre-trained generative large language model
PALM抗体语言模型设计CDR3
Multi-Fusion Convolutional Neural Network (MF-CNN)预测亲和力

抗体序列：
Generative Antibody Design for Complementary Chain Pairing Sequences through Encoder-Decoder Language Model
编码器+解码器
AntiBARTy Diffusion for Property Guided Antibody Design

结构和功能设计RFdiffusion
De novo design of protein structure and function with RFdiffusion
https://github.com/RosettaCommons/RFdiffusion

抗体序列+抗体抗原结构共设计（关注下如何利用序列数据，解决结构数据不足的问题）：
Pre-training Antibody Language Models for Antigen-Specific Computational Antibody Design
ABGNN：GNN+BERT

图神经网络
End-to-End Full-Atom Antibody Design
dyMEAN：等变图神经网络

Antibody-antigen Docking and Design via Hierarchical Equivariant Refinement
HERN：

In vitro validated antibody design against multiple therapeutic antigens using generative inverse folding
微调PROTEINMPNN  融合ESM 反向折叠

AntiFold: Improved antibody structure design using inverse folding 反向折叠

Generative Diffusion Models for Antibody Design, Docking, and Optimization
Abdesign+Abdock

Guiding diffusion models for antibody sequence and structure co-design with developability properties
开发性引导的diffab 无需重新训练的

Epitope-specific antibody design using diffusion models on the latent space of ESM embeddings
加入ESM信息的扩散模型



An Energy Based Model for Incorporating Sequence Priors for Target-Specific Antibody Design
语言模型+GNN+能量

强化学习
Stable Online and Offline Reinforcement Learning for Antibody CDRH3 Design

对接/筛选
Towards the accurate modelling of antibody-antigen complexes from sequence using machine learning and information-driven docking
HADDOCK新论文

Evaluating Zero-Shot Scoring for In Vitro Antibody Binding Prediction with Experimental Validation
筛选方法评价 包括ESM、残差水平模型置信度（Abbuild2）、RMSD 均方根偏差、魔改dyMEAN的界面距离


SAGERank: Inductive Learning of Protein-Protein Interaction from Antibody-Antigen Recognition using Graph Sample and Aggregate Networks Framework
图神经网络对接排序


考虑边界序列重复性
An Energy Based Model for Incorporating Sequence Priors for Target-Specific Antibody Design
考虑能量



反向折叠
AntiFold: Improved antibody structure design using inverse folding
可用

In vitro validated antibody design against multiple therapeutic antigens using generative inverse folding
Igdesign





蛋白质设计
HelixDiff: Hotspot-Specific Full-atom Design of Peptides Using Diffusion Models
扩散模型全原子设计

Fast non-autoregressive inverse folding with discrete diffusion
使用预训练的 ProteinMPNN 并通过扩散对其进行微调


AMP-Diffusion: Integrating Latent Diffusion with Protein Language Models for Antimicrobial Peptide Generation
将潜在扩散与蛋白质语言模型相结合以生成抗菌肽


Structure-informed Language Models Are Protein Designers

Adapter 微调plm + 结构编码条件生成 （重新掩码概率低的位置）


Full-Atom Peptide Design with Geometric Latent Diffusion

全原子潜在扩散生成结合肽
