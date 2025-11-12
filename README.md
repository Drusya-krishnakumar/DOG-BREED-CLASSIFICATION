# Dog Breed Classification using Deep Learning

## 1. Project Overview
This project focuses on building a deep learning model that can classify images of dogs into different breeds.  
The model uses transfer learning based on **MobileNetV2**, a pre-trained convolutional neural network trained on the ImageNet dataset.  
The dataset for this project was downloaded from **Kaggle** and contains labeled images of dog breeds for training and testing.

---

## 2. Project Objectives
- Develop a convolutional neural network capable of classifying dog breeds accurately.
- Apply transfer learning using MobileNetV2 to improve performance with limited data.
- Implement image preprocessing and augmentation techniques for better generalization.
- Build a simple GUI for breed prediction using the trained model.

---

## 3. Dataset Description
- **Source:** Kaggle Dog Breed Identification Dataset  
- **Contents:**
  - `train/` : Folder containing labeled dog images used for training and validation.
  - `test/` : Folder containing unlabeled dog images for prediction.
  - `labels.csv` : Contains image IDs and their corresponding dog breed labels.
- **Number of Classes:** 120 dog breeds.
- **Image Format:** JPEG (`.jpg`)
- **Image Size:** Resized to 224x224 pixels for input to MobileNetV2.

---

## 4. Project Files
| File Name | Description |
|------------|-------------|
| `dog_breed_classification.ipynb` | Main Jupyter notebook containing model building, training, and evaluation code. |
| `dog_breed_gui.ipynb` | GUI notebook for predicting dog breeds using the trained model. |
| `labels.csv` | CSV file containing image IDs and their corresponding labels. |
| `class_indices.json` | JSON file storing mapping between class indices and breed names. |
| `dog_breed_classifier_120.h5` | Saved model file containing trained weights. |
| `dog_breed_predictions.csv` | Output CSV file with test image IDs and predicted breeds. |
| `train/`, `test/` | Image folders for training and testing respectively. |

---

## 5. Libraries and Dependencies
Make sure the following libraries are installed before running the notebooks:

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn
