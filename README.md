# Endo-SLAM Dataset
In this repository, endoscopy image dataset and the codes to manipulte these images and how these modifications affect the visual odometry algorithms will be introduced. 

If you use this code and dataset, please cite:

>    Kutsev Bengisu Ozyoruk, Gulfize Coskun, Guliz Irem Gokceler, Kagan Incetan, Yasin Almalioglu, Faisal Mahmood, Nicholas J. Durr, Eva Curto, Luis Perdigoto, Marina Oliveira, Helder Araujo, Henrique Alexandrino, Mehmet Turan. "Quantitative Evaluation of Endoscopic SLAM 
Methods: ENDO-SLAM Dataset.". 

## Overview

We introduce a comprehensive endoscopic SLAM dataset containing both capsule and standard endoscopy recordings.

In total, 35 sub-datasets are provided: 18 sub-datasets for colon, 12 sub-datasets for stomach and five sub-datasets for small intestine, whereas four of these contain polyp-mimicking elevations carried out by an expert gastroenterologist. 

### Contributions

The experimentally collected dataset is designed to meet the following major requirements for scientific research and development of endoscopic SLAM methods:
  - Time-synchronized, ground-truth 6 DoF pose data
  - High precision, ground-truth 3D reconstructions
  - Multiple organs from multiple individuals
  - Images from cameras with differing optical properties
  - Image sequences with differing native frame rates
  - A variety of lighting conditions
  - Distinguishable features of diagnostic significance (e.g. presence/absence of polyps)
  
### Equipment

The equipment employed during generation of the dataset from eight ex-vivo porcine GI-tract organs as following:

<p align="center">
<img src='imgs/collage_with_cams.png' width=620/> 
</p>

- **a)** Franka Emika Panda: robotic arm employed as motion device.
- **b)** Capsule Holder: special production two-piece holder used as a medium between the WCE cameras and the robotic arm.
- **c)** MiroCam Data Belt PillCam capsule endoscope
- **d)** Real Porcine Colon: sewn onto an 'L' shaped semi-cylindrical scaffold in high-density foam.
- **e)** MiroCam MR1100 receiver: Digital video grabber that converts analog data from receiver into digital to computer.
- **f)** PillCam recorder
- **g)** Artec Eva: 3D scanner used to generate ground truth - ply file. 
- **h)** EinScan Pro 2X: 3D scanner used to generate ground truth - .ply, .obj, .stl and .ASC file.
- **i)** Wireless Endoscope Camera (YPC-HD720P): high resolution - 1280×720 and HD640×480. 
- **j)** Endoscope 3 in 1 Camera: low resolution - 640×480.
- **k)** Camera Holder: special design one-piece holder for the high and low resolution endoscope cameras used to fixed on the robotic arm.
- **l)** PillCam COLON2: WCE double tip camera.
- **m)** MiroCam Regular MC1000-W: WCE camera employed to capture frames from real porcine stomach and send to receiver. 

### Collection of frames taken on endoscope trajectories

### 3D-Scanner Images for Endo-SLAM Dataset

## Getting Started

### 1. Installation

- Clone this repo:

```bash
cd ~
git clone https://github.com/CapsuleEndoscope/Endo-SLAM
cd Endo-X-Dataset
```

### 2. Prerequisites

-Matlab2020a

### 3. Code Base Structure

...

### 4. Dataset Organization

