
# CNN_HEPATO

**CNN_HEPATO** is a computer vision project that utilizes Convolutional Neural Networks (CNNs) to classify CT scan images for **Hepatocellular Carcinoma (HEPATO)** detection. The dataset contains images categorized into *normal* and *HEPATO* cases, with preprocessing and model training performed using Python and common ML libraries.

---

## Project Structure

```
CNN_HEPATO/
├── hepato.ipynb        # Main notebook with full pipeline (preprocessing, EDA, training)
├── /data               # CT scan images (used in Kaggle input path)
├── README.md           # Project documentation
└── model/              # Trained models (optional)
```

---

## Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/)
- **Classes**:
  - `HEPATO`: Contains images of liver with cancer.
  - `Normal`: Contains healthy liver scans.

The images are grayscale CT scans, organized into class folders:
```
/HEPATO/CT/
├── HEPATO/
├── normal cases/
```

---

## Main Features

- **Image preprocessing** using OpenCV (resizing, grayscale conversion).
- **Data cleaning**: filters invalid images.
- **Exploratory Data Analysis (EDA)**:
  - Visualization of sample CT images.
  - Pixel intensity histograms.
  - Image shape distribution.
- **Train/Test Split** using `train_test_split`.
- **CNN Model** built using `TensorFlow` or `PyTorch` (if included in the final cells).
- **Model Evaluation**: Accuracy, loss visualization, confusion matrix, etc.

---

## Installation

To run the notebook:

```bash
pip install numpy opencv-python matplotlib tqdm scikit-learn
# and optionally tensorflow or torch depending on model used
```

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Over-Mind1/CNN_HEPATO
   cd CNN_HEPATO
   ```

2. Open `hepato.ipynb` in Jupyter Notebook or Kaggle.

3. Modify the dataset path if needed.

4. Run all cells to:
   - Preprocess and explore the data
   - Train and evaluate the CNN model

---

## Sample Visualizations

- Random CT scan samples from each class.
- Pixel intensity histogram for contrast analysis.
- Confusion matrix of predictions.

---

## TODO

- [ ] Add trained model weights and export code.
- [ ] Implement model deployment (e.g., Streamlit or Flask app).
- [ ] Extend dataset and perform hyperparameter tuning.

---

## License

MIT License
