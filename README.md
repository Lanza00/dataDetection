# 🍎 Fruit Ripeness Classifier (Ripe vs Not Ripe)

This project is a deep learning application that classifies whether a fruit is **ripe (Masak)** or **not ripe (Belum Masak)** using a Convolutional Neural Network (CNN) model built with TensorFlow and Keras. It includes image preprocessing, model training, and prediction with visual feedback using OpenCV.

---

## 📁 Dataset Structure

This project uses a dataset of oil palm fruit ripeness from Kaggle:

🔗 [Ripeness of Oil Palm Fruit Dataset (by ramadanizikri112)](https://www.kaggle.com/datasets/ramadanizikri112/ripeness-of-oil-palm-fruit?select=Belum+Masak)

Download the dataset and extract it into the `projectDataset/` folder with the following structure:


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
git clone https://github.com/Lanza00/dataDetection.git
```
2. Add your dataset in the projectDataset folder (with masak/ and belum_masak/ subfolders).
3. Run the script:
```bash
python main.py

```
4. After training, test the model by changing the image file path in:
```bash
file_path = "test.jpg"  # Replace with your image file

```
5. The script will display the image with a prediction label and bounding box using OpenCV.

📊 Output Examples
Training Accuracy Plot:
A graph showing training and validation accuracy over epochs.

Prediction Result:
The script will:

- Resize and normalize the image
- Predict using the CNN model
- Draw a colored box and label on the fruit image:
  - 🟩 Green box: Ripe
  - 🟨 Yellow box: Not Ripe


🧪 Future Enhancements
- Add object detection using YOLO or SSD for bounding ripe fruit automatically
- Expand dataset for better accuracy
- Deploy model with a web interface using Streamlit or Flask

🧑‍💻 Author
Developed by [Aznal Anas] | Ai Tools



---

Let me know if you want me to generate this file for download or include a badge (like TensorFlow version, license, etc.)!


