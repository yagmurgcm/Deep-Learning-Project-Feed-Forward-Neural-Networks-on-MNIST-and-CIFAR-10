# Image Classification on MNIST and CIFAR-10

This project focuses on image classification using different machine learning and deep learning models on two benchmark datasets: MNIST and CIFAR-10.

## 📊 Objective
The goal of this project is to compare the performance of:
- Logistic Regression (baseline)
- Feed-Forward Neural Network (MLP)
- Convolutional Neural Network (CNN)

across datasets with different levels of complexity.

## 🧠 Models Used
- **Logistic Regression** → Linear baseline model  
- **MLP (Multi-Layer Perceptron)** → Non-linear fully connected network  
- **CNN (Convolutional Neural Network)** → Spatial feature learning model  

## 📁 Datasets
- **MNIST**: 28×28 grayscale handwritten digits (simple dataset)
- **CIFAR-10**: 32×32 RGB images with 10 classes (complex dataset)

## ⚙️ Training Setup
- Loss Function: Cross-Entropy Loss  
- Optimizer: Adam  
- Learning Rate: 0.001  
- Batch Size: 64  
- Epochs: 10  

## 📈 Results Summary

| Dataset   | Logistic | MLP   | CNN   |
|----------|----------|-------|-------|
| MNIST    | ~92%     | ~98%  | ~99%  |
| CIFAR-10 | ~34%     | ~36%  | ~65%  |

## 🔍 Key Insights
- CNN consistently outperforms other models due to its ability to capture spatial features.
- MNIST is relatively easy, and even simple models perform well.
- CIFAR-10 is significantly more complex, requiring more advanced architectures.
- MLP improves over Logistic Regression but struggles with spatial data.

## ⚠️ Observations
- Overfitting observed in CNN on CIFAR-10 (train ↑, val plateau)
- Underfitting observed in simpler models on CIFAR-10

## 🚀 Future Improvements
- Deeper CNN architectures (e.g., ResNet)
- Data augmentation (flip, rotation, cropping)
- Hyperparameter tuning (learning rate, batch size, dropout)

## 🛠️ Technologies
- Python
- PyTorch
- NumPy, Matplotlib
- Google Colab (GPU acceleration)

## 👩‍💻 Authors
- Yağmur Geçim
- Berkay Bilici
