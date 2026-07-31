# Water-Potability-Project

# 💧 Water Potability Prediction Using Machine Learning

Water Quality Classification using 6 ML Models

## 📌 Project Overview
This project aims to classify water samples as **potable (safe to drink)** or **non-potable (not safe to drink)** based on 9 chemical and physical properties. The dataset contains 3276 water samples with various quality parameters.

## 🧪 Dataset Features
- **pH**: Acidity/Basicity of water
- **Hardness**: Mineral content in water
- **Solids**: Total dissolved solids (TDS)
- **Chloramines**: Chlorine and ammonia compound
- **Sulfate**: Sulfate concentration
- **Conductivity**: Electrical conductivity
- **Organic_carbon**: Organic carbon content
- **Trihalomethanes**: Disinfection byproducts
- **Turbidity**: Water clarity/cloudiness

## 🤖 Models Implemented
| Model | Description |
|-------|-------------|
| Logistic Regression | Simple and fast baseline model |
| Decision Tree | Interpretable tree-based model |
| Random Forest | Ensemble of decision trees |
| **XGBoost** | **Best performing model** |
| SVM | Kernel-based classifier |
| KNN | Distance-based classifier |

## 📊 Results
| Model | Accuracy |
|-------|----------|
| XGBoost | 66.46% 🏆 |
| Random Forest | 66% |
| Decision Tree | 64.78% |
| SVM | 62.34% |
| KNN | 62.04% |
| Logistic Regression | 60.97% |

## 🚀 Live Demo
This project includes a **Gradio** web application where users can input water parameters and get instant predictions.

## 🛠️ Technologies Used
- **Python** (3.11.5)
- **Scikit-learn** (Machine Learning)
- **XGBoost** (Gradient Boosting)
- **Pandas & NumPy** (Data Processing)
- **Matplotlib & Seaborn** (Visualization)
- **Gradio** (Deployment)

## 📁 Project Structure

Water-Potability-Project/
├── water_potability_notebook.ipynb # Main notebook with all code
├── app_gradio.py # Gradio web application
├── water_potability_model.pkl # Saved best model (XGBoost)
├── scaler.pkl # Saved StandardScaler
├── final_model_comparison.csv # Results comparison table
├── model_report.txt # Detailed model report
├── model_comparison_accuracy.png # Accuracy comparison chart
├── confusion_matrices_all_models.png # Confusion matrices
└── README.md # This file
