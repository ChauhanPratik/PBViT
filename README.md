# PBViT: Patch-Based Vision Transformer for Brain Tumor Detection

This repository contains the full implementation of the **PBViT (Patch-Based Vision Transformer)** model as described in the published IEEE research paper:

> 📄 [Patch-Based Vision Transformer for Accurate Brain Tumor Detection](https://ieeexplore.ieee.org/abstract/document/10811909), IEEE Access, 2024

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
