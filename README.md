# Tea-Leaves-Disease-prediction
This project aims to assist tea farmers and agricultural professionals by detecting diseases in tea leaves using convolutional neural network
(CNN) and transfer learning techniques. The solution provides precise disease identification and a user-friendly interface for uploading leaf 
images to receive predictions.

# Project Overview
Tea leaf diseases can cause significant losses in the agriculture sector. Early and accurate detection is crucial for mitigating these effects. This project:

Utilizes a CNN architecture along with transfer learning for effective classification.
Includes a Flask-based web interface for easy usage.
Supports multiple tea leaf disease categories and provides actionable insights.

# Features
Disease Classification: Identifies specific diseases affecting tea leaves.
Transfer Learning: Leverages pre-trained models like ResNet, VGG, or Inception for enhanced accuracy.
User Interface: Flask-based application to upload images and view predictions.
Customizable: Easily extendable to include new diseases or improve model performance.
# Technologies Used
Programming Language: Python
Deep Learning Framework: TensorFlow/Keras or PyTorch
Web Framework: Flask
Pre-trained Models: ResNet, VGG, Inception (Transfer Learning)
Visualization: Matplotlib, Seaborn
Database: SQLite or MongoDB (Optional, for storing predictions)

# Setup and Installation
## Prerequisites
Python 3.8+
Virtual Environment Tool (e.g., venv or conda)
# Steps
1. Clone this repository:

git clone https://github.com/your-username/tea-leaf-disease-detection.git
cd tea-leaf-disease-detection
2. Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies:

pip install -r requirements.txt
4. Run the application:

python app.py

# Usage
Open the web application in your browser (http://127.0.0.1:5000).
Upload an image of a tea leaf using the interface.
View the disease prediction and confidence score.

# Model Training
The model was trained using:

Dataset: Collected from public and custom datasets of tea leaf images.
Augmentation: Data augmentation techniques like rotation, flipping, and scaling.
Transfer Learning: Fine-tuned pre-trained models for improved accuracy.
To retrain the model:

Place your dataset in the data/ directory.
1. Run the training script:

python train.py

# Results
Accuracy: Achieved an accuracy of 94% on the validation dataset.
Loss: Reduced validation loss using transfer learning techniques.
Deployment: Successfully deployed a lightweight model for inference via Flask.


