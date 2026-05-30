# PRODIGY_ML_03
# 🐱🐶 Cats vs Dogs Image Classification using Support Vector Machine (SVM)

## 📌 Overview

This project implements a Support Vector Machine (SVM) model to classify images of Cats and Dogs. The model is trained using image data from the Microsoft PetImages dataset and predicts whether a given image belongs to a cat or a dog.

The project demonstrates the complete machine learning workflow, including image preprocessing, feature extraction, model training, evaluation, and prediction.

This project was developed as part of my Machine Learning Internship at Prodigy InfoTech.

---

## 🚀 Features

- Image Classification using Support Vector Machine (SVM)
- Image Preprocessing with OpenCV
- Image Resizing and Feature Extraction
- Training and Testing Pipeline
- Accuracy Evaluation
- Classification Report Generation
- Custom Image Prediction
- Visualization using Matplotlib

---

## 📂 Dataset

**Dataset:** Microsoft PetImages Dataset

**Official Dataset Source:**  
https://www.microsoft.com/en-us/download/details.aspx?id=54765

The dataset contains thousands of cat and dog images organized into separate folders:

```text
PetImages/
│
├── Cat/
│   ├── 0.jpg
│   ├── 1.jpg
│   └── ...
│
└── Dog/
    ├── 0.jpg
    ├── 1.jpg
    └── ...
```

### Dataset Information

- Total Categories: 2
  - Cat 🐱
  - Dog 🐶
- Image Format: JPG
- Real-world image dataset
- Suitable for image classification and computer vision tasks

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 🧠 Machine Learning Algorithm

### Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification tasks.

SVM works by finding the optimal hyperplane that separates different classes while maximizing the margin between them.

### Key Concepts

- Supervised Learning
- Classification
- Hyperplane
- Support Vectors
- Margin Maximization

---


## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/vijay-614/Cats-vs-Dogs.git
cd cats-vs-dogs-svm-classifier
```

### Install Required Libraries

```bash
pip install numpy matplotlib scikit-learn opencv-python
```

---

## ▶️ Running the Project

Run the Python file:

```bash
python Cat_vs_Dog_.ipynb
```

---

## 🔄 Workflow

### Step 1: Load Images

Images are loaded from:

```text
PetImages/Cat
PetImages/Dog
```

### Step 2: Image Preprocessing

- Read image using OpenCV
- Resize image to 64×64 pixels
- Flatten image into a feature vector

### Step 3: Data Preparation

- Assign label 0 for Cats
- Assign label 1 for Dogs
- Convert data into NumPy arrays

### Step 4: Train-Test Split

Dataset is divided into:

- 80% Training Data
- 20% Testing Data

### Step 5: Train SVM Model

A linear SVM classifier is trained using:

```python
model = SVC(kernel='linear')
```

### Step 6: Model Evaluation

Performance is measured using:

- Accuracy Score
- Precision
- Recall
- F1-Score

### Step 7: Custom Image Prediction

Users can provide an image path and the model predicts:

- Cat 🐱
- Dog 🐶

---

## 📊 Sample Output

### Model Accuracy

```text
Model Accuracy:
89.50%
```

*Accuracy may vary depending on the number of images used.*

### Classification Report

```text
precision    recall    f1-score
```

Generated automatically after training.

---

## 🧪 Testing Custom Images

Example:

```text
Enter image path to test:
PetImages/Cat/150.jpg
```

Output:

```text
Prediction: Cat 🐱
```

or

```text
Prediction: Dog 🐶
```

---

## 📷 Results

The model successfully classifies images of cats and dogs using SVM and basic image preprocessing techniques.

The project demonstrates:

- Image Processing
- Feature Extraction
- Machine Learning Classification
- Model Evaluation

---

## 💡 Future Improvements

- Use CNN (Convolutional Neural Networks)
- Implement Deep Learning Models
- Add Streamlit Web Interface
- Real-Time Webcam Classification
- Improve Accuracy with Feature Engineering
- Deploy Model on Cloud Platforms

---

## 📚 Learning Outcomes

Through this project, I learned:

- Computer Vision Fundamentals
- Image Preprocessing
- Support Vector Machines
- Data Preparation Techniques
- Model Evaluation Metrics
- Practical Machine Learning Workflow

---

## 🙌 Acknowledgements

- Microsoft PetImages Dataset
- Scikit-learn Documentation
- OpenCV Documentation
- Prodigy InfoTech Internship Program

---

## 👨‍💻 Author

**Vijay Tamminaina**

Machine Learning Intern | AI & ML Enthusiast

GitHub: https://github.com/vijay-614

---

⭐ If you found this project useful, consider giving it a Star on GitHub! 🚀🐱🐶
