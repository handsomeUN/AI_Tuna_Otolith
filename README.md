# AI_Tuna_Otolith

## 🐟 Introduction

Accurate age estimation of fish is essential for understanding growth patterns, population dynamics, and guiding effective fishery management strategies. Traditionally, fish age is determined by counting the alternating opaque and translucent zones on otolith sections—a process that is both time-consuming and prone to subjectivity. Recent advances in machine learning, particularly deep learning, have shown promise in automating otolith-based age estimation with high reliability.

This project explores transformer-based age prediction of Southern bluefin tuna (Thunnus maccoyii) using cross-section otolith images. This notebook implements and evaluates a predictive model trained on real otolith data. The methodology reflects a modern, cost-effective alternative to expert manual readings, and serves as a preliminary foundation for deploying AI-assisted fish age classification tools.

The notebook covers:
- Image preprocessing and augmentation strategies
- A Vit-based model for age classification (ages 1-21+)
- Model evaluation using ±1 accuracy

This work aims to support the continued development of AI-enhanced otolith reading tools and contribute to sustainable marine resource management.


## 📂 File Structure

- `SBT_2025.ipynb`: Main notebook with full analysis
- `requirements.txt`: Python packages used
- `assets/`: Figures or data used in the notebook (optional)

## 🚀 Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/SBT_2025.git
cd SBT_2025
pip install -r requirements.txt
