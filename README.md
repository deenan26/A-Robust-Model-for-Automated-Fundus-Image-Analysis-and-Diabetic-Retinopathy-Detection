# A Robust Deep Neural Network Model for Automated Fundus Image Analysis and Diabetic Retinopathy Detection

## 📌 Project Overview
This project develops a deep learning system for automated detection and classification of Diabetic Retinopathy (DR) from retinal fundus images. Early detection of DR is crucial because the disease often shows minimal symptoms in its initial stages.

The proposed hybrid deep learning model combines EfficientNet-B0 for detailed local feature extraction and MobileViT for capturing global contextual patterns in retinal images. Image preprocessing techniques enhance retinal features, while an attention mechanism focuses on critical regions such as blood vessels and lesions. The system improves diagnostic accuracy and supports early screening for vision-threatening diseases.

---

## ⚙️ Technologies Used
- Python
- Deep Learning
- EfficientNet-B0
- MobileViT
- Computer Vision
- OpenCV
- NumPy
- SciPy
- CLAHE Image Preprocessing
- Attention Mechanism

---

## 🚀 Key Features
- Automated Diabetic Retinopathy detection from fundus images
- Hybrid deep learning architecture combining CNN and Transformer models
- Image preprocessing for improved retinal feature visibility
- Attention mechanism for lesion and vessel detection
- Multi-class classification of DR severity levels
- Improved screening accuracy for early disease detection

---

## 🔧 Working Principle
The system processes retinal fundus images through multiple stages. First, preprocessing techniques such as contrast enhancement and CLAHE are applied to improve visibility of retinal features.

EfficientNet-B0 extracts fine-grained local features such as microaneurysms and exudates, while MobileViT captures global contextual information from the retinal structure. The extracted features are combined and passed through an attention module that highlights clinically relevant regions.

Finally, the model classifies the images into different stages of Diabetic Retinopathy, enabling early detection and diagnosis.

---

## 📊 Applications
- Automated diabetic retinopathy screening systems
- Medical image analysis
- AI-assisted healthcare diagnostics
- Early disease detection in ophthalmology
- Computer-aided clinical decision support systems

---

## 📷 Project Demonstration
(Add images or results here)

Examples:
- Fundus image samples
- Model architecture diagram
- Training accuracy and loss graphs
- Confusion matrix or classification results

---

## 📂 Project Structure
