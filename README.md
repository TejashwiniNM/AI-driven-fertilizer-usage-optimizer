# AI-driven-fertilizer-usage-optimi# 🌱 AI-Driven Sustainable Fertilizer Usage Optimizer

## 📌 Project Overview
This project uses Machine Learning to recommend the **best fertilizer** based on soil nutrients (NPK), soil type, crop type, temperature, humidity, and moisture.  
The goal is to promote **sustainable agriculture** and **higher yields** by optimizing fertilizer usage.

---

## 📊 Dataset
- Source: Kaggle (Fertilizer Recommendation Dataset – Ismail Saleem)  
- File used: `data_core_updated.csv`  
- Features:
  - Temperature
  - Humidity
  - Soil Moisture
  - Soil Type
  - Crop Type
  - Nitrogen, Phosphorus, Potassium (NPK)
- Target:
  - Fertilizer type (e.g., Urea, MOP, DAP, etc.)

---

## 🔎 Exploratory Data Analysis (EDA)
- Histograms for numeric features (NPK, temperature, humidity, soil moisture)  
- Correlation heatmap for feature relationships  
- Fertilizer type distribution  

---

## 🤖 Machine Learning Models
- Decision Tree Classifier  
- Random Forest Classifier (chosen due to higher accuracy)  

### Accuracy
Random Forest achieved better performance compared to Decision Tree.

---

## 🔮 Prediction Demo
Example custom input:
```python
Temperature = 28
Humidity = 65
Soil Moisture = 55
Soil Type = Loamy
Crop Type = Wheat
Nitrogen = 90
Phosphorus = 30
Potassium = 40
zer

Note: The .ipynb notebook may not render properly on GitHub due to size.
Please download and open it locally in Jupyter/VS Code to view execution.
The .pkl model files are binary and should be loaded in Python using joblib.load().
