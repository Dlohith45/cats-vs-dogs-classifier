# 🐱🐶 Cats vs Dogs Classification using CNN

This project is a deep learning model that classifies images as **Cats or Dogs** using a Convolutional Neural Network (CNN).

---

## Features

* Image classification using CNN
* TensorFlow & Keras implementation
* Automatic dataset loading using TFDS
* Visualization of predictions

---

## Model Architecture

* Conv2D (32 filters)
* MaxPooling
* Conv2D (64 filters)
* MaxPooling
* Conv2D (128 filters)
* MaxPooling
* Dense layers
* Sigmoid output (Binary classification)

---

## Dataset

* Source: TensorFlow Datasets
* Classes: Cat  / Dog 
* Total Images: ~25,000

---

## Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/cats-vs-dogs-classifier.git
cd cats-vs-dogs-classifier
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

* Open `notebooks/cats_dogs.ipynb` in Jupyter or Colab

---

##  Output

The model predicts images and displays:

* True label
* Predicted label
* Correct predictions in green ✅
* Incorrect predictions in red ❌

---

##  Results

* Achieved good validation accuracy with a simple CNN model.

---

##  Future Improvements

* Use Transfer Learning (ResNet, VGG16)
* Increase epochs for better accuracy
* Deploy as a web app

---

## Author

Lohith Chandra
