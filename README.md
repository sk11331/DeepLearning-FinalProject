# Real-Time Face Verification Using Siamese Neural Networks
This repository contains the source code for a real-time face verification system implemented using Siamese neural networks. The system is capable of accurately verifying whether a given face matches a reference face in a database.

## Table of Contents
Introduction
Problem Description
Model Architecture
Training
Evaluation
Results
Usage
Contributing
License

## Introduction
In the digital age, the need for robust and reliable face verification systems has become increasingly important. Face verification systems find applications in various domains such as security access control, identity verification, and personalized user experiences. This project aims to develop a real-time face verification system capable of accurately verifying faces in real-world scenarios.

## Problem Description
The primary goal of this project is to develop a face verification system capable of operating in real-time. The system should accurately verify whether a given face matches a reference face in a database. Challenges include handling variations in lighting conditions, facial expressions, and poses, while ensuring high accuracy and efficiency.

## Model Architecture
Our face verification system utilizes a Siamese neural network architecture. The network consists of twin embedding networks that share weights, followed by a distance layer to compute the L1 distance between embeddings. The model is trained using binary cross-entropy loss.

## Training
The model is trained on a dataset consisting of anchor, positive, and negative face images. Data augmentation techniques are applied to increase the diversity of training samples. The model is trained using the Adam optimizer with a learning rate of 1e-4 for 50 epochs.

## Evaluation
The performance of the face verification system is evaluated using precision, recall, and accuracy metrics on a separate test dataset.

## Results
The results of the evaluation demonstrate the effectiveness of the face verification system, achieving high precision, recall, and accuracy.

## Usage
To use the face verification system, follow these steps:

Clone the repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt.
Run the face_verification.py script to launch the real-time face verification system.
Contributing
Contributions to the project are welcome! Feel free to fork the repository and submit pull requests with your enhancements or bug fixes.

# References
[1] "Labeled Faces in the Wild," University of Massachusetts, Amherst. Available: https://vis-www.cs.umass.edu/lfw/.

[2] Hamdani, Nesrine & Bousahba, Nassima & Bousbai, Ahmed & Braikia, Amina. (2023). Face Detection and Recognition using Siamese Neural Network.


# Team Members
1). Shanmukeshwar Reddy Kanjula(sk11331) 2). Nathaniel Sehati(nys2021)
