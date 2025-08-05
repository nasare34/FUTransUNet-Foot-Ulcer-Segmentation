# FUTransUNet-Foot-Ulcer-Segmentation

FUTransUNet: Self-Attention for Clinical Precision
A Hybrid Transformer-U-Net with Grad-CAM for High-Fidelity Foot Ulcer Segmentation


📄 Paper Summary
This repository contains the implementation of FUTransUNet, a novel hybrid deep learning architecture that integrates the global attention mechanism of Vision Transformers (ViTs) into the U-Net framework for automated segmentation of diabetic foot ulcers (DFUs) from clinical photographs.

Our method was rigorously evaluated on the Foot Ulcer Segmentation Challenge (FUSeg) dataset and demonstrated strong segmentation performance with enhanced explainability using Grad-CAM.
🔗 Link to paper: (Pending Review)

🧠 Model Architecture

Combines Vision Transformers for capturing global context with U-Net for precise localization.

Incorporates a Transformer block at the U-Net bottleneck.

Uses Grad-CAM for interpretability of the model’s attention regions.



These results show that FUTransUNet achieves high-fidelity segmentation and clinical-grade performance.



🧪 Dataset
Foot Ulcer Segmentation Challenge (FUSeg) dataset.

Over 1,200 de-identified clinical images with corresponding binary masks.

Pixel values: 255 = ulcer, 0 = non-ulcer.

🔍 Visualizations
Training & Validation Curves (Loss, Accuracy, Dice, IoU)

Overlay of Predictions on Input Images

Side-by-side Comparisons of Inputs and Masks

Grad-CAM Heatmaps indicating model focus during prediction

📌 Sample visualizations can be found in the /notebook.






@article{AsareAkwas_2025futransunet,
  title={FUTransUNet–Self-Attention for Clinical Precision: A Hybrid Transformer-U-Net with Grad-CAM for High-Fidelity Foot Ulcer Segmentation},
  author={Akwasi Asare, Mary Sagoe, Justice Williams Asare},
  journal={MICCAI Foot Ulcer Segmentation Challenge},
  year={2025}
}
