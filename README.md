Traffic Sign Recognition using CNN

Overview:
This project implements a Traffic Sign Recognition system using a Convolutional Neural Network (CNN) trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.
The model automatically classifies traffic sign images into 43 categories and can be applied in Intelligent Transportation Systems (ITS) and Autonomous Driving applications.

Objectives:
Perform preprocessing on traffic sign images
Design and train a CNN for multi-class classification
Evaluate model performance on training, validation, and test datasets
Visualize model accuracy, loss, and predictions

Dataset:
Dataset used is the German Traffic Sign Recognition Benchmark (GTSRB)
Classes are 43 traffic sign categories
Images captured under varying lighting and environmental conditions

Model Architecture:
The CNN model includes:
Multiple Convolutional layers (feature extraction)
ReLU activation functions
Max Pooling layers
Fully connected (Dense) layers
Softmax output layer for multi-class classification

Model Performance:
Dataset	Accuracy
Training	~99%
Validation	~95%
Testing	~96%

Observations:
High training accuracy indicates strong feature learning.
Validation and testing accuracy demonstrate good generalization.
Slight gap between training and validation suggests minimal overfitting.

Technologies Used:
Core: Python, TensorFlow, Keras
Data Science: NumPy, Pandas
Computer Vision: OpenCV
Visualization: Matplotlib, Seaborn

How to Run:
Open the notebook in Google Colab
Upload your Kaggle API key (if dataset download is required)
Run all cells sequentially
View training results and evaluation metrics

Security Note
Kaggle API credentials are not included in this repository for security reasons. Users must upload their own kaggle.json file when running the notebook.
