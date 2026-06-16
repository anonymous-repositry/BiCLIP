# BiCLIP: Bidirectional and Consistent Language-Image Processing for Robust Medical Image Segmentation

This repository accompanies a paper currently under peer review.

---

## 📌 Overview

BiCLIP (Bidirectional and Consistent Language-Image Processing) is a vision-language framework designed for robust medical image segmentation. The method introduces:

- Bidirectional information exchange between image and text for segmentation  
- ABF-based refinement that integrates visual cues into textual representations and projects them back to image space  
- Image Augmentation Consistency (IAC) to improve feature stability under diverse medical image transformations  
- Robust performance under limited annotations, noise corruption, and motion blur  
- Effective text-guided segmentation across four medical imaging datasets  

Further methodological details are available in the manuscript.

---

## 📂 Planned Repository Structure

```text
BiCLIP/
│── config/
│── engine/
│── utils/
│── datasets/
│── pretrained_weights/
│── requirements.txt
│── train.py
│── evaluate.py
