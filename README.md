# awesome-graph-diffusion-generation
Organize the current research on graph diffusion generation.

+ A curated list of up-to-date graph diffusion generation papers and resources.
+ This Repo is being actively updated and maintained! 03/21/24
+ Please let us know if we miss any papers!

# Survey
Generative Diffusion Models on Graphs: Methods and Applications IJCAI 2023

# Algorithm
Sparse Training of Discrete Diffusion Models for Graph Generation Arxiv 2024
Autoregressive Diffusion Model for Graph Generation ICML 2023
Efficient and Degree-Guided Graph Generation via Discrete Diffusion Modeling ICML 2023
DiGress: Discrete Denoising diffusion for graph generation ICLR 2023
Conditional Diffusion Based on Discrete Graph Structures for Molecular Graph Generation AAAI 2023
GraphGDP: Generative Diffusion Processes for Permutation Invariant Graph Generation ICDM 2022

## SMLD on Graphs
Permutation Invariant Graph Generation via Score-Based Generative Modeling
Chenhao Niu, Yang Song, Jiaming Song, Shengjia Zhao, Aditya Grover, Stefano Ermon
AISTATS 2021. [Paper] [Github]
2 Mar 2020

Learning gradient fields for molecular conformation generation
Chence Shi, Shitong Luo, Minkai Xu, Jian Tang
ICML 2021. [Paper] [Github]
9 May 2021

## DDPM on Graphs
Diffusion Models for Graphs Benefit From Discrete State Spaces
Kilian Konstantin Haefeli, Karolis Martinkus, Nathanaël Perraudin, Roger Wattenhofer
LoG 2022 and NeurIPS GLFrontiers 2022. [Paper] [Github]
4 Oct 2022

DiGress: Discrete Denoising diffusion for graph generation
Clement Vignac1, Igor Krawczuk1, Antoine Siraudin, Bohan Wang, Volkan Cevher, Pascal Frossard
ICLR 2023. [Paper] [Github]
29 Sep 2022


## SGM on Graphs
GraphGDP: Generative Diffusion Processes for Permutation Invariant Graph Generation
Han Huang, Leilei Sun, Bowen Du, Yanjie Fu, Weifeng Lv
IEEE ICDM 2022. [Paper] [Github]
4 Dec 2022

Score-based Generative Modeling of Graphs via the System of Stochastic Differential Equations
Jaehyeong Jo, Seul Lee, Sung Ju Hwang
ICML, 2022. [Paper] [Github]
5 Feb 2022

Fast Graph Generative Model via Spectral Diffusion
Tianze Luo, Zhanfeng Mo, Sinno Jialin Pan
arXiv 2022. [Paper]
16 Nov 2022

Score-based graph generative modeling with self-guided latent diffusion
Ling Yang, Zhilong Zhang, Wentao Zhang, and Shenda Hong
OpenReview. [Paper]
02 Feb 2023


# Application
Geometric Latent Diffusion Models for 3D Molecule Generation ICML 2023
Coarse-to-Fine: a Hierarchical Diffusion Model for Molecule Generation in 3D ICML 2023
Learning Joint 2D & 3D Diffusion Models for Complete Molecule Generation Arxiv 2023
MiDi: Mixed Graph and 3D Denoising Diffusion for Molecule Generation Arxiv 2023

## Molecule Modeling
### Molecule Conformation Generation
#### SMLD
MDM: Molecular Diffusion Model for 3D Molecule Generation
Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong
Submitted to AAAI'23. [Paper]
13 Sep 2022

#### DDPM
GeoDiff: a Geometric Diffusion Model for Molecular Conformation Generation
Minkai Xu, Lantao Yu, Yang Song, Chence Shi, Stefano Ermon, Jian Tang
ICLR 2022. [Paper] [Github]
6 Mar 2022

Equivariant Diffusion for Molecule Generation in 3D
Emiel Hoogeboom, Vıctor Garcia Satorras, Clement Vignac, and Max Welling
ICML 2022. [Paper] [Github]
31 Mar 2022

Equivariant Energy-Guided SDE for Inverse Molecular Design
Fan Bao, Min Zhao, Zhongkai Hao, Peiyao Li, Chongxuan Li, Jun Zhu
ICLR 2023. [Paper] [Github]
30 Sep 2022

#### SGM
Predicting Molecular Conformation via Dynamic Graph Score Matching
Shitong Luo, Chence Shi, Minkai Xu, Jian Tang
NeurIPS 2021. [Paper]
22 May 2021

