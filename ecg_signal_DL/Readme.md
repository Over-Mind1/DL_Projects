
# 📊 ECG Signal Classification using 1D CNN

This project uses a 1D Convolutional Neural Network (CNN) to classify ECG (Electrocardiogram) signals into **normal** and **abnormal** categories. It's designed to assist with early detection of cardiac anomalies using deep learning techniques.

## 🔍 Features

- 🧠 Deep learning model using 1D CNN
- 🧹 Data loading and preprocessing
- 📈 Signal visualization
- 📊 Model evaluation using accuracy, classification report, and confusion matrix

## 📁 Dataset

The model uses two datasets:
- `normal.csv` — contains normal ECG samples
- `abnormal.csv` — contains abnormal ECG samples

Each signal is assigned a binary label:
- `0`: Normal
- `1`: Abnormal

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Over-Mind1/ecg_signal_DL.git
   cd ecg-model
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook ecg-model.ipynb
   ```

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy / Pandas
- Scikit-learn
- Matplotlib / Seaborn

## 📊 Model Architecture

The 1D CNN consists of:
- Conv1D and MaxPooling layers
- Dense layers with ReLU and dropout
- Sigmoid activation for binary classification

## 📈 Evaluation

Performance is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 📌 License

MIT License
