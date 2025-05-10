# PBViT: Patch-Based Vision Transformer for Brain Tumor Detection

This repository contains the full implementation of the **PBViT (Patch-Based Vision Transformer)** model as described in the published IEEE research paper:

> 📄 [PBVit: A Patch-Based Vision Transformer for Enhanced Brain Tumor Detection](https://ieeexplore.ieee.org/abstract/document/10811909), IEEE Access, 2024

---

## 📁 Repository Structure

```bash
PBViT/
├── preprocessing/
│   ├── 1_dataset_preparation_pbvit.ipynb       # Raw image handling and patch generation
│   └── 2_train_test_split_pbvit.ipynb          # Stratified split of dataset into train/test
├── training/
│   └── 3_Training.ipynb                         # Full training pipeline with evaluation
└── README.md
```

## 🚀 Model Overview
PBViT is a lightweight and accurate Transformer-based model optimized for medical imaging tasks. Instead of operating on full-resolution brain scans, PBViT processes fixed-size image patches, capturing localized features crucial for tumor localization and classification.

## 🧠 Key Features
- 🧩 Patch-based processing for improved granularity
- 🎯 Transformer encoder to model spatial dependencies
- 🔬 Targeted for brain tumor detection using MRI slices
- 📊 Reproducible training pipeline with visual metrics and evaluation

## 📚 Citation
```bash
@article{chauhan2024pbvit,
  title={PBVit: A Patch-Based Vision Transformer for Enhanced Brain Tumor Detection},
  author={Chauhan, Pratikkumar and Lunagaria, Munindra and Verma, Deepak Kumar and Vaghela, Krunal and Tejani, Ganshyam and Sharma, Sunil and Khan, Ahmad Raza},
  journal={IEEE Access},
  year={2024},
  publisher={IEEE}
}
```
