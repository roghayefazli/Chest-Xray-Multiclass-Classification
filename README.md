# 🫁 Lung Disease Classification using ResNet50 Transfer Learning

A deep learning project for multi-class chest X-ray image classification using **Transfer Learning** with **ResNet50** in TensorFlow/Keras.

The project demonstrates an end-to-end medical image classification pipeline, including data preprocessing, transfer learning, fine-tuning, model evaluation, and visualization.

---

## 🚀 Project Highlights

* ✅ Transfer Learning using **ResNet50**
* ✅ Multi-class chest X-ray classification
* ✅ Image preprocessing and normalization
* ✅ Fine-tuning of pretrained CNN
* ✅ Training and validation monitoring
* ✅ Model evaluation with multiple classification metrics
* ✅ Easy-to-extend notebook implementation

---

## 🩺 Classification Classes

The model classifies chest X-ray images into three categories:

* Lung Opacity
* Normal
* Viral Pneumonia


---

## 🛠️ Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

---

## 📊 Model Performance

| Metric            |    Score |
| ----------------- | -------: |
| Accuracy          |  **81%** |
| Weighted F1-score | **0.81** |
| Macro F1-score    | **0.81** |

### Classification Report

| Class           | Precision |   Recall | F1-score |
| --------------- | --------: | -------: | -------: |
| Lung Opacity    |      0.78 |     0.76 |     0.77 |
| Normal          |      0.83 |     0.71 |     0.77 |
| Viral Pneumonia |  **0.82** | **0.97** | **0.89** |

---

## 📈 Evaluation

The notebook includes:

* Training & Validation Accuracy
* Training & Validation Loss
* Classification Report
* Model Prediction Examples

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/Lung-Cancer-prediction-resnet-base.git
cd Lung-Cancer-prediction-resnet-base
```

Install dependencies:

```bash
pip install tensorflow keras numpy matplotlib
```

---

## ▶️ Run

Open the notebook in **Google Colab** or Jupyter Notebook.

Update the dataset paths and execute all cells sequentially.

---

## 🔮 Future Improvements

* Add data augmentation
* Compare ResNet50 with EfficientNet and DenseNet
* Apply Grad-CAM for explainable AI
* Export trained model to ONNX
* Hyperparameter optimization
* Model quantization for edge deployment

---

## 📄 License

This project is released under the MIT License.

---

## 👩‍💻 Author

**Roghaye Fazli**

M.Sc. Student in Artificial Intelligence

GitHub: https://github.com/roghayefazli

LinkedIn: https://linkedin.com/in/roghaye-fazli-662566281
