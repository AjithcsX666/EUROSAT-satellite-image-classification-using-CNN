🛰️ EuroSAT Satellite Image Classification Using CNN

📌 Project Overview

This project uses Deep Learning and Convolutional Neural Networks (CNN) to classify satellite images into 10 different land-use and land-cover categories using the EuroSAT dataset.

The model analyses satellite images and predicts the corresponding geographical category.

🎯 Project Objectives

- Classify satellite images into 10 land-cover categories.
- Build a CNN-based image classification model.
- Apply image preprocessing and data augmentation.
- Evaluate model performance using classification metrics.
- Predict classes for custom satellite images.

📂 Dataset

Dataset: EuroSAT

The dataset contains satellite images belonging to 10 classes:

1. AnnualCrop
2. Forest
3. HerbaceousVegetation
4. Highway
5. Industrial
6. Pasture
7. PermanentCrop
8. Residential
9. River
10. SeaLake

🛠️ Technologies and Libraries

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Pillow

🧠 Model Architecture

A Convolutional Neural Network (CNN) is used for image classification.

The model includes:

- Image resizing and rescaling
- Data augmentation
- Convolutional layers
- Batch Normalization
- Max Pooling
- Global Average Pooling
- Dense layers
- Dropout
- Softmax output layer

⚙️ Installation

Install the required libraries:

pip install tensorflow matplotlib scikit-learn pillow numpy seaborn

🚀 How to Run the Project

1. Download or clone this repository.
2. Extract the EuroSAT dataset into the project directory.
3. Install the required libraries.
4. Open "EuroSAT.ipynb" using Jupyter Notebook.
5. Run the notebook cells in order.
6. Train and evaluate the CNN model.
7. Upload a satellite image to test the prediction functionality.

📊 Model Evaluation

The model is evaluated using:

- Test Accuracy
- Test Loss
- Classification Report
- Precision
- Recall
- F1-Score
- Confusion Matrix

🔮 Future Improvements

- Improve model accuracy through hyperparameter tuning.
- Experiment with transfer learning models such as MobileNetV2 and ResNet50.
- Build a simple web application for image prediction.
- Improve classification performance on custom satellite images.

👨‍💻 Author

Ajith

Deep Learning | Python | Machine Learning

📜 License

This project is intended for educational and learning purposes.
