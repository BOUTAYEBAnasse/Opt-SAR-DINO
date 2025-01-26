#🦖🛰️ OPT-SAR DINO Object Detection Project

This repository presents the **OPT-SAR DINO** model, designed for small-scale object detection tasks on optical and SAR images. It utilizes the following datasets:
- **Pleiades Aircraft Dataset** for optical imagery.
- **SSDD Dataset** for ship detection on SAR imagery.

![Couverture](assets/GITHUB_COVER.PNG)

## 🤖 OPT-SAR DINO model

Our **OPT-SAR DINO** model is inspired by **DINO** (*DEtection TRansformer with Improved Non-degenerate Objectives*), an advanced architecture for object detection introduced by Zhang et al. (2022). DINO improves the performance of transforming models through bipartite optimization and efficient regularization targets.

**Reference article**: [“DINO: DETR with Improved DeNoising Anchor Boxes”](https://arxiv.org/abs/2203.03605), Zhang et al., 2022.

**OPT-SAR DINO** model integrates deformable attention mechanisms to better handle objects of different scales and locations in images. It also exploits the **CDN (Conditional Denoising)** approach to improve training stability and convergence.

**OPT-SAR DINO Architecture**

![Description du graphique](assets/DINO-Model-reduced.png)

## 📊 Notebooks for Benchmarking 

This repository contains benchmarking notebooks for each dataset. For both **Pleiades Aircraft Dataset** and **SSDD Dataset**, the following models are implemented:
- **OPT-SAR DINO**
- **Deformable DETR** (Zhu et al., 2021)
- **Faster R-CNN** (Ren et al., 2015)
- **YOLOV10** (Redmon et al., 2016 – YOLO foundation)


---

## 📁 Repository Structure

The proposed notebooks contain implementations of each model, our own (OPT-SAR DINO) and the other object detectors used for benchmarking. We present one notebook for each model and dataset, 8 in all.

---

## ▶️ Execution Instructions

To execute these notebooks, use **Google Colab** with a **GPU environment**. For optimal performance, it's recommended to use an **NVIDIA A100 GPU**.

---

## 🧪 Testing Phase 

The testing phase includes:
1. Visualizing predictions.
2. Calculating the following metrics:
   - **Precision**
   - **Recall**
   - **F1-Score**
   - **mAP@50**
   - **mAP@75**
   - **mAP@[0.5:0.95]**

---

Thank you for exploring this project!
