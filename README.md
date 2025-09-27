# Skin_Foundation

This repository contains the code related to my MSc final project at UCL.  
The project investigates the ability of **Vision Foundation Models** to classify close-up facial images related to different skin conditions — such as **moisture, oiliness, elasticity, texture, and hyperpigmentation**.  

Because the dataset is **small and highly imbalanced**, the project leverages **Stable Diffusion (img2img)** for **data augmentation**, improving data diversity and model robustness.

---

## Project Overview

- **Goal**: Classify facial skin condition attributes using foundation models.  
- **Challenges**: Small dataset, class imbalance, high intra-class variability.  
- **Approach**:  
  - Data augmentation with Stable Diffusion (img2img).  
  - Fine-tuning of Vision Foundation Models on skin datasets.  
  - Evaluation of model robustness and generalization.  

---

## Repository Structure

```markdown

.
├── 0_Plots.ipynb # Visualisation of model outputs and results (included in the report)
├── 1_Data augmentation.ipynb # Data augmentation using Stable Diffusion (img2img)
├── 2_Foundation Models.ipynb # Training & fine-tuning Vision Foundation Models
├── Dataset split.ipynb # Splits dataset into train / validation / test sets
├── GDF_embeddings extraction.ipynb # Extract embeddings from Google Derm Foundation model
└── README.md # Project documentation

```

## Acknowledgements
The project makes use of the following pre-trained models and resources
- [PanDerm] (https://github.com/SiyuanYan1/PanDerm)
- [Google Derm Foundation] (https://github.com/Google-Health/derm-foundation)
- [Stable Diffusion model] (https://github.com/CompVis/stable-diffusion)
