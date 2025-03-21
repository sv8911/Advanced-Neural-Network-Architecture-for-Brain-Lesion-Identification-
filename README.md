# Advanced Neural Network Architecture for Brain Lesion Identification

This repository contains the research paper **“Advanced Neural Network Architecture for Brain Lesion Identification”** by Vaibhav Parihar, Shreya Abraham Varghese, and Dr. Babu S(Faculty). The paper focuses on leveraging Convolutional Neural Network (CNN) models for rapid and accurate brain tumor (lesion) detection using MRI scans.

---

## Overview

- **Goal**: Develop a deep-learning approach that identifies brain tumors from MRI images more quickly and accurately than manual diagnosis alone.
- **Dataset**: A curated set of 3000 MRI scans (split into “tumor” and “no tumor” categories). Images were resized and normalized to enhance consistency for model training.
- **Models Compared**: 
  - **VGG16**: Achieved the highest accuracy (98%).
  - **InceptionV3**: Noted strong performance (95%+ accuracy).
  - **Xception**: Demonstrated 91.6% accuracy with depthwise separable convolutions.
- **Key Findings**: CNN-based approaches can drastically reduce detection time and maintain high accuracy, potentially aiding in faster, more reliable clinical diagnoses.

---

## Paper Contents

1. **Introduction**  
   Describes the motivation behind automated brain tumor detection and the importance of accurate, early diagnosis.

2. **Literature Review**  
   Summarizes existing research on CNNs in medical imaging, transfer learning, and data augmentation techniques for improving diagnostic accuracy.

3. **Algorithms Taken for Comparison**  
   - **VGG16**  
   - **InceptionV3**  
   - **Xception**  
   Each architecture is briefly introduced, highlighting its core design principles (e.g., 3×3 filters, inception modules, depthwise separable convolutions).

4. **Experimental Technology**  
   - **Dataset**: Sourced from Kaggle, consisting of labeled MRI scans.  
   - **Pre-processing**: Resizing, normalization, and data augmentation.  
   - **Proposed Model**: CNN-based approach leveraging transfer learning and fine-tuning for classification.  

5. **Accuracy Table**  
   Presents a side-by-side comparison of the three models (VGG16, InceptionV3, Xception) in terms of accuracy, precision, recall, and F1-score.

6. **Conclusion and Future Enhancement**  
   Discusses how the findings can be extended with advanced data augmentation, ensemble methods, and interpretability techniques to further improve results.

7. **Graphical Representation**  
   Plots showcasing model accuracy and loss trends during training for each architecture.

8. **References**  
   Comprehensive list of cited works supporting the study’s methods and findings.

---

## How to Use This Repository

1. **Paper PDF**  
   The main research paper (`Research_paper_B121.pdf`) outlines the methodology, experiments, and results in detail.

2. **Dataset**  
   - Due to size constraints, the actual MRI images may not be stored in this repository.  
   - The link to the dataset - https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection

---

## Contact

- **Primary Authors**:  
  - Vaibhav Parihar (<vaibhavparihar0@gmail.com>)  
  - Shreya Abraham Varghese (<Sav.shreya02@gmail.com>)
 
- Keep Learning :) 
- **Supervisor**:  
  - Dr. Babu S (<babus@srmist.edu.in>)

Feel free to open an issue or pull request if you have questions, suggestions, or improvements regarding the methods discussed in this research.

---
