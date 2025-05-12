# Outlier Detection for Leaf C:N:P Dataset

This repository contains a simple Python script used to identify potential outliers in leaf carbon (C), nitrogen (N), and phosphorus (P) concentration data, based on the mean ± 3 standard deviations rule.

## File

- `outlier_detection.ipynb`: A Jupyter Notebook used during data processing to detect outliers in repeated leaf and soil nutrient measurements.

## Method

The method applies a standard statistical rule:
- Calculates the mean and standard deviation of repeated measurements.
- Flags values outside the range:  
  `mean ± 3 × standard deviation`

## Requirements

- Python 3.7.0
- NumPy

Install dependencies with:

```bash
pip install numpy
