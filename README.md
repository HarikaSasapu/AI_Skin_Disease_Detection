# Skin Disease AI: Advanced Machine Learning for Skin Lesion Diagnosis

Welcome to **Skin Disease AI**, an innovative system designed to diagnose six types of skin lesions using cutting-edge machine learning and image processing techniques. This project provides a robust AI-driven solution to support dermatological diagnosis.

---

## 🌟 Features
- **High Accuracy**: Achieved 92% accuracy on test data using the Xception architecture.
---

## 🎯 Introduction
Skin conditions are among the leading causes of clinic visits, where early and accurate diagnosis is critical. This project leverages advanced convolutional neural networks (CNNs) to analyze images and identify skin lesions, providing an assistive tool for dermatological care.

---

## 📚 Dataset
The dataset used for this project includes:
- **1,657 Images** representing six types of skin lesion classes and one non-lesion class.
- Data sourced from **public dermatologist datasets** and **self-collected images**.
- **Data Augmentation** applied to balance classes with fewer images.

---

## 🤖 Model
- **Architecture**: Built using the **Xception** model, a state-of-the-art deep learning architecture.
- **Training**: Utilized data augmentation techniques to enhance training on imbalanced classes.
- **Evaluation Metrics**: Included confusion matrix, accuracy and loss histograms, and a detailed classification report.

---

## 📂 Repository Structure
The repository contains the following key components:

1. **`preprocessing.py`**  
   - Loads the dataset, preprocesses images, and splits them into training, validation, and test sets.

2. **`sets_visualization.py`**  
   - Visualizes the distribution of skin lesion classes across training, validation, and test datasets.

3. **`augmentation.py`**  
   - Implements data augmentation techniques to balance underrepresented classes.

4. **`model.py`**  
   - Defines the Xception model architecture used for diagnosing skin lesions.

5. **`evaluate.py`**  
   - Evaluates the trained model, generating confusion matrices, accuracy and loss plots, and classification reports.

6. **`predict.py`**  
   - Enables batch predictions of images from a directory using the trained model.

---

## 🛠️ Technology Stack
- **Frameworks**: TensorFlow, Keras
- **Libraries**: OpenCV, NumPy, Matplotlib
- **Techniques**: CNNs, Data Augmentation, Image Preprocessing


