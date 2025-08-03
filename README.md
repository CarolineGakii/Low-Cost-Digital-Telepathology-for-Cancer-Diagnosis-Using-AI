# Low-Cost Digital Telepathology Workflow for Cancer Diagnosis Using AI

This project presents a practical, low-cost digital telepathology system developed and deployed in rural Kenya to support cancer diagnosis through AI-assisted histology slide analysis. The system integrates 3D-printed OpenFlexure Microscopes, cloud-based image sharing (MyPathomation™), and a fine-tuned deep learning model (ResNet50V2) for image classification.

## 🎯 Objectives

- Develop a low-cost digital workflow for cancer diagnosis using open-source tools.
- Capture and digitize histology slides using OpenFlexure Microscopes.
- Enable remote diagnosis through cloud-based slide sharing (MyPathomation™).
- Train and evaluate AI models to classify histological images as benign or malignant.
- Validate AI predictions against expert pathologists and assess real-world feasibility.

## 🧠 Model

- **Architecture:** ResNet50V2 (transfer learning)
- **Dataset:** BreakHis (5,429 malignant and 2,480 benign breast cancer images)
- **Training:** 8 epochs with fine-tuning
- **Evaluation Metrics:**
  - Accuracy: 94%
  - Sensitivity: 90%
  - Specificity: 97%
  - ROC-AUC: 0.99
  - Pathologist agreement: 60%

## 🛠 Workflow Overview

1. **Microscope Fabrication**  
   - 3D-printed OpenFlexure Microscopes using PLA and Raspberry Pi components.

2. **Slide Digitization**  
   - Histological slides scanned and stitched into high-resolution images.

3. **Cloud Upload & Review**  
   - Digitized slides uploaded to MyPathomation™ for remote review by trained pathologists.

4. **AI Model Training & Testing**  
   - ResNet50V2 trained on BreakHis dataset and evaluated using ROC-AUC, sensitivity, and specificity.

5. **Clinical Deployment**  
   - Deployed in a rural clinic in Kenya with real-time pathologist training and use.

## 📍 Key Features

- Low-cost, open-source telepathology platform
- Combines hardware, cloud services, and AI into a deployable pipeline
- High performance metrics despite hardware and bandwidth constraints
- Adaptable to other diseases and diagnostic use-cases

## 🧪 Tools & Technologies

- Python (TensorFlow, Keras, Pandas, NumPy)
- Jupyter Notebooks
- OpenFlexure Microscope
- MyPathomation™ (cloud pathology platform)
- Raspberry Pi

## 📌 Conference Presentation

Presented at **MUSTIC2025** — The 4th Annual International Conference at Meru University of Science and Technology.

## 🌍 Real-World Impact

- Empowers rural health centers with digital diagnostic tools
- Reduces dependency on centralized labs and delays
- Supports pathologists with AI triage to enhance decision-making
- Promotes ethical, affordable, and reproducible AI in healthcare

## 📚 Related Media

- [Medium article (if available)](https://medium.com/mindful-data-science/i-trained-resnet-coatnet-and-densenet-on-real-cancer-images-heres-what-surprised-me-a6e3155bd933)
- Project slide deck: *(upload here if you wish)*

## 🤝 Contributors

- Caroline Gakii (Lead – AI & Model Development)  
- Collaborators from Meru University of Science and Technology, Meru County Government, and Meru Teaching & Referral Hospital

## 📌 License

This project is shared for educational and research purposes.
