# Dino-DR
Dino2-DR: A Trustworthy and Explainable Vision Transformer for Cross-Domain Diabetic Retinopathy Grading

This repository provides the complete training pipeline and pretrained weights for the Dino2-DR model, developed as part of the official thesis work. The released models are ready for inference under the two evaluation protocols introduced in the paper: **Leave-One-Domain-Out (LODO)** and **Fixed-Source Multi-Target (FSMT)**.

- In the **LODO** protocol, six models were trained using five out of six public diabetic retinopathy datasets (**APTOS**, **DeepDRiD**, **FGADR**, **IDRiD**, **Messidor2**, **RLDR**), holding one domain out at each iteration for out-of-distribution testing.  
- In the **FSMT** protocol, a single model was trained on the largest and most diverse datasets, **EyePACS** and **DDR**, and evaluated on all remaining domains.
