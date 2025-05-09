# ISIC Classifier

This repository contains the implementation and results for binary skin lesion classification (melanoma vs. non-melanoma) as part of the ISIC 2017 Challenge Task 3.

## Files

- `best.ipynb`: Jupyter notebook containing the training, validation, and test pipeline using EfficientNet-B3. It includes data preprocessing, model training with early stopping, and final evaluation on the ISIC 2017 test set.
- `ISIC.pdf`: A 1-page summary report detailing the methodology, model architecture, training strategy, data splits, performance metrics, and visualizations.

## Method Overview

- **Model**: EfficientNet-B3 (pretrained on ImageNet)
- **Training Set**: 500 images (sampled from 2000)
- **Validation Set**: 150 images
- **Test Set**: 600 images
- **Metrics**: AUC = 0.707, Accuracy = 0.69


## Usage

To run the model:

```bash
# Inside your virtual environment
jupyter notebook best.ipynb
