<h1 align="center">Image Matting</h1>


This repo contains a comprehensive list of our research works related to **image matting**, including papers, codes, datasets, demos, and citations. For any related questions, please contact <strong><a href="https://github.com/jizhiziLi/">Jizhizi Li</a></strong> at [jili8515@uni.sydney.edu.au](mailto:jili8515@uni.sydney.edu.au) and <strong><a href="https://github.com/xymsh">Sihan Ma</a></strong> at [sima7436@uni.sydney.edu.au](mailto:sima7436@uni.sydney.edu.au).

***
>
><h3><strong><i>🚀 News</i></strong></h3>
>
> [2023-04-10]: Publish the paper [Deep Image Matting: A Comprehensive Survey](https://arxiv.org/abs/2304.04672) on arXiv.
> 
> [2023-03-28]: The paper [Rethinking Portrait Matting with Privacy Preserving](https://arxiv.org/abs/2203.16828) has been accepted by the International Journal of Computer Vision ([IJCV](https://www.springer.com/journal/11263)) 🎉
> 
> [2023-02-28]: The paper [Referring Image Matting](https://arxiv.org/abs/2206.05149) has been accepted by the Computer Vision and Pattern Recognition Conference ([CVPR](https://cvpr2023.thecvf.com/)) 🎉
***


## Overview

[1. Deep Image Matting: A Comprehensive Survey, arXiv, 2023](#survey) &emsp; <a href="https://arxiv.org/abs/2304.04672"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/JizhiziLi/matting-survey"><img src="https://img.shields.io/github/stars/JizhiziLi/matting-survey.svg?logo=github&label=Stars"></a>


[2. Rethinking Portrait Matting with Privacy Preserving, IJCV, 2023](#rethink_p3m) &emsp; <a href="https://arxiv.org/abs/2203.16828"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/ViTAE-Transformer/P3M-Net"><img src="https://img.shields.io/github/stars/ViTAE-Transformer/P3M-Net.svg?logo=github&label=Stars"></a> <a href="https://github.com/ViTAE-Transformer/P3M-Net#ppt-setting-and-p3m-10k-dataset"><img src="https://img.shields.io/badge/dataset-P3M--10k-orange">

[3. Referring Image Matting, CVPR, 2023](#rim) &emsp; <a href="https://arxiv.org/abs/2206.05149"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/JizhiziLi/rim/"><img src="https://img.shields.io/github/stars/JizhiziLi/rim.svg?logo=github&label=Stars"></a> <a href="https://github.com/JizhiziLi/rim/#refmatte"><img src="https://img.shields.io/badge/dataset-RefMatte-orange">

[4. Bridging Composite and Real: Towards End-to-end Deep Image Matting, IJCV, 2022](#gfm)  &emsp; <a href="https://arxiv.org/abs/2010.16188"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/JizhiziLi/gfm/"><img src="https://img.shields.io/github/stars/JizhiziLi/gfm.svg?logo=github&label=Stars"></a> <a href="https://github.com/JizhiziLi/gfm/#am-2k"><img src="https://img.shields.io/badge/dataset-AM--2k-orange"> <a href="https://github.com/JizhiziLi/gfm/#bg-20k"><img src="https://img.shields.io/badge/dataset-BG--20k-orange">

[5. Privacy-preserving Portrait Matting, ACM MM, 2021](#p3m) &emsp; <a href="https://arxiv.org/abs/2104.14222"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/JizhiziLi/p3m/"><img src="https://img.shields.io/github/stars/JizhiziLi/p3m.svg?logo=github&label=Stars"></a> <a href="https://github.com/JizhiziLi/p3m/#ppt-setting-and-p3m-10k-dataset"><img src="https://img.shields.io/badge/dataset-P3M--10k-orange">

[6. Deep Automatic Natural Image Matting, IJCAI, 2021](#aim) &emsp; <a href="https://arxiv.org/abs/2107.07235"><img  src="https://img.shields.io/badge/arxiv-Paper-brightgreen" ></a> <a href="https://github.com/JizhiziLi/aim/"><img src="https://img.shields.io/github/stars/JizhiziLi/aim.svg?logo=github&label=Stars"></a> <a href="https://github.com/JizhiziLi/aim/#aim-500"><img src="https://img.shields.io/badge/dataset-AIM--500-orange"></a>


## Projects

### <span id="survey">📘 Deep Image Matting: A Comprehensive Survey [arXiv-2023]</span>

<em>Jizhizi Li, Jing Zhang, and Dacheng Tao</em>

[Paper](https://arxiv.org/abs/2304.04672) | [Github Code](https://github.com/JizhiziLi/matting-survey) | [BibTex](./assets/arXiv_2023_Survey/matting_survey.bib)

Image matting refers to extracting precise alpha matte from natural images, and it plays a critical role in various downstream applications, such as image editing. The emergence of deep learning has revolutionized the field of image matting and given birth to multiple new techniques, including automatic, interactive, and referring image matting. Here we present a comprehensive review of recent advancements in image matting in the era of deep learning.

<img src="https://github.com/JizhiziLi/matting-survey/raw/master/src/timeline.jpg" width="100%">

***

### <span id="rethink_p3m">📘 Rethinking Portrait Matting with Privacy Preserving [IJCV-2023]</span>

<img src="https://github.com/ViTAE-Transformer/P3M-Net/raw/main/demo/gif/p_3cf7997c.gif" width="25%"><img src="https://github.com/ViTAE-Transformer/P3M-Net/raw/main/demo/gif/2.gif" width="25%"><img src="https://github.com/ViTAE-Transformer/P3M-Net/raw/main/demo/gif/3.gif" width="25%"><img src="https://github.com/ViTAE-Transformer/P3M-Net/raw/main/demo/gif/4.gif" width="25%">

<em>Sihan Ma<sup>&#8727;</sup>, Jizhizi Li<sup>&#8727;</sup>, Jing Zhang, He Zhang, and Dacheng Tao. (*equal contribution)</em>

[Paper](https://arxiv.org/abs/2203.16828) | [Github Code](https://github.com/ViTAE-Transformer/P3M-Net) | [Dataset](https://github.com/ViTAE-Transformer/P3M-Net#ppt-setting-and-p3m-10k-dataset) | [Demo](https://colab.research.google.com/drive/1pD_XKx31Lgd7zwq46dRpz2jGdsH1ZIay?usp=sharing) | [BibTex](./assets/IJCV_2023_Rethink_P3M/rethink_p3m.bib)

This paper introduces three variants of P3M-Net based on both transformer and CNN backbones to solve the portrait matting problem with privacy preserving. Also a simple yet effective Copy and Paste strategy (P3M-CP) is devised to enable the matting model to process both face-blurred and normal images without extra effort during inference.

<img src="https://github.com/ViTAE-Transformer/P3M-Net/raw/main/demo/p3m-net-variants.png" width="100%">

---

### <span id="rim">📘 Referring Image Matting [CVPR-2023]</span>

<img src="https://github.com/JizhiziLi/RIM/raw/master/demo/src/more_k.jpg" width="50%"><img src="https://github.com/JizhiziLi/RIM/raw/master/demo/src/more_rw.jpg" width="50%">

<em>Jizhizi Li, Jing Zhang, and Dacheng Tao</em>

[Paper](https://arxiv.org/abs/2206.05149) |  [Github Code](https://github.com/JizhiziLi/rim/) | [Dataset](https://github.com/JizhiziLi/rim/#refmatte) | [BibTex](./assets/CVPR_2023_RIM/rim.bib)

Image matting refers to extracting the accurate foregrounds in the image. Current automatic methods tend to extract all the salient objects in the image indiscriminately. In this paper, we propose a new task named Referring Image Matting (RIM), referring to extracting the meticulous alpha matte of the specific object that can best match the given natural language description. We then propose a large-scale dataset RefMatte and a carefully designed method CLIPMat to serve as a baseline suite for RIM. We believe the new task RIM along with the RefMatte dataset and the method CLIPMat will open new research directions in this area and facilitate future studies.

<img src="https://github.com/JizhiziLi/RIM/raw/master/demo/src/clipmat.png" width="100%">

---

### <span id="gfm">📘 Bridging Composite and Real: Towards End-to-end Deep Image Matting [IJCV-2022]</span>


<img src="https://github.com/JizhiziLi/GFM/raw/master/demo/src/homepage/spring.gif" width="25%"><img src="https://github.com/JizhiziLi/GFM/raw/master/demo/src/homepage/summer.gif" width="25%"><img src="https://github.com/JizhiziLi/GFM/raw/master/demo/src/homepage/autumn.gif" width="25%"><img src="https://github.com/JizhiziLi/GFM/raw/master/demo/src/homepage/winter.gif" width="25%">


<em>Jizhizi Li<sup>1&#8727;</sup>, Jing Zhang<sup>1&#8727;</sup>, Stephen J. Maybank, and Dacheng Tao</em>. (*equal contribution)


[Paper](https://arxiv.org/abs/2010.16188) |  [Github Code](https://github.com/JizhiziLi/gfm/) | [Dataset](https://github.com/JizhiziLi/gfm/#am-2k) | [Demo](https://colab.research.google.com/drive/1EaQ5h4u9Q_MmDSFTDmFG0ZOeSsFuRTsJ?usp=sharing) | [BibTex](./assets/IJCV_2022_GFM/gfm.bib)

We propose a novel Glance and Focus Matting network (GFM), which employs a shared encoder and two separate decoders to learn both tasks in a collaborative manner for end-to-end image matting. We also establish a novel Animal Matting dataset (AM-2k) to serve for end-to-end matting task. Furthermore, we investigate the domain gap issue between composition images and natural images systematically, propose a carefully designed composite route RSSN and a large-scale high-resolution background dataset (BG-20k) to serve as better candidates for composition.

<img src="https://github.com/JizhiziLi/GFM/raw/master/demo/src/homepage/gfm.png" width="100%">

---

### <span id="p3m">📘 Privacy-Preserving Portrait Matting [ACM MM-21]</span>

<img src="https://github.com/JizhiziLi/P3M/raw/master/demo/gif/p_2c2e4470.gif" width="25%"><img src="https://github.com/JizhiziLi/P3M/raw/master/demo/gif/p_4dfffce8.gif" width="25%"><img src="https://github.com/JizhiziLi/P3M/raw/master/demo/gif/p_d4fd9815.gif" width="25%"><img src="https://github.com/JizhiziLi/P3M/raw/master/demo/gif/p_64da52e3.gif" width="25%">

<em>Jizhizi Li<sup>&#8727;</sup>, Sihan Ma<sup>&#8727;</sup>, Jing Zhang, and Dacheng Tao. (*equal contribution)</em>

[Paper](https://arxiv.org/abs/2104.14222) | [Github Code](https://github.com/JizhiziLi/P3M) | [Dataset](https://github.com/JizhiziLi/p3m/#ppt-setting-and-p3m-10k-dataset) | [BibTex](./assets/ACM_MM_2021_P3M/p3m.bib)

This work presents P3M-10k, which is the first large-scale anonymized benchmark for Privacy-Preserving Portrait Matting, to solve the increasing concerns about the privacy in image matting. They also propose P3M-Net, which leverages the power of a unified framework for both semantic perception and detail matting, and specifically emphasizes the interaction between them and the encoder to facilitate the matting process. 

<img src="https://github.com/JizhiziLi/P3M/raw/master/demo/network.png" width="100%">

---

### <span id="aim">📘 Deep Automatic Natural Image Matting [IJCAI-21]</span>

<img src="https://github.com/JizhiziLi/AIM/raw/master/demo/o_e92b90fc.gif" width="33%"><img src="https://github.com/JizhiziLi/AIM/raw/master/demo/o_2749e288.gif" width="33%"><img src="https://github.com/JizhiziLi/AIM/raw/master/demo/o_87e77b32.gif" width="33%">

<em>Jizhizi Li, Jing Zhang, and Dacheng Tao</em>

[Paper](https://arxiv.org/abs/2107.07235) | [Github Code](https://github.com/JizhiziLi/aim/) | [Dataset](https://github.com/jizhiziLi/aim#aim-500) | [BibTex](./assets/IJCAI_2021_AIM/aim.bib)

We investigate the difficulties when extending the automatic matting methods to natural images with salient transparent/meticulous foregrounds or non-salient foregrounds by proposing a novel end-to-end matting network, which can predict a generalized trimap for any image of the above types as a unified semantic representation and simultaneously guide the matting network to focus on the transition areas via an attention mechanism. We also construct a test set AIM-500 that contains 500 diverse natural images covering all types along with manually labeled alpha mattes, making it feasible to benchmark the generalization ability of AIM models.

<img src="https://github.com/JizhiziLi/AIM/raw/master/demo/network.png" width="100%">







