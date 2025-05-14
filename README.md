# 🍎 Fruit Ripeness Classifier (Ripe vs Not Ripe)

This project is a deep learning application that classifies whether a fruit is **ripe (Masak)** or **not ripe (Belum Masak)** using a Convolutional Neural Network (CNN) model built with TensorFlow and Keras. It includes image preprocessing, model training, and prediction with visual feedback using OpenCV.

---

## 📁 Dataset Structure

The dataset should be organized as follows inside the `projectDataset` folder:

projectDataset/
├── masak/ # Folder with images of ripe fruit
└── belum_masak/ # Folder with images of unripe fruit


---

## 🧠 Model Architecture

- 2 Convolutional layers with ReLU activation
- 2 MaxPooling layers
- 1 Dense hidden layer
- Dropout for regularization
- Sigmoid output layer for binary classification

---

## 🔧 Installation & Requirements

Install the required Python packages:

```bash
pip install numpy opencv-python matplotlib scikit-learn tensorflow
```
Ensure your Python version is compatible (recommended: Python 3.8+).

🚀 How to Run
1. Clone this repository:
```bash
git clone [git@github.com:Lanza00/dataDetection.git](https://github.com/Lanza00/dataDetection.git)
```
2. Add your dataset in the projectDataset folder (with masak/ and belum_masak/ subfolders).
3. Run the script:
```bash
python main.py

```
4. After training, test the model by changing the image file path in:

5. 

