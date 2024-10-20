# Retinal Disorder Classification Using Optical Coherence Tomography (OCT) Images

## Project Overview

This project focuses on the detection and classification of retinal disorders using Optical Coherence Tomography (OCT) images. The study aims to categorize patients into four groups: Choroidal Neovascularization (CNV), Diabetic Macular Edema (DME), Drusen, and Normal. Two novel transfer learning-based techniques, **VGG16** and **Inception V3 Net**, were applied for the first time to tackle this classification challenge. The project leverages a large dataset of OCT images and achieves state-of-the-art accuracy in identifying retinal disorders.

## Problem Statement

Retinal disorders such as CNV, DME, and Drusen are leading causes of vision impairment and blindness. Early detection and classification are critical for effective treatment. However, manual diagnosis is time-consuming and requires expert knowledge. This project addresses the challenge by applying machine learning, specifically transfer learning, to automatically classify retinal disorders from OCT images.

## Project Goals
- Categorize patients into four classes: CNV, DME, Drusen, and Normal using OCT images.
- Leverage transfer learning techniques (VGG16 and Inception V3 Net) for accurate classification.
- Achieve high accuracy, surpassing traditional methods and even human experts in some cases.

## Data Sources

1. **OCT Images Dataset**:
   - **VGG16 Model**: 20,000 OCT images were used for training and testing.
   - **Inception V3 Net**: 18,000 OCT images were used for data partitioning.
   
The dataset contains labeled OCT images across the four categories: CNV, DME, Drusen, and Normal.

## Images of Retinal Diseases

Images of various retinal diseases identified through the clinical trials using the ODF-based SD-OCT system. The OCT images display key retinal regions including:

- **ELM**: External Limiting Membrane
- **PCV**: Polypoidal Choroidal Vasculopathy
- **RPE**: Retinal Pigment Epithelium
- **CSR**: Central Serous Retinopathy
- **PED**: Pigment Epithelium Detachment Region
- **CME**: Cystoid Macular Edema

![An-OCT-image-showing-a-double-layer-sign-in-a-patient-with-CMD-in-CSCR-arrowheads-A](https://github.com/user-attachments/assets/90c11504-3c84-4803-b129-9b882904fdc7)

## Methods

### 1. **Transfer Learning Models**
   - **VGG16**: Pre-trained on ImageNet, the model was fine-tuned for OCT image classification.
   - **Inception V3 Net**: Also pre-trained on ImageNet and adapted for the same task.
   - **Modified SqueezeNet**: A customized model used to further improve classification accuracy.

### 2. **Performance Evaluation**
   - The modified **SqueezeNet** model achieved an impressive accuracy of **99.06%**.
   - The robustness of the transfer learning approach was demonstrated by outperforming traditional classifiers and even a human expert.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdullahRagheb/retinal-disorders.git
2. Navigate to the project directory:

   ```bash
   cd retinal-disorders-detection

Major Dependencies:
Python 3.x
NumPy: For numerical computations
Pandas: For data handling and manipulation
Scikit-learn: For machine learning model training
OpenCV: For computer vision and image preprocessing
Matplotlib / Seaborn: For data visualization
TensorFlow / PyTorch (if using neural networks)
Contributing
We welcome contributions! Please follow these steps if you'd like to contribute:

Fork the project repository.
Create a new feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For any inquiries or issues, feel free to contact the project team at abdullahragheb12@icloud.com.
