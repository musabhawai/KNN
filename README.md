# K-Nearest Neighbors (KNN) – Classification Examples

## 📌 Overview
This repository contains examples of the *K-Nearest Neighbors (KNN)* algorithm applied to real-world datasets:
1. *Ads Purchase Prediction* – Classifies whether a person will purchase an ad based on features like age and salary.
2. *Flower Species Prediction* – Identifies the species of a flower from the Iris dataset, evaluated with a confusion matrix.

## 📖 About KNN
KNN is a *non-parametric, instance-based learning* algorithm used for both classification and regression.  
- For classification, it predicts the label based on the *majority vote* of its nearest neighbors in the feature space.
- The performance depends heavily on the choice of *K* and the *distance metric*.

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Ads Purchase Prediction
- Uses KNN to classify users into “Purchased” or “Not Purchased.”
- Features: Age, Estimated Salary.
- Scaled features for better distance calculations.

### 2️⃣ Flower Species Prediction
- Classifies Iris dataset flowers into Setosa, Versicolor, or Virginica.
- Evaluation done using a *confusion matrix* for accuracy and error analysis.
