# Dino2-DR
This repository contains the official implementation and pretrained models from the work  
**_Dino2-DR: A Trustworthy and Explainable Vision Transformer for Cross-Domain Diabetic Retinopathy Grading_**

It includes the full training pipeline and ready-to-use weights for inference under the two evaluation protocols described in the paper:

- **Leave-One-Domain-Out (LODO):** Six models trained on five out of six public diabetic retinopathy datasets (**APTOS**, **DeepDRiD**, **FGADR**, **IDRiD**, **Messidor2**, **RLDR**), each time leaving one domain out for testing.  
- **Fixed-Source Multi-Target (FSMT):** A single model trained on the two largest and most diverse datasets, **EyePACS** and **DDR**, then evaluated on the six held-out domains.
