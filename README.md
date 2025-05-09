# AI_Tuna_Otolith

## 🐟 Introduction

Accurate age estimation of fish is essential for understanding growth patterns, population dynamics, and guiding effective fishery management strategies. Traditionally, fish age is determined by counting the alternating opaque and translucent zones on otolith sections—a process that is both time-consuming and prone to subjectivity. Recent advances in machine learning, particularly deep learning, have shown promise in automating otolith-based age estimation with high reliability.

This project explores transformer-based age prediction of Southern bluefin tuna (Thunnus maccoyii) using cross-section otolith images. This notebook implements and evaluates a predictive model trained on real otolith data. The methodology reflects a modern, cost-effective alternative to expert manual readings, and serves as a preliminary foundation for deploying AI-assisted fish age classification tools.

The notebook covers:
- Image preprocessing and augmentation strategies
- A Vit-based model for age classification (ages 1-21+)
- **Confusion matrix analysis** to assess model misclassification across age groups
- **Grad-CAM++ heatmap visualization** to highlight age-relevant otolith regions and improve model interpretability
- Model evaluation using ±1 accuracy

This work aims to support the continued development of AI-enhanced otolith reading tools and contribute to sustainable marine resource management.

## 📂 Data

This project utilizes otolith image data provided by the Institute of Oceanography, National Taiwan University (NTU). **Due to academic and ethical considerations, the original dataset is not included in this repository.** If you are interested in using the dataset, please contact the original data providers for access permission.

### 📁 Recommended Folder Structure

Please organize your dataset in the following structure under a `data/` directory:

├── train/
│   ├── 1/
│   |   ├── img001.jpg
│   |   ├── img002.jpg
│   |   └── ....
│   ├── 2/
│   |   ├── img001.jpg
│   |   ├── img002.jpg
│   |   └── ....
│   └── ....
└──
├── test/
│   ├── 1/
│   |   ├── img001.jpg
│   |   ├── img002.jpg
│   |   └── ....
│   ├── 2/
│   |   ├── img001.jpg
│   |   ├── img002.jpg
│   |   └── ....
│   └── ....
└──
