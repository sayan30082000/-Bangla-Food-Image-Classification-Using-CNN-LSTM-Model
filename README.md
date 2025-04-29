# 📌 Bangla Food Image Classification Using CNN-LSTM Model

This project implements a hybrid **Convolutional Neural Network (CNN)** combined with a **Long Short-Term Memory (LSTM)** model to classify Bangladeshi food images into multiple categories.  
The model extracts spatial features using CNN and captures sequential dependencies through LSTM layers, enhancing overall classification performance.

---

## 🧠 Model Architecture

- **Convolutional Neural Networks (CNN)**: For feature extraction from food images.
- **Long Short-Term Memory (LSTM)**: To capture sequential patterns from extracted features.
- **Dense layer with Softmax**: For final multi-class classification.

> 🛠️ Model is built using TensorFlow/Keras.

---

## 📁 Dataset

The dataset is structured into three directories:
- `train/`
- `test/`
- `val/`

Each directory contains subfolders named after the classes (e.g., `Hilsha`, `Biryani`, etc.), and each subfolder contains the corresponding images.

> ⚠️ **Note**:  
> The dataset is not included in the repository due to its size and possible copyright restrictions.
> 
> **You must manually place the dataset at:**  
> `/kaggle/input/fppd03/`  
> With subfolders: `/train`, `/test`, `/val`.

If you want to test the project, you can use your own food image dataset following the same structure.

---
## 📊 Project Results
-The following outputs are generated after training:

-**Training and Validation Accuracy and Loss graphs**

-**Confusion Matrix heatmap**

-**Precision, Recall, and F1-Score Bar Charts**

-**Sample predictions on test images**

-**Final Test Accuracy and Loss**

##🛠️ Technologies Used
**Python 3.x**

**TensorFlow 2.x**

**Keras**

**Pandas**

**NumPy**

**Matplotlib**

**Seaborn**

**Scikit-learn**

## 📜 License
This project is intended for academic and educational purposes.
If you reuse or modify this project, please give appropriate credit.

## 🙏 Acknowledgments
TensorFlow and Keras Documentation

Kaggle Datasets (for food images)

Open-source contributors for CNN-LSTM tutorials and examples

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/sayan203002212/bangla-food-cnn-lstm.git
cd bangla-food-cnn-lstm


