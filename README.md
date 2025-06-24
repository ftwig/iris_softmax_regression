# 🌸 Iris Flower Classification - Softmax Regression from Scratch

This project demonstrates how to build a **multiclass classifier** for the famous Iris dataset using **softmax regression (multinomial logistic regression)** implemented **entirely from scratch** using **NumPy** and **Pandas**.

---

## Features

- Classifies flowers into: *Setosa*, *Versicolor*, *Virginica*
- Implements Softmax Regression (multiclass logistic regression) manually
- Visualizes data using Matplotlib and Seaborn
- Achieves ~96.6% accuracy
- Trains using gradient descent
- Includes complete data preprocessing, one-hot encoding, and normalization

---

## Dataset

The [Iris dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset) contains:
- 150 samples (50 per class)
- 4 features per flower:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (only for accuracy metric)

---

## 📈 Accuracy

- Training Accuracy: **96.6%**

---

## 📷 Visualization

Scatter plot of first two features colored by species:

![Scatter Plot]!
[image](https://github.com/user-attachments/assets/ce14076a-2372-4e02-ac18-4c0b8ec15ffe)

---

## 🧪 Usage

```bash
# Clone this repo
git clone https://github.com/your-username/iris-softmax

# Change directory
cd iris-softmax

# Run the script
python iris_softmax.py
