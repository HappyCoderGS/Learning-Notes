## Study Plan
AML - [Advanced Machine Learning](topics/advanced_ml.md) | MIC - [Medical Image Computing](topics/mic.md) | Prog - [Programming](topics/programming.md)

NB: Time below means when I "studied", not when it has been.

## 2018-10
Main focus: preparing CVPR (and IPMI) [ddl](https://creedai.github.io/ai-deadlines/)

### Study
* [x] 一堂課讓你認識肺癌（Basic Concepts of Lung Cancer: Diagnosis and Treatment）([Coursera](https://www.coursera.org/learn/lung-cancer/))
* [x] Computational Neuroscience 计算神经科学 ([Xuetangx](http://www.xuetangx.com/courses/course-v1:NTHU+MOOC_04+sp/courseware/def9437b3df2456e88dd2e7fa0bb227a/))
  * [x] week3 - Signal propagation in neurons
  * [x] week4 - Neural Network simulators

### Reading
* 3D vision is still the main reading
  * [x] FoldingNet: Point Cloud Auto-encoder via Deep Grid Deformation ([CVPR2018](https://arxiv.org/abs/1712.07262))
  * [x] PU-Net: Point Cloud Upsampling Network ([CVPR2018](https://arxiv.org/abs/1801.06761))
  * [x] Pointwise Convolutional Neural Networks ([CVPR2018](https://arxiv.org/abs/1712.05245))
  * [x] 3D Graph Neural Networks for RGBD Semantic Segmentation ([ICCV2017](http://www.cs.toronto.edu/~rjliao/papers/iccv_2017_3DGNN.pdf))
  * [x] Recurrent Slice Networks for 3D Segmentation of Point Clouds ([CVPR2018](https://arxiv.org/abs/1802.04402))
  * [x] Learning Representations and Generative Models for 3D Point Clouds ([ICML2018](https://arxiv.org/abs/1707.02392)): apart from the GAN for point cloud, the metric to measure two point clouds is also useful (togethor with its [code](https://github.com/optas/latent_3d_points)). A paper solid to win (8-page supplementary experiments).
  * [x] PointGrid: A Deep Network for 3D Shape Understanding ([CVPR2018](http://openaccess.thecvf.com/content_cvpr_2018/papers/Le_PointGrid_A_Deep_CVPR_2018_paper.pdf)): a simple yet effective and efficient solution for point cloud. I do like this paper (though not very well-wrtien). However, it seems a purified methodology version of VoxelNet (also CVPR2018). No cross citation between these two papers.
  * [x] VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection ([CVPR2018](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/3333.pdf)): a "PointGrid" (CVPR2018 as well) on kitti, better writen. No cross citation between these two papers.
  * [x] PointGrow: Autoregressively Learned Point Cloud Generation with Self-Attention ([OpenReview](https://openreview.net/forum?id=r1eWW2RqFX), ICLR2019 under review): not very clear writen. Some evaluation is mssing better metrics. Some baseline is missing. I guess a 60% probability to accept. Maybe writen by an intern of authors of DGCNN.
* Group Equivariance
  * [ ] Group Equivariant Convolutional Networks ([ICML2016](https://arxiv.org/abs/1602.07576)): as a premilary for other papers on this topic.
  * [ ] Learning Steerable Filters for Rotation Equivariant CNNs ([CVPR2018](http://openaccess.thecvf.com/content_cvpr_2018/papers/Weiler_Learning_Steerable_Filters_CVPR_2018_paper.pdf))
  * [ ] 3D Steerable CNNs: Learning Rotationally Equivariant Features in Volumetric Data ([arXiv](https://arxiv.org/abs/1807.02547))
* Attention / Graph
  * [x] Hyperbolic Attention Networks ([OpenReview](https://openreview.net/forum?id=rJxHsjRqFQ), [arXiv](https://arxiv.org/abs/1805.09786), ICLR2019 under review): a paper I do not fully understand due to so much missing knowledge in Hyperbolic geometry. A Hyperblic space embedding seems appealing; However, it seems that this paper does not well explained why it is suitable for attention instead of general neural network representation. Worth more exploration.
  * [ ] Relational Graph Attention Networks ([OpenReview](https://openreview.net/forum?id=Bklzkh0qFm), ICLR2019 under review)
  * [ ] Hierarchical Graph Representation Learning with Differentiable Pooling ([arXiv](https://arxiv.org/abs/1806.08804))
  * [ ] Learning Visual Question Answering by Bootstrapping Hard Attention ([ECCV2018](https://arxiv.org/abs/1808.00300))
* [ ] A New Angle on L2 Regularization ([blog](https://thomas-tanay.github.io/post--L2-regularization/))
* [x] Efficient Annotation of Segmentation Datasets with PolygonRNN++ ([CVPR2018](http://www.cs.toronto.edu/polyrnn/)): very interesting application of existing algorithms (segmentation + RL + GNN), but some details are missing in this conference paper (maybe better in its journal version?). Many engineering details.
* [x] Taskonomy: Disentangling Task Transfer Learning ([CVPR2018 best](http://taskonomy.stanford.edu/)): hard to understand.
* [x] A Low Power, Fully Event-Based Gesture Recognition System ([CVPR2017](https://ieeexplore.ieee.org/document/8100264))
* [x] Hand PointNet: 3D Hand Pose Estimation using Point Sets ([CVPR2018](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ge_Hand_PointNet_3D_CVPR_2018_paper.pdf)): not my area actually. A PointNet application for hand pose regression.
* [x] Visible Machine Learning for Biomedicine ([Cell](https://linkinghub.elsevier.com/retrieve/pii/S0092-8674(18)30719-0) Commentary)

### 2018-09

Our paper `3D Deep Learning from CT Scans Predicts Tumor Invasiveness of Subcentimeter Pulmonary Adenocarcinomas` is accepted by  *[Cancer Research](http://cancerres.aacrjournals.org/content/early/2018/10/02/0008-5472.CAN-18-0696)* (DOI: 10.1158/0008-5472.CAN-18-0696).

### Reading
* 3D Vision
  * [ ] Spherical CNNs ([ICLR2018 best](https://openreview.net/forum?id=Hkbd5xZRb)): this paper is too complicated for me to understand :(
  * [x] Spherical convolutions and their application in molecular modelling ([NIPS2017](https://papers.nips.cc/paper/6935-spherical-convolutions-and-their-application-in-molecular-modelling)): difficult to read for non-native Engish. A good illustration for cubed-sphere grid ([link](http://acmg.seas.harvard.edu/geos/cubed_sphere/CubeSphere_step-by-step.html)).
  * [x] Escape from Cells: Deep Kd-Networks for the Recognition of 3D Point Cloud Models ([ICCV2017](https://arxiv.org/abs/1704.01222))
  * [x] SO-Net: Self-Organizing Network for Point Cloud Analysis ([CVPR2018](https://arxiv.org/abs/1803.04249)): basically a PointNet++ with "SOM" clustering.
  * [x] SPLATNet: Sparse Lattice Networks for Point Cloud Processing ([CVPR2018 oral](https://arxiv.org/abs/1802.08275)): it uses differentiable projection to regular grids (permutohedral lattices), together with sparse convolution for efficiency. However, I have not understood its advantage over set-based networks (e.g., PointNet++). Partial reasons are that I have not understood the advantage of bilateral convolution layer (BCL).
  * [x] Neural 3D Mesh Renderer ([CVPR2018](https://arxiv.org/abs/1711.07566)) ([project page](http://hiroharu-kato.com/projects_en/neural_renderer.html))
    - *NB*: very fancy, very useful, but I have not fully understood the graphics-heavy work. I will renew my understanding further. tl;dr: 3 kinds of parameters can be optimized. `vertices`: [n_vertices, 3 (XYZ)], `textures` [n_faces, texture_size, texture_size, texture_size, 3 (RGB)], and `camera_position` [3]. Besides, `faces` [n_faces, 3 (triangle)] indicates the link of vertices (3 vs make a face), which makes the mesh can be processed like graph (it's graph indeed). `faces` seems can not be diff. The paper uses a Straight-Through Estimator to provide the gradients (for the vertices only, not sure at present; the others should have gradients naturally). 
  * [x] Generating 3D Adversarial Point Clouds ([arXiv](https://arxiv.org/abs/1809.07016)): poorly written.
  * [x] Mining Point Cloud Local Structures by Kernel Correlation and Graph Pooling ([arXiv](https://arxiv.org/abs/1712.06760)): not very insightful. Trivial modification uses too much language. Limited empirical improvements. However, learning visible (point) kernel is a good idea for interpretability in deep pc learning (which needs more exploration further).
  * [x] Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images ([ECCV2018](https://arxiv.org/abs/1804.01654)): though appealing, it needs 3D supervision, which is very different from N3MR.
* [x] Self-Attention Generative Adversarial Networks ([arXiv](https://arxiv.org/abs/1805.08318)): simple yet effective.
* [x] Spectral Normalization Explained ([paper: ICLR2018](https://openreview.net/forum?id=B1QRgziT-)) ([blog](https://christiancosgrove.com/blog/2018/01/04/spectral-normalization-explained.html)): greatly explained. SN means a $W/\sigma(W)$, $\sigma(W)$ denotes the max eigen vector of $W$. Then it provides a simple way to lower the computation.
* [x] Generative adversarial interpolative autoencoding: adversarial training on latent space interpolations encourage convex latent distributions ([arXiv](https://arxiv.org/abs/1807.06650)): an interesting paper, though intuitive.
* [x] Analyzing Inverse Problems with Invertible Neural Networks ([arXiv](https://arxiv.org/abs/1808.04730)): poorly written, hard to read.
* [x] Image Transformer ([ICML2018](https://arxiv.org/abs/1802.05751)): self-attention application to autoregressive models.
* [x] Self-Attention with Relative Position Representations ([NAACL2018](https://arxiv.org/abs/1803.02155)): a short paper, but provides good insight: instead of using pre-defined absolute postion-encoding, it uses learnable relative position embeddings. 
* [x] Universal Transformers ([arXiv](https://arxiv.org/abs/1807.03819)): just a simple modification: add recurrence in Transformers (i.e. sharing weights for multiple layers), plus a trivial ACT (just like my setting in the code ...)
* [x] A radiomics approach to assess tumour-infiltrating CD8 cells and response to anti-PD-1 or anti-PD-L1 immunotherapy: an imaging biomarker, retrospective multicohort study ([LANCET Oncology](https://www.thelancet.com/journals/lanonc/article/PIIS1470-2045(18)30413-3/fulltext)): excellent angle on the usage of radiomics, though methodology is simple, the study is very meaningful and promising. 
* [x] Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples ([ICML2018 best paper](https://arxiv.org/abs/1802.00420))
  - *NB*: a brilliant conference paper like a journal paper (a research article, a review and a comment paper). Well-writen, comprehensive, well-performing. Very insightful. All the 8 pages are very worth reading. However, its journal version could be better (if it exists further), since some techniques proposed seem not well suited in its Case Study section, e.g., the Reparameterization for solving Vanisihing & Exploding Gradients seems not to appear; instead, it was solved by BPDA. Besides, I don't understand why LID appears in the "Gradient Shattering" section, let alone that LID was not circumbented by the 3 main attack techniques proposed. Overall, the paper developped a good story about 3 shields (Shattered Gradients, Stochastic Gradients and Exploding & Vanishing Gradients) and 3 swords (Backward Pass Differentiable Approximation BPDA, Expectation over Transformation EOT and Reparameterization), while one should be very cafeful that the shields & swords are not the whole of the paper. The comments in the discussion are also valuable for future studies.
* [x] Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning ([ICLR2016 -> T-PAMI](https://arxiv.org/abs/1704.03976)):
  - *NB*: good empirical results, elegant solutions. 3 Hyper-parameters: `eplison` (default: 8.0, norm length for (virtual) adversarial training), `num_power_iterations` or `K` (default: 1, the number of power iterations) and `xi` (default: 1e-6, small constant for finite difference). A clean PyTorch implementation [here](https://github.com/lyakaap/VAT-pytorch) but seems with wrong default hyper-p. For the VAT loss only, it needs `K+2` forwards, and `K+1` backwards (my calc is sightly different from the paper).

## 2018-08
My Bayesian month :)

### Reading
* Variantional Inference and Discrete Distribution
  * [x] A Tutorial on Variational Bayesian Inference ([pdf](http://www.orchid.ac.uk/eprints/40/1/fox_vbtut.pdf))
    - *NB*: very clear description on mean field interation, but seems non-trivial on VMP framework. Mean field is something using independant distribution to approximate the whole distribution.
  * [x] Tutorial on Variational Autoencoders ([arXiv](https://arxiv.org/abs/1606.05908))
  * [x] Categorical Reparameterization with Gumbel-Softmax ([ICLR2017](https://openreview.net/forum?id=rkE3y85ee))
  * [x] Learning Latent Permutations with Gumbel-Sinkhorn Networks ([ICLR2018](https://arxiv.org/abs/1802.08665)) 
  * [x] The Humble Gumbel Distribution ([blog](http://amid.fish/humble-gumbel))
* Generative Flow
  * [x] i-RevNet: Deep Invertible Networks ([ICLR2018](https://openreview.net/forum?id=HJsjkMb0Z)): a very interesting paper with numbers of potential applications; but it's not that novel at this time indeed, e.g., highly related to RealNVP and NICE.
  * [x] Glow: Generative Flow with Invertible 1x1 Convolutions ([arXiv](https://arxiv.org/abs/1807.03039)): introduce a trick Conv1x1 (based on Real NVP, Glow:RealNVP::DCGAN:GAN).
  * [x] Density estimation using Real NVP ([ICLR2017](https://arxiv.org/abs/1605.08803)): a **fantastic** paper.
  * [x] Flow-GAN: Combining Maximum Likelihood and Adversarial Learning in Generative Models ([AAAI2018](https://arxiv.org/abs/1705.08868))
  * [x] Normalizing Flows Tutorial ([Part 1](https://blog.evjang.com/2018/01/nf1.html)) ([Part 2](https://blog.evjang.com/2018/01/nf2.html))
  * [x] Improving Variational Inference with Inverse Autoregressive Flow ([arXiv](https://arxiv.org/abs/1606.04934), plus a good [blog](http://bjlkeng.github.io/posts/variational-autoencoders-with-inverse-autoregressive-flows/))
  * [x] NICE: Non-linear Independent Components Estimation ([ICLR2015](https://arxiv.org/abs/1410.8516))
* [x] The Building Blocks of Interpretability ([Distill](https://distill.pub/2018/building-blocks/))
* [x] Sampling Generative Networks ([NIPS2016](https://arxiv.org/abs/1609.04468)): a good paper with bad writing.
* [x] Understanding and Improving Interpolation in Autoencoders via an Adversarial Regularizer ([arXiv](https://arxiv.org/abs/1807.07543))
* [x] Instance Noise: A trick for stabilising GAN training ([blog](https://www.inference.vc/instance-noise-a-trick-for-stabilising-gan-training/))


## 2018-07
A busy month for reproducing [DeepLabv3+](https://github.com/duducheng/deeplabv3p_gluon) and NIPS rebuttal. 

### Reading
* [x] Learning Deep Matrix Representations ([arXiv](https://arxiv.org/abs/1703.01454))
* [x] Graph Memory Networks for Molecular Activity Prediction ([arXiv](https://arxiv.org/abs/1801.02622))
* [x] Weighted Transformer Network for Machine Translation ([OpenReview](https://openreview.net/forum?id=SkYMnLxRW))

## 2018-06
### Study Plan
* [ ] Introduction to Biomedical Imaging 生物医学成像学导论 ([MIC](topics/mic.md))
  * [x] Module 2 CT
  * [ ] Module 3 Ultrasounds
  * [ ] Module 4 MRI
  * [ ] Module 5 PET
* [x] Computational Neuroscience 计算神经科学 ([MIC](topics/mic.md))
  * [x] week1 - Basic neuronal models
  * [x] week2 - Synapse and channel dynamics

### Reading
* [x] A mixed-scale dense convolutional neural network for image analysis ([PNAS](http://www.pnas.org/content/115/2/254))
* [ ] Suggestive Annotation: A Deep Active Learning Framework for Biomedical Image Segmentation ([MICCAI2017](https://arxiv.org/abs/1706.04737))
* [ ] In Silico Labeling: Predicting Fluorescent Labels in Unlabeled Images ([Cell](https://www.cell.com/cell/fulltext/S0092-8674(18)30364-7))
* [ ] A Tutorial on Variational Bayesian Inference ([pdf](http://www.orchid.ac.uk/eprints/40/1/fox_vbtut.pdf))
* [ ] Tutorial on Variational Autoencoders ([arXiv](https://arxiv.org/abs/1606.05908))
* [ ] World Models ([website](https://worldmodels.github.io/)) ([arXiv](https://arxiv.org/abs/1803.10122))
* [ ] The Building Blocks of Interpretability ([Distill](https://distill.pub/2018/building-blocks/))
* [x] Using Artiﬁcial Intelligence to Augment Human Intelligence ([Distill](https://distill.pub/2017/aia/))
* [ ] Memory-Efficient Implementation of DenseNets ([arXiv](https://arxiv.org/abs/1707.06990))
* [x] A Comparison of MCC and CEN Error Measures in Multi-Class Prediction ([PLOS ONE](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3414515/))
* [x] Fully Convolutional Networks for Semantic Segmentation ([CVPR2015](https://arxiv.org/abs/1411.4038))
* [x] Pyramid Scene Parsing Network ([CVPR2017](https://arxiv.org/abs/1411.4038))
* [x] Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation (a.k.a DeepLab v3+) ([arXiv](https://arxiv.org/abs/1802.02611))
* [x] Enhancing The Reliability of Out-of-distribution Image Detection in Neural Networks (a.k.a ODIN) ([ICLR2018](https://arxiv.org/abs/1706.02690))
* [x] Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery ([IPMI2017](https://arxiv.org/abs/1703.05921))
* [x] Anomaly Detection using One-Class Neural Networks ([KDD2018](https://arxiv.org/abs/1802.06360))
* [x] Thoughts on "mixup: Data-Dependent Data Augmentation" ([blog](http://www.inference.vc/mixup-data-dependent-data-augmentation/))
* 3D Vision & Point clouds
  * [x] RGBD Datasets: Past, Present and Future ([arXiv](https://arxiv.org/abs/1604.00999))
  * [x] 3D ShapeNets: A Deep Representation for Volumetric Shapes (the ModelNet dataset paper) ([CVPR2015](https://arxiv.org/abs/1406.5670))
* Few Shot
  * [x] Learning to Compare: Relation Network for Few-Shot Learning ([CVPR2018](https://arxiv.org/abs/1711.06025))
  * [x] Low-shot learning with large-scale diffusion ([CVPR2018](https://arxiv.org/abs/1706.02332))
  * [x] Few-Shot Image Recognition by Predicting Parameters from Activations ([CVPR2018](https://arxiv.org/abs/1706.03466))


## 2018-05
Still a very busy month for preparing papers.

### Reading
* EGFR
  * [x] Somatic mutations drive distinct imaging phenotypes in lung cancer ([Cancer Research](http://cancerres.aacrjournals.org/content/early/2017/05/31/0008-5472.CAN-17-0122))
  * [x] Defining a Radiomic Response Phenotype: A Pilot Study using targeted therapy in NSCLC ([Scientific Reports](https://www.nature.com/articles/srep33860))
  * [x] Non–Small Cell Lung Cancer Radiogenomics Map Identifies Relationships between Molecular and Imaging Phenotypes with Prognostic Implications ([Radiology](https://pubs.rsna.org/doi/10.1148/radiol.2017161845?url_ver=Z39.88-2003&rfr_id=ori%3Arid%3Acrossref.org&rfr_dat=cr_pub%3Dpubmed))
  * [x] Radiomic Features Are Associated With EGFR Mutation Status in Lung Adenocarcinomas ([Clinical Lung Cancer](https://www.sciencedirect.com/science/article/pii/S1525730416300055?via%3Dihub))
* [ ] World Models ([website](https://worldmodels.github.io/)) ([arXiv](https://arxiv.org/abs/1803.10122))
* [ ] The Building Blocks of Interpretability ([Distill](https://distill.pub/2018/building-blocks/))
* [ ] Using Artiﬁcial Intelligence to Augment Human Intelligence ([Distill](https://distill.pub/2017/aia/))
* Dynamic Graph CNN for Learning on Point Clouds ([arXiv](https://arxiv.org/abs/1801.07829))

## 2018-04
A very busy month for preparing papers.

### Reading
* Interpretability
  * [x] Learning with Rejection ([page](https://cs.nyu.edu/~mohri/pub/rej.pdf))
  * [x] Predict Responsibly: Increasing Fairness by Learning To Defer ([arXiv](https://arxiv.org/abs/1711.06664))  
* PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space ([NIPS](https://arxiv.org/abs/1706.02413))
* PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation ([CVPR](https://arxiv.org/abs/1612.00593))

## 2018-03
### Study Plan
* [ ] lunglab-keras ([MIC](topics/mic.md))
* [x] Pointer Network in PyTorch and plus ([AML](topics/advanced_ml.md))
* [ ] Try radiomics and genomics ([MIC](topics/mic.md))

### Reading
* MIC
  * [x] Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs ([JAMA](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/45732.pdf))
  * [x] Dermatologist-level classification of skin cancer with deep neural networks ([Nature](https://www.nature.com/articles/nature21056))
  * [x] Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning ([Cell](http://www.cell.com/cell/abstract/S0092-8674(18)30154-5))
  * [x] Scalable and accurate deep learning for electronic health records ([arXiv](https://arxiv.org/abs/1801.07860))
  * [x] CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning ([arXiv](https://arxiv.org/abs/1711.05225))
  * [x] Automated Pulmonary Nodule Detection via 3D ConvNets with Online Sample Filtering and Hybrid-Loss Residual Learning ([arXiv](https://arxiv.org/abs/1708.03867))
  * [x] DeepLung: 3D Deep Convolutional Nets for Automated Pulmonary Nodule Detection and Classification ([arXiv](https://arxiv.org/abs/1709.05538))
  * [x] A Survey on Deep Learning in Medical Image Analysis ([arXiv](https://arxiv.org/abs/1702.05747))
  * [x] Decoding tumour phenotype by noninvasive imaging using a quantitative radiomics approach ([Nature Comm](https://www.nature.com/articles/ncomms5006))
  * [x] Computational Radiomics System to Decode the Radiographic Phenotype ([Cancer Research](http://cancerres.aacrjournals.org/content/77/21/e104.full-text.pdf))
  * [ ] Suggestive Annotation: A Deep Active Learning Framework for Biomedical Image Segmentation ([arXiv](https://arxiv.org/abs/1706.04737))
* MIL
  * [x] Graph Attention Networks ([arXiv](https://arxiv.org/abs/1710.10903))
  * [x] Deep learning of feature representation with multiple instance learning for medical image analysis ([ICASSP](http://ieeexplore.ieee.org/document/6853873/)): bad writing, trival idea, non-sense to read.
  * [x] Deep Multi-instance Networks with Sparse Label Assignment for Whole Mammogram Classification ([arXiv](https://arxiv.org/abs/1612.05968)) ([code](https://github.com/wentaozhu/deep-mil-for-whole-mammogram-classification))
  * [x] Multi-Instance Deep Learning: Discover Discriminative Local Anatomies for Bodypart Recognition: trival writing, same idea as DSB2017 THU solution.
  * [x] Learning from Experts: Developing Transferable Deep Features for Patient-Level Lung Cancer Prediction ([MICCAI](https://link.springer.com/chapter/10.1007/978-3-319-46723-8_15)): very very bad writing, hard to find the details of the model / training / data. 
  * [x] Attention-based Deep Multiple Instance Learning ([ICML2018](https://arxiv.org/abs/1802.04712): !)
  * [x] Attention Solves Your TSP ([arXiv](https://arxiv.org/abs/1803.08475))
  * [ ] Multiple-Instance Learning for Medical Image and Video Analysis ([IEEE](http://ieeexplore.ieee.org/document/7812612/))
  * [ ] Revisiting Multiple Instance Neural Networks ([arXiv](https://arxiv.org/abs/1610.02501))
* [x] An introduction to ROC analysis ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S016786550500303X))
* [ ] Adaptive Computation Time for Recurrent Neural Networks ([arXiv](https://arxiv.org/abs/1603.08983))
* [ ] Spatially Adaptive Computation Time for Residual Networks ([arXiv](https://arxiv.org/abs/1612.02297))
* [ ] A mixed-scale dense convolutional neural network for image analysis ([PNAS](http://www.pnas.org/content/115/2/254))
* [x] mixup: Beyond Empirical Risk Minimization ([arXiv](https://arxiv.org/abs/1710.09412))
* Hyper Networks ([blog](http://blog.otoro.net/2016/09/28/hyper-networks/))


## 2018-02
### Study Plan
* [ ] 生物医学成像学导论 ([MIC](topics/mic.md))
    * [ ] Module 2 CT
* [ ] lunglab-keras ([MIC](topics/mic.md))
* [ ] Pointer Network in PyTorch ([AML](topics/advanced_ml.md))

### Reading
* Set / Points
  * [x] Deep Learning with Sets and Point Clouds ([arXiv](https://arxiv.org/abs/1611.04500)) (another paper: Deep Sets)
  * [x] Order Matters: Sequence to sequence for sets ([arXiv](https://arxiv.org/abs/1511.06391))
  * [x] Neural Message Passing for Quantum Chemistry ([arXiv](https://arxiv.org/abs/1704.01212))  
  * [x] PointCNN ([arXiv](https://arxiv.org/abs/1801.07791))
* Interpretability
  * [x] Learning Deep Features for Discriminative Localization (a.k.a CAM) ([arXiv](https://arxiv.org/abs/1512.04150))
  * [x] Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization ([arXiv](https://arxiv.org/abs/1610.02391))
  * [x] Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning ([arXiv](https://arxiv.org/abs/1506.02142))
  * A Baseline for Detecting Misclassified and Out-of-Distribution Examples in Neural Networks ([arXiv](https://arxiv.org/abs/1610.02136))
* [x] Fraternal Dropout ([arXiv](https://arxiv.org/abs/1711.00066))
* [ ] A Tutorial on Variational Bayesian Inference ([pdf](http://www.orchid.ac.uk/eprints/40/1/fox_vbtut.pdf))
* [ ] Tutorial on Variational Autoencoders ([arXiv](https://arxiv.org/abs/1606.05908))

## 2018-01
### MyWeekly
  * [Reinforcement Learning Demystified](weekly/RL_demystified.pdf)
### Study Plan
* [x] ADLxMLDS ([AML](topics/advanced_ml.md))
    * [x] RL (Deep RL + Deep RL2 + Imitation Learning)
    * [x] 5 Attention 
    * [x] 6 Special Networks
    * [x] 7 Tips
    * [x] 10 GAN 
    * [x] 11 GAN for Seq 
    * [x] 12 More GAN 
* [x] CS231n 2017 ([AML](topics/advanced_ml.md))
    * [x] Lecture 12: Visualizing and Understanding ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture12.pdf))
    * [x] Lecture 16: Adversarial Examples and Adversarial Training ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture16.pdf))
* [x] Atari Game Playing ([AML](topics/advanced_ml.md))
* [ ] Fundamentals of Medical Imaging ([MIC](topics/mic.md))
    * [ ] Chapter 1 
    * [ ] Chapter 2 X-rays
    * [ ] Chapter 3 CT  
* [ ] 生物医学成像学导论 ([MIC](topics/mic.md))
    * [ ] Module 2 CT
* [ ] lunglab-keras ([MIC](topics/mic.md))
### Reading
* Convolutional Invasion and Expansion Networks for Tumor Growth Prediction ([IEEE](http://ieeexplore.ieee.org/document/8110658/)): very simple algorithm, even some bad design... but good at bio-medical explanation. Good feature engineering. 
* Runtime Neural Pruning ([NIPS](https://nips.cc/Conferences/2017/Schedule?showEvent=9006))
* [x] Attention Is All You Need ([arXiv](https://arxiv.org/abs/1706.03762)): 
  - *NB*: very impressive work. Seems to be inspired by Conv Seq2Seq, but more general. 3 key points: 
  - 1) variable-length inputs can be also processed in "attention": softmax(KT.dot(Q)).dot(V) => fix size `d`
  - 2) seq2seq is indeed `encoder output` + `decoder scoring per step`! Can be parallel implemented with masking (seems to come from conv seq2seq?)
  - 3) RNN / Conv architecture can still be used, espeically in decoder
* [x] One Model To Learn Them All ([arXiv](https://arxiv.org/abs/1706.05137)): Xception+Transformer+Sparse MoE in one network. Too big title.
* [x] Convolutional Sequence to Sequence Learning ([arXiv](https://arxiv.org/abs/1705.03122)): Transformer paper seems to absort all of its goodness... 
* [x] Evaluate the Malignancy of Pulmonary Nodules Using the 3D Deep Leaky Noisy-or Network ([arXiv](https://arxiv.org/abs/1711.08324)): DSB2017 1st paper.
* [x] On Bayesian Deep Learning and Deep Bayesian Learning ([YouTube](https://www.youtube.com/watch?v=LVBvJsTr3rg))
* [x] Pointer Networks ([arXiv](https://arxiv.org/abs/1506.03134))
* 动手学深度学习第十三课：正向传播、反向传播和通过时间反向传播 ([YouTube](https://www.youtube.com/watch?v=xPFbbLxegH0&list=PLLbeS1kM6teJqdFzw1ICHfa4a1y0hg8Ax&index=13))
* 动手学深度学习第十六课：词向量（word2vec）([YouTube](https://www.youtube.com/watch?v=C4X0Cb5_FSo&index=16&list=PLLbeS1kM6teJqdFzw1ICHfa4a1y0hg8Ax))

## 2017-12
### Study Plan
* [ ] CS231n 2017 ([AML](topics/advanced_ml.md))
  * [ ] Lecture 12: Visualizing and Understanding ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture12.pdf))
  * [x] Lecture 13: Generative Models ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture13.pdf))
  * [x] Lecture 14: Deep Reinforcement Learning ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture14.pdf))
  * [x] Lecture 15: Efficient Methods and Hardware for Deep Learning ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture15.pdf))
  * [ ] Lecture 16: Adversarial Examples and Adversarial Training ([slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture16.pdf))
* [ ] Fundamentals of Medical Imaging ([MIC](topics/mic.md))
  * [ ] Chapter 1 
  * [ ] Chapter 2 X-rays
* [x] 生物医学成像学导论 ([MIC](topics/mic.md))
  * [x] Module 1 X-rays
### Reading
* An Overview of Multi-Task Learning in Deep Neural Networks ([blog](http://ruder.io/multi-task/)): Hard to say very good review, but mentioned a lot. **"Recent approaches have thus looked towards learning what to share"**.
* Deep Learning: Practice and Trends (NIPS 2017 Tutorial) ([YouTube](https://www.youtube.com/watch?v=YJnddoa8sHk)) ([slide](https://docs.google.com/presentation/d/e/2PACX-1vQMZsWfjjLLz_wi8iaMxHKawuTkdqeA3Gw00wy5dBHLhAkuLEvhB7k-4LcO5RQEVFzZXfS6ByABaRr4/pub?slide=id.p))
* Towards automatic pulmonary nodule management in lung cancer screening with deep learning ([Scientific Reports](https://www.nature.com/articles/srep46479))
* Special Deep Learning Structure of [MLDS](http://speech.ee.ntu.edu.tw/~tlkagk/courses_MLDS17.html)
  * Spatial Transformer Layer ([slide](http://speech.ee.ntu.edu.tw/~tlkagk/courses/MLDS_2017/Lecture/Special%20Structure%20(v6).pdf))
  * Highway Network & Grid LSTM ([slide](http://speech.ee.ntu.edu.tw/~tlkagk/courses/MLDS_2017/Lecture/Special%20Structure%20(v6).pdf))


## 2017-11
* Time-series Extreme Event Forecasting with Neural Networks at Uber ([ICML Time Series Workshop](http://roseyu.com/time-series-workshop/submissions/TSW2017_paper_3.pdf))
* Deep Forecast: Deep Learning-based Spatio-Temporal Forecasting ([arXiv](https://arxiv.org/abs/1707.08110)): ICML Time Series Workshop, yet very simple work
* Neural Turing Machines ([arXiv](https://arxiv.org/abs/1410.5401)): very inspirational
* Dynamic Routing Between Capsules ([arXiv](https://arxiv.org/abs/1710.09829))
* Show, Attend and Tell: Neural Image Caption Generation with Visual Attention ([arXiv](https://arxiv.org/abs/1502.03044))
* Computerized detection of lung nodules through radiomics ([Medical Physics](http://onlinelibrary.wiley.com/doi/10.1002/mp.12331/abstract;jsessionid=749B7153927F5A6F42C3AE5BF9CF3B62.f04t01))

## 2017-10
* MyWeekly
  * [Modern CNN Design](weekly/Modern_CNN_Design.pdf)
* ["天池医疗AI大赛[第一季]：肺部结节智能诊断"](https://tianchi.aliyun.com/competition/introduction.htm?spm=5176.100067.5678.1.4c5fd3b5Y0gzo&raceId=231601) (Team: `LAB518-CreedAI`, rank: 3 / 2887)
* Identity Mappings in Deep Residual Networks (a.k.a. ResNet-1001 / ResNet200) ([arXiv](https://arxiv.org/abs/1603.05027))
* ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices ([arXiv](https://arxiv.org/abs/1707.01083))
* Squeeze-and-Excitation Networks ([arXiv](https://arxiv.org/abs/1709.01507))
* Deep Convolutional Neural Networks with Merge-and-Run Mappings ([arXiv](https://arxiv.org/abs/1611.07718))
* Interleaved Group Convolutions for Deep Neural Networks ([arXiv](https://arxiv.org/abs/1707.02725))

## 2017-09
* WSISA: Making Survival Prediction from Whole Slide Histopathological Images ([CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhu_WSISA_Making_Survival_CVPR_2017_paper.pdf))
  - *NB*: it's suitable for small data cases while large data size (large per case). It use KMeans in the paper for patch level clustering, train separate models and use the prediction as features. Not beautiful solution.
* Feature Pyramid Networks for Object Detection ([arXiv](https://arxiv.org/abs/1612.03144))
  - *NB*: clean top results with single beautiful. Some so-called bells and whistles that have not been tried in the paper: iterative regression [9], hard negative mining [35], context modeling [16], strong data augmentation [22], etc.
* Xception: Deep Learning with Depthwise Separable Convolutions ([arXiv](https://arxiv.org/abs/1610.02357))
* Aggregated Residual Transformations for Deep Neural Networks (a.k.a. ResNeXt) ([arXiv](https://arxiv.org/abs/1611.05431))
  * *NB*: Group Conv, interpreted as "Network in Neuron".

## 2017-08
* Internship in Tencent Social Ads Team @Shenzhen
* Show and Tell: A Neural Image Caption Generator ([arXiv](https://arxiv.org/abs/1411.4555))
* Dual Path Networks ([arXiv](https://arxiv.org/abs/1707.01629))
* Densely Connected Convolutional Networks ([arXiv](https://arxiv.org/abs/1608.06993))
* VoxResNet: Deep Voxelwise Residual Networks for Volumetric Brain Segmentation ([arXiv](https://arxiv.org/abs/1608.05895)) ([project page](http://appsrv.cse.cuhk.edu.hk/~hchen/research/seg_brain.html))

## 2017-07
* Busy month for ["天池医疗AI大赛[第一季]：肺部结节智能诊断"](https://tianchi.aliyun.com/competition/introduction.htm?spm=5176.100067.5678.1.4c5fd3b5Y0gzo&raceId=231601) (Team: `LAB518-CreedAI`, Season 1 rank: 5 / 2887)
* Conditional Random Fields as Recurrent Neural Networks ([arXiv](https://arxiv.org/abs/1502.03240))
* Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer ([arXiv](https://arxiv.org/abs/1701.06538))
* Accurate Pulmonary Nodule Detection in Computed Tomography Images Using Deep Convolutional Neural Networks ([arXiv](https://arxiv.org/abs/1706.04303))
* Dilated Residual Networks ([arXiv](https://arxiv.org/abs/1705.09914))
* Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour ([arXiv](https://arxiv.org/abs/1706.02677))

## 2017-06
* Multilevel Contextual 3-D CNNs for False Positive Reduction in Pulmonary Nodule Detection ([IEEE](http://ieeexplore.ieee.org/document/7576695/))
* Wide Residual Networks ([arXiv](https://arxiv.org/abs/1605.07146))
* D. Silver Lecture 1: Introduction to Reinforcement Learning ([UCL](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html))
* CS231n ([Stanford](http://vision.stanford.edu/teaching/cs231n/syllabus.html)): Lecture 2 (Linear classification I), Lecture 3 (Linear classification II), Lecture 4 (Backpropagation), Lecture 5 (Training 1), Lecture 6 (Training 2), Lecture 7 (ConvNets), Lecture 10 (RNN). 
  * Till now, finished all CS231n lectures (vidoes), notes and some readings.
* DL book RNN chapter ([link](http://www.deeplearningbook.org/contents/rnn.html))

## 2017-05
* SSD: Single Shot MultiBox Detector ([arXiv](https://arxiv.org/abs/1512.02325))
* Attention and Augmented Recurrent Neural Networks ([Distill](http://distill.pub/2016/augmented-rnns/))
* R-FCN: Object Detection via Region-based Fully Convolutional Networks ([arXiv](https://arxiv.org/abs/1605.06409))
* Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks ([arXiv](https://arxiv.org/abs/1506.01497))
* Training Region-based Object Detectors with Online Hard Example Mining ([arXiv](https://arxiv.org/abs/1604.03540))
* Deep Learning, NLP, and Representations ([blog](http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/))
* CS231n ([Stanford](http://vision.stanford.edu/teaching/cs231n/syllabus.html)): Lecture 12 (Deep Learning Tools), 14 (Videos, Unsupervised learning), 15 (Invited Talk: Jeff Dean)

## 2017-04
* MyWeekly
  * [Restricted Boltzmann Machines](weekly/rbm.pdf)
* Recurrent Dropout without Memory Loss ([arXiv](https://arxiv.org/abs/1603.05118))
  * *NB*: simple, implemented in TensorFlow. It archieves similar (if not better) results in LSTMs than Gal 2015. In short, it drops the recurrent updates but not the recurrent connections, it allows per-step dropout. Moon et al. 2015 drop the recurrent update and connections, with per-sequence dropout, which allows long-term learning but forget the long-term memory in inference.
* CS231n ([Stanford](http://vision.stanford.edu/teaching/cs231n/syllabus.html)): Lecture 8 (Detection), 13 (Segmentation and Attention)
* The One Hundred Layers Tiramisu: Fully Convolutional DenseNets for Semantic Segmentation ([arXiv](https://arxiv.org/abs/1611.09326)): there are some typos in Table2.
* Multi-Scale Context Aggregation by Dilated Convolutions ([arXiv](https://arxiv.org/abs/1511.07122)), a.k.a "Dilated-8"
* A Simple Way to Initialize Recurrent Networks of Rectified Linear Units ([arXiv](https://arxiv.org/abs/1504.00941)), a.k.a "IRNN"
* Convolutional LSTM Network: A Machine Learning Approach for Precipitation Nowcasting ([arXiv](https://arxiv.org/abs/1506.04214))
* Understanding Convolutions ([blog](http://colah.github.io/posts/2014-07-Understanding-Convolutions/))
* Groups & Group Convolutions ([blog](http://colah.github.io/posts/2014-12-Groups-Convolution/))
* Deconvolution and Checkerboard Artifacts ([Distill](http://distill.pub/2016/deconv-checkerboard/))
* Calculus on Computational Graphs: Backpropagation ([blog](http://colah.github.io/posts/2015-08-Backprop/))
* Neural Networks, Manifolds, and Topology ([blog](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/))

## 2017-03
* MyWeekly
  * [On Time Series: DTW, Viz of RNN and Clockwalk RNN Revisiting](weekly/dtw_vizrnn_cwrnn.pdf)
  * [On Time Series (2): Echo State Network and Temporal Kernel RNN](weekly/tkrnn_esn.pdf)
  * [On Time Series (3): Phased LSTM and STL](weekly/plstm_stl.pdf)
  * [On Time Series (4): Fast weights](weekly/fast_weights.pdf)
* [STL: A Seasonal-Trend Decomposition Procedurue Base on Loess](notes/stl.md) ([link](http://www.wessa.net/download/stl.pdf))
* [Temporal-Kernel Recurrent Neural Networks](notes/tkrnn.md) ([ScienceDirect](http://www.sciencedirect.com/science/article/pii/S0893608009002664))
* [REVISIT] A Clockwork RNN ([arXiv](https://arxiv.org/abs/1402.3511)) (non-official [code](https://github.com/braingineer/ikelos/blob/master/ikelos/layers/cwrnn.py))
* [Visualizing and Understanding Recurrent Networks](notes/viz_rnn.md) ([arXiv](https://arxiv.org/abs/1506.02078))
* Neural Networks for Time Series Prediction ([CMU](https://www.cs.cmu.edu/afs/cs/academic/class/15782-f06/slides/timeseries.pdf)): super old lecture, even not covering LSTM. While still useful, especially it talks many concepts of time series analysis in engineering guys' eyes (rather than statstician's), though some of them are too "Digital Signal Processing" that make my undergraduate "Signal & System" concepts revive :)
* Dynamic Time Wrapping
  * *NB*: Yet another example of dynamic programming in sequence modeling, I think CTC's idea benifits from DTW (and absolutely HMM).
  * K Nearest Neighbors & Dynamic Time Warping ([code](https://github.com/markdregan/K-Nearest-Neighbors-with-Dynamic-Time-Warping)): clean code, using DTW and kNN for Human Activity Recognition. It clearly shows the esential idea of DTW, and the code is well factored. But something funny is that, in this code, not all the imports are valid, you should import something manualy before running the code.
  * Everything you know about Dynamic Time Warping is Wrong ([link](http://wearables.cc.gatech.edu/paper_of_week/DTW_myths.pdf)): gives some highlights of using and researching DTW (about 10 years ago 😐). The wording of this paper is very sharp. 3 chaims: 1) fix length doesn't hurt 2) narrow band doesn't hurt 3) speeding up DTW with tight lower bound is pointless.
* MC and MCMC from Probabilistic Graphical Models Eric Xing ([CMU](http://www.cs.cmu.edu/~epxing/Class/10708-14/lecture.html)): Lecture 16-18.
  * *NB*: great review for sampling based inference. MC: naive, rejection sampling, importance sampling. MCMC: Metropolis-Hasting, Gibbs, collapsed (Rao-Blackwellised) Gibbs, slice sampling, Reversible Jump MCMC (RJMCMC). RJMCMC is really non-trivial, which I didn't fully understand. It's a MCMC to jump among models' space, designed without detailed balance, while stationary.
* Probabilistic Programming & Bayesian Methods for Hackers ([link](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)) ([code](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers))
* Probabilistic Graphical Models 3: Learning ([Coursera](https://www.coursera.org/learn/probabilistic-graphical-models-3-learning/))
* [Forecasting at Scale](notes/prophet.md) ([Prophet](https://facebookincubator.github.io/prophet/))
* Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift ([arXiv](https://arxiv.org/abs/1502.03167)): simple math but full of brilliant ideas and tricks. ([code](https://gist.github.com/tomokishii/0ce3bdac1588b5cca9fa5fbdf6e1c412): good demenstration of using "global" moment and `ewa`)
* Layer Normalization ([arXiv](https://arxiv.org/abs/1607.06450)): even simpler principle, good for RNN but, worse than BN for CNN.
* [Phased LSTM: Accelerating Recurrent Network Training for Long or Event-based Sequences](notes/plstm.md) ([NIPS](https://papers.nips.cc/paper/6310-phased-lstm-accelerating-recurrent-network-training-for-long-or-event-based-sequences.pdf)) (TensorFlow [implement](https://github.com/Enny1991/PLSTM), Keras [implement](https://github.com/fferroni/PhasedLSTM-Keras), both good and clear.)
* Using Fast Weights to Attend to the Recent Past ([arXiv](https://arxiv.org/abs/1610.06258)) (TensorFlow [implement](https://github.com/ajarai/fast-weights)): Very simple math, and easy enough to implement, but it seems lots of physiology background. This paper is another trial aimed to beat LSTM. Fast weights (`FW`) based on IRNN, works well on the mentioned task. The `FW` can be regarded as something to be "memorised" during the step update. I found papers of Hinton are usually recondite. (maybe Canadian English?)
* Neural Networks for Machine Learning by Geoffrey Hinton ([Coursera](https://www.coursera.org/learn/neural-networks/)): Finally finished. Good review for neural network approaches. Absolutely not a first course. It's a very course that can inspire you a lot if you've already known; but if you haven't known something mentioned in the course, it can be very hard for you to fully understand without other materials.
* [MLaPP](https://www.cs.ubc.ca/~murphyk/MLbook/): Chapter 27.7 Restricted Boltzman machines (RBMs)

## 2017-02
Reprise from the Spring Festival 😐
* A Critical Review of Recurrent Neural Networks for Sequence Learning ([arXiv](https://arxiv.org/abs/1506.00019))
  * *NB*: there is not any new insight, while good to reflash some idea; it talks about vanilla RNN, LSTM, BRNN and a little bit NTM, and introduce some application, with emphasis on NLP.
* [Connectionist Temporal Classification: Labelling Unsegmented Sequence Data with Recurrent Neural Networks](notes/ctc.md) ([ICML](http://www.cs.toronto.edu/~graves/icml_2006.pdf))
* Bootstrap Methods for Time Series ([link](https://www.kevinsheppard.com/images/0/0a/Kreiss_and_lahiri.pdf))
  * *NB*: Though the article regards itself as a simple intro, it seems too theoretical for me. It provides some good review of bootstrap for time series, remember 1. generate series for AR like model; 2. block bootstrap; 3. markov chain bootstrap; 4. frequency domain by DFT 5. other mixtures.
* Hidden Markov Model
  * Markov model and HMM by mathematicalmonk ([YouTube](https://www.youtube.com/watch?v=7KGdE2AK_MQ&list=PLD0F06AA0D2E8FFBA&index=95)): covering forward-backward and Viterbi.
  * [统计学习方法](https://book.douban.com/subject/10590856/) 第10章 隐马尔可夫模型
* Conditional Random Field
  * Lecture from CMU ([YouTube](https://www.youtube.com/watch?v=B1nl8fLgKMk&t=1748s))
  * [统计学习方法](https://book.douban.com/subject/10590856/) 第11章 条件随机场
* Monte Carlo by mathematicalmonk ([YouTube](https://www.youtube.com/watch?v=AadKNJU1-lk&list=PLD0F06AA0D2E8FFBA&index=1275)): covering importance sampling, Smirnov transform and rejection sampling.
* MCMC by mathematicalmonk ([YouTube](https://www.youtube.com/watch?v=7KGdE2AK_MQ&list=PLD0F06AA0D2E8FFBA&index=95)): covering ergodic theorem and Metropolis, very gentle and intuitive.
* Probabilistic Programming & Bayesian Methods for Hackers ([code](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers))
  * *NB*: Great book, about practical Bayesian modeling and PyMC3.
* Variation Inference from Probabilistic Graphical Models Eric Xing ([CMU](http://www.cs.cmu.edu/~epxing/Class/10708-14/lecture.html)): Lecture 13-15.
  * *NB*: really good (somehow advanced) introduction to VI: loopy belief Propagation, mean field approximation, and general variational principles (solve problem in optimization fashion with dual form of function). The principles part is really abstract, but at least I got the idea. A brief to LDA is also presented in Lecture 15.
* Bayesian optimization by Nando de Freitas ([YouTube](https://www.youtube.com/watch?v=vz3D36VXefI))
  * *NB*: Great intro to Bayesian opt, in 10 minutes you get the whole picture, and the rest tells some details.

## 2017-01
* MyWeekly
  * [Advanced Linear Regression](weekly/Advanced_Linear_Regression.pdf)
* Online Kernel Ridge
  * Online regression with kernel ([link](https://gtas.unican.es/files/pub/ch21_online_regression_with_kernels.pdf))
    * *NB*: Indeed a good review for this family of approach, which really hits my ideas (how HAVE they "copied" my idea T_T). However, this paper put strong emphasis on Signal Processing, which is not suit for Machine Learning mind.
  * Local online kernel ridge regression for forecasting of urban travel times ([ScienceDirect](http://www.sciencedirect.com/science/article/pii/S0968090X14001648))
* Gaussian Processes: A Quick Introduction ([arXiv](https://arxiv.org/abs/1505.02965))
* CS229 Lecture note of Gaussian Process ([Stanford](http://cs229.stanford.edu/section/cs229-gaussian_processes.pdf))
* Bayesian Linear Regression ([YouTube](https://www.youtube.com/watch?v=dtkGq9tdYcI)): A very good deduction, while use not commonly used symbols.
* Recursive Least Square (RLS) ([OTexts](https://www.otexts.org/1582))
* [Time Series Blogs by QuantStart](https://www.quantstart.com/articles/#time-series-analysis)
  * *NB*: These blogs are quite good, covering lots of concepts on Time Series Analysis. While it focus on the representation level, not on the learning level, which means there is less content in these blogs talking about parameter estimate. Anyway, good introduction to ARIMA, GARCH, Kalman Filter and HMM on Time Series.
* Understanding the Basis of the Kalman Filter Via a Simple and Intuitive Derivation ([IEEE](http://ieeexplore.ieee.org/document/6279585/)): Lecture note. It's quite intuitive to understand the "basis" of Kalman Filter, as titled.
* [MLaPP](https://www.cs.ubc.ca/~murphyk/MLbook/): Chapter 18 State Space Model
* Probabilistic Graphical Models 2: Inference ([Coursera](https://www.coursera.org/learn/probabilistic-graphical-models-2-inference/))
* [Probabilistic Graphical Models: Principles and Techniques](http://pgm.stanford.edu/): Chapter 9, 10, 11, 13 (selected sections)

## 2016-12
* Spectral Clustering
  * On Spectral Clustering: Analysis and an algorithm ([NIPS](http://ai.stanford.edu/~ang/papers/nips01-spectral.pdf))
  * Spectral Clustering Tutorial Series by Chieu from NEU ([YouTube](https://www.youtube.com/playlist?list=PLdk2fd27CQzT7opzoGHvqDuDbltozWn7O)): Good but too trivial
  * Implement the Gaussian Mixture Models ([notebooks](https://github.com/duducheng/clustering))
* [统计学习方法](https://book.douban.com/subject/10590856/) 第9章 EM算法及其推广

## 2016-11

* MyWeekly
  * [Recipe of Gradient Descent](weekly/Recipe_Gradient_Descent.pdf)
  * [Brief Intro to Variational Inference (Minimal Statistics Background)](weekly/Intro_Variational_Inference.pdf)
* Optimization on Neural Networks
  * How to make the learning go faster by Geoffrey Hinton ([Coursera](https://www.coursera.org/learn/neural-networks/): Week 6)
  * An overview of gradient descent optimization algorithms ([blog](http://sebastianruder.com/optimizing-gradient-descent/))
  * CS231n Course Notes on gradient based optimization ([Stanford](http://cs231n.github.io/neural-networks-3/))
* [REVISIT] Convolution for Neural Networks
  * Convolution arithmetic tutorial ([blog](http://deeplearning.net/software/theano_versions/dev/tutorial/conv_arithmetic.html#transposed-convolution-arithmetic))
  * Conv Nets: A Modular Perspective ([blog](http://colah.github.io/posts/2014-07-Conv-Nets-Modular/))
* Probabilistic Graphical Models 1: Representation ([Coursera](https://www.coursera.org/learn/probabilistic-graphical-models/))
* [Probabilistic Graphical Models: Principles and Techniques](http://pgm.stanford.edu/): Chapter 1, 2, 3, 5, 6
  * *NB*: I read the Chinese Version ([概率图模型：原理与技术](http://www.tup.tsinghua.edu.cn/bookscenter/book_03992101.html)), quite good if you are taking the course (and you are Chinese of course); if not, there will be something confusing in the translation version. Anyway, great thanks to the effort of Prof. Wang and Prof. Han
* Implement the Gaussian Mixture Models ([code](https://github.com/rushter/MLAlgorithms/blob/master/mla/gaussian_mixture.py)) ([notebooks](https://github.com/duducheng/clustering))
* Visual Information Theory ([blog](https://colah.github.io/posts/2015-09-Visual-Information/))
* Towards my research
  * Two Machine Learning Approaches for Short-Term Wind Speed Time-Series Prediction ([IEEE](http://ieeexplore.ieee.org/document/7091914/))
  * Forecasting day ahead electricity spot prices: The impact of the EXAA to other European electricity markets ([arXiv](https://arxiv.org/abs/1501.00818))



## 2016-10
* MyWeekly
  * [More on RNNs](weekly/More_on_RNNs.pdf)
  * [Thoughts on Wavenet](weekly/Thoughts_on_Wavenet.pdf)
  * [RNN and LSTM](weekly/RNN-LSTM.pdf)
  * [Attention](weekly/Attention.pdf)
* Topics on RNN
  * [REVISIT] Understanding LSTM Networks ([blog](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)) ([code](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/udacity/6_lstm.ipynb))
    - *NB*: The code from Udacity Deep Learning course is exactly the same as described in the blog.
  * LSTM: A Search Space Odyssey ([arXiv](https://arxiv.org/abs/1503.04069))
  * An Empirical Exploration of Recurrent Network Architectures ([JMLR](http://jmlr.org/proceedings/papers/v37/jozefowicz15.pdf))
  * Empirical Evaluation of Gated Recurrent Neural Networks on Sequence Modeling ([arXiv](https://arxiv.org/abs/1412.3555))
  * A Theoretically Grounded Application of Dropout in Recurrent Neural Networks ([arXiv](https://arxiv.org/abs/1512.05287))
  * Sequence to Sequence Learning with Neural Networks ([arXiv](https://arxiv.org/abs/1409.3215))
  * A Clockwork RNN ([arXiv](https://arxiv.org/abs/1402.3511))
  * Recurrent Neural Networks for Multivariate Time Series with Missing Values ([arXiv](https://arxiv.org/abs/1606.01865))
  * Deep Learning Lecture 13: Alex Graves on Hallucination with RNNs ([YouTube](https://www.youtube.com/watch?v=-yX1SYeDHbg))
  * RNNs in TensorFlow, a Practical Guide and Undocumented Features ([blog](http://www.wildml.com/2016/08/rnns-in-tensorflow-a-practical-guide-and-undocumented-features/))
  * Recurrent Neural Network Regularization ([arXiv](https://arxiv.org/abs/1409.2329))
  * Multi-task Sequence to Sequence Learning ([arXiv](https://arxiv.org/abs/1511.06114))
* Topics on Variational Autoencoders
  * Variational Inference Tutorial Series by Chieu from NEU ([YouTube](https://www.youtube.com/playlist?list=PLdk2fd27CQzSd1sQ3kBYL4vtv6GjXvPsE))
  * Deep Learning Lecture 14: Karol Gregor on Variational Autoencoders and Image Generation ([YouTube](https://www.youtube.com/watch?v=P78QYjWh5sM))
  * Building Autoencoders in Keras ([blog](https://blog.keras.io/building-autoencoders-in-keras.html))
  * Markov Chain Monte Carlo Without all the Bullshit ([blog](https://jeremykun.com/2015/04/06/markov-chain-monte-carlo-without-all-the-bullshit/))
* [WaveNet: A Generative Model for Raw Audio](notes/wavenet.md)  ([arXiv](https://arxiv.org/abs/1609.03499)) ([blog](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)) ([code](https://github.com/usernaamee/keras-wavenet))
  - *NB*: The repo of code is a very simple version to read.
* t-SNE
  * Visualizing Data Using t-SNE ([YouTube](https://www.youtube.com/watch?v=RJVL80Gg3lA))
  * How to Use t-SNE Effectively ([blog](http://distill.pub/2016/misread-tsne/?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=revue))
* [Neural Style and Deep Dream](notes/neural-style-deep-dream.md)
  * A Neural Algorithm of Artistic Style ([arXiv](https://arxiv.org/abs/1508.06576))
  * Keras Deep Dream ([code](https://github.com/fchollet/keras/blob/master/examples/deep_dream.py))
  * Keras Neural Style ([code](https://github.com/fchollet/keras/blob/master/examples/neural_style_transfer.py))
  * CS231n ([Stanford](http://vision.stanford.edu/teaching/cs231n/syllabus.html)): Lecture 9
* Deep Learning for ChatBots (blog: [Part1](http://www.wildml.com/2016/04/deep-learning-for-chatbots-part-1-introduction/) [Part2](http://www.wildml.com/2016/07/deep-learning-for-chatbots-2-retrieval-based-model-tensorflow/))
* Courses
  * CS224d ([Stanford](http://cs224d.stanford.edu/syllabus.html)): Lecture 1 - 3
  * CS231n ([Stanford](http://vision.stanford.edu/teaching/cs231n/syllabus.html)): Lecture 1
  * Neural Networks for Machine Learning by Geoffrey Hinton ([Coursera](https://www.coursera.org/learn/neural-networks/)): Week 1 - 3
* Towards my research
  * A Novel Empirical Mode Decomposition With Support Vector Regression for Wind Speed Forecasting ([IEEE](http://ieeexplore.ieee.org/document/6895279/))

## 2016-09
* [Spatial Transformer Networks](notes/spatial-transformer-network.md) ([arXiv](https://arxiv.org/abs/1506.02025)) ([blog](http://torch.ch/blog/2015/09/07/spatial_transformers.html)) ([code](https://github.com/tensorflow/models/tree/master/transformer))
* Attention and Memory in Deep Learning and NLP ([blog](http://www.wildml.com/2016/01/attention-and-memory-in-deep-learning-and-nlp/))
* Deep Residual Learning for Image Recognition ([arXiv](http://arxiv.org/abs/1512.03385))
* Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning ([arXiv](https://arxiv.org/abs/1602.07261))
* Bilinear CNN Models for Fine-grained Visual Recognition ([arXiv](https://arxiv.org/abs/1504.07889))
