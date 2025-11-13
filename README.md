# 🗑️ Waste Segregation Classification  
A deep learning project for automated waste classification using a **Hybrid ResNet + CBAM attention model**.  
The project includes full training pipeline, evaluation, ROC/PR curves, Grad-CAM visualization, and detailed metrics.

---

## 📌 Project Overview  
This project aims to classify waste images into predefined categories using a convolutional neural network enhanced with a **Channel & Spatial Attention Module (CBAM)**.  
The hybrid architecture improves feature extraction, robustness, and overall classification performance.

---

## 🧠 Model Architecture  
### **Hybrid Model: ResNet Backbone + CBAM Attention**
- Base model: **ResNet**
- Added: **CBAM (Convolutional Block Attention Module)**
  - Channel Attention  
  - Spatial Attention  
- Enhanced feature selection  
- Better handling of subtle texture differences  
- Improved class discrimination  

---

## 📊 Dataset  
Dataset is structured as follows:
dataset/
├── train/
├── validation/
└── test/


Each folder contains category-wise subdirectories.

---

## 🚀 Features  
- Complete training pipeline  
- Hybrid ResNet + CBAM architecture  
- Evaluation Reports: Accuracy, Loss, MCC, Precision, Recall  
- ROC-AUC curves (class-wise)  
- PR curves  
- Grad-CAM heatmaps  
- Confusion matrix  
- GPU-optimized training  

---

## 📈 Performance Summary  
> (*Based directly on your notebook outputs*)

### **Metrics Printed in Notebook**  
- ✔️ Training & Validation Accuracy curves plotted  
- ✔️ Precision, Recall, F1 Score reported  
- ✔️ MCC (Matthews Correlation Coefficient) printed  
- ✔️ Cohen’s Kappa Score printed  
- ✔️ Confusion Matrix visualized  
- ✔️ Class-wise ROC Curve & PR Curve  
- ✔️ Grad-CAM Visualization for interpretability  

(*If you want, I can extract exact metric values from the notebook — just tell me to “extract metrics”*)

---



