# 🖋️ MNIST Digit Classification (Keras + CNN)

This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits (0–9) from the **MNIST dataset**.  
The model is built using **TensorFlow/Keras** and achieves high accuracy on the test set.  

---

## 📂 Project Structure
├── MNIST_Digit_Recognition.ipynb # Main Jupyter Notebook
├── README.md # Project documentation

## ⚙️ Requirements
Make sure you have the following installed:

- Python 3.8+
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies with:
pip install tensorflow numpy matplotlib jupyter

## How to Run
Open the notebook
Run all cells step by step:
Step 1: Import libraries
Step 2: Load dataset
Step 3: Preprocess & normalize data
Step 4: Build CNN model
Step 5: Train the model
Step 6: Evaluate on test data
Step 7: Save/Load model (optional)
Step 8: Final predictions

## Model Architecture
Input: 28 x 28 x 1 grayscale image
Conv2D → ReLU → MaxPooling
Flatten → Dense(128, ReLU)
Dense(10, Softmax)

## Results
Accuracy on test set: ~98%
The model successfully classifies handwritten digits with high accuracy.
