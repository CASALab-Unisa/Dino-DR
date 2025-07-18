# Dino2-DR

This repository contains the official implementation and pretrained models from the paper  
**"_Dino2-DR: A Trustworthy and Explainable Vision Transformer for Cross-Domain Diabetic Retinopathy Grading_"**,  
accepted at the [BISCUIT Workshop @ ICCV 2025](https://sites.google.com/di.uniroma1.it/biscuit-workshop-1).

It includes the full training pipeline and ready-to-use weights for inference under the two evaluation protocols described in the paper:

- **Leave-One-Domain-Out (LODO):** Six models trained on five out of six public diabetic retinopathy datasets (**APTOS**, **DeepDRiD**, **FGADR**, **IDRiD**, **Messidor2**, **RLDR**), each time leaving one domain out for testing.  
- **Fixed-Source Multi-Target (FSMT):** A single model trained on the two largest and most diverse datasets, **EyePACS** and **DDR**, then evaluated on the six held-out domains.

## 📌 Reference

If you use this code or the pretrained models in your research or applications, **please cite the following paper**:

> Cascone, L., Di Biasi, L., Genito, G., & Nappi, M.  
> *Dino2-DR: A Trustworthy and Explainable Vision Transformer for Cross-Domain Diabetic Retinopathy Grading*  
> Accepted at BISCUIT Workshop @ ICCV 2025.  
> [https://sites.google.com/di.uniroma1.it/biscuit-workshop-1](https://sites.google.com/di.uniroma1.it/biscuit-workshop-1)

### BibTeX

```bibtex
@inproceedings{cascone2025dino2dr,
  title     = {Dino2-DR: A Trustworthy and Explainable Vision Transformer for Cross-Domain Diabetic Retinopathy Grading},
  author    = {Cascone, Lucia and Di Biasi, Luigi and Genito, Giuseppe and Nappi, Michele},
  booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  year      = {2025},
}


