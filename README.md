# ResNet18 Experiments

This repository contains experiments conducted using the ResNet18 architecture for image classification as an exercise in regularization techniques and pythonic functional programming. The experiments analyze the model's performance under different conditions, including baseline training, dropout regularization, and L2 weight regularization. Various metrics, including loss curves, accuracy trends, and confusion matrices, are visualized to assess the model’s performance.

---

## 📌 **Project Overview**
The goal of this project is to evaluate the effectiveness of different training techniques on ResNet18 for image classification. The experiments include:
- **Baseline Training**: Standard training without regularization.
- **Dropout Regularization**: Introduces dropout layers to prevent overfitting.
- **L2 Regularization**: Applies weight decay to improve generalization.

---

## 📁 **Files and Notebooks**
- `ExperimentswithResNet18.ipynb` - Jupyter Notebook containing code for training and evaluation.
- `baselineplot.png` - Training and validation loss/accuracy for the baseline model.
- `confusion_matrix.png` - Confusion matrix of the best-performing model.
- `dropoutplots.png` - Training and validation metrics for the dropout experiment.
- `l2plots.png` - Training and validation metrics for the L2 regularization experiment.
- `model_comparison.png` - Comparison of different training approaches.
- `training_metrics.png` - Summary plots showing key training metrics.

---

## 📊 **Experiment Results**
### **1️⃣ Baseline Training**
The following plot shows the loss and accuracy curves for the ResNet18 model without regularization:

![Baseline Training Metrics](https://github.com/SYEDFAIZAN1987/ResNet18Experiments/blob/main/baselineplot.png)

---

### **2️⃣ Model Performance: Confusion Matrix**
The confusion matrix highlights the classification performance of the best-trained model:

![Confusion Matrix](https://github.com/SYEDFAIZAN1987/ResNet18Experiments/blob/main/confusion_matrix.png)

---

### **3️⃣ Dropout Regularization**
The effect of adding dropout layers during training:

![Dropout Training Metrics](https://github.com/SYEDFAIZAN1987/ResNet18Experiments/blob/main/dropoutplots.png)

---

### **4️⃣ L2 Regularization**
Training and validation results when applying L2 weight decay:

![L2 Regularization Training Metrics](https://github.com/SYEDFAIZAN1987/ResNet18Experiments/blob/main/l2plots.png)

---

### **5️⃣ Model Comparisons**
A comparison of all models (Baseline, Dropout, and L2 Regularization):

![Model Comparison](https://github.com/SYEDFAIZAN1987/ResNet18Experiments/blob/main/model_comparison.png)

---

### **6️⃣ Training Metrics Overview**
A combined view of training loss and accuracy across all models:

![Training Metrics](https://github.com/SYEDFAIZAN1987/ResNet18Experiments/blob/main/training_metrics.png)

---

## 🛠 **Setup and Usage**
### **Prerequisites**
- Python 3.x
- PyTorch
- Matplotlib
- NumPy
- Scikit-learn

### **Run the Notebook**
1. Clone the repository:
   ```
   git clone https://github.com/SYEDFAIZAN1987/ResNet18Experiments.git
   cd ResNet18Experiments
   ```

### 📌 Conclusion
This project demonstrates how different regularization techniques impact the performance of ResNet18. The results suggest that L2 regularization and dropout help improve generalization, preventing overfitting.

### 📜 License
This project is released under the MIT License.
