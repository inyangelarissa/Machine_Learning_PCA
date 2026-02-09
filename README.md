# PCA Agriculture Analysis Library

A lightweight Python library designed to support **Principal Component Analysis (PCA)** for agricultural and food security datasets, based on the *African Agriculture and Food Security Indicators* project.

This library simplifies data loading, standardization, PCA computation, and visualization for students and researchers working with real-world agricultural data.

---

## Project Structure

```
pca_agriculture/
│
├── pca_agriculture/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── pca_model.py
│   └── visualization.py
│
├── examples/
│   └── agriculture_pca_example.ipynb
│
├── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone or Download the Project

```bash
git clone <repository-url>
cd pca_agriculture
```

Or download and extract the ZIP file.

---

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

* **Windows**

```bash
venv\Scripts\activate
```

* **macOS / Linux**

```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Required packages include:

* `numpy`
* `pandas`
* `scikit-learn`
* `matplotlib`
* `seaborn`

---

