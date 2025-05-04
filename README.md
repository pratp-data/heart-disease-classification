## Project Overview

This project uses a Jupyter Notebook (`.ipynb`) on Google Colab to build and evaluate a machine learning model for heart disease prediction using the Kaggle Heart Disease dataset. The notebook includes data preprocessing, analysis, model training, evaluation, and visualizations.

---

## How to Run This Notebook on Google Colab

### 1. **Open the Notebook in Colab**
- Upload the notebook (`heart_disease_classification.ipynb`) to your Google Drive.
- Right-click on the file in Google Drive, select **Open with > Google Colaboratory**.
- Alternatively, go to [Google Colab](https://colab.research.google.com), click **File > Upload notebook**, and select your `.ipynb` file.

### 2. **Upload or Mount the Dataset**
- **If your dataset (`heart.csv`) is on your local computer:**
    ```
    from google.colab import files
    uploaded = files.upload()
    ```
    Use the file picker to select `heart.csv` from your computer.

- **If your dataset is in Google Drive:**
    ```
    from google.colab import drive
    drive.mount('/content/drive')
    ```
    Then, access your file with a path like `/content/drive/My Drive/path/to/heart.csv`.

### 3. **Install Any Required Libraries **
Colab comes with most common libraries pre-installed. If you need to install any additional packages, use:
