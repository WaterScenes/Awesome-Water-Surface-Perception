
# Awesome Water Surface Perception

<img src='images/cover.jpg' width=600 /> 

## Overview
- [Teams](#teams)
- [Workshops](#workshops)
- [Surveys](#surveys)
- [Datasets](#datasets)
- [Tasks](#tasks)
  - [Detection](#detection)
    - [Small Object Detection](#small-object-detection)
  - [Segmentation](#segmentation)
  - [Tracking](#tracking)


## Teams
* ### WaterScenes [[Website](https://github.com/WaterScenes)] 
  University of Liverpool, Xi'an Jiaotong-Liverpool University, Institute of Deep Perception Technology, Jiangsu Industrial Technology  Research Institute

  
* ### Marine Intelligent Perception and Computation (MIPC) Group [[Website]](http://mipc.whut.edu.cn/publications.html) 
  Wuhan University of Technology
  
* ### Visual Cognitive Systems (ViCos) Laboratory [[Website](https://vicos.si/research/autonomous-boats) [Datasets](https://box.vicos.si/borja/viamaro/index.html)] 
  University of Ljubljana 

## Workshops

* ### MaCVi 2024
  * The 2nd Workshop on Maritime Computer Vision (MaCVi) 2024 [[Website](https://macvi.org/workshop/macvi24) [Results](https://arxiv.org/abs/2311.14762)]
  * Baseline: **SeaDronesSee**: A Maritime Benchmark for Detecting Humans in Open Water [__`SeaDroneSee`__] [[Paper](https://arxiv.org/abs/2105.01922)]
  * 2023 - **Sea You Later**: Metadata-Guided Long-Term Re-Identification for UAV-Based Multi-Object Tracking [__`SeaDroneSee-MOT`__] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.03561)] (1st place of the UAV-based Multi-Object Tracking with Reidentification Challenge)
  * 2023 - **ReIDTracker Sea**: the technical report of BoaTrack and SeaDronesSee-MOT challenge at MaCVi [__`SeaDroneSee-MOT`__] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.07616)]


## Surveys
  * 2023 - Deep learning-based object detection in maritime unmanned aerial vehicle imagery: Review and experimental comparisons __`EAAI`__ [[Paper](https://www.sciencedirect.com/science/article/pii/S0952197623016974)]

## Datasets

| **Name** | **Year** | **Task** | **Affiliation** | **Link** |
| --- | --- | --- | --- | --- |
| **MarDCT** | 2015 | Classification <br> Object Detection <br> Tracking | Sapienza University of Rome| [Website](http://www.diag.uniroma1.it//~labrococo/MAR/index.htm) <br> [Paper](http://www.diag.uniroma1.it//~bloisi/papers/bloisi-vrs2015-draft.pdf) |
| **MODD** | 2016 | Object Detection <br> Semantic Segmentation | University of Ljubljana| [Website](http://vision.fe.uni-lj.si/RESEARCH/modd/) <br> [Paper](https://arxiv.org/abs/1503.01918) <br> [Github](https://vicos.si/resources/modd/) |
| **SMD** | 2017 | Object Detection <br> Object Tracking | The Arctic University of Norway| [Website](https://sites.google.com/site/dilipprasad/home/singapore-maritime-dataset) <br> [Paper](https://openaccess.thecvf.com/content_CVPRW_2019/papers/PBVS/Moosbauer_A_Benchmark_for_Deep_Learning_Based_Object_Detection_in_Maritime_CVPRW_2019_paper.pdf) <br> [Github](https://github.com/yaoshanliang/Singapore-Maritime-Dataset) |
| **Visual-Inertial-Canoe dataset**  | 2018 | SLAM |  University of Illinois at Urbana-Champaign| [Website](https://databank.illinois.edu/datasets/IDB-9342111) <br> [Paper](https://journals.sagepub.com/doi/pdf/10.1177/0278364917751842)|
| **MODD2** | 2018 | Object Detection <br> Semantic Segmentation  |University of Ljubljana| [Website](https://box.vicos.si/borja/viamaro/index.html) <br> [Paper](https://arxiv.org/abs/1802.07956) <br> [Github](https://arxiv.org/abs/1802.07956) |
| **MaSTr1325** | 2019 | Semantic Segmentation | University of Ljubljana| [Website](https://vicos.si/resources/mastr1325/) <br> [Paper](https://ieeexplore.ieee.org/document/8967909) <br> [Github](https://github.com/bborja/modd) |
| **Tampere-WaterSeg** | 2019 | Semantic Segmentation | Tampere University| [Paper](https://ieeexplore.ieee.org/document/8918694) |
| **MID** | 2020 | Object Detection | Shanghai University| [Paper](https://doi.org/10.1002/rob.21983) <br> [Github](https://github.com/aluckyi/MID) |
| **WSODD** | 2021 | Object Detection <br> Instance Segmentation | Beijing Institute of Technology | [Paper](https://www.frontiersin.org/articles/10.3389/fnbot.2021.723336/full) <br>[Github](https://github.com/sunjiaen/WSODD) |
| **USVInland** | 2021 | SLAM <br> Stereo Matching <br> Water Segmentation | ORCA-tech | [Weibsite](https://www.orca-tech.cn/datasets/USVInland/Introduction) <br> [Paper](https://arxiv.org/abs/2103.05383) <br> [Github](https://github.com/ORCA-Uboat/USVInland-Dataset) |
| **FloW** | 2021 | Object Detection <br> Multimodal Object Detection | ORCA-tech | [Website](https://www.orca-tech.cn/datasets/FloW/Introduction) <br> [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Cheng_FloW_A_Dataset_and_Benchmark_for_Floating_Waste_Detection_in_ICCV_2021_paper.html) <br> [Github](https://github.com/ORCA-Uboat/USVInland-Dataset) |
| **SeaDronesSee** | 2021 | Object Detection <br> Object Tracking | University of Tuebingen | [Website](https://seadronessee.cs.uni-tuebingen.de) <br> [GitHub](https://github.com/Ben93kie/SeaDronesSee) <br> [Paper](https://openaccess.thecvf.com/content/WACV2022/html/Varga_SeaDronesSee_A_Maritime_Benchmark_for_Detecting_Humans_in_Open_Water_WACV_2022_paper.html) |
| **WaterScenes** | 2023 | Object Detection <br> Instance Segmentation <br> Semantic Segmentation <br> Free-Space Segmentation <br> Waterline Segmentation <br> Panoptic Perception | University of Liverpool | [Website](https://waterscenes.github.io) <br> [GitHub](https://github.com/WaterScenes/WaterScenes) <br> [Paper](https://arxiv.org/abs/2307.06505) |
| **LaRS** | 2023 | Semantic Segmentation <br> Panoptic Segmentation | University of Ljubljana | [Website](https://lojzezust.github.io/lars-dataset) <br> [GitHub](https://github.com/lojzezust/lars_evaluator) <br> [Paper](https://arxiv.org/abs/2308.09618) |




## Tasks

### Detection

* 2023 - Achelous: A Fast Unified Water-surface Panoptic Perception Framework based on Fusion of Monocular Camera and 4D mmWave Radar __`ITSC`__ [__`WaterScenes`__] [[Paper](https://arxiv.org/abs/2307.07102) [GitHub](https://github.com/GuanRunwei/Achelous)]

#### Small Object Detection
* 2023 - A novel Multi to Single Module for small object detection  [__`SeaDroneSee`__] [[Paper](https://arxiv.org/abs/2303.14977)]

### Segmentation

### Tracking
* 2021 - A Robust Deep Affinity Network for Multiple Ship Tracking  __`TIM`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/9423987)]
* 2023 - Asynchronous Trajectory Matching-Based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways __`TITS`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10159572)]

* 2023 - Stable Yaw Estimation of Boats from the Viewpoint of UAVs and USVs __`ECMR`__ [[Paper](https://arxiv.org/abs/2306.14056)]
