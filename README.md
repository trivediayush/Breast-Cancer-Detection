# Breast Cancer Detection using Logistic Regression

This project aims to predict whether a breast cancer tumor is malignant or benign based on a dataset of cell features from breast tissue. The classification model uses a Logistic Regression algorithm to distinguish between malignant and benign tumors.

## Features
- **Dataset**: The dataset includes various features related to the characteristics of cell nuclei obtained from fine needle aspirates (FNA) of breast tissue.
- **Classification**: Using the features, a Logistic Regression model classifies the tumors into two categories:
  - **Malignant** (cancerous)
  - **Benign** (non-cancerous)
  
- **Data Preprocessing**: The features are preprocessed using `pandas` and `numpy` for easy manipulation and model input.

- **Model Evaluation**: The model's performance is evaluated based on the accuracy score of the classification.

## Libraries and Tools
This project uses the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
  - `LogisticRegression`
  - `train_test_split`
  - `accuracy_score`

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which contains 30 features describing the characteristics of cell nuclei present in breast cancer images. The features include radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.

### Key attributes:
- **Malignant (0)**: Cancerous tumors
- **Benign (1)**: Non-cancerous tumors

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/trivediayush/Breast-Cancer-Detection.git
    cd Breast-Cancer-Detection
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the model**:
    - The model is implemented in `Breast-Cancer.ipynb`. You can run it by executing the following command:

    - After running the script, the model will make predictions for given input data and print whether the breast cancer is **Malignant** or **Benign**.

4. **Input**: 
    - Example input format for predicting cancer type:
    ```python
    input_data = (13.54, 14.36, 87.46, 566.3, 0.09779, 0.08129, 0.06664, 0.04781, 0.1885, 0.05766, 0.2699, 0.7886, 2.058, 23.56, 0.008462, 0.0146, 0.02387, 0.01315, 0.0198, 0.0023, 15.11, 19.26, 99.7, 711.2, 0.144, 0.1773, 0.239, 0.1288, 0.2977, 0.07259)
    ```

5. **Output**:
    - The script will output whether the breast cancer is **Malignant** or **Benign**.

