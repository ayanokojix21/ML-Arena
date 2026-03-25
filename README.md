# 🧠 ML Arena

## 🗺 What is this?

ML Arena is a **open-source ML repo** where contributors implement machine learning algorithms, explore datasets, and optimize models — all inside Jupyter notebooks. Every contribution earns points. The best implementations win.

There are **4 types of tasks**, each targeting a different skill level:

| Type | What you build | 
|---|---|
| 🧠 **Scratch** | Full algorithm using only NumPy
| ⚡ **Optimization** | Extend scratch with momentum, pruning, tuning 
| 📦 **Library** | Clean sklearn/statsmodels implementation 
| 🔬 **Exploration** | EDA + model behaviour plots in one notebook
---

## 📁 Repository Structure

```
ML-Arena/
├── README.md
├── problems/
│   ├── 01_linear_regression/
│   │   ├── README.md
│   │   ├── dataset.csv
│   │   ├── scratch/
│   │   │   └── training.ipynb
│   │   ├── library/
│   │   │   └── training.ipynb
│   │   └── exploration/
│   │       └── exploration.ipynb
│   ├── 02_logistic_regression/   ← same layout
│   ├── 03_decision_tree/
│   ├── 04_kmeans_clustering/
│   └── 05_neural_network/
└── templates/
    ├── scratch_training_template.ipynb
    ├── library_training_template.ipynb
    └── exploration_template.ipynb
```

---

## 🚀 Quick Start

### 1. Fork & Clone

```bash
# Fork via GitHub UI, then:
git clone https://github.com/YOUR_USERNAME/ML-Arena.git
cd ML-Arena
```

### 3. Dataset Availability

All problem datasets are stored locally in this repository at:

- `problems/01_linear_regression/dataset.csv`
- `problems/02_logistic_regression/dataset.csv`
- `problems/03_decision_tree/dataset.csv`
- `problems/04_kmeans_clustering/dataset.csv`
- `problems/05_neural_network/dataset.csv`

### 4. Pick an Issue

Go to [**Issues**](../../issues) and filter by label:

- `scratch` → hardest, most points
- `library` → good starting point
- `exploration` → data-focused
- `optimization` → extends existing scratch work

### 5. Work in Your Branch

```bash
git checkout -b scratch/linear-regression
# ... do your work ...
git add problems/01_linear_regression/scratch/training.ipynb
git commit -m "feat: implement linear regression from scratch"
git push origin scratch/linear-regression
```

### 6. Open a Pull Request

Use the PR template. Link the issue with `Closes #<issue-number>`

---

## 🎯 Open Issues

> Browse all open issues in the repository [Issues](../../issues) tab.

### 🔬 Exploration 
| # | Task | Notebook |
|---|---|---|
| #3 | Exploration: Linear Regression dataset | `problems/01_linear_regression/exploration/exploration.ipynb` |
| #6 | Exploration: Spam Classification dataset | `problems/02_logistic_regression/exploration/exploration.ipynb` |
| #12 | Exploration: K-Means dataset | `problems/04_kmeans_clustering/exploration/exploration.ipynb` |

### 🧠 Scratch Training 
| # | Task | Notebook |
|---|---|---|
| #1 | [Scratch] Linear Regression from scratch | `problems/01_linear_regression/scratch/training.ipynb` |
| #7 | [Scratch] Decision Tree from scratch | `problems/03_decision_tree/scratch/training.ipynb` |
| #13 | [Scratch] K-Means from scratch | `problems/04_kmeans_clustering/scratch/training.ipynb` |
| #16 | [Scratch] Neural Network from scratch | `problems/05_neural_network/scratch/training.ipynb` |

### 📦 Library Training 
| # | Task | Notebook |
|---|---|---|
| #2 | [Library] Linear Regression with sklearn | `problems/01_linear_regression/library/training.ipynb` |
| #8 | [Library] Logistic Regression with sklearn | `problems/02_logistic_regression/library/training.ipynb` |
| #14 | [Library] K-Means with sklearn | `problems/04_kmeans_clustering/library/training.ipynb` |

### ⚡ Optimization 
| # | Task | Notebook |
|---|---|---|
| #4 | Optimize: Add momentum to gradient descent | `problems/01_linear_regression/scratch/training.ipynb` |
| #9 | Optimize: Hyperparameter tuning for Decision Tree | `problems/03_decision_tree/scratch/training.ipynb` |

---

### Branch Naming

```
scratch/problem-name       # e.g. scratch/linear-regression
library/problem-name       # e.g. library/kmeans
exploration/problem-name   # e.g. exploration/decision-tree
optimization/problem-name  # e.g. optimization/momentum-gd
```