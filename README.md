# PCOS Detection Using Deep Learning

## Overview

This project presents a deep learning-based Computer-Aided Diagnosis (CAD) system for detecting **Polycystic Ovary Syndrome (PCOS)** from ultrasound images. The model is designed to assist in early diagnosis by automatically identifying ovarian cyst patterns from ultrasound scans using Convolutional Neural Networks (CNNs).

The system aims to reduce manual interpretation effort and improve diagnostic support in clinical settings.

<img width="1760" height="611" alt="image" src="https://github.com/user-attachments/assets/50436ad6-70ba-4f1c-92e3-47a9ea69adfc" />   
<img width="484" height="390" alt="image" src="https://github.com/user-attachments/assets/bdaf5539-c128-4fde-92b5-b2b5e4adf0e3" />



---

## Features

* Deep learning-based PCOS detection
* Ultrasound image preprocessing pipeline
* CNN model training and evaluation
* Data visualization and performance metrics
* Binary classification: PCOS / Non-PCOS
* Jupyter Notebook implementation

---

## Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Dataset

The project uses ovarian ultrasound images for binary classification.

### Classes

* PCOS
* Normal

<img width="590" height="390" alt="image" src="https://github.com/user-attachments/assets/3d28cf3e-4d67-43df-ba5e-5ed52ba454f1" />


### Preprocessing Steps

* Image resizing
* Normalization
* Data augmentation
* Train-test split

> Note: Dataset is used only for educational and research purposes.

---

## Model Architecture

The project uses a Convolutional Neural Network (CNN) architecture for feature extraction and classification.

### Workflow

1. Load ultrasound images
2. Preprocess and augment data
3. Train CNN model
4. Evaluate model performance
5. Predict PCOS from unseen images

---

## Results

The model demonstrates effective classification performance on ultrasound images and can assist in early PCOS screening.

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

<img width="484" height="390" alt="image" src="https://github.com/user-attachments/assets/206e2e3d-d67f-4897-9ad2-bffdf1701f47" />


---

## Project Structure

```bash
PCOS-Detection/
│
├── dataset/
├── models/
├── outputs/
├── Poly_Cystic_Ovary_Syndrome_detection.ipynb
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/PCOS-Detection.git
cd PCOS-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook:

```bash
jupyter notebook
```

Open:

```bash
Poly_Cystic_Ovary_Syndrome_detection.ipynb
```

---

## Future Improvements

* Deploy as a web application
* Improve model accuracy with larger datasets
* Add explainable AI (XAI) visualizations
* Integrate real-time ultrasound analysis
* Mobile-friendly diagnostic interface

---

## Applications

* Medical imaging research
* AI-assisted healthcare systems
* Early PCOS diagnosis support
* Clinical decision support systems

---

## Author

Ashitha P I
 Deep Learning Enthusiast

---

## License

This project is intended for educational and research purposes.
