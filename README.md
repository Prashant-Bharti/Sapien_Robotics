# Sapien Robotics – AI Vision Assignments

---

## Assignment 1: Custom Object Detection with Model Training from Scratch

This project implements a complete object detection pipeline trained **entirely from scratch** (no pre-trained weights) on a custom dataset containing **3–5 object classes**. The objective is to design, train, and evaluate a robust detection system using architectures such as **Faster R-CNN** or a **custom CNN-based detector**.

The implementation includes:
- Custom architecture design and justification  
- Data preprocessing and augmentation strategies  
- Training methodology and hyperparameter tuning  
- Performance evaluation using **mAP**, **FPS**, and **model size**  
- Detailed analysis of accuracy vs. speed trade-offs  

The repository also provides **real-time detection videos/GIFs** demonstrating inference behavior and deployment performance.

---

## Assignment 2: Automated Quality Inspection System for Manufacturing

This project develops an end-to-end **automated visual inspection system** for detecting and classifying defects in manufactured products such as **PCBs, fabrics, or printed materials**.

The system pipeline:
1. Analyzes an input image of the product  
2. Detects and localizes defect regions (bounding boxes or segmentation masks)  
3. Classifies each defect type with confidence scores  
4. Outputs precise **(x, y)** pixel coordinates of defect centers  
5. Computes a **severity assessment** for each detected defect  

The dataset includes both **defective and non-defective samples** with full annotations, all of which are provided in the GitHub repository for transparency and reproducibility.

---

##  Assignment 3: Custom VLM Design for Industrial Quality Inspection

This section presents the design of a **custom Vision–Language Model (VLM)** for **offline PCB inspection** in a semiconductor manufacturing environment.

Given a dataset of **50,000 PCB images with bounding box annotations** and no QA pairs, the proposed solution focuses on:
- Preventing hallucination common in generic VLMs  
- Supporting natural language interaction for inspectors  
- Producing structured responses with **defect locations and confidence scores**  
- Achieving **<2 seconds inference time** for industrial deployment  

The design introduces specialized architectural modifications for precise localization, multimodal alignment, and real-world manufacturing constraints.

---
