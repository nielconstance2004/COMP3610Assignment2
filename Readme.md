
# 🚖 COMP 3610 – Assignment 2: ML Model Training & Evaluation

**University of the West Indies**  
**Semester II, 2025-2026**  
**Author:** Nie-l Constance

---

## 📘 Overview

This repository contains the Jupyter notebook for Assignment 2 in COMP 3610 (Big Data Analytics). The notebook builds, evaluates and interprets machine learning models that predict taxi tip amounts using the NYC Yellow Taxi Trip dataset (January 2024). It includes:

- Feature engineering and data preprocessing  
- Baseline regression and classification models  
- Hyperparameter tuning with cross‑validation  
- A feed‑forward neural network built with PyTorch  
- Comprehensive evaluation and interpretation of all models

---

## 🗂 Repository Structure

```
COMP3610Assignment2/
├── assignment2.ipynb          # Main Jupyter notebook
├── requirements.txt           # Python dependencies
├── README.md                  # This file
└── .gitignore                 # Excludes data/ and model files
```

> **Note:** Data files are not stored in this repository. The notebook downloads them automatically the first time it runs.

---

## ⚙️ Setup Instructions

Follow these steps to run the notebook locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/nielconstance2004/COMP3610Assignment2.git
cd COMP3610Assignment2
```

### 2️⃣ Create and Activate a Virtual Environment

**On macOS / Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

**On Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Launch Jupyter and Run the Notebook

```bash
jupyter notebook
```

Open `assignment2.ipynb` in the browser and run the cells sequentially.  
All required libraries are included in `requirements.txt`.

---

## 🧠 What You'll See

- **Part 1:** Data cleaning, feature engineering, train/validation/test splits, scaling, and a detailed feature summary table.
- **Part 2:** Baseline models (Linear Regression, Random Forest, Logistic Regression), hyperparameter tuning using `RandomizedSearchCV` with 5‑fold cross‑validation, and a PyTorch neural network.
- **Part 3:** Comprehensive test‑set evaluation, ROC curves, confusion matrices, scatter plots, residual analysis, feature‑importance plots, and a thorough written analysis.
- **Part 4:** Code and notebook documentation, AI‑usage disclosure.

---

## 📊 Results at a Glance

| Task           | Best Model               | Key Metric     | Value   |
|----------------|--------------------------|----------------|---------|
| Regression     | Random Forest Regressor  | R²             | ≈ 0.64  |
| Classification | Tuned Random Forest      | AUC‑ROC        | ≈ 0.62  |

The neural network performed competitively, but the tuned Random Forest offered the best balance of performance and interpretability.

---

## 🤖 AI Tools Used

- **GitHub Copilot** – for boilerplate code and docstrings.
- **ChatGPT** – for refining the written analysis and improving clarity.

All AI‑generated content was reviewed and understood by the author.

---

## 📝 License

This project is submitted for academic assessment. All rights reserved.

---

**Thank you for reviewing this assignment! 🙌**
