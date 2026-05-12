# CropGuard - Plant Disease Detection System

A deep learning-based image classification system that detects plant diseases from leaf images. Built to help agricultural users identify diseases early and take timely action.

---

## Overview

CropGuard uses a Convolutional Neural Network (CNN) trained on the Kaggle plant disease dataset to classify leaf images into healthy or disease-specific categories. The system processes an uploaded leaf image and returns a disease classification along with an early action recommendation.

---

## Workflow

Leaf image upload → Image preprocessing → CNN inference → Disease classification → Early action recommendation

---

## Project Structure

```
CropGuard/
├── Train_plant_disease.ipynb           # Model training notebook
├── Train_plant_disease-checkpoint.ipynb
├── Test_plant_disease.ipynb            # Model testing and evaluation notebook
├── Test_plant_disease-checkpoint.ipynb
├── training_hist.json                  # Training history and metrics
├── training_hist-checkpoint.json
```

---

## Tech Stack

- **Language:** Python
- **Framework:** TensorFlow / Keras
- **Model Architecture:** Convolutional Neural Network (CNN)
- **Dataset:** Kaggle Plant Disease Dataset

---

## Features

- Classifies leaf images into healthy and multiple disease-specific categories
- Preprocessing pipeline for consistent image input
- Early intervention recommendations based on classification output
- High classification accuracy across disease categories

---

## How to Run

**1. Clone the repository**

```bash
git clone https://github.com/Pragna-824/CropGuard.git
cd CropGuard
```

**2. Install dependencies**

```bash
pip install tensorflow keras numpy matplotlib scikit-learn pillow
```

**3. Train the model**

Open and run `Train_plant_disease.ipynb` in Jupyter Notebook or Google Colab.

**4. Test the model**

Open and run `Test_plant_disease.ipynb` with your leaf images to get disease predictions.

---

## Dataset

The model is trained on the [Plant Disease Dataset from Kaggle](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset), which contains images of healthy and diseased plant leaves across multiple crop categories.

---

## Requirements

- Python 3.8 or higher
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pillow
- scikit-learn

---

## Results

- High classification accuracy across healthy and disease-specific leaf categories
- Supports early disease detection to enable timely agricultural intervention

---

## Author

**Deva Pragna Mankena**
- GitHub: [github.com/devapragna](https://github.com/devapragna)
- LinkedIn: [linkedin.com/in/deva-pragna-mankena](https://linkedin.com/in/deva-pragna-mankena)

---

## License

This project is open source and available under the [MIT License](LICENSE).
