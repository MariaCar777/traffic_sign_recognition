# Traffic Sign Recognition 🚦

A deep learning project that classifies traffic signs to support the development of safer autonomous vehicles.

## Overview
Road traffic accidents cause over 38,000 deaths annually in the U.S. This project addresses that problem by training a Convolutional Neural Network (CNN) to accurately identify 43 categories of traffic signs in real time, a critical capability for autonomous vehicle systems.

## Dataset
- **Source:** [GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) via Kaggle
- 43 traffic sign classes
- Thousands of labeled images split 80:20 for training and testing

## Tools & Technologies
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- OpenCV (cv2)
- Matplotlib
- Jupyter Notebook / Google Colab

## Model Architecture
- 2 Convolutional layers (Conv2D) for spatial feature extraction
- MaxPooling layers for downsampling
- Dropout layers to prevent overfitting
- Fully connected Dense layer (256 units)
- Output layer with Softmax activation (43 classes)
- Optimizer: Adam | Loss: Categorical Crossentropy

## Results
| Metric | Score |
|--------|-------|
| Test Accuracy | **94.07%** |
| Epochs | 15 |
| Batch Size | 32 |

## AI Ethics Considerations
This project incorporates ethical AI principles including:
- **Safety:** Reliable predictions to prevent accidents
- **Fairness:** Diverse training data across sign types and environments
- **Transparency:** Explainable model decisions for real-world trust
- **Privacy:** No personal data collected or used

## Project Structure
```
traffic_sign_recognition/
├── traffic_sign_recognition.ipynb   # Main notebook
├── Train.csv                        # Training data labels
├── Test.csv                         # Test data labels
└── Meta.csv                         # Sign class metadata
```

## Author
Maria Carmona | Miami Dade College | AS Applied Artificial Intelligence
