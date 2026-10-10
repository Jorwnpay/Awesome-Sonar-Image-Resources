# Awesome Sonar Image Resources

This repo gathers open-source sonar image resources for classification, detection, and segmentation. Update weekly!

> :mega:More open resources links are welcome:smiley:. Let's build a better open-source environment for sonar image recognition community together!:heart:Please feel free to contribute!

## :file_folder:Datasets

### 1. Classification

**1.[NKSID](https://github.com/Jorwnpay/NK-Sonar-Image-Dataset)**

**Description**: A newly created forward-looking sonar image recognition benchmark, named NanKai Sonar Image Dataset (NKSID). This dataset contains 2617 images from 8 categories, with labels showing a natural long tail distribution.

**2.[SeabedObjects-KLSG](https://github.com/huoguanying/SeabedObjects-Ship-and-Airplane-dataset)**

**Description**: This open dataset contains 385 ship images and 62 airplane images, and can be used for acedemic purpose.

**3.[marine-debris-fls-datasets-turntable-cropped](https://github.com/mvaldenegro/marine-debris-fls-datasets/tree/master/md_fls_dataset/data/turntable-cropped)**

**Description**: Marine-Debris Datasets captured with a Forward-Looking Sonar in a water tank and turntable using an ARIS Explorer 3000 Sonar. The turntable dataset is captured with the sonar in a fixed position and pose, while objects are placed in a rotating turntable, allowing to capture a full yaw rotation of each object. For now only a classification task is available.

**4.[Marine_PULSE](https://zenodo.org/records/7922705)**

**Description**: A side-scan sonar image classification dataset containing 627 images of pipelines or cables, underwater residual mounds, seabed surfaces, and engineering platforms. Images were collected using multiple sonar instruments, and the public download includes training and test splits.

### 2. Detection

**1.[Forward-looking-Sonar-Detection-Dataset](https://github.com/XingYZhu/Forward-looking-Sonar-Detection-Dataset)**

**Description**: This forward-looking sonar(FLS) detection dataset including underwater *victim, boat, and plane* data. All the FLS data is obtained by Oculus M1200d sonar for academic research.

**2.[SCTD: Sonar Common Target Detection Dataset](https://github.com/freepoet/SCTD)**

**Description**:  It collected 497 high resolution images obtained by side-scan sonars, forward-looking sonars, and (interferometric) synthetic aperture sonars, on which 596 targets are included. (The average number of targets per image is 1.2.)

**3.[UATD](https://openi.pcl.ac.cn/OpenOrcinus_orca/URPC2021_sonar_images_dataset)**

**Description**: The Pengcheng Laboratory provided this underwater sonar image dataset, comprising 7600 sonar images, and made it available as scientific data. This dataset includes three categories of regular geometric structure objects (cube, ball, and cylinder) and seven other types of underwater objects (human body, metal bucket, tyre, square cage, circle cage, plane, and ROV).

**4.[LSOD](https://github.com/Jelly0618/LSOD)**

**Description**: A long-range forward-looking sonar dataset for small-target detection, with images captured at scanning distances from 3 m to 40 m. The repository provides sample images and a Baidu Netdisk download link with an extraction code. It accompanies the **ESWA 2025** paper [A lightweight detector for small targets using forward-looking sonar in underwater search scenarios](https://doi.org/10.1016/j.eswa.2025.128373).

**5.[SWDD: Sonar Wall Detection Dataset](https://zenodo.org/records/13692547)**

**Description**: A side-scan sonar dataset for underwater wall detection, collected by an autonomous underwater vehicle carrying a Klein 3500 sonar. It provides 216 original images, 864 images after augmentation, COCO annotations, and 6243 annotated video frames. The release also includes SWDD-Validation and SWDD-Adversarial for robustness studies.

**6.[SubPipe](https://zenodo.org/records/12666132)**

**Description**: A multimodal underwater pipeline inspection dataset with side-scan sonar, RGB cameras, and navigation sensors. The sonar images have pipeline detection bounding boxes; the segmentation annotations belong to the RGB images. The SubPipeMini2 download focuses on the side-scan sonar detection data.

### 3. Segmentation

**1.[Forward-looking-Sonar-Segmentation-Dataset](https://github.com/XingYZhu/Forward-looking-Sonar-Segmentation-Dataset)**

**Description**: This forward-looking sonar(FLS) segmentation dataset including underwater boat and plane data. All the FLS data is obtained by Oculus M1200d sonar for academic research.

**2.[marine-debris-fls-datasets-watertank-segmentation](https://github.com/mvaldenegro/marine-debris-fls-datasets)**

**Description**: The dataset consists of images obtained from a forward looking SONAR and the corresponding semantic labels for 11 classes (except background).

**3.[AI4Shipwrecks](https://umfieldrobotics.github.io/ai4shipwrecks/)**

**Description**: A side-scan sonar shipwreck segmentation dataset collected by an autonomous underwater vehicle in Thunder Bay National Marine Sanctuary. It provides sonar images and binary masks for shipwrecks and associated debris, with training and test sets separated by site. The official project page links to the dataset download and the **IJRR 2025** paper.

**4.[SDVDs: Sonar Drowned Victim Datasets](https://github.com/AJaszcz/SDVDs-Sonar-Drowned-Victim-Datasets)**

**Description**: Three annotated sonar image subsets for drowned-victim segmentation: SDVD, CleanedSDVD, and ExtendedSDVD. They contain 256x256 grayscale images and binary masks, collected using a submerged metal effigy to simulate a human figure. A versioned archive is available on [Zenodo](https://zenodo.org/records/18268201).

### 4. Others

**1.[OpenSonarDatasets](https://github.com/remaro-network/OpenSonarDatasets)**

**Description**: A repository dedicated to consolidate open-source sonar datasets for underwater research and development. They provided a comprehensive summary of the currently available sonar datasets, which is an excellent piece of work.

## :computer:Codes

### 1. Classification

**1.[ZSL-SSS](https://github.com/guizilaile23/ZSL-SSS)**

**Description**: zero shot side scan sonar image classification code for **Applied Acoustics 2021** paper “<u>[Zero shot objects classification method of side scan sonar image based on synthesis of pseudo samples](https://www.sciencedirect.com/science/article/pii/S0003682X20307957)</u>”

**2.[ssl-sonar-images](https://github.com/agrija9/ssl-sonar-images)**

**Description**: This is the official repository for the [Self-supervised Learning for Sonar Image Classification](https://arxiv.org/abs/2204.09323) paper published at **CVPR2022 workshop**.

**3.[TGRS_BETL](https://github.com/Jorwnpay/TGRS_BETL)**

**Description**: This repo shows the source code of **IEEE TGRS 2022** article: [Sonar Images Classification While Facing Long-Tail and Few-Shot](https://ieeexplore.ieee.org/document/9910166).

**4.[TFRN](https://github.com/guizilaile23/TFRN)**

**Description**: Code and data of **Remote Sensing 2023** article: [A Texture Feature Removal Network for Sonar Image Classification and Detection](https://www.mdpi.com/2072-4292/15/3/616). (Baidu Cloud link)

**5.[Sonar-OLTR](https://github.com/Jorwnpay/Sonar-OLTR)**

**Description**: This repo contains the implementation code for the **ESWA 2024** article [Open-set recognition with long-tail sonar images](https://www.sciencedirect.com/science/article/pii/S0957417424003609).

**6.[GCEANet](https://github.com/baizhongyu/GCEANet)**

**Description**: The source code of the **IEEE TIM 2024** paper [Side-Scan Sonar Image Classification With Zero-Shot and Style Transfer](https://ieeexplore.ieee.org/document/10399359).

**7.[FETL](https://github.com/baizhongyu/FETL)**

**Description**: The source code of the paper Feature Enhancement-Based Transfer Learning for Few-Shot Sonar Image Classification. (Not available yet).

**8.[GZSL](https://github.com/JiaYP0433/CADA-Generalized-Zero-Shot-Side-Scan-Sonar-Image-Classification)**

**Description**:  The source code of the **IEEE TIM 2025** paper CADA-SSS Generalized Zero Shot Side Scan Sonar Image Classification.

### 2. Detection

**1.[underwater-object-detection](https://github.com/zhengye1995/underwater-object-detection)**

This is a repo for `Kesci underwater object detection algorithm contest`. (Readme file is in Chinese)

**2.[autodetector](https://github.com/automlresearch/autodetector)**

This is the official codes for IEEE TGRS 2021 paper `Self-trained detection detectors are implemented on small-scale Radar and Sonar detection datasets`.

**3.[KD-YOLOX-ViT](https://github.com/remaro-network/KD-YOLOX-ViT)**

**Description**: The official implementation of [Knowledge Distillation in YOLOX-ViT for Side-Scan Sonar Object Detection](https://arxiv.org/abs/2403.09313). It combines YOLOX, Vision Transformer layers, and knowledge distillation, with training and evaluation code for underwater wall detection on SWDD.

**4.[ROSAR-framework](https://github.com/remaro-network/ROSAR-framework)**

**Description**: The official implementation of ROSAR, an adversarial retraining framework for robust side-scan sonar object detection. It includes robustness analysis, adversarial example generation, and released ONNX models, with links to the SWDD validation and adversarial datasets.

### 3. Low-Level Tasks
**1.[WFC-BSN](https://github.com/xzq-2000/WFC-BSN)**

The code of EAAI 2025 article "WFC-BSN:Wavelet Fusion-Based Conditional Blind-Spot Network for Self-Supervised Forward Sonar Denoising".

### 4. Segmentation

**1.[SonarSAM](https://github.com/wangsssky/SonarSAM)**

**Description**: The official code for [When SAM Meets Sonar Images](https://arxiv.org/abs/2306.14109). It provides training and evaluation for adapting the Segment Anything Model to sonar images, including LoRA, visual prompt tuning, box prompts, and semantic segmentation on the Marine Debris dataset.

**2.[ai4shipwrecks-scripts](https://github.com/umfieldrobotics/ai4shipwrecks-scripts)**

**Description**: Official helper scripts for the AI4Shipwrecks segmentation dataset. They provide a PyTorch dataset loader and generate overlapping square crops from full-sized sonar images and their corresponding segmentation masks.
