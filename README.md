# 🌾⚙️ AI-Based Predictive and Agricultural Systems

This repository contains my internship project completed under **The IoT Academy in collaboration with Upskill Campus**.  
The project focuses on applying Artificial Intelligence in two domains:
1. **Crop & Weed Detection using Computer Vision**
2. **Turbofan Engine Remaining Useful Life (RUL) Prediction using Predictive Maintenance**

All implementations for both projects are included in a single notebook:  
📌 `AI_Internship_Project.ipynb`

---

## ✅ Project 1: Crop & Weed Detection

### 🔹 Objective:
To classify whether an image contains a crop or weed using Deep Learning models.

### 🔹 Workflow:
- Dataset loaded and preprocessed
- Built a CNN model for binary classification
- Improved results using **ResNet50 (Transfer Learning)**
- Visualized predictions and accuracy

### 🔹 Results:
| Model       | Accuracy |
|-------------|----------|
| CNN         | ~92%     |
| ResNet50    | ~97%     |

---

## ✅ Project 2: Turbofan Engine RUL Prediction

### 🔹 Objective:
To predict the remaining useful life (RUL) of a turbofan engine using NASA CMAPSS dataset.

### 🔹 Workflow:
- Sensor data preprocessing
- Built baseline **RandomForest Regression**
- Used **LSTM (Long Short-Term Memory)** for time-series forecasting
- Evaluated using Mean Absolute Error (MAE)

### 🔹 Results:
| Model            | MAE (Mean Absolute Error) |
|------------------|----------------------------|
| RandomForest     | ~20 cycles                 |
| LSTM             | ~11 cycles                 |

---

## 📁 Repository Structure

