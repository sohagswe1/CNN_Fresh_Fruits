🍎 **CNN Fruit Image Classification (PyTorch)**
📌 **Project Overview**

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify 10 types of fruits.
The model is trained on a standard image dataset and tested on real-world custom images captured using a mobile phone, fulfilling all requirements of the CNN Image Classification Assignment.

🔍 Fruit Classes

Apple

Avocado

Banana

Cherry

Kiwi

Mango

Orange

Pineapple

Strawberry

Watermelon

🧠 Technologies Used

Python

PyTorch

Torchvision

Matplotlib & Seaborn

Google Colab

GitHub

📂 **Project Structure**
<img width="471" height="627" alt="image" src="https://github.com/user-attachments/assets/f5cf371b-6e38-4de6-b076-4d0f23bf6157" />

Input: RGB Image (64 × 64)

Convolution Layers:

Conv2D (32 filters)

Conv2D (64 filters)

MaxPooling

Fully Connected Layers:

Dense (128 units)

Output Layer (10 classes)

Activation: ReLU

Loss Function: CrossEntropyLoss

Optimizer: Adam


🔄 **Data Preprocessing**

Resize images to 64 × 64

Convert images to Tensor

Dataset loaded automatically using ImageFolder

DataLoader used for batch processing

🚀 Training Details

Epochs: 10

Batch Size: 32

Device: CPU (stable & error-free)

📈 Training Performance

Training Loss vs Epoch plot

Training Accuracy vs Epoch plot
📊 Evaluation & Analysis
✅ Confusion Matrix

A confusion matrix is generated on the test dataset to visualize classification performance for each fruit class.

❌ Visual Error Analysis

Misclassified test images are displayed in a single row, showing:

True Label

Predicted Label

This helps analyze where the CNN makes mistakes.

Custom Image Prediction (Real-World Testing)

Custom fruit images were captured using a smartphone and stored in the Custom/ folder.
The trained model predicts:

Fruit class

Confidence percentage
How to Run the Project

**Open Google Colab**

Clone the repository:

git clone https://github.com/sohagswe1/CNN_Fresh_Fruits.git


Open CNN_*Fresh_Fruits.ipynb

Click Runtime → Run all

The notebook will:

Load dataset

Train the CNN

Save the model

Predict custom images

Display plots & analysis

🎓 **Assignment Compliance**

✔ CNN built using PyTorch
✔ Automatic dataset loading
✔ Model saved in .pth format
✔ Custom real-world images used
✔ Confusion matrix & plots included
✔ Visual error analysis provided
✔ Fully reproducible via GitHub

👤 **Author**

Samsur Rahman Sohag
Department of Computer Science & Engineering (CSE),
Jashore University of Science and Technology

⭐ **Final Note**

This project demonstrates a complete CNN workflow, from dataset preparation to real-world testing, making it suitable for academic submission, viva, and future deep learning projects.
