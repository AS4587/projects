# Cell Instance Segmentation Experiments

## Overview
This notebook explores instance segmentation workflows, comparing different model setups and training strategies. It covers data preparation, model training, hyperparameter searches, and summarizes the best-performing configuration.

## Project Structure
- `cell-is.ipynb` — data preparation, model training, and evaluation workflows for instance segmentation experiments.

## Data
The notebook expects cell image datasets prepared for YOLOACT and FPN-based pipelines. Refer to the notebook cells for data paths and preprocessing steps.

## Requirements
- Python 3.x
- Jupyter Notebook/Lab
- Typical CV/ML stack (e.g., numpy, pandas, torch, torchvision, OpenCV)

## Usage
1. Open `cell-is.ipynb` in Jupyter.
2. Run the cells to prepare data, train models, and review results.

## Results
The best trial metrics and qualitative outputs are captured in the notebook output cells.

## Notes
- Adjust dataset paths and experiment parameters as needed.
- Training time varies depending on hardware and dataset size.
