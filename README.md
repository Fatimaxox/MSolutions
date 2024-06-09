# MSolutions Toolkit: Where AI Brings Sparks of Hope 🚀

![MSolutions](https://sonographictendencies.files.wordpress.com/2021/03/ms-header.png?w=1400&h=400&crop=1)

Welcome to the MSolutions repository. This project showcases the MSolutions toolkit, an innovative AI-driven solution designed to aid in the diagnosis and management of Multiple Sclerosis (MS).

## Project Overview

MSolutions is a collaborative effort by senior AI students at Imam Abdulrahman Bin Faisal University, College of Computer Science and Information Technology (CCSIT) and the MS department at KFSH. Our mission is to develop intelligent solutions for Multiple Sclerosis, a chronic disease affecting millions worldwide.

## The Problem 🧩

![Multiple Sclerosis](https://cdn.bangkokhospital.com/2023/04/ms-pic2.jpeg)

Multiple Sclerosis (MS) is a chronic disease that affects approximately 2.9 million people worldwide as of 2024. It impacts the brain and spinal cord, leading to a variety of symptoms that can severely affect patients' daily lives, such as:
- Dizziness
- General muscle weakness
- Memory issues <br>
And more

### Challenges in MS Diagnosis 🏥

1. **Specialist Collaboration**: Diagnosing MS typically requires collaboration among several specialists for each case to arrive at a final diagnosis.
2. **Manual Processes**: The current diagnostic process is largely manual, lacking technological integration for lesion annotation and diagnosis.
3. **Comprehensive Testing**: Accurate classification of MS types (e.g., RRMS, SPMS, PPMS) requires more than MRI scans; it also involves tracking relapses and other observations.

## Our Solution 🌟

MSolutions is designed to be the ultimate toolkit for MS specialists, enabling them to diagnose and identify MS lesions effectively and efficiently.

### Key Features

1. **Automatic Lesion Segmentation**: Identifies and segments infected lesions.
2. **MS Type Classification**: Classifies the type of MS (RRMS, SPMS, PPMS) and differentiates MS from other conditions such as brain tumors.

## Technical Details 🔧

### Classification

- **Models Tested**: CNN, ResNet, DenseNet, EfficientNet
- **Dataset**: 100% Saudi dataset with approximately 229 patients

**Results**:
- Achieved 96% F1 score and 97% recall with ResNetV101 as the best model.

### Segmentation

- **Framework Used**: MONAI for data preparation, preprocessing, and core development.
- **Model**: Tested SegResNet from MONAI for MS case segmentation, which had previously won several competitions for similar problems like brain tumors. [Look here for more details](https://developer.nvidia.com/blog/nvidia-data-scientists-take-top-spots-in-miccai-2021-brain-tumor-segmentation-challenge/).

**Results**:
- Achieved a loss of 13.93% and a dice score of 44.59% with 200 epochs.

## Future Work 

Our work is set to be tested and validated on real-life patients. We aim to explore other disciplines that could benefit from segmentation and classification improvements in MS cases. This is an actively developing area, and we are committed to contributing further.


## Why MSolutions? 🤝

Discover the reasons to choose MSolutions for revolutionizing MS diagnosis:

### Cutting-edge Technology

MSolutions leverages state-of-the-art AI algorithms and frameworks to deliver accurate and efficient MS lesion segmentation and classification.

### Collaboration Excellence

Our project is the result of a collaborative effort between AI experts, medical professionals, and data scientists. We ensure comprehensive solutions by working hand-in-hand with specialists from King Fahad Specialized Hospital (KFSH).

### Recognized Achievements

MSolutions has been recognized and nominated in prestigious competitions such as Women in Data Science (WiDS) 2024, the 6th National Computing College Conference, and She Codes 2024. Our commitment to excellence and innovation sets us apart.

### Future-focused Development

We are dedicated to continuous improvement and development. Our team is actively exploring new avenues in MS diagnosis and remains committed to contributing to the field.

## Collaboration Opportunities 💡

We are open to collaborating with interested individuals and medical institutions. 

## Acknowledgments 

Special thanks to the hardworking AI team and our supervisor, Dr. Mustafa Youldash, for their unwavering support and dedication.

## Contact 📬

For more information, please contact:
- **Fatima Algharash (Team Leader)**: [2200002685@iau.edu.sa](mailto:2200002685@iau.edu.sa) or [fatima.habib.hl@gmail.com](mailto:fatima.habib.hl@gmail.com)
- **Dr. Mustafa Youldash (Supervisor)**: [mmzyouldash@iau.edu.sa](mailto:mmzyouldash@iau.edu.sa)

---

All rights reserved to MSolutions team - Sparks
