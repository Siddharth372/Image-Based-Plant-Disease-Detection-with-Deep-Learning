# 🌿 Image-Based-Plant-Disease-Detection-with-Deep-Learning

This project uses Convolutional Neural Networks (CNNs) to detect and classify plant diseases from leaf images. The model is trained on a dataset comprising labeled images of common crop diseases affecting Apple, Corn, and Tomato plants.

## 🧠 Overview

The goal is to automate the process of plant disease detection to support farmers and agronomists in early diagnosis and treatment, ultimately improving crop yield and quality.

## 🗂️ Dataset

The dataset consists of image folders for training and testing, organized by class labels:

- **Apple**
  - Apple Scab
  - Black Rot
  - Cedar Apple Rust
  - Healthy
- **Corn (Maize)**
  - Cercospora Leaf Spot (Gray Leaf Spot)
  - Common Rust
  - Northern Leaf Blight
  - Healthy
- **Tomato**
  - Bacterial Spot
  - Early Blight
  - Late Blight
  - Leaf Mold
  - Septoria Leaf Spot
  - Tomato Mosaic Virus
  - Healthy

## 🛠️ Features

- Image classification using CNNs
- Custom data loading from local directories
- Confusion matrix for model evaluation
- Visualization using Seaborn and Matplotlib
- Integrated with OpenCV for preprocessing

📁 Project Structure

plant-disease-classification/
├── main.ipynb
├── train/
├── test/
├── requirements.txt
└── README.md


## 📦 Libraries Used

- TensorFlow
- NumPy
- OpenCV
- scikit-learn
- Seaborn
- Matplotlib
- tqdm

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/plant-disease-classification.git
   cd plant-disease-classification
2. Install dependencies
   pip install -r requirements.txt
3. Prepare the dataset
   Ensure your dataset is structured like this:

   final-Medicinal/
   ├── train/
   │   ├── Apple___Black_rot/
   │   ├── Corn_(maize)___Common_rust_/
   │   └── ...
   └── test/
       ├── Tomato___Early_blight/
       └── ...

   Update the paths in load_data() if needed.
4. Run the notebook
   jupyter notebook main.ipynb
