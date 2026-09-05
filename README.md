# Plant Disease Classification with CNN

Project: Plant disease detection — Jupyter notebook, data links, training and evaluation for plant disease classification.

## What this project does
This project demonstrates end-to-end exploration and supervised image classification for plant disease detection using the PlantVillage dataset (kaggle: mohitsingh1804/plantvillage). It includes dataset download/connection, exploratory data analysis (class counts, sample images), and the experimental work (notebook contains the data exploration steps; model training and evaluation cells can be added or extended).

## Highlights
- Dataset: PlantVillage (mohitsingh1804/plantvillage)
- Structure: train/ and val/ directories with 38 classes (several thousand images across classes)
- Demonstrated tasks: dataset download (kagglehub), directory inspection, class distribution analysis, and visualization of sample images
- Notebook: Untitled3.ipynb contains the data exploration steps used for EDA and dataset verification

## Repository structure (top-level)
- Untitled3.ipynb — Jupyter notebook used for dataset download, exploration, and visualization
- (Add) requirements.txt — recommended Python dependencies for reproducing the notebook
- (Optional) models/ — place to save trained model checkpoints
- (Optional) reports/ — evaluation reports (confusion matrix, metrics)
- (Optional) README.md — this file

## Reproducibility — requirements
Install required packages (example):
```bash
python -m venv venv
source venv/bin/activate      # or venv\Scripts\activate on Windows
pip install --upgrade pip
pip install jupyter numpy matplotlib pillow kagglehub
# If you plan to train models:
pip install tensorflow scikit-learn
