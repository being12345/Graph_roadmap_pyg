# Graph Neural Network RoadMap 
In this repo I will give a roadmap about how to learn GNN, according to my experience. 

It will be a effective way to learn GNN.

## GCN 
### video
+ [Spectral Graph Convolutional Layers](https://pytorch-geometric.readthedocs.io/en/latest/get_started/colabs.html) 

It may be confused if you don't have experience in signal and system. Don't worry, following videoes will guide you!

+ [台大李宏毅助教讲解GNN图神经网络](https://www.bilibili.com/video/BV1G54y1971S/?spm_id_from=333.337.search-card.all.click)

Part 2 explain Fourier and Laplacian in graph convolution.

### Code 
+ [cheb_conv source code](https://pytorch-geometric.readthedocs.io/en/latest/_modules/torch_geometric/nn/conv/cheb_conv.html#ChebConv)

I will explain this code step by step in another repo.

### Papers
this part would be the survey of Cross-cutting areas with CV & GNN.

temporarily we may focus on 3D Point Cloud or Visual Relationship Detection. Therefore the following are some reference.

+ [Visual Relation Detection: A Survey (AAAI 2019)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9693341)
+ [Scene Graph Generation: A Comprehensive Survey (arXiv 2020)](https://arxiv.org/pdf/2201.00443.pdf)
+ [Point Cloud Upsampling: A Survey (arXiv 2020)](https://arxiv.org/pdf/2106.04779.pdf)
+ [A Survey of Graph Neural Networks for Image Segmentation (arXiv 2021)](https://arxiv.org/pdf/2106.06307.pdf)

+ [Lu et al.《Visual Relationship Detection with Language Priors》(ECCV 2016)](https://arxiv.org/pdf/1608.00187.pdf)

The pioneering work of VRD.

### BaseLines
Some most popelar baselines in VRD. (Just like the one U-Net made.)

+ [《GPS-Net: Graph Property Sensing Network for Scene Graph Generation》(CVPR 2020)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lin_GPS-Net_Graph_Property_Sensing_Network_for_Scene_Graph_Generation_CVPR_2020_paper.pdf)

+ [《Graph R-CNN for Scene Graph Generation》(ECCV 2018)](https://arxiv.org/pdf/1808.00191.pdf)
+ [《Factorizable Net: An Efficient Subgraph-based Framework for Scene Graph Generation》(ECCV 2018)](https://arxiv.org/pdf/1806.11538.pdf)
+ [Pix2SG<Location-Free Scene Graph Generation>](https://arxiv.org/pdf/2303.10944v1.pdf)

### Datasets
-- Following three are Datasets for VRD or SGG.
+ [《Visual Relationship Detection with Language Priors》(ECCV 2016)](https://arxiv.org/pdf/1608.00187.pdf)

  VRD dataset: 5,000 images, 100 object categories, 70 relationship types.

+ [《Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations》(IJCV 2017)](https://arxiv.org/pdf/1602.07332.pdf)

  Visual Genome dataset: 108K images, average 35 objects, 26 attributes, 21 pairwise relationships per image.

+ [《4D-OR: Semantic Scene Graphsfor OR Domain Modeling》].(https://arxiv.org/pdf/2203.11937v1.pdf)
  
  4D-Object-Relation Dataset (4DOR): This dataset contains 10,000 images with annotations of 3D objects, 3D poses, human poses, and human-object interactions.



