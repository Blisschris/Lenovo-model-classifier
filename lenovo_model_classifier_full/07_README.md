# Lenovo Laptop Model Classifier

This project uses a synthetic dataset of Lenovo laptops to classify the device into its correct model category (e.g., ThinkPad, IdeaPad, Yoga, etc.) based on hardware specifications using a Random Forest Classifier.

## 🧠 Features Used
- CPU
- RAM
- Storage Type and Size
- Screen Size
- Resolution
- GPU
- Battery Life
- Weight
- Touchscreen
- Price

## 📊 Outputs
- `classification_report.txt` – Precision, recall, and f1-score per class
- `confusion_matrix.png` – Heatmap of actual vs. predicted
- `feature_importance.png` – Which features contributed most to the model

## 📁 Files
- `lenovo_laptop_data.csv` – Input dataset
- `random_forest_model.pkl` – Trained model
- `requirements.txt` – Dependencies
- `README.md` – Project overview

## 🚀 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Load the dataset and model using the provided Python code
3. Predict or evaluate further

---

*Built for showcasing classification and model explainability using Lenovo specs.*
