# 🐶 Dog Breed Identification Using Pre-trained CNNs
## 🧠 Project Overview
This project is part of the AI Programming with Python Nanodegree from Udacity. It focuses on building an image classification system that can identify dog breeds from pet images using pre-trained Convolutional Neural Networks (CNNs). The system also detects whether an image contains a dog or a human, and if it's a human, it predicts the dog breed they most resemble.

## 🎯 Objectives
- Detect whether an image contains a dog or a human.
- Classify the breed of the dog in the image.
- Evaluate and compare the performance of different CNN architectures (ResNet, AlexNet, VGG).
  
## 🛠️ Technologies Used
- Python 3
- PyTorch
- Pre-trained CNN models: VGG16, ResNet, AlexNet
- OpenCV: for human face detection
- NumPy, argparse: for data handling and CLI support
  
## 📁 Project Structure
Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds/
│
├── pet_images/                      # Dataset of pet images
├── uploaded_images/                 # Images for testing
├── check_images.py                  # Main script for classification
├── classifier.py                    # Loads and applies pre-trained models
├── get_input_args.py                # Parses command-line arguments
├── get_pet_labels.py                # Extracts labels from filenames
├── classify_images.py               # Performs classification
├── adjust_results4_isadog.py        # Flags whether labels are dogs
├── calculates_results_stats.py      # Computes classification statistics
├── print_results.py                 # Displays results summary
├── dognames.txt                     # List of valid dog breed names
└── README.md                        # This file

## ⚙️ Workflow Summary
- Label Extraction
- Extracts pet labels from image filenames.
- Model Selection
- Loads a pre-trained CNN (VGG, ResNet, or AlexNet).
- Classification
- Classifies each image and compares predictions to actual labels.
- Dog Detection
- Determines whether the image contains a dog or not.
- Results Evaluation
- Computes accuracy metrics and highlights misclassifications.
  
## 📈 Key Results
- The VGG16 model achieved the highest accuracy in both dog detection and breed classification.
- The system successfully distinguishes between dog and non-dog images and provides breed predictions with high reliability.


