
# 🍱 FoodNet498: Deep Learning for Multi-Label Food Image Classification (498 Classes)

> ⚡ **Kaggle Public Competition** | 🧠 **Custom Neural Network** + 🚀 **EfficientNet-B4 Backbone** | 🎯 **Micro F1 Score Optimization**

---

## 📌 Overview

**FoodNet498** is a deep learning project developed for a **Kaggle-hosted public competition** focused on **multi-label food image classification**. The dataset comprises nearly **40,000 labeled images**, each possibly containing **multiple food categories** out of **498 possible classes**.  

The primary challenge: accurately detect **all food categories** visible in a given image using state-of-the-art computer vision techniques.  

This repository demonstrates a high-performing deep learning pipeline using **EfficientNet-B4** and custom classification layers, delivering optimized predictions using **sigmoid activations** and **threshold tuning** for F1 performance.

---

## 🧠 Project Objective

The task is a **multi-label image classification problem**, where each image can belong to multiple food categories simultaneously. This problem is common in real-world image tagging, recommendation systems, and intelligent food logging applications.

Key goals:
- Build a robust model that generalizes well on real-world food images
- Handle **extreme class imbalance** across 498 food categories
- Optimize predictions using **Micro F1 Score** as the evaluation metric

---

## 🏆 Kaggle Competition Details

- 📅 **Duration:** April 2, 2025 – June 20, 2025  
- 🧾 **Type:** Multi-label classification  
- 🖼️ **Dataset:** AICrowd Food Recognition Benchmark (2022)  
- 🧮 **Classes:** 498 food categories  
- 📊 **Metric:** Micro F1 Score  
- 🧪 **Test Set Size:** 1,000 images (hidden labels)

---

## 🔗 Dataset Access

📥 **[Click to Download the Dataset (Google Drive)](https://drive.google.com/file/d/15YOou6J-yZjIWY0SiNrPGRIvSxN9CZxB/view?usp=sharing)**

Structure:

Structure:
data/
├── images_test/
├── images_train/
└── categories_new.csv
└── train_onehot.csv

