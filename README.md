# Animal Image Classification Using Deep Learning


A deep learning project for multi-class animal image classification using transfer learning and fine-tuning with different convolutional neural network architectures.

The project investigates multiple pretrained models and training strategies to classify images across **64 animal categories**.

---

## 📌 Project Overview

The main objective of this project is to develop and evaluate deep learning models capable of automatically classifying animal images into their corresponding categories.

The project follows a multi-phase experimental approach:

* Dataset preparation
* Stratified 5-fold cross-validation
* Initial model development
* Transfer learning
* Feature extraction using frozen pretrained models
* Full fine-tuning
* Partial fine-tuning
* Comparative evaluation of different architectures

---

## 🗂️ Project Structure

```text
Animal-Image-Classification/
│
├── notebooks/
│   ├── phase_1/
│   ├── phase_2/
│   └── phase_3/
│
├── reports/
│   ├── Phase_1_AlexNet_VGG16_Classification_Report.docx
│   ├── Phase_2_GoogLeNet_Transfer_Learning_Analysis.docx
│   └── Phase_3_InceptionV3_vs_ResNet50_Transfer_Learning_Analysis.docx
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🐾 Dataset

This project uses an animal image dataset containing **64 animal classes**.

The images are organized into separate folders according to their corresponding animal categories.

Due to the large size of the dataset, the original image files are **hosted on Google Drive rather than stored directly in this GitHub repository**.

### 📂 Dataset Access

The complete dataset can be accessed through the following Google Drive folder:

👉 **[Access the Animal Image Dataset on Google Drive](https://drive.google.com/drive/folders/1C0QeSZxVp6ydMNO7HqCJCToJbJhfy678?usp=drive_link)**

### Dataset Organization

```text
Dataset/
├── Class_1/
├── Class_2/
├── Class_3/
├── ...
└── Class_64/
```

Each class folder contains the images belonging to that animal category.

> **Note:** The dataset is stored separately on Google Drive because of its large size. The GitHub repository contains the notebooks, reports, documentation, and project configuration files.

---

## 🔬 Experimental Phases

### Phase 1 — Dataset Preparation and Initial Modeling

The first phase focuses on preparing the dataset and establishing the experimental setup.

Main tasks include:

* Dataset organization
* Label preparation
* Data preprocessing
* Stratified dataset splitting
* 5-fold cross-validation
* Initial model experimentation

---

### Phase 2 — GoogLeNet Transfer Learning

The second phase investigates **GoogLeNet** using different transfer-learning strategies.

#### V1 — Frozen Feature Extraction

The pretrained convolutional layers are frozen and used as a feature extractor, while the classification layers are trained for the target dataset.

#### V2 — Full Fine-Tuning

The pretrained network is allowed to update its parameters during training so that the learned features can adapt to the animal classification task.

#### V3 — Partial Fine-Tuning

Only selected layers of the pretrained network are fine-tuned while earlier layers remain frozen.

---

### Phase 3 — InceptionV3 and ResNet50

The third phase evaluates two additional pretrained architectures.

#### InceptionV3

Three training strategies are investigated:

* Frozen feature extraction
* Full fine-tuning
* Partial fine-tuning

#### ResNet50

Three training strategies are investigated:

* Frozen feature extraction
* Full fine-tuning
* Partial fine-tuning

The experiments allow comparison between different architectures and fine-tuning strategies.

---

## 🧠 Models

The project investigates the following deep learning architectures:

| Model       | Experimental Strategy           |
| ----------- | ------------------------------- |
| GoogLeNet   | Transfer Learning & Fine-Tuning |
| InceptionV3 | Transfer Learning & Fine-Tuning |
| ResNet50    | Transfer Learning & Fine-Tuning |

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

* Image resizing
* Data augmentation
* Image normalization
* Label encoding
* Stratified dataset splitting

The exact preprocessing configuration can be found in the corresponding notebooks.

---

## 📊 Evaluation Metrics

The models are evaluated using standard multi-class classification metrics:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-score**

Training and validation performance are also monitored to evaluate model convergence and identify potential overfitting.

Detailed experimental analysis is provided in the reports.

---

## 🧪 Cross-Validation

A **stratified 5-fold cross-validation** strategy is used during the experiments.

Stratification helps maintain a similar distribution of animal classes across the different folds, providing a more reliable evaluation of model performance.

---

## 💻 Technologies

The project was developed using:

* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Pandas**
* **Scikit-learn**
* **Matplotlib**
* **Jupyter Notebook**
* **Google Colab**

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/3abdullahelsayed/Animal-Image-Classification.git
cd Animal-Image-Classification
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Project

To reproduce the experiments:

1. Clone this repository.
2. Access the dataset using the **Google Drive link** above.
3. Configure the dataset path according to the notebooks.
4. Start with the dataset preparation notebook in `notebooks/phase_1/`.
5. Run the model experiments in the corresponding phase directories.
6. Review the evaluation metrics.
7. Refer to the reports for detailed experimental analysis.

---

## 📄 Reports

The `reports/` directory contains the project's experimental documentation and analysis.

The reports cover:

* Initial classification experiments
* GoogLeNet transfer learning
* InceptionV3 experiments
* ResNet50 experiments
* Comparative analysis of different approaches

---

## 🎯 Project Topics

This project covers:

* Deep Learning
* Computer Vision
* Image Classification
* Convolutional Neural Networks
* Transfer Learning
* Fine-Tuning
* Data Augmentation
* Cross-Validation
* Model Evaluation
* Multi-Class Classification

---

## 👥 Project

This project was developed as an academic machine learning and deep learning project focused on animal image classification and transfer learning.

---

## 📜 License

This project is intended primarily for educational and academic purposes.
