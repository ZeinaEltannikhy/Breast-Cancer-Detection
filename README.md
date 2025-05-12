# 🧠 Breast Cancer Image Classification using Deep Learning

This project is part of my exploration into medical imaging and AI. It focuses on detecting breast cancer from histopathological images using convolutional neural networks (CNNs). As a pharmacy student with a passion for AI in healthcare, I built this model to understand how deep learning can support early diagnosis and improve patient outcomes.

---

## 🔍 Project Overview

The goal of this project is to build a reliable deep learning model that can classify breast tissue images as benign or malignant. The model processes image data and learns visual patterns indicative of cancerous cells.

---

## 🧬 Key Features

- 📊 **Binary classification**: Benign vs. Malignant
- 📁 **Image input**: Histopathological breast cancer slides
- 🧠 **Model**: CNN architecture built using Keras & TensorFlow
- 📉 **Evaluation metrics**: Accuracy, loss curves, and confusion matrix
- 📚 **Notebook**: Fully documented and interactive in `breast-cancer-image-project.ipynb`

---

## 🗂 Project Structure

📁 breast-cancer-image-classification/
├── breast-cancer-image-project.ipynb # Main Jupyter notebook with full pipeline
├── dataset/ # Image folders: benign/ and malignant/
├── models/ # Saved trained models (if any)
├── README.md # Project overview (this file)

---

## 🚀 How to Run

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/breast-cancer-image-classification.git
cd breast-cancer-image-classification
Install dependencies:

pip install -r requirements.txt

Launch the notebook:

jupyter notebook breast-cancer-image-project.ipynb

Make sure to have the dataset in the correct path (e.g., dataset/benign/ and dataset/malignant/).

🛠 Model Details
Preprocessing: Resizing, normalization, and image augmentation

Architecture: 3 convolutional layers + max pooling + fully connected layers

Optimizer: Adam

Loss function: Binary cross-entropy

Epochs: Adjustable via notebook

📈 Results
Achieved High accuracy on validation set 

Visualized training/validation loss and accuracy

Evaluated using confusion matrix to analyze false positives/negatives

🧠 Why This Project?
I’m deeply interested in how AI can assist in clinical decision-making. Breast cancer remains one of the most common and deadly cancers among women. This project allowed me to apply deep learning concepts to a meaningful real-world healthcare challenge.

📌 Future Improvements
Experiment with transfer learning using models like ResNet or VGG16

Deploy as a web app using Streamlit or Flask

Add heatmaps (Grad-CAM) for interpretability

Expand dataset for better generalization

