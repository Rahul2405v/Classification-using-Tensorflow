Image Classification project (Cats vs Dogs)
# Cat vs Dog Image Classification

## Overview
This project implements a Cat vs Dog image classifier using Transfer Learning with TensorFlow and Keras. 
A pretrained CNN is fine-tuned using the Functional API for improved accuracy.

## Dataset
- Source: Kaggle (downloaded via KaggleHub)
- Classes: Cats, Dogs
- Images resized and normalized before training

## Model Architecture
- Pretrained CNN backbone
- Global Average Pooling
- Fully connected layers
- Softmax output layer

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- KaggleHub

## Training
- Loss: Categorical Crossentropy
- Optimizer: Adam
- Batch size: 32
- Epochs: 5

## Results
Achieved good classification accuracy using transfer learning.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/cat_dog_classification.ipynb
