# Intel Image Classification Project

## Project Overview

This project focuses on scene classification using Deep Learning techniques. The objective is to classify images into six scene categories using a custom Convolutional Neural Network (CNN) and a MobileNetV2 Transfer Learning model.

The project is implemented using TensorFlow/Keras and evaluated on the Intel Image Classification Dataset.

---

## Dataset

**Dataset Name:** Intel Image Classification Dataset

**Dataset Link:**

https://www.kaggle.com/datasets/puneet6060/intel-image-classification

### Classes

* Buildings
* Forest
* Glacier
* Mountain
* Sea
* Street

### Dataset Size

Approximately 25,000 RGB images across six classes.

---

## Project Objectives

* Develop a CNN-based image classification model.
* Apply data augmentation techniques.
* Evaluate model performance using standard metrics.
* Compare CNN performance with MobileNetV2 Transfer Learning.
* Perform error analysis on misclassified images.

---

## Methodology

### Data Preprocessing

* Image Resizing (150 × 150)
* Image Normalization
* Train/Validation/Test Split

### Data Augmentation

* Random Flip
* Random Rotation
* Random Zoom

### Models Implemented

#### 1. Custom CNN

* Convolution Layers
* MaxPooling Layers
* Dense Layers
* Dropout Layer
* Softmax Output Layer

#### 2. MobileNetV2 Transfer Learning

* Pre-trained on ImageNet
* Global Average Pooling
* Dense Classification Layers
* Dropout Regularization

---

## Evaluation Metrics

The following evaluation metrics were used:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report
* ROC Curve

---

## Results

| Model                         | Test Accuracy |
| ----------------------------- | ------------- |
| CNN + Data Augmentation       | 81.8%         |
| MobileNetV2 Transfer Learning | 87.7%         |

MobileNetV2 achieved the highest accuracy and outperformed the custom CNN model.

---

## Generated Outputs

* CNN Accuracy and Loss Curves
* CNN Confusion Matrix
* CNN ROC Curve
* MobileNetV2 Accuracy and Loss Curves
* MobileNetV2 Confusion Matrix
* MobileNetV2 ROC Curve
* Classification Reports
* Model Comparison Table
* Error Analysis

---

## Repository Contents

```text
Scene_Classification_CNN_MobileNetV2.ipynb
Phase2_Proposal_Scene_Classification_CNN_MobileNetV2.pdf
README.md

cnn_accuracy_loss_curve.pdf
cnn_confusion_matrix.pdf
cnn_roc_curve.pdf

mobilenetv2_accuracy_loss_curve.pdf
mobilenetv2_confusion_matrix.pdf
mobilenetv2_roc_curve.pdf

classification_report.txt
mobilenetv2_classification_report.txt

model_comparison_table.pdf
error_analysis.pdf
```

## How to Run

1. Download the Intel Image Classification Dataset.
2. Open the notebook in Kaggle or Jupyter Notebook.
3. Install required libraries:

   * TensorFlow
   * NumPy
   * Pandas
   * Matplotlib
   * Seaborn
   * Scikit-learn
4. Run all notebook cells sequentially.
5. Generated figures and reports will be saved automatically.

---

## Conclusion

This project demonstrates the effectiveness of Deep Learning for scene classification. While the custom CNN achieved strong performance, MobileNetV2 Transfer Learning provided higher accuracy and better generalization, making it the best-performing model in this study.
