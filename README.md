# 🌿 Plant Leaf Disease Detection using Deep Learning

This project focuses on automatic identification of plant leaf diseases using a Deep Convolutional Neural Network (CNN). It uses transfer learning with MobileNetV2 to classify plant leaves into multiple disease categories efficiently.

---

## 🚀 Project Overview

Agriculture plays a crucial role in our ecosystem, and early detection of plant diseases can significantly improve crop yield. This project aims to build a smart and scalable image classification system that detects plant diseases from leaf images.

---

## 🧠 Model Architecture

- Base Model: MobileNetV2 (pretrained on ImageNet)
- Global Average Pooling layer
- Dropout layer (0.3) for regularization
- Dense output layer with Softmax activation
- Transfer Learning (base model frozen)

---

## 📂 Dataset

- Dataset: Plant Leaf Diseases Dataset with Augmentation
- Contains multiple classes such as:
  - Healthy
  - Early Blight
  - Late Blight
  - (and more depending on dataset)

- Data split:
  - Training: 80%
  - Validation: 20%

---

## 🔧 Features

- Automatic dataset extraction from ZIP files  
- Image preprocessing (resize to 224×224)  
- Data augmentation (flip, rotation, zoom)  
- Fast training setup  
- Model saving & loading  
- Single image prediction with probability output  

---

## 🏋️ Training Details

- Loss Function: Sparse Categorical Crossentropy  
- Optimizer: Adam  
- Metrics: Accuracy  
- Batch Size: 32  
- Epochs: Configurable (default used: 1 for testing)  

---

## 📊 Output

- Displays training & validation accuracy  
- Predicts disease class for a given leaf image  
- Shows probability scores for all classes  

---

## 🧪 Testing

To test the model on a custom image:

1. Provide the image path  
2. The model will:
   - Preprocess the image  
   - Predict the class  
   - Display confidence scores  

---

## 💾 Model File

```
leaf_disease_model.h5
```

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  

---

## 📌 Future Improvements

- Increase training epochs for better accuracy  
- Fine-tune the base model  
- Deploy as a web/mobile application  
- Add real-time camera detection  

---

## 🤝 Contribution

Feel free to fork this repository, raise issues, or submit pull requests.

---

## ⭐ Support

If you found this project helpful, consider giving it a star ⭐
