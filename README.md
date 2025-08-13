# FUTransUNet – Foot Ulcer Segmentation

**Self-Attention for Clinical Precision**  
*A Hybrid Transformer-U-Net with Grad-CAM for High-Fidelity Foot Ulcer Segmentation*

---

## 📄 Paper
This repository contains the implementation of **FUTransUNet**, a novel hybrid deep learning architecture that integrates the **global attention mechanism of Vision Transformers (ViTs)** into the **U-Net** framework for automated segmentation of diabetic foot ulcers (DFUs) from clinical photographs.  

Our approach was evaluated on the **Foot Ulcer Segmentation Challenge (FUSeg)** dataset and demonstrated **high segmentation accuracy with enhanced interpretability** via Grad-CAM visualizations.  

🔗 **Link to Paper:** [FUTransUNet – Self-Attention for Clinical Precision](https://doi.org/10.48550/arXiv.2508.03758)  

---

## 🧠 Model Overview

- **Hybrid Architecture**: Combines **Vision Transformers** for capturing global context with **U-Net** for fine-grained localization.  
- **Transformer Bottleneck**: A Transformer block is placed at the U-Net bottleneck for enriched feature representation.  
- **Model Interpretability**: Uses **Grad-CAM** to visualize regions of attention during predictions.  

**Key Strengths:**
- High-fidelity segmentation  
- Clinically relevant attention maps  
- Robust performance on a challenging medical imaging dataset  

---

## 🧪 Dataset

- **Source**: Foot Ulcer Segmentation Challenge (FUSeg) dataset  
- **Size**: 1,200+ de-identified clinical images with binary masks  
- **Mask Encoding**:  
  - `255` = ulcer  
  - `0` = non-ulcer  

---

## 🔍 Visualizations

- **Training & Validation Curves**: Loss, Accuracy, Dice coefficient, IoU  
- **Prediction Overlays**: Segmentation masks over clinical photographs  
- **Side-by-Side Comparisons**: Inputs vs. ground truth masks  
- **Grad-CAM Heatmaps**: Highlighting model’s focus regions during inference  

Sample visualizations are provided in the `/notebook` directory.  

---

## 📚 Citation

If you use FUTransUNet in your research, please cite:  

@article{2025, volume={73},
   ISSN={2231-5381},
   url={
https://doi.org/10.48550/arXiv.2508.03759},
   DOI={10.14445/22315381/ijett-v73i6p106},
   number={6},
   journal={International Journal of Engineering Trends and Technology},
   publisher={Seventh Sense Research Group Journals},
   year={2025},
   month=jun }

