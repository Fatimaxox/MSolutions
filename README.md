# MSolutions Toolkit: Where AI Brings Sparks of Hope

![MSolutions](https://multiplesclerosisnewstoday.com/wp-content/uploads/2018/10/shutterstock_118491940.jpg)

Welcome to the MSolutions repository. This project showcases the MSolutions toolkit, an innovative AI-driven solution designed to aid in the diagnosis and management of Multiple Sclerosis (MS).

## Project Overview

MSolutions is a collaborative effort by senior AI students at Imam Abdulrahman Bin Faisal University, College of Computer Science and Information Technology (CCSIT) in Dammam, Saudi Arabia. Our mission is to develop intelligent solutions for Multiple Sclerosis, a chronic disease affecting millions worldwide.

## The Problem

<img src="https://cdn.bangkokhospital.com/2023/04/ms-pic2.jpeg" alt="Multiple Sclerosis" width="600">

Multiple Sclerosis (MS) is a chronic disease that affects approximately 2.9 million people worldwide as of 2024. It impacts the brain and spinal cord, leading to a variety of symptoms that can severely affect patients' daily lives, such as:
- Dizziness
- General muscle weakness
- Memory issues
- And more

### Challenges in MS Diagnosis

1. **Specialist Collaboration**: Diagnosing MS typically requires collaboration among several specialists for each case to arrive at a final diagnosis.
2. **Manual Processes**: The current diagnostic process is largely manual, lacking technological integration for lesion annotation and diagnosis.
3. **Comprehensive Testing**: Accurate classification of MS types (e.g., RRMS, SPMS, PPMS) requires more than MRI scans; it also involves tracking relapses and other observations.

## Our Solution

MSolutions is designed to be the ultimate toolkit for MS specialists, enabling them to diagnose and identify MS lesions effectively and efficiently.

### Key Features

1. **Automatic Lesion Segmentation**: Identifies and segments infected lesions.
2. **MS Type Classification**: Classifies the type of MS (RRMS, SPMS, PPMS) and differentiates MS from other conditions such as brain tumors.

### Collaborative Effort

This project is a collaboration with the MS department at King Fahad Specialized Hospital (KFSH) and supervised by two consultants who helped address the problem and find suitable solutions.

## Technical Details

### Classification

- **Models Tested**: CNN, ResNet, DenseNet, EfficientNet
- **Dataset**: 100% Saudi dataset with approximately 229 patients

**Results**:
- Achieved 96% F1 score and 97% recall with ResNetV101 as the best model.

### Segmentation

- **Framework Used**: MONAI for data preparation, preprocessing, and core development.
- **Model**: Tested SegResNet from MONAI for MS case segmentation, which had previously won several competitions for similar problems like brain tumors.

**Results**:
- Achieved a loss of 13.93% and a dice score of 44.59% with 200 epochs.

## Future Work

Our work is set to be tested and validated on real-life patients. We aim to explore other disciplines that could benefit from segmentation and classification improvements in MS cases. This is an actively developing area, and we are committed to contributing further.

## Collaboration Opportunities

We are open to collaborating with interested individuals and medical institutions. 

## Acknowledgments

Special thanks to the hardworking AI team and our supervisor, Dr. Mustafa Youldash, for their unwavering support and dedication.

## Contact

For more information, please contact:
- **Fatima Algharash (Team Leader)**: [2200002685@iau.edu.sa](mailto:2200002685@iau.edu.sa) or [fatima.habib.hl@gmail.com](mailto:fatima.habib.hl@gmail.com)
- **Dr. Mustafa Youldash (Supervisor)**: [mmzyouldash@iau.edu.sa](mailto:mmzyouldash@iau.edu.sa)

---

All rights reserved to MSolutions team - Sparks
