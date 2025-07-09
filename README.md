# Pneumonia Detection using Transfer Learning

## Objective

This project aims to fine-tune a pre-trained Inception-V3 model to distinguish between normal and pneumonia chest X-rays from the **PneumoniaMNIST** dataset. The focus is on handling class imbalance and preventing overfitting to build a robust classifier.

## Dataset

*   **Name**: [PneumoniaMNIST](https://medmnist.com/`PneumoniaMNIST`)
*   **Description**: A binary classification dataset of chest X-ray images, categorized as 'normal' or 'pneumonia'.
*   **Challenge**: The dataset is significantly imbalanced, with a much larger number of pneumonia cases than normal cases in the training set.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd <your-repo-name>
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the training and evaluation script:**
    ```bash
    python train.py
    ```
    The script will download the dataset, train the model, evaluate it on the test set, and print the final performance metrics.
