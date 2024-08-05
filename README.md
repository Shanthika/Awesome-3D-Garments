# Awesome-3D-Garments

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curation of research papers and datasets related to 3D garment digitization and simulation

Table of Contents
=================

- [Courses](#courses)
- [Papers](#papers)
	- [Classical Cloth Simulation](#classical-cloth-simulation)
 	- [Collision Handling and Contact Friction Modeling](#collision-handling-and-contact-friction-modeling)
	- [Neural Cloth Simulation](#neural-cloth-simulation)
	- [DL for Simulation](#dl-for-simulation)
	- [Inverse Cloth Simulation](#inverse-cloth-simulation)
	- [Avatar Generation](#avatar-generation)
   	- [Garment Generation](#garment-generation)
  	- [Dynamic Human Reconstruction from Multiview Video](#dynamic-human-reconstruction-from-multiview-video)
  	- [Dynamic Human Reconstruction from Monocular Video](#dynamic-human-reconstruction-from-monocular-view)
  	- [Garment Reconstruction from Monocular Video](#garment-reconstruction-from-monocular-video)
  	- [Garment Reconstruction from Multiview Video](#garment-reconstruction-from-multiview-video)
  	- [Panel Based Garment Representation](#panel-based-garment-reconstruction)
  	- [Clothed Human Reconstruction from Monocular Image or Video](#clothed-human-reconstruction-from-monocular-image-or-video)
  	- [Learning Clothed Human Deformation from 3D scans](#learning-clothed-human-deformation-from-3d-scans)
  	- [Garment Retargetting](#garment-retargetting)
   	- [Virtual Try On](#virtual-try-on)
   	
- [Datasets](#datasets)
	- [Garment Dataset](#garment-dataset)
	- [Clothed Human Dataset](#clothed-human-dataset)


# Courses
- [Physics Based Animation](https://github.com/dilevin/CSC417-physics-based-animation?tab=readme-ov-file)
- Cloth Simulation: [1](https://graphics.stanford.edu/~mdfisher/cloth.html#EquationsOfMotion) [2](https://cg.informatik.uni-freiburg.de/course_notes/sim_03_cloth1.pdf)
- [Linear Implicit Solver](https://people.engr.tamu.edu/sueda/courses/CSCE489/2021F/assignments/A5/index.html)
- FEM Simulation of 3D Deformable Solids: [1](https://viterbi-web.usc.edu/~jbarbic/femdefo/barbic-courseNotes-modelReduction.pdf) [2](https://viterbi-web.usc.edu/~jbarbic/femdefo/barbic-courseNotes-modelReduction.pdf)


# Papers
## Classical Cloth Simulation 
- [Large Steps in Cloth Simulation](https://www.cs.cmu.edu/~baraff/papers/sig98.pdf)
- [Numerical Methods in Cloth Simulation](https://www.wuwayne.com/files/clothsim/report.pdf)  
- [Implicit and Explicit Methods of Cloth Simulation](https://www.cs.ru.ac.za/research/groups/vrsig/pastprojects/052cloth/paper03.pdf)  
- [Position Based Dynamics](https://matthias-research.github.io/pages/publications/posBasedDyn.pdf) 
  	#### Implementation
  	- [PBD](https://carmencincotti.com/2022-07-11/position-based-dynamics/)
  	- [Velvet](https://github.com/vitalight/Velvet)
  	  
- [Adaptive Anisotropic Remeshing for Cloth Simulation](http://graphics.berkeley.edu/papers/Narain-AAR-2012-11/Narain-AAR-2012-11.pdf)
	#### Implementations:
	- [ArcSim](https://github.com/DanielTakeshi/ARCSim-Installation-Instructions)
	- [Argus](https://github.com/lijieumn/argus-distribution)
- [Cloth simulation and collision detection using geometry images](https://ujcontent.uj.ac.za/esploro/outputs/graduate/Cloth-simulation-and-collision-detection-using/9910105707691/filesAndLinks?index=0)
 - [Multi-Layer Thick Shells](https://dl.acm.org/doi/pdf/10.1145/3588432.3591489) 


## Collision Handling and Contact Friction Modeling
#### 2022
- [DiffCloth: Differentiable Cloth Simulation with Dry Frictional Contact](https://people.csail.mit.edu/liyifei/uploads/Li-liyifei-SM-EECS-2022-thesis.pdf) \
  Yifei Li, Tao Du, Kui Wu, Jie Xu, Wojciech Matusik \
  ACM TOG, 2022
#### 2020
- [Incremental Potential Contact: Intersection- and Inversion-free, Large-Deformation Dynamics](https://dl.acm.org/doi/pdf/10.1145/3386569.3392425) \
  Minchen Li,  Zachary Ferguson,  Teseo Schneider,  Timothy Langlois,  Denis Zorin,  Daniele Panozzo, Chenfanfu Jiang,  Danny M. Kaufman \
  SIGGRAPH, 2020
#### 2018
- [An Implicit Frictional Contact Solver for Adaptive Cloth Simulation](https://www-users.cselabs.umn.edu/~lixx4611/contact_friction.html) \
  Jie Li, Gilles Daviet, Rahul Narain, Florence Bertails-Descoubes, Matthew Overby, George Brown, Laurence Boissieux \
  SIGGRAPH, 2018
- [Inverse Elastic Shell Design with Contact and Friction](https://inria.hal.science/hal-01883655/file/inverseShellModeling.pdf) \
  Mickaël Ly, Romain Casati, Florence Bertails-Descoubes, Mélina Skouras, Laurence Boissieux \
  SIGGRAPH Asia, 2018
- [I-Cloth: Incremental Collision Handling for GPU-Based Interactive Cloth Simulation](https://min-tang.github.io/home/ICloth/files/icloth.pdf) \
  Min Tang , Tongtong Wang, Zhongyuan Liu, Ruofeng Tong, and Dinesh Manocha \
  SIGGRAPH Asia, 2018
#### 2009
- [Implicit Contact Handling for Deformable Objects](https://media.disneyanimation.com/uploads/production/publication_asset/32/asset/EG2009_implicit_contact.pdf) \
  Miguel A. Otaduy, Rasmus Tamstorf, Denis Steinemann, Markus Gross \
  EUROGRAPHICS, 2009
#### 2002
- [Robust Treatment of Collisions, Contact and Friction for Cloth Animation](https://graphics.stanford.edu/papers/cloth-sig02/cloth.pdf) \
  Robert Bridson, Ronald Fedkiw, John Anderson \
  SIGGRAPH, 2002

## Neural Cloth Simulation
#### 2024
- [Bayesian Differentiable Physics for Cloth Digitalization](https://openaccess.thecvf.com/content/CVPR2024/papers/Gong_Bayesian_Differentiable_Physics_for_Cloth_Digitalization_CVPR_2024_paper.pdf) \
  Deshan Gong, Ningtao Mao, He Wang \
  CVPR, 2024
- [A Neural-Network-Based Approach for Loose-Fitting Clothing](https://arxiv.org/pdf/2404.16896) \
  YONGXU JIN, DALTON OMENS, ZHENGLIN GENG, JOSEPH TERAN, ABISHEK KUMAR, KENJI TASHIRO, RONALD FEDKIW \
  ArXiv, 2024
#### 2023
- [Data-Free Learning of Reduced-Order Kinematics](https://nmwsharp.com/media/papers/neural-physics-subspaces/neural_physics_subspaces.pdf) \
  Nicholas Sharp, Cristian Romero, Alec Jacobson, Etienne Vouga, Paul Kry, David I.W. Levin, Justin Solomon \
  SIGGRAPH '23: ACM SIGGRAPH 2023 Conference Proceedings
- [NeuralClothSim: Neural Deformation Fields Meet the Kirchhoff-Love Thin Shell Theory](https://arxiv.org/pdf/2308.12970.pdf) \
  NAVAMI KAIRANDA, MARC HABERMANN, CHRISTIAN THEOBALT, and VLADISLAV GOLYANIK
  ArXiv, 2023


## DL for Simulation
#### 2024
- [ContourCraft: Learning to Resolve Intersections in Neural Multi-Garment Simulations](https://dl.acm.org/doi/pdf/10.1145/3641519.3657408) \
  Artur Grigorev, Giorgio Becherini, Michael Black, Otmar Hilliges, Bernhard Thomaszewski \
  SIGGRAPH, 2024
- [GAPS: Geometry-Aware, Physics-Based, Self-Supervised Neural Garment Draping](https://arxiv.org/pdf/2312.01490.pdf) | [Code](https://github.com/simonhfls/gaps) \
  Ruochen Chen, Liming Chen, Shaifali Parashar \
  3DV, 2024
- [HOOD: Hierarchical Graphs for Generalized Modelling of Clothing Dynamics](https://arxiv.org/pdf/2212.07242.pdf) | [Code](https://github.com/Dolorousrtur/HOOD/tree/main) \
  Artur Grigorev, Bernhard Thomaszewski, Michael J. Black, Otmar Hilliges \
  CVPR, 2024
#### 2023
- [Towards Multi-Layered 3D Garments Animation](https://arxiv.org/pdf/2305.10418) \
  Yidi Shao, Chen Change Loy, Bo Dai \
  ICCV, 2023
- [GenSim: Unsupervised Generic Garment Simulator](https://openaccess.thecvf.com/content/CVPR2023W/DLGC/papers/Tiwari_GenSim_Unsupervised_Generic_Garment_Simulator_CVPRW_2023_paper.pdf) \
  Lokender Tiwari Brojeshwar Bhowmick Sanjana Sinha \
  CVPR Workshop, 2023
#### 2022
- [Neural Cloth Simulation](https://dl.acm.org/doi/pdf/10.1145/3550454.3555491) | [Code](https://github.com/hbertiche/NeuralClothSim/) \
  HUGO BERTICHE, MEYSAM MADADI, and SERGIO ESCALERA \
  SIGGRAPH Asia 2022
- [SNUG: Self-Supervised Neural Dynamic Garments](https://arxiv.org/pdf/2204.02219.pdf) | [Code](https://github.com/isantesteban/snug/tree/main) \
  Igor Santesteban, Miguel A. Otaduy, and Dan Casas
  IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022 (Oral)
#### 2019
- [Learning-Based Animation of Clothing for Virtual Try-On](https://arxiv.org/pdf/1903.07190) \
  Igor Santesteban, Miguel A. Otaduy, Dan Casas \
  EUROGRAPHICS, 2019

  
## Inverse Cloth Simulation
#### 2023
- [DiffXPBD : Differentiable Position-Based Simulation of Compliant Constraint Dynamics](https://arxiv.org/pdf/2301.01396.pdf) \
  Tuur Stuyck, Hsiao-yu Chen \
  ACM- Computer Graphics and Interactive Techniques, 2023
#### 2022
- [Φ-SfT: Shape-from-Template with a Physics-Based Deformation Model](https://4dqv.mpi-inf.mpg.de/phi-SfT/) | [Code](https://github.com/navamikairanda/phi_sft/tree/main) \
  Navami Kairanda, Edith Tretschk, Mohamed Elgharib, Christian Theobalt, Vladislav Golyanik \
  CVPR, 2022
#### 2019
- [Differentiable Cloth Simulation for Inverse Problems](https://gamma.umd.edu/researchdirections/virtualtryon/differentiablecloth) | [Code](https://github.com/williamljb/DifferentiableCloth/tree/master?tab=readme-ov-file) \
  Junbang Liang, Ming C. Lin, Vladlen Koltun \
  NeurIPS, 2019
  

## Avatar Generation
#### 2024
- [GAvatar: Animatable 3D Gaussian Avatars with Implicit Mesh Learning](https://nvlabs.github.io/GAvatar) \
  Ye Yuan, Xueting Li, Yangyi Huang, Shalini De Mello, Koki Nagano, Jan Kautz, Umar Iqbal \
  CVPR, 2024 (Highlight)
#### 2022
- [Dressing Avatars: Deep Photorealistic Appearance for Physically Simulated Clothing](https://arxiv.org/pdf/2206.15470.pdf)
  Donglai Xiang, Timur Bagautdinov, Tuur Stuyck, Fabian Prada, Javier Romero, Weipeng Xu, Shunsuke Saito, Jingfan Guo, Breannan Smith, Takaaki Shiratori, 
  Yaser Sheikh, Jessica Hodgins, and Chenglei Wu \
  ACM Transactions on Graphics (TOG), 2022
  
## Garment Generation
#### 2024
- [Design2Cloth: 3D Cloth Generation from 2D Masks](https://jiali-zheng.github.io/Design2Cloth/) \
  Jiali Zheng, Rolandos Alexandros Potamias, Stefanos Zafeiriou \
  CVPR, 2024
- [Garment3DGen: 3D Garment Stylization and Texture Generation](https://nsarafianos.github.io/garment3dgen) \
  Nikolaos Sarafianos, Tuur Stuyck, Xiaoyu Xiang, Yilei Li, Jovan Popovic, Rakesh Ranjan \
  ArXiv, 2024
- [GarmentDreamer: 3DGS Guided Garment Synthesis with Diverse Geometry and Texture Details](https://arxiv.org/pdf/2405.12420) \
  Boqian Li, Xuan Li, Ying Jiang, Tianyi Xie, Feng Gao, Huamin Wang, Yin Yang, Chenfanfu Jiang \
  ArXiv, 2024
- [WordRobe: Text-Guided Generation of Textured 3D Garments](https://arxiv.org/pdf/2403.17541) \
  Astitva Srivastava, Pranav Manu, Amit Raj, Varun Jampani, Avinash Sharma \
  ECCV, 2024

## Dynamic Human Reconstruction from Multiview Video
#### 2024
- [Animatable and Relightable Gaussians for High-fidelity Human Avatar Modeling](https://arxiv.org/pdf/2311.16096)\
  Zhe Li, Yipengjing Sun, Zerong Zheng, Lizhen Wang, Shengping Zhang, Yebin Liu \
  CVPR, 2024 \
  NOTE: Map to Canonical
- [PhysAvatar: Learning the Physics of Dressed 3D Avatars from Visual Observations](https://arxiv.org/pdf/2404.04421.pdf) \
  Yang Zheng, Qingqing Zhao, Guandao Yang, Wang Yifan, Donglai Xiang, Florian Dubost, Dmitry Lagun, Thabo Beeler, Federico Tombari, Leonidas Guibas, Gordon Wetzstein \
  ArXiv, 2024
#### 2022
- [ARAH: Animatable Volume Rendering of Articulated Human SDFs](https://neuralbodies.github.io/arah/) \
  Shaofei Wang,  Katja Schwarz,  Andreas Geiger,  Siyu Tang \
  ECCV, 2022
- [TAVA: Template-free Animatable Volumetric Actors](https://github.com/facebookresearch/tava) \
  Ruilong Li,Julian Tanke, Minh Vo, Michael Zollhoefer, Jürgen Gall, Angjoo Kanazawa, Christoph Lassner \
  ECCV, 2022

## Dynamic Human Reconstruction from Monocular Video
#### 2024
- [GaussianAvatar: Towards Realistic Human Avatar Modeling from a Single Video via Animatable 3D Gaussians](https://openaccess.thecvf.com/content/CVPR2024/html/Hu_GaussianAvatar_Towards_Realistic_Human_Avatar_Modeling_from_a_Single_Video_CVPR_2024_paper.html) \
  Liangxiao Hu, Hongwen Zhang, Yuxiang Zhang, Boyao Zhou, Boning Liu, Shengping Zhang, Liqiang Nie \
  CVPR, 2024 \
  NOTE: Map to Canonical T-pose
- [GaussianBody: Clothed Human Reconstruction via 3d Gaussian Splatting](https://arxiv.org/pdf/2401.09720) \
  Mengtian Li, Shengxiang Yao, Zhifeng Xie, Keyu Chen \
  ArXiv, 2024 \
  NOTE: Map to Canonical T-pose
  
  
## Garment Reconstruction from Monocular Video
#### 2023
- [REC-MV: REconstructing 3D Dynamic Cloth from Monocular Videos](https://github.com/GAP-LAB-CUHK-SZ/REC-MV) \
  Lingteng Qiu1, Guanying Chen, Jiapeng Zhou, Mutian Xu, Junle Wang,Xiaoguang Han \
  CVPR, 2023 \
  NOTE:  Deformation of T-pose template mesh
#### 2022
- [PERGAMO: Personalized 3D Garments from Monocular Video](https://arxiv.org/pdf/2210.15040) \
  Andrés Casado-Elvira, Marc Comino Trinidad, Dan Casas \
  SIGGRAPH, 2022
#### 2021
- [Deep Physics-aware Inference of Cloth Deformation for Monocular Human Performance Capture](https://arxiv.org/pdf/2011.12866) \
  Yue Li, Marc Habermann, Bernhard Thomaszewski, Stelian Coros, Thabo Beeler and Christian Theobalt \
  3DV, 2021 \
  NOTE: Temporal deformation
  
## Garment Reconstruction from Multiview Video
#### 2023
- [Drivable 3D Gaussian Avatars](https://zielon.github.io/d3ga/) \
  Wojciech Zielonka, Timur Bagautdinov, Shunsuke Saito, Michael Zollhöfer, Justus Thies, Javier Romero \
  ArXiv\
  NOTE: Map to Canonical T-pose, 2023
  

## Panel Based Garment Representation
#### 2024
- [DiffAvatar: Simulation-Ready Garment Optimization with Differentiable Simulation](https://arxiv.org/pdf/2311.12194#page=4.27) \
  Yifei Li, Hsiao-yu Chen, Egor Larionov, Nikolaos Sarafianos, Wojciech Matusik, Tuur Stuyck \
  CVPR, 2024
- [Inverse Garment and Pattern Modeling with a Differentiable Simulator](https://arxiv.org/pdf/2403.06841) \
  Boyang Yu, Frederic Cordier, and Hyewon Seo \
  ArXiv, 2024
#### 2023
- [Towards Garment Sewing Pattern Reconstruction from a Single Image](https://sewformer.github.io/) \
  Lijuan Liu, Xiangyu Xu, Zhijie Lin, Jiabin Liang, Shuicheng Yan \
  SIGGRAPH ASIA, 2023
#### 2022
- [NeuralTailor: Reconstructing Sewing Pattern Structures from 3D Point Clouds of Garments](https://dl.acm.org/doi/pdf/10.1145/3528223.3530179) \
  Maria Korosteleva and Sung-Hee Lee \	
  ACM Transactions on Graphics (TOG), 2022
#### 2021
- [Garment4D: Garment Reconstruction from Point Cloud Sequences](https://proceedings.neurips.cc/paper_files/paper/2021/file/eb160de1de89d9058fcb0b968dbbbd68-Paper.pdf) \
  Fangzhou Hong, Liang Pan, Zhongang Cai, Ziwei Liu \
  NeurIPS, 2021

## Clothed Human Reconstruction from Monocular Image/Video 
#### 2024
- [ANIM: Accurate Neural Implicit Model for Human Reconstruction from a single RGB-D image](https://marcopesavento.github.io/ANIM/ANIM_camera_ready.pdf) \
  Marco Pesavento, Yuanlu Xu, Nikolaos Sarafianos, Robert Maier, Ziyan Wang, Chun-Han Yao, Marco Volino, Edmond Boyer, Adrian Hilton, Tony Tung \
  CVPR, 2024
- [SiTH: Single-view Textured Human Reconstruction with Image-Conditioned Diffusion](https://sith-diffusion.github.io/) \
  Hsuan-I Ho, Jie Song, Otmar Hilliges \
  CVPR, 2024
- [Garment Recovery with Shape and Deformation Priors](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Garment_Recovery_with_Shape_and_Deformation_Priors_CVPR_2024_paper.pdf) \
  Ren Li, Corentin Dumery, Benoît Guillard, Pascal Fua \
  CVPR, 2024
- [LayerNet: High-Resolution Semantic 3D Reconstruction of Clothed People](https://www.iri.upc.edu/files/scidoc/2760-LayerNet:-high-resolution-semantic-3D-reconstruction-of-clothed-people.pdf) \
  Enric Corona, Guillem Aleny`a, Gerard Pons-Moll, Francesc Moreno-Noguer \
  TPAMI, 2024
#### 2022
- [Layered-Garment Net: Generating Multiple Implicit Garment Layers from a Single Image](https://personal.utdallas.edu/~xguo/ACCV2022.pdf) | [Code](https://github.com/alakhag/lgn?tab=readme-ov-file) \
  Alakh Aggarwal, Jikai Wang, Steven Hogue, Saifeng Ni, Madhukar Budagavi, Xiaohu Guo \
  ACCV

## Learning Clothed Human Deformation from 3D scans 
#### 2023
- [CaPhy: Capturing Physical Properties for Animatable Human Avatars](https://suzhaoqi.github.io/assets/pdf/CaPhy.pdf)\
  Zhaoqi Su, Liangxiao Hu, Siyou Lin, Hongwen Zhang, Shengping Zhang, Justus Thies, Yebin Liu \
  ICCV, 2023
- [CloSET: Modeling Clothed Humans on Continuous Surface with Explicit Template Decomposition](https://arxiv.org/pdf/2304.03167.pdf)\
  Hongwen Zhang, Siyou Lin, Ruizhi Shao, Yuxiang Zhang, Zerong Zheng, Han Huang, Yandong Guo, Yebin Liu \
  CVPR, 2023
#### 2021
- [SCANimate: Weakly Supervised Learning of Skinned Clothed Avatar Networks](https://openaccess.thecvf.com/content/CVPR2021/papers/Saito_SCANimate_Weakly_Supervised_Learning_of_Skinned_Clothed_Avatar_Networks_CVPR_2021_paper.pdf) \
  Shunsuke Saito, Jinlong Yang, Qianli Ma, Michael J. Black \
  CVPR, 2021 \
  NOTE: Map to canonical t-pose
#### 2018
- [DeepWrinkles: Accurate and Realistic Clothing Modeling](https://openaccess.thecvf.com/content_ECCV_2018/papers/Zorah_Laehner_DeepWrinkles_Accurate_and_ECCV_2018_paper.pdf) \
  Zorah Lahner, Daniel Cremers, Tony Tung \
  ECCV, 2018
#### 2017
- [ClothCap: Seamless 4D Clothing Capture and Retargeting](https://dl.acm.org/doi/pdf/10.1145/3072959.3073711) \
  Gerard Pons-Moll, Sergi Pujades, Sonny Hu, and Michael J. Black \
  ACM- TOG, 2017
  
## Garment Retargetting
#### 2023
- [DrapeNet: Garment Generation and Self-Supervised Draping](https://arxiv.org/pdf/2211.11277.pdf) | [Code](https://github.com/liren2515/DrapeNet) \
  Luca De Luigi, Ren Li, Benoit Guillard, Mathieu Salzmann, Pascal Fua \
  CVPR, 2023
- [ISP: Multi-Layered Garment Draping with Implicit Sewing Patterns](https://liren2515.github.io/page/isp/isp.html) | [Code](https://github.com/liren2515/ISP) \
  Ren Li, Benoit Guillard, Pascal Fua \
  NeurIPS, 2023
- [ClothCombo: Modeling Inter-Cloth Interaction for Draping Multi-Layered Clothes](https://arxiv.org/pdf/2304.03492.pdf) \
  DOHAE LEE, Yonsei University, HYUN KANG, IN-KWON LEE \
  ACM TOG, 2023
#### 2022
- [DIG: Draping Implicit Garment over the Human Body](https://arxiv.org/pdf/2209.10845) | [Code](https://github.com/liren2515/DIG) \
  	Ren Li, Benoît Guillard, Edoardo Remelli, Pascal Fua \
  	ACCV, 2022
- [ULNeF: Untangled Layered Neural Fields for Mix-and-Match Virtual Try-On](https://dancasas.github.io/docs/santesteban_NeurIPS2022.pdf) \
  Igor Santesteban, Miguel A. Otaduy, Nils Thuerey, Dan Casas
  NeurIPS 2022
#### 2021
- [Self-Supervised Collision Handling via Generative 3D Garment Models for Virtual Try-On](https://dancasas.github.io/docs/santesteban_CVPR2021.pdf) | [Code](https://github.com/isantesteban/vto-garment-collisions) \
  Igor Santesteban, Nils Thuerey, Miguel A. Otaduy, Dan Casas \
  CVPR, 2021
- [M3D-VTON: A Monocular-to-3D Virtual Try-On Network](https://arxiv.org/pdf/2108.05126) \
  Fuwei Zhao, Zhenyu Xie, Michael Kampffmeyer, Haoye Dong, Songfang Han, Tianxiang Zheng, Tao Zhang, Xiaodan Lian\
  ICCV, 2021
#### 2020
- [Fully Convolutional Graph Neural Networks for Parametric Virtual Try-On](https://arxiv.org/pdf/2009.04592) \
  Raquel Vidaurre, Igor Santesteban, Elena Garces, Dan Casas \
  SIGGRAPH, 2020

## Virtual Try On
#### 2024
- [LayGA: Layered Gaussian Avatars for Animatable Clothing Transfer](https://arxiv.org/pdf/2405.07319)\
  	Siyou Lin, Zhe Li, Zhaoqi Su, Zerong Zheng, Hongwen Zhang, Yebin Liu \
  	SIGGRAPH, 2024

  
# Datasets
## Garment Dataset 
### 1. [Cloth3D](https://chalearnlap.cvc.uab.cat/dataset/38/description/)
This dataset contains a large collection of synthetic garment data obtained via animation SMPL models wearing different garments. They contain 6 different categories: t-shirt, top, dress, trousers, skirts and jumpsuits; each with different variation in topology such as length of sleeves, torso, legs, distance from body etc.  They also provide UV mapping, allowing one to swap in any desired textures. 
<img src="images/cloth3d.png" width="600">


### 2. [Deep Fashion3D](https://github.com/kv2000/deepFashion3D) 
They provide a collection of 3D garments obtained from 3D reconstruction of images. It contains over 2000 3D garment models, spanning 10 different cloth categories. Colored 3D point cloud of garments, body pose of underlying human body, line annotations are provided.

<img src="images/deepfashion3d.png" width="600">


### 3. [MGN](https://virtualhumans.mpi-inf.mpg.de/mgn)
<img src="images/mgn.png" width="600">


### 4. [SIZER](https://virtualhumans.mpi-inf.mpg.de/sizer/)
<img src="images/sizer.jpg" width="600">


### 5. [Generating Datasets of 3D Garments with Sewing Patterns](https://github.com/maria-korosteleva/Garment-Pattern-Generator)
<img src="images/sewing_patterns.png" width="600">

### 6. [Simulated garment dataset for virtual try-on](https://github.com/isantesteban/vto-dataset)
<img src="images/vto.gif" width="600">


## Clothed Human Dataset
### 1. [3D Humans](https://cvit.iiit.ac.in/research/projects/cvit-projects/3dhumans)
<img src="images/3dhumans.png" width="600">


### 2. [THuman](https://github.com/ytrock/THuman2.0-Dataset)
<img src="images/thuman.jpg" width="600">



### 3. [XHumans](https://github.com/Skype-line/X-Avatar)
<img src="images/xhumans.png" width="600">



### 4. [BUFF](https://buff.is.tue.mpg.de/)
<img src="images/buff.png" width="600">


### 5. [4D-DRESS Dataset Subjects](https://eth-ait.github.io/4d-dress/)
<img src="images/4d_dress.png" width="600">

### 6. [MultiHuman](https://github.com/y-zheng18/MultiHuman-Dataset)
<img src="images/MultiHuman.jpg" width="600">


