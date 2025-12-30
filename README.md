# 🧠 Image Classification using CNN (MNIST Dataset)

## 📌 Project Overview
This project implements a **Deep Learning-based Image Classification system** using a **Convolutional Neural Network (CNN)**.  
The model is trained on the **MNIST dataset**, which contains images of handwritten digits (0–9), and is built using **TensorFlow (Keras)**.

The goal of this project is to understand how deep learning models learn visual patterns from images and how their performance can be evaluated using visualizations.

---

## 🎯 Aim of the Project
To build a functional **CNN model** that can accurately classify handwritten digit images and demonstrate its performance using:
- Accuracy and loss graphs
- Predictions on unseen test images

---

## 📂 Dataset Used
**MNIST Dataset**
- 70,000 grayscale images of handwritten digits
- Image size: **28 × 28 pixels**
- Classes: **0 to 9**
- Split:
  - 60,000 training images
  - 10,000 testing images

The dataset is directly loaded using TensorFlow, so no manual download is required.

---

## 🧠 Model Used
**Convolutional Neural Network (CNN)**

### Architecture Highlights:
- Convolutional layers for feature extraction
- Max pooling layers for dimensionality reduction
- Fully connected (Dense) layers for classification
- Softmax output layer for multi-class prediction

The model is trained using the **Adam optimizer** and evaluated using **accuracy**.

---

## ⚙️ Technologies & Libraries
- Python
- TensorFlow (Keras)
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🧪 Project Workflow
1. Import required libraries  
2. Load the MNIST dataset  
3. Visualize sample digit images  
4. Normalize and preprocess image data  
5. Reshape data for CNN input  
6. Build and compile the CNN model  
7. Train the model with validation data  
8. Visualize training and validation accuracy and loss  
9. Evaluate the model on test data  
10. Predict and display results on random test images  

---

## 📊 Results & Visualizations
- **Accuracy vs Epoch graph**
- **Loss vs Epoch graph**
- **Actual vs Predicted digit visualization**

These visualizations help analyze model learning and performance.

---

## ✅ Final Outcome
- Successfully trained a CNN model for digit classification
- Achieved high accuracy on unseen test data
- Demonstrated results through clear visualizations

---

## 🚀 Future Scope
- Extend the model to real-time digit recognition using a camera
- Improve accuracy using deeper CNN architectures
- Apply the same approach to other image classification datasets

---

## 📌 How to Run the Project
1. Open the Jupyter Notebook
2. Run all cells sequentially
3. Observe training progress, graphs, and predictions

---

## 👨‍💻 Author
**Parth Makwana**  
B.Tech Computer Science (Data Science Internship Project)

---

## 📄 License
This project is licensed under the **MIT License**.
