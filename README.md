# WaveMamba-YOLO - Datasets
This document lists the datasets used in the WaveMamba-YOLO project for metallic surface defect detection.

## Dataset List
| Dataset Name | Official Link |
|--------------|---------------|
| NEU-DET | [http://faculty.neu.edu.cn/songkechen/zh_CN/zdylm/263270/list/](http://faculty.neu.edu.cn/songkechen/zh_CN/zdylm/263270/list/) |
| GC10-DET | [https://github.com/lvxiaoming2019/GC10-DET-Metallic-Surface-Defect-Datasets](https://github.com/lvxiaoming2019/GC10-DET-Metallic-Surface-Defect-Datasets) |
| Severstal Steel Defect Detection | [https://www.kaggle.com/competitions/severstal-steel-defect-detection/data](https://www.kaggle.com/competitions/severstal-steel-defect-detection/data) |

## Dataset Details
### 1. NEU-DET
- **Source**: Northeastern University (NEU), China
- **Focus**: Hot-rolled steel strip surface defect detection
- **Defect Classes**: 6 types (Inclusion, Scratches, Patches, Pitted Surface, Crazing, Rolled-in Scale)
- **Data Scale**: 1800 grayscale images (300 samples per class), 200×200 pixels resolution
- **Annotation**: Bounding box labels for defect category and location

### 2. GC10-DET
- **Focus**: Metallic surface defect detection
- **Defect Classes**: 10 common types of metallic surface defects
- **Annotation**: Bounding box annotations for defect localization
- **Reference**: Associated with the paper *Deep Metallic Surface Defect Detection: the New Benchmark and Detection Network*

### 3. Severstal Steel Defect Detection
- **Source**: Severstal (leading global steel manufacturer)
- **Focus**: Steel surface defect detection in production lines
- **Defect Classes**: 4 types (Spots/patches, Scratches, Surface Defects, Miscellaneous anomalies)
- **Data Scale**: High-resolution grayscale images (1600×256 pixels)
- **Challenges**: Imbalanced class distribution, subtle visual variations of defects, expert-annotated labels

## Notes
- NEU-DET requires access to the official website of Northeastern University (China) for download.
- GC10-DET is open-sourced on GitHub and can be cloned directly.
- Severstal dataset is hosted on Kaggle; registration/login is required for download.
