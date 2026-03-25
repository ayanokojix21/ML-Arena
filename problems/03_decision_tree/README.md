# 03 Decision Tree

## Goal

Build a tree-based classifier from scratch and compare with library baseline.

## Dataset

Use `problems/03_decision_tree/dataset.csv` (already committed).

- Source: UCI Adult / Census Income (id=2)
- Shape: 10000 rows, 15 columns after dropping rows with missing placeholders
- Target column: `income`

## Suggested Beginner Issues

- Exploration: Data quality checks plus confusion-matrix and depth-behavior plots.
- Scratch: Implement Gini impurity and recursive split.
- Library: Train sklearn DecisionTreeClassifier baseline.
- Optimization: Add max_depth tuning and pruning comparison.

## Target Files by Task Type

- Exploration: exploration/exploration.ipynb
- Scratch training: scratch/training.ipynb
- Library training: library/training.ipynb