Torsional Diffusion for Molecular Conformer Generation
Bowen Jing, Gabriele Corso, Regina Barzilay, Tommi S. Jaakkola
NeurIPS 2022. [Paper] [Github]
1 Jun 2022

Exploring Chemical Space with Score-based Out-of-distribution Generation
Seul Lee, Jaehyeong Jo, Sung Ju Hwang
ICML 2023. [Paper] [Github]
6 Jun 2022

Diffusion-based Molecule Generation with Informative Prior Bridges
Lemeng Wu1, Chengyue Gong1, Xingchao Liu, Mao Ye, Qiang Liu
NeurIPS 2022. [Paper]
2 Sep 2022

### Molecule Docking
#### DDPM
Equivariant 3D-Conditional Diffusion Models for Molecular Linker Design
Ilia Igashov, Hannes Stärk, Clément Vignac, Victor Garcia Satorras, Pascal Frossard, Max Welling, Michael Bronstein, Bruno Correia
NeurIPS 2022. [Paper] [Github]
11 Oct 2022

DiffBP: Generative Diffusion of 3D Molecules for Target Protein Binding
Haitao Lin1, Yufei Huang1, Meng Liu, Xuanjing Li, Shuiwang Ji, Stan Z. Li
arXiv 2022. [Paper]
21 Nov 2022

Pocket-specific 3D Molecule Generation by Fragment-based Autoregressive Diffusion Models
Xingang Peng, Jiaqi Guan, Jian Peng, Jianzhu Ma
OpenReview 2022. [Paper]
02 Feb 2023

3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction
Jiaqi Guan, Wesley Wei Qian, Xingang Peng, Yufeng Su, Jian Peng, Jianzhu Ma
ICLR 2023. [Paper] [Github]
6 Mar 2023

#### SGM
DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking
Gabriele Corso, Hannes Stärk, Bowen Jing, Regina Barzilay, Tommi Jaakkola
ICLR 2023. [Paper] [Github]
4 Oct 2022

## Molecule Modeling
### Protein Generation
#### DDPM
Protein Representation Learning by Geometric Structure Pretraining
Zuobai Zhang, Minghao Xu, Arian Jamasb, Vijil Chenthamarakshan, Aurelie Lozano, Payel Das, Jian Tang
arXiv 2022.. [Paper] [Github]
11 Mar 2022

Protein Structure and Sequence Generation with Equivariant Denoising Diffusion Probabilistic Models
Namrata Anand, Tudor Achim
arXiv 2022. [Paper] [Project] [Github]
26 May 2022

Diffusion probabilistic modeling of protein backbones in 3D for the motif-scaffolding problem
Brian L. Trippe1, Jason Yim1, Doug Tischer, Tamara Broderick, David Baker, Regina Barzilay, Tommi Jaakkola
ICLR 2023. [Paper] [Github]
8 Jun 2022

Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models
Shitong Luo1, Yufeng Su1, Xingang Peng, Sheng Wang, Jian Peng, Jianzhu Ma
NeurIPS 2022. [Paper]
11 Jul 2022

Protein structure generation via folding diffusion
Kevin E. Wu, Kevin K. Yang, Rianne van den Berg, James Y. Zou, Alex X. Lu, Ava P. Amini
arXiv 2022. [Paper] [Github]
30 Sep 2022

#### SGM
Score-based generative modeling for de novo protein design
Jin Sub Lee, Jisun Kim & Philip M. Kim
Nature Computational Science 2023. [Paper] [Github]
04 May 2023

Protein-ligand Complex Structure Predictiong
DDPM
End-to-end protein–ligand complex structure generation with diffusion-based generative models
Shuya Nakata, Yoshiharu Mori, and Shigenori Tanaka
BMC Bioinformatics 2023. [Paper]
22 December 2022

#### SGM
Dynamic-backbone protein-ligand structure prediction with multiscale generative diffusion models tate-specific protein-ligand complex structure prediction with a multi-scale deep generative model (new version) Zhuoran Qiao, Weili Nie, Arash Vahdat, Thomas F Miller III, and Anima Anandkumar
NeurIPS 2022. [Paper]
22 December 2022








# Biology
Protein Design with Guided Discrete Diffusion NeurIPS 2023




Thanks this works：
@article{fan2023generative,
  title={Generative diffusion models on graphs: Methods and applications},
  author={Fan, Wenqi and Liu, Chengyi and Liu, Yunqing and Li, Jiatong and Li, Hang and Liu, Hui and Tang, Jiliang and Li, Qing},
  journal={arXiv preprint arXiv:2302.02591},
  year={2023}
}


