# Single-Layer Perceptron

## Overview
This project implements a **Single-Layer Perceptron (SLP) from scratch** using Python and NumPy for binary classification. The model is trained and tested on the Breast Cancer Wisconsin (Diagnostic) dataset.

## Dataset
- **Name:** Breast Cancer Wisconsin (Diagnostic)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- **Total Samples:** 569
- **Features:** 30
- **Classes:** 
  - Benign (0)
  - Malignant (1)

## Technologies Used
- Python
- NumPy
- Pandas
- Jupyter Notebook

## Implementation
1. Load the dataset.
2. Separate features and target labels.
3. Split data into 80% training and 20% testing.
4. Normalize the features.
5. Implement the Single-Layer Perceptron from scratch.
6. Train the model using the Perceptron learning algorithm.
7. Predict test samples.
8. Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix.

## Project Structure
```text
single-layer-perceptron/
│
├── Single_Layer_Perceptron.ipynb
├── wdbc.data
├── wdbc.names
└── README.md
```

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/USERNAME/single-layer-perceptron.git
```

2. Install required libraries:
```bash
pip install numpy pandas matplotlib
```

3. Open Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `Single_Layer_Perceptron.ipynb` and run all cells.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Note
The Single-Layer Perceptron is implemented from scratch without using prebuilt machine learning models.

## Author
Ali Haider