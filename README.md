# WiCAL: Accurate Wi-Fi-Based 3D Localization Enabled by Collaborative Antenna Arrays

### <p align="center"> [📰Paper](https://ieeexplore.ieee.org/abstract/document/11072249)</p>

Accurate 3D localization is essential for realizing advanced sensing functionalities in next-generation Wi-Fi communication systems. This study investigates the potential of multistatic localization in Wi-Fi networks through the deployment of multiple cooperative antenna arrays. 

### Dataset Description
This repository aims to open-source real-world measured datasets for wireless sensing research. It provides Channel State Information (CSI) datasets collected using RF-switch-based multiplexing of multiple RF chains. The data were acquired for wireless sensing tasks using antenna array configurations and are categorized into two types:

#### Single-Array CSI for 3D AoA Estimation
CSI measurements collected from a single Uniform Rectangular Array (URA) using RF switching. These data are suitable for high-resolution 3D Angle-of-Arrival (AoA) estimation and beamforming research.

#### Dual-Array CSI for 3D Localization
CSI measurements jointly captured from two spatially separated URAs. These data enable 3D source localization via collaborative signal processing across arrays, supporting algorithm development in geometric or learning-based localization.

All data were collected under controlled settings with known ground truth positions and synchronized switching sequences.

### Data preparation
#### WiCAL 3D AoA Dataset
Download the dataset from [LINK](https://drive.google.com/file/d/1bLcx-BwGriu5drKyFbsueIgeqMj9aLzc/view?usp=drive_link).

#### Data Structure
We organize the datasets like this:
```
├── data
    ├── test.2024.9.5
    |   ├── 1_1.dat
    |   ├── 2_1.dat
    |   ├── ...
    |   ├── x_1.dat
    |   ├── ...
```

### Running
RUN main_52G.m in MATLAB without any issues.



### Citation
If you find our work useful in your research, please be so kind to cite:
```
@article{wang2025wical,
  title={WiCAL: Accurate Wi-Fi-based 3D localization enabled by collaborative antenna arrays},
  author={Wang, Fuhai and Li, Zhe and Xiong, Rujing and Mi, Tiebin and Qiu, Robert Caiming},
  journal={IEEE Journal on Selected Areas in Communications},
  year={2025},
  volume={43},
  number={11},
  pages={3752-3765}
}
```



