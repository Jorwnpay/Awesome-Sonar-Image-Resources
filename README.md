# Awesome Sonar Image Resources

This repo gathers public datasets and code for sonar image perception, sonar-language alignment, sonar-optical multimodal learning, vision-language models (VLMs), image generation, 3D reconstruction, and embodied agents. Emerging world-model research and pending releases are tracked separately. Update weekly!

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

### 3. Segmentation

**1.[Forward-looking-Sonar-Segmentation-Dataset](https://github.com/XingYZhu/Forward-looking-Sonar-Segmentation-Dataset)**

**Description**: This forward-looking sonar(FLS) segmentation dataset including underwater boat and plane data. All the FLS data is obtained by Oculus M1200d sonar for academic research.

**2.[marine-debris-fls-datasets-watertank-segmentation](https://github.com/mvaldenegro/marine-debris-fls-datasets)**

**Description**: The dataset consists of images obtained from a forward looking SONAR and the corresponding semantic labels for 11 classes (except background).

**3.[AI4Shipwrecks](https://umfieldrobotics.github.io/ai4shipwrecks/)**

**Description**: A side-scan sonar shipwreck segmentation dataset collected by an autonomous underwater vehicle in Thunder Bay National Marine Sanctuary. It provides sonar images and binary masks for shipwrecks and associated debris, with training and test sets separated by site. The official project page links to the dataset download and the **IJRR 2025** paper.

**4.[SDVDs: Sonar Drowned Victim Datasets](https://github.com/AJaszcz/SDVDs-Sonar-Drowned-Victim-Datasets)**

**Description**: Three annotated sonar image subsets for drowned-victim segmentation: SDVD, CleanedSDVD, and ExtendedSDVD. They contain 256x256 grayscale images and binary masks, collected using a submerged metal effigy to simulate a human figure. A versioned archive is available on [Zenodo](https://zenodo.org/records/18268201).

**5.[Confined-MSIS](https://github.com/NGC4MR-YJ/Confined-MSIS)**

**Description**: A mechanically scanning imaging sonar dataset collected in confined underwater environments, with raw ping records from seven positions, rendered angle-range and polar images, and paired segmentation labels. The repository directly hosts data and segmentation ZIP archives, experimental setup documentation, and MATLAB rendering utilities. This is acquired sonar data and its image representations, rather than a simulated image corpus.

### 4. Sonar-Language Alignment and VLMs

**1.[OceanInstruction: Sonar-Open](https://huggingface.co/datasets/zjunlp/OceanInstruction/tree/main/Sonar-Open)**

**Description**: The sonar subset of the [OceanPile](https://arxiv.org/abs/2605.00877) instruction-tuning corpus, with 26,356 image-text instructions reported in the dataset card. It releases instruction/response tables and associated sonar images for target recognition and visual question answering, including Chinese and English examples. The wider corpus also contains optical and text-only subsets; this entry covers Sonar-Open. The 400-row preview on the main dataset page is a separate mixed example file.

### 5. Sonar-Optical Multimodal Perception

**1.[UXO Acoustic-Optical Dataset](https://zenodo.org/records/13778485)**

**Description**: Real underwater recordings with an ARIS 3000 imaging sonar and a GoPro camera, covering nearly 100 trajectories and over 74,000 frames of three unexploded-ordnance targets. Most sonar frames have matched optical frames; the release includes camera annotations, calibration, target-relative poses, and 3D models for cross-modal perception and reconstruction. Pairing uses motion-based temporal alignment rather than hardware-synchronized camera timestamps.

**2.[UMOD](https://github.com/UM-Research-Ng/UMOD-dataset)**

**Description**: A real underwater vision-sonar dataset collected by an ROV equipped with a BlueView M900 sonar and a ZED2 camera. It covers nine static and dynamic targets for cross-modal detection, tracking, and feature matching. The repository provides a demo and a Baidu Netdisk download link with an extraction code; visual and sonar images and labels are organized separately.

**3.[OA-Stereo: DAVE Sonar Dataset](https://huggingface.co/datasets/c237814486/dave_sonar)**

**Description**: A simulated opti-acoustic dataset generated with the DAVE underwater robotics platform for self-supervised stereo, dense depth estimation, and 3D reconstruction. Four scenes provide synchronized stereo RGB images, forward-looking sonar images, camera/sonar calibration, and depth or disparity maps. This public release is simulation data; the accompanying method also reports real-world experiments.

**4.[SubPipe](https://zenodo.org/records/12666132)**

**Description**: A real multimodal underwater pipeline inspection dataset with side-scan sonar, RGB cameras, and navigation sensors. The sonar images have pipeline detection bounding boxes; the segmentation annotations belong to the RGB images. The SubPipeMini2 download focuses on the side-scan sonar detection data. It supports studying complementary acoustic and optical observations, with modality-specific annotations.

**5.[AONeuS Demo Data](https://github.com/kzhang2/aoneus/tree/main/data)**

**Description**: A small synthetic acoustic-optical example bundled with the AONeuS reconstruction implementation. It provides RGB images, imaging-sonar observations, and camera/sonar configuration files for a simulated turtle scene. This is a public demonstration subset for testing multimodal neural surface reconstruction, rather than a complete real-world survey dataset. The corresponding implementation is listed under 3D Reconstruction and Novel View Synthesis.

**6.[SonarSweep Simulation Dataset](https://huggingface.co/datasets/Lingpenghaha/Sonarsweep_dataset)**

**Description**: Released simulated camera and forward-looking sonar observations for dense depth estimation and 3D reconstruction with SonarSweep. The [author repository](https://github.com/LIAS-CUHKSZ/SonarSweep) reports more than 7,000 data points and trajectory-based training, validation, and test splits. Public samples include stereo camera images, sonar frames, depth arrays, and calibration files; the hosting also includes a test manifest and OceanSim scene assets. This entry covers the simulation release; the authors describe further real-world data collection as ongoing.

**7.[HODOR](https://doi.pangaea.de/10.1594/PANGAEA.980000)**

**Description**: Real, synchronized forward-looking imaging-sonar and stereo-camera recordings from a stationary underwater fish observatory in the Baltic Sea. The [project](https://github.com/TAWilts/HODOR) reports 5,850 sequences and about 430 hours per sensor, with timestamps, environmental measurements, and species-activity counts. PANGAEA provides metadata and links to video files; bulk video archives require registration according to the authors. Machine-learning-based annotations are still announced as forthcoming, and the metadata activity counts differ from the publication's sonar-extrapolated species estimates.

### 6. Embodied Agent Benchmarks

**1.[OceanGym Benchmark Data](https://huggingface.co/datasets/zjunlp/OceanGym)**

**Description**: Released data and assets for a simulated underwater embodied-agent benchmark. Its perception tasks combine camera views, imaging sonar, and language-based evaluation under different lighting and context settings. The release also contains agent decision outputs and logs. This is a simulation benchmark for VLM perception and agent evaluation, rather than a real-world robot trajectory dataset.

### 7. Synthetic Data and Generative Augmentation

**1.[Synthetic Side-Scan Sonar FLUX+LoRA](https://www.kaggle.com/datasets/yangyuanxu/sonar-flux-synthetic)**

**Description**: A generated side-scan sonar detection dataset with 2,380 images and YOLO-format labels, covering body, plane, and ship targets. The [author repository](https://github.com/yanzhi0526/sonar-flux-lora-augmentation) documents 1,780 automatically screened images and a 600-image manually annotated subset, with file manifests and generation/screening metadata. All images in this release are synthetic; the original real sonar images and FLUX/LoRA weights are not redistributed. Data reuse follows the stated CC BY-NC-SA 4.0 terms.

### 8. Others

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

### 5. Multimodal Perception and Data Processing

**1.[OA-Stereo](https://github.com/c237814486/OA-Stereo)**

**Description**: The official **IEEE RA-L 2025** implementation of self-supervised opti-acoustic stereo for dense underwater depth estimation. It fuses calibrated optical and sonar observations and uses reconstructed-sonar consistency for supervision. The repository provides network and loss implementations, training, validation, visualization, and a link to its simulated DAVE dataset.

**2.[uxo-dataset2024](https://github.com/dfki-ric/uxo-dataset2024)**

**Description**: Official preparation and viewing utilities for the UXO acoustic-optical dataset. They extract ARIS sonar frames, generate polar images, align sonar and camera recordings using motion, process trajectories, and export paired records. The release includes calibration files and a viewer for stepping through matched observations.

**3.[SeafloorAI Data Processing](https://github.com/deep-real/SeafloorAI)**

**Description**: Public preprocessing code accompanying **NeurIPS 2024 Datasets and Benchmarks** SeafloorAI and its sonar-language extension SeafloorGenAI. It reprojects, resamples, merges, and patchifies sonar backscatter and bathymetry surveys, with slope and rugosity utilities. The currently verified release is preprocessing code; the full image-text dataset and VLM training implementation are not provided by this repository.

**4.[hodor-python](https://github.com/gboeer/hodor_python)**

**Description**: The Python data-access package linked by the HODOR authors. It loads sequence metadata and activity counts into pandas, filters sequences by species activity, and provides targeted downloads of paired stereo-camera and sonar videos. The repository includes package source and a command-line interface; it is a data-access and analysis utility rather than a pretrained perception model. See the HODOR entry under Datasets for data-access conditions and annotation limits.

### 6. Vision-Language Models and Embodied Agents

**1.[OceanGym](https://github.com/OceanGPT/OceanGym)**

**Description**: An open underwater simulation and evaluation environment for embodied agents. It provides VLM perception evaluation with camera-only, camera-plus-sonar, and sonar-example prompting settings, alongside language-driven decision tasks and agent execution code. The repository includes sensor data collection scripts and links to benchmark data. Its simulator supports acoustic and optical inputs; it is not a learned world model.

### 7. Text-to-Sonar Generation

**1.[Synth-SONAR](https://github.com/Purushothaman-natarajan/Synth-SONAR)**

**Description**: Public code for text-conditioned sonar image synthesis using diffusion models, style injection, and LoRA fine-tuning. It includes image-caption metadata preparation, language-model caption generation, a VLM captioning script, and style clustering. This resource supports sonar-language data preparation and generative augmentation; the repository does not establish a released sonar-language retrieval benchmark.

**2.[sonar-flux-lora-augmentation](https://github.com/yanzhi0526/sonar-flux-lora-augmentation)**

**Description**: Public reproduction assets for [Diffusion-Model-Based Data Augmentation for Target Detection in Side-Scan Sonar Images](https://www.mdpi.com/2072-4292/18/13/2193). They include YOLO configuration templates, prompt templates, label auditing and quality-screening utilities, evaluation scripts, and result tables. The synthetic image release is listed under Datasets; this repository does not redistribute the real source images or FLUX/LoRA checkpoints, so it is not a complete pretrained generator release.

### 8. 3D Reconstruction and Novel View Synthesis

**1.[SonarSplat](https://github.com/umfieldrobotics/sonar_splat)**

**Description**: The official **IEEE RA-L 2025** code for [SonarSplat: Novel View Synthesis of Imaging Sonar via Gaussian Splatting](https://arxiv.org/abs/2504.00159). It represents acoustic scenes with 3D Gaussians and provides imaging-sonar rasterization, training, image evaluation, mesh export, and reconstruction evaluation. The [project page](https://umfieldrobotics.github.io/sonarsplat3D/) links real sonar sequences with sensor poses and selected ground-truth meshes. This is scene reconstruction and rendering, rather than a learned action-conditioned world model.

**2.[AONeuS](https://github.com/kzhang2/aoneus)**

**Description**: The official **ACM SIGGRAPH 2024** implementation of [AONeuS: A Neural Rendering Framework for Acoustic-Optical Sensor Fusion](https://doi.org/10.1145/3641519.3657446). It combines optical and imaging-sonar measurements through neural implicit surfaces and sensor-specific rendering. The repository includes model, rendering, data-loading, and reconstruction code, configurations, and a runnable example with synthetic turtle observations; the bundled data are a demonstration subset.

**3.[SonarSweep](https://github.com/LIAS-CUHKSZ/SonarSweep)**

**Description**: Public code for [SonarSweep: Fusing Sonar and Vision for Robust 3D Reconstruction via Plane Sweeping](https://arxiv.org/abs/2511.00392). It matches camera and forward-looking sonar features in a differentiable plane-sweep cost volume to estimate dense metric depth. The repository includes training/testing scripts, network and geometric-warping implementations, a pretrained checkpoint, visualization utilities, and download helpers for its simulated dataset. The paper reports real-world experiments, while the verified public dataset is simulated.

## :hourglass_flowing_sand:Emerging Research and Release Tracking

These entries have public papers or partial releases, but their complete datasets or model implementations were not verified as publicly downloadable on 2026-10-25. Release status is checked during weekly maintenance.

### 1. Sonar-Language Datasets and VLMs

**1.[SeafloorGenAI / SeafloorAI](https://arxiv.org/abs/2411.00172)**

**Description**: A sonar-language seafloor mapping resource reporting 696K sonar images, 696K descriptions, and approximately 7M question-answer pairs. Language annotations are generated with GPT-4 using marine-scientist examples and geological attributes. The official repository currently states that hosting its 400GB dataset is pending and provides preprocessing code instead; a complete image-text download was not verified. See the released preprocessing resource under Codes.

**2.[SonarLLM / SonarBench](https://arxiv.org/abs/2608.24325)**

**Description**: A 2026 preprint on a native sonar-optical multimodal large language model and a paired benchmark for recognition, counting, visual question answering, and captioning. It studies sonar-only, optical-only, and fused inputs under controlled optical degradation. The paper is public; an official code, weights, or benchmark download was not verified as of the date above.

### 2. Sonar-Optical Datasets

**1.[uScenes](https://arxiv.org/abs/2608.27795)**

**Description**: A 2026 preprint describing real field recordings pairing RGB images with 3D multibeam imaging-sonar point clouds. The paper reports 110 scenes and 95,834 observation pairs; temporal association uses nearest timestamps with an 83 ms tolerance, rather than hardware synchronization. The acoustic representation is 3D returns rather than conventional 2D sonar images. The [repository linked by the authors](https://github.com/era-research-lab/uScenes) was empty when checked on 2026-10-18, so a usable code or dataset release was not verified.

**2.[RSFusion / RSFusionDet](https://arxiv.org/abs/2608.25367)**

**Description**: A 2026 preprint on RGB-sonar object detection and cross-modal object matching. It reports tank recordings from an Oculus MD750d imaging sonar and an optical camera, with 5,658 training and 1,415 validation image pairs spanning seven target classes, lighting conditions, and sonar range settings. The detector uses cross-attention for spatially misaligned features and an object-matching head. The [author-linked repository](https://github.com/LEFTeyex/RSFusionDet) was empty when checked on 2026-10-25, so the paper's claimed public code/data release was not verified.

### 3. World Models

**1.[AquaJEPA](https://arxiv.org/abs/2607.29393)**

**Description**: A 2026 preprint on action-conditioned predictive representations combining RGB, forward-looking sonar, proprioception, and thruster commands for underwater robot dynamics and planning. It studies future latent prediction and sensor dropout in Stonefish simulation, including camera-only and sonar-only variants. The paper is public; an official code, weights, or training-data download was not verified as of the date above. Reported validation is simulated.
