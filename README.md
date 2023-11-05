# Awesome Image Matting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of deep learning image matting papers and codes since 2016, Inspired by [awesome-object-detection](https://github.com/amusi/awesome-object-detection), [deep_learning_object_detection](https://github.com/hoya012/deep_learning_object_detection) and [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers).

#### UPDATE
- [x] Video Matting


#### :star: If you find this repo useful, please star it!!

## Background

**Image Matting** is the process of accurately estimating the foreground object in images and videos. It is a very important technique in image and video editing applications, particularly in film production for creating visual effects. In case of image segmentation, we segment the image into foreground and background by labeling the pixels. Image segmentation generates a binary image, in which a pixel either belongs to foreground or background. However, Image Matting is different from the image segmentation, wherein some pixels may belong to foreground as well as background, such pixels are called partial or mixed pixels. In order to fully separate the foreground from the background in an image, accurate estimation of the alpha values for partial or mixed pixels is necessary.

## Video Matting

- Attention-guided Temporally Coherent Video Object Matting [MM 2021] [Paper](https://arxiv.org/abs/2105.11427)

- Deep Video Matting via Spatio-Temporal Alignment and Aggregation [CVPR 2021] [Paper](https://arxiv.org/abs/2104.11208) [Code](https://github.com/nowsyn/DVM)

- Robust High-Resolution Video Matting with Temporal Guidance [WACV 2022] [Paper](https://arxiv.org/pdf/2108.11515.pdf) [Code](https://github.com/PeterL1n/RobustVideoMatting) [Project](https://peterl1n.github.io/RobustVideoMatting/#/)

## Image Matting

- ViTMatte: Boosting Image Matting with Pretrained Plain Vision Transformers [Information Fusion] [Paper](https://arxiv.org/abs/2305.15272)  [Code](https://github.com/hustvl/ViTMatte)  [🤗Transformers-ViTMatte](https://huggingface.co/docs/transformers/main/model_doc/vitmatte#vitmatte) :fire:

- MatteFormer: Transformer-Based Image Matting via Prior-Tokens [CVPR 2022] [Paper](https://arxiv.org/abs/2203.15662)  [Code](https://github.com/webtoon/matteformer) :fire:

- Boosting Robustness of Image Matting with Context Assembling and
Strong Data Augmentation [arXiv 2022] [Paper](https://arxiv.org/abs/2201.06889)

- MODNet: Real-Time Trimap-Free Portrait Matting via Objective Decomposition [AAAI 2022] [Paper](https://arxiv.org/pdf/2011.11961.pdf) [Code](https://github.com/ZHKKKe/MODNet)

- Deep Automatic Natural Image Matting [IJCAI 2021] [Paper](https://arxiv.org/abs/2107.07235) [Code](https://github.com/JizhiziLi/AIM)

- Deep Image Matting with Flexible Guidance Input [BMVC 2021] [Paper](https://arxiv.org/abs/2110.10898) [Code](https://github.com/Charch-630/FGI-Matting)

- Highly Efficient Natural Image Matting [BMVC 2021] [Paper](https://arxiv.org/abs/2110.12748)

- Semantic Image Matting [CVPR 2021] [Paper](https://arxiv.org/abs/2104.08201) [Code](https://github.com/nowsyn/SIM)

- Towards Enhancing Fine-grained Details for Image Matting [WACV 2021] [Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Liu_Towards_Enhancing_Fine-Grained_Details_for_Image_Matting_WACV_2021_paper.pdf)

- Multi-scale Information Assembly for Image Matting [Pacific Graphics 2020] [Paper](https://arxiv.org/abs/2101.02391)

- Improved Image Matting via Real-time User Clicks and Uncertainty Estimation [CVPR 2021] [Paper](https://arxiv.org/abs/2012.08323)

- Mask Guided Matting via Progressive Refinement Network [CVPR 2021] [Paper](https://arxiv.org/pdf/2012.06722.pdf) 

- Real-Time High-Resolution Background Matting [CVPR 2021] [Paper](https://arxiv.org/abs/2012.07810) [Code](PeterL1n/BackgroundMattingV2)


- End-to-end Animal Image Matting [arXiv] [Paper](https://arxiv.org/pdf/2010.16188.pdf) [Code](https://github.com/JizhiziLi/animal-matting)

- Hierarchical Opacity Propagation for Image Matting [arXiv] [Paper](https://arxiv.org/pdf/2004.03249.pdf) [Code](https://github.com/Yaoyi-Li/HOP-Matting)

- High-Resolution Deep Image Matting [AAAI 2021] [Paper](https://arxiv.org/abs/2009.06613)

- FBA: F, B, Alpha Matting. [arXiv] [Paper](https://arxiv.org/abs/2003.07711) [Code](https://github.com/MarcoForte/FBA_Matting) 

- Background Matting: The World is Your Green Screen. [CVPR 2020] [Paper](https://arxiv.org/pdf/2004.00626v2.pdf) [Code](https://github.com/senguptaumd/Background-Matting) [ProjectPage](https://grail.cs.washington.edu/projects/background-matting/) :fire:

- HAttMatting: Attention-Guided Hierarchical Structure Aggregation for Image Matting [CVPR 2020] [Paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Qiao_Attention-Guided_Hierarchical_Structure_Aggregation_for_Image_Matting_CVPR_2020_paper.pdf) [ProjectPage](https://wukaoliu.github.io/HAttMatting/)

- Boosting Semantic Human Matting with Coarse Annotations[CVPR 2020] [Paper](https://arxiv.org/pdf/2004.04955.pdf)

- Natural Image Matting via Guided Contextual Attention. [AAAI 2020] [Paper](http://arxiv.org/abs/2001.04069) [Code](https://github.com/Yaoyi-Li/GCA-Matting) :fire: 

- Indices Matter: Learning to Index for Deep Image Matting. [ICCV 2019] [Paper](https://arxiv.org/abs/1908.00672) [Code](https://github.com/poppinace/indexnet_matting) :fire: 

- Context-Aware Image Matting for Simultaneous Foreground and Alpha Estimation [ICCV 2019] [Paper](https://arxiv.org/pdf/1909.09725v2.pdf) [Code](https://github.com/hqqxyy/Context-Aware-Matting) :fire: 

- Disentangled Image Matting [ICCV 2019] [Paper](https://arxiv.org/abs/1909.04686)

- LFM: A Late Fusion CNN for Digital Matting. [CVPR 2019] [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_A_Late_Fusion_CNN_for_Digital_Matting_CVPR_2019_paper.pdf)

- Learning-based sampling for natural image matting [CVPR 2019] [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tang_Learning-Based_Sampling_for_Natural_Image_Matting_CVPR_2019_paper.pdf)

- Very Deep Residual Network for Image Matting [ICIP 2019] [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8803682)

- SHM: Semantic Human Matting. [MM 18] [Paper](https://arxiv.org/pdf/1809.01354.pdf)

- AlphaGAN: Generative adversarial networks for natural image matting. [BMVC 2018] [Paper](https://arxiv.org/abs/1807.10088) [ProjectPage](https://v-sense.scss.tcd.ie/research/deep-learning/alphagan-generative-adversarial-networks-for-natural-image-matting/)

- DIM: Deep Image Matting. [CVPR 2017] [Paper](https://arxiv.org/abs/1703.03872) [Code](https://github.com/foamliu/Deep-Image-Matting-PyTorch) [ProjectPage](https://sites.google.com/view/deepimagematting) :fire: 

- Deep Automatic Portrait Matting. [ECCV 2016] [Paper](http://www.cse.cuhk.edu.hk/~leojia/projects/automatting/papers/deepmatting.pdf) [ProjectPage](http://www.cse.cuhk.edu.hk/~leojia/projects/automatting/index.html) 


## Dataset & BenchMark

- alphamatting: [www.alphamatting.com](www.alphamatting.com)
- Compostition-1K: [Please Email the Author](https://sites.google.com/view/deepimagematting)
- Distinctions-646: [Please Email the Author](https://wukaoliu.github.io/HAttMatting/)
- Matting Human Datasets: [Github](https://github.com/aisegmentcn/matting_human_datasets) [WebPage](www.aisegment.com)

## Tools
- [pymatting](https://github.com/pymatting/pymatting)

## Evaluation Methods
- A Perceptually Motivated Online Benckmark for Image Matting. [CVPR 2009] [Paper](https://www.microsoft.com/en-us/research/publication/a-perceptually-motivated-online-benchmark-for-image-matting/)
