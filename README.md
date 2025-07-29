# Wheat-Insight

Leveraging Artificial Intelligence and Computer Vision to Help the Agricultural Sector of Asia.

---

## 📽️ Project Overview Video

[▶️ Watch the project demo video](./Wheat%20Insight%20Final%20Linkedin.mp4)

---

## Introduction

Wheat is one of the major food crops consumed in Pakistan and other Asian countries. Unfortunately, a substantial amount of wheat is lost annually due to diseases such as yellow rust and others. To address this, we have developed a system that enables early diagnosis of six types of wheat diseases, including:

1. Yellow Rust  
2. Brown Rust  
3. Healthy  
4. Blast Leaves  
5. Stem Rust  
6. Tan Spot  

Using vision transformers, we achieved an impressive accuracy of up to **97%**.

---

## Yellow Rust Severity Classification

We also focused on classifying the severity levels of yellow rust, the most common airborne disease. Using an open-source dataset from Kaggle, we achieved an outstanding **95%** accuracy with vision and Swin transformers. The severity levels include:

1. No disease (0: No signs of infection)  
2. Resistant (R: Minor signs of infection)  
3. Moderately Resistant (MR: Small and medium signs of infection)  
4. Moderately Resistant-Moderately Susceptible (MRMS)  
5. Moderately Susceptible (MS: Medium signs of infection)  
6. Susceptible (S: Major signs of infection)  

---

## Wheat Spike Counting for Yield Estimation

Furthermore, we developed a method for counting the number of wheat spikes in a field to accurately estimate the yield. We utilized Ultralytics' newly released YOLOv8-OBB with orientation features and small bounding boxes around wheat spikes, making it ideal for UAV/drone imagery (GWHD 2021).

---

This project has been a remarkable journey, and we are proud of the positive impact it can have on
