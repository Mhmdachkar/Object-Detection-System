# 🖼️ Object Detection System

An advanced image classification and object detection project built using **Python**, **TensorFlow**, **Keras**, and **ResNet50**.  
Trained on the **CIFAR-10** dataset, this system combines **custom CNN architectures** and **transfer learning** to achieve high accuracy and robust generalization.

---

## 📌 Features
- **92% accuracy** on CIFAR-10 benchmark.
- Hybrid model combining:
  - **Custom Convolutional Neural Network (CNN)**
  - **Transfer Learning with ResNet50**
- **Regularization techniques**: Dropout & Batch Normalization.
- **Data augmentation** to prevent overfitting and improve robustness.
- Configurable training pipeline.

---

## 🗂️ Dataset
- **CIFAR-10**:  
  - 60,000 32x32 color images in 10 classes.
  - 50,000 training images and 10,000 test images.

---

## 🏗️ Model Architecture
1. **Custom CNN layers** for initial feature extraction.
2. **ResNet50 backbone** for deep feature representation.
3. Fully connected layers for classification.
4. **Softmax** activation for final predictions.

---


🛠️ Technologies Used

Python 3.x

TensorFlow / Keras

NumPy, Pandas, Matplotlib, Seaborn

OpenCV (for preprocessing)

ResNet50 (transfer learning)
