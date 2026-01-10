# Sapien_Robotics
##Assignment 1. Custom Object Detection with Model Training from Scratch: 
Implement a complete object detection pipeline for a custom dataset. Your task is to build and train a detection model from scratch (no pre-trained weights) such as Faster R-CNN, or a custom CNN-based detector. Train on a custom dataset of at least 3-5 object classes (you can use publicly available datasets like PASCAL VOC subset, or create your own). Evaluate the models based on mAP (mean Average Precision), inference speed (FPS), and model size. Provide a detailed report including architecture design choices, data augmentation strategies, training methodology, results comparison, and a discussion on the trade-offs between accuracy and speed. Also attach videos/GIFs showing real-time detection results with the github link.



##2. Automated Quality Inspection System for Manufacturing: Background:
A manufacturing facility produces some components and needs automated visual inspection to detect defects before packaging. Task: Develop a computer vision solution to identify and classify defects on items of your choice. Requirements:
1. Choose any manufactured item with visible features (PCBs, fabric, printed materials, etc.) for your prototype.
2. Capture or source actual images containing at least 3 types of defects (scratches, misalignment, missing components, discoloration, etc.) along with defect-free samples.
3. Write a script that:
1. Analyzes an input image of the product
2. Detects and localizes defect regions (bounding boxes or segmentation masks)
3. Classifies each defect type with confidence scores
4. Outputs the (x, y) pixel coordinates of defect centers and severity assessment
4. Submit sample images (defective and non-defective) with annotations in the github repository


##3. Custom VLM Design for Industrial Quality Inspection
Scenario: A semiconductor manufacturer needs an offline AI system for PCB inspection where inspectors ask natural language questions about defects and receive structured responses with locations and confidence scores (<2s inference). Available: 50,000 PCB images with defect bounding boxes (no QA pairs). Generic VLMs hallucinate.
