# Satellite Image Classification Using CNN

##  Project Overview
This deep learning project classifies satellite images into four categories: **Water**, **Green Area**, **Desert**, and **Cloud**. The model is built using **Convolutional Neural Networks (CNNs)** for accurate image recognition.

## 📊 Dataset
- **Water**: Satellite images of water bodies
- **Green Area**: Forests, fields, and vegetated land
- **Desert**: Arid and sandy landscapes
- **Cloud**: Various cloud formations

## 🔧 Technologies & Libraries Used
- **Python**, **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib** for visualization
- **TensorFlow**, **Keras** for deep learning
- **Scikit-learn** for evaluation metrics

## 🔄 Preprocessing Steps
1. Loaded and labeled images:
    - 0: **Water**
    - 1: **Green Area**
    - 2: **Desert**
    - 3: **Cloud**
2. Shuffled dataset for better generalization
3. Resized images to **64×64 pixels**
4. Split dataset into **training (70%)** and **testing (30%)**

## 🤖 Model Architecture
- **Conv2D Layers**: Extract spatial patterns
- **MaxPooling Layers**: Reduce feature map size
- **Flatten Layer**: Convert matrices into a vector
- **Dense Layers**: Fully connected layers for prediction
- **Softmax Activation**: Multi-class classification

## 📈 Results & Evaluation
- **Accuracy**: Evaluated on test data
- **Confusion Matrix**: Analyzed performance across categories
- **Predictions**: Model successfully classifies satellite images

