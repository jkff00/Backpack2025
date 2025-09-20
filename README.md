# Large-Scale LiDAR-Inertial Dataset for Degradation-Robust High-Precision Mapping

## 🎥 Demo
[![Watch the video](./images/abstract.png)](https://github.com/CNITECH-CV-LAB/Backpack2025/releases/download/v1.0/ral-video-2k.mp4)  
👉 [Download video](https://github.com/CNITECH-CV-LAB/Backpack2025/releases/download/v1.0/ral-video-2k.mp4)

### Dataset Structure
```
dataset_root/
└─ sequences/
├─ seq01/
│ ├─ bag/ # ROS bag with IMU (400Hz), LiDAR (dual 10Hz), RTK-GNSS (1Hz)
│ ├─ pcd/ # Deskewed LiDAR scans in .pcd format
│ │ ├─ 0.pcd
│ │ ├─ 1.pcd
│ │ └─ ...
│ ├─ gt/ # Ground truth poses
│ │ └─ GT_pose.txt # TUM format
│ └─ calib.yaml # Calibration parameters
├─ seq02/
│ └─ ...
└─ seq08/
```
## 📦 Dataset Download

The dataset is hosted on Google Drive.  
👉 You can download individual sequences using the links below:

| Sequence | Length (m) | Duration (s) | Size (GB) | Environment | Download |
|----------|------------|--------------|-----------|-------------|----------|
| Seq.1    | 1561.8     | 1558.3       | 82.0      | Dense building cluster (indoor corridors) | [Google Drive](https://drive.google.com/file/d/SEQ01_ID/view?usp=sharing) |
| Seq.2    | 1279.0     | 1174.9       | 65.3      | Dense building cluster (outdoor loop) | [Google Drive](https://drive.google.com/file/d/SEQ02_ID/view?usp=sharing) |
| Seq.3    | 1002.0     | 1626.6       | 88.7      | Multi-story, IO transitions | [Google Drive](https://drive.google.com/file/d/SEQ03_ID/view?usp=sharing) |
| Seq.4    | 1764.3     | 1688.1       | 97.2      | Mountainous terrain | [Google Drive](https://drive.google.com/file/d/SEQ04_ID/view?usp=sharing) |
| Seq.5    | 814.4      | 1101.6       | 62.0      | Multi-story tower | [Google Drive](https://drive.google.com/file/d/SEQ05_ID/view?usp=sharing) |
| Seq.6    | 1833.2     | 1791.8       | 87.5      | Underground tunnel | [Google Drive](https://drive.google.com/file/d/SEQ06_ID/view?usp=sharing) |
| Seq.7    | 1505.4     | 1849.6       | 100.4     | Dense architecture, IO transitions | [Google Drive](https://drive.google.com/file/d/SEQ07_ID/view?usp=sharing) |
| Seq.8    | 1307.8     | 1245.3       | 70.9      | Dense architecture, long corridor | [Google Drive](https://drive.google.com/file/d/SEQ08_ID/view?usp=sharing) |
