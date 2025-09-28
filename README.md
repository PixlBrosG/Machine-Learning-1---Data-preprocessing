# Ames Housing Price Prediction

This repository contains a Jupyter Notebook for **Assignment 1** in Machine Learning (Fall 2025).  
The task was to analyze the Ames Housing dataset, perform preprocessing, feature engineering, visualization, and compare three regression models:

- **Linear Regression**
- **Polynomial Regression**
- **Random Forest Regressor**

---

## 📂 Dataset

The dataset is not included in this repository.  
Please download it from Kaggle:

👉 [Ames Housing Dataset](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset)

After downloading, place the CSV file (e.g. `AmesHousing.csv`) in the same directory as the notebook.

---

## 🚀 Usage

1. Clone or download this repository.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the dataset file (`AmesHousing.csv`) in the project root directory.
4. Open the notebook:
   ```bash
   jupyter notebook AmesHousing.ipynb
   ```
5. Run all cells to reproduce the analysis and results.

---

## 📊 Results

Model performance (on test data):

| Model                 | R²    | RMSE     | MAE    |
| --------------------- | ----- | -------- | ------ |
| Linear Regression     | 0.896 | 8.34e+08 | 15,969 |
| Polynomial Regression | 0.853 | 1.17e+09 | 18,022 |
| Random Forest         | 0.911 | 7.10e+08 | 15,918 |

---

## ✨ Notes

- The focus of this assignment was **data preprocessing, feature selection, and reasoning** rather than algorithm fine-tuning.
- Accuracy differences reflect model strengths: Random Forest handled non-linearities best, while Polynomial Regression tended to overfit.

---

## 📦 Requirements

Save the following as `requirements.txt`:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
```
