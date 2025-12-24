# 🌱 Crop Recommendation System

A machine learning system that recommends the optimal crop to plant based on soil nutrients and environmental conditions.

## 🎯 Features
- **Dual Model Comparison**: Decision Tree vs. Naive Bayes classifiers
- **7 Parameter Input**: N, P, K, temperature, humidity, pH, rainfall
- **Interactive CLI**: Real-time user input and prediction
- **Model Evaluation**: Accuracy scores, confusion matrices, classification reports
- **Google Colab Ready**: Developed and tested in Colab environment

## 📊 Results
- **Best Model**: Gaussian Naive Bayes
- **Accuracy**: 85%+
- **Dataset**: 2200+ samples with 7 features

## 🚀 Quick Start

### Installation

pip install -r requirements.txt
Usage
bash
python crop_recommendation.py
Enter values when prompted:

Nitrogen (N): 90

Phosphorous (P): 42

Potassium (K): 43

Temperature (°C): 21

Humidity (%): 82

pH level: 6.5

Rainfall (mm): 203

Output Example: Recommended crop: Rice

🛠️ Technologies Used
Python 3.8+

Scikit-learn - Machine learning algorithms

Pandas - Data manipulation

Google Colab - Development environment

📚 Dataset
Source: Kaggle Crop Recommendation Dataset

Samples: 2200

Features: 7 numerical parameters

Target: 22 crop types

📝 Development Notes
Originally developed in Google Colab for GPU acceleration

Focus on agricultural decision support

Model chosen based on comparative accuracy analysis

👨‍💻 Author
Amna Mumtaz - Software Engineering Student @ IIU
