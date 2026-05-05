# Sim2Maritime
A high-fidelity multi-modal synthetic dataset (RGB-D-N) for small object detection in maritime search and rescue. Supporting the NeurIPS 2026 Datasets &amp; Benchmarks Track submission.
# Sim2Maritime Dataset

This repository contains the **Sim2Maritime** dataset, a high-fidelity multi-modal synthetic dataset for maritime search and rescue (SAR).

## 📊 Dataset Overview
- **Images:** 15,000 high-resolution frames.
- **Modalities:** Synchronized RGB, Depth, and Surface Normal.
- **Tasks:** Tiny object detection (swimmers, boats, etc.).

## 📂 Structure
- `/images`: RGB data.
- `/labels`: YOLO format annotations.
- `croissant.jsonld`: Dataset metadata.

## 📥 Download
[在这里填入你的完整数据集下载链接，例如 Hugging Face 链接]
## License
This dataset is licensed under a [Creative Commons Attribution 4.0 International License (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/).
## 🛠️ Code and Benchmarks
The training and evaluation scripts used for the YOLOv11 experiments described in the paper will be fully released upon acceptance. Currently, users can refer to the standard YOLOv11 implementation for reproduction using our provided data.
