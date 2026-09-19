# SIIM-FISABIO-RSNA COVID-19 Detection

Computer-vision pipeline for the SIIM-FISABIO-RSNA COVID-19 Kaggle competition combining study-level chest X-ray classification with image-level abnormality localization.

> Research/educational project. This is not a clinical diagnostic system.

## Pipeline

1. DICOM preprocessing and exploratory analysis
2. Study-level classification with TensorFlow/Keras backbones
3. Image-level abnormality localization with YOLOv5
4. Cross-validation and experiment tracking
5. Combined final inference

## Study-level labels

- Negative for Pneumonia
- Typical Appearance
- Indeterminate Appearance
- Atypical Appearance

## Repository structure

```text
notebooks/
  siim-covid-19-data-preparation.ipynb
  siim-covid-19-data-visualization.ipynb
  siim-covid-19-study-level-predictions.ipynb
  siim-covid-19-yolo-v5-image-level-predictions.ipynb
  siim-covid-19-final-inference.ipynb
```

## Tech stack

Python, TensorFlow/Keras, YOLOv5, OpenCV, pandas, NumPy, DICOM tooling, matplotlib, seaborn, and Weights & Biases.

The original competition dataset, model weights, and third-party research PDFs are not redistributed in this portfolio repository. Obtain permitted data from the competition source before reproducing experiments.

## Disclaimer

Model outputs are experimental and have not been validated for clinical use.
