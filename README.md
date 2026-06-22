# RSD-YOLO Rail Surface Defect Dataset

This repository provides the rail surface defect dataset used in the paper:

**RSD-YOLO: A Lightweight Model for Rail Surface Defect Detection**

## 1. Dataset Description

The dataset contains rail surface defect images for object detection. It includes three defect categories:

| Class ID | Class Name |
|---|---|
| 0 | Spalling |
| 1 | Wheel burn |
| 2 | Squat |

The annotations are provided in YOLO txt format. Each image has a corresponding label file with the same file name.

## 2. Dataset Size

The dataset contains 4,020 images in total.

| Split | Number of Images |
|---|---:|
| Train | 3,216 |
| Validation | 402 |
| Test | 402 |
| Total | 4,020 |

## 3. Directory Structure

```text
RSD-YOLO-Dataset/
├── data.yaml
├── classes.txt
├── train.txt
├── val.txt
├── test.txt
├── images/
│   ├── train/
│   ├── val/
│   └── test/
├── labels/
│   ├── train/
│   ├── val/
│   └── test/
└── stats/
    └── class_distribution.csv
