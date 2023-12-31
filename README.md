# Vehicle Number Plate Recognition

In this assignment, I together with my groupmate have implemented a Car Number Plate Recognition System for Punjab/Pakistan using ANN based solution. This was a group assignment. My group members was Sana Farooq, another Data Science Major.

# Overview
This project implements a Car Number Plate Recognition System (ANPR) using Artificial Neural Networks (ANN) in Python with OpenCV. Recognizing car number plates in Punjab, Pakistan involves various complexities, including image processing, character recognition, and neural network training.

# Project Highlights
Data Collection: Curated a diverse dataset of car number plate images from Punjab, Pakistan, encompassing different fonts, styles, and environmental conditions.

Image Preprocessing: Enhanced image quality and reduced noise through resizing, cropping, grayscale conversion, and noise reduction filters using OpenCV.

Character Segmentation: Utilized edge and contour detection techniques to isolate individual characters on number plates.

Character Recognition: Trained an ANN for character recognition using TensorFlow or PyTorch, requiring labeled data for neural network training.

Text Recognition: Grouped recognized characters to form complete number plates using regular expressions or Tesseract OCR.

Testing and Evaluation: Conducted thorough testing to evaluate system accuracy, precision, and recall using test datasets, refining the model for enhanced performance.

Deployment: Integrated the ANPR system into specific applications or environments, potentially creating a user interface and connecting to cameras or video streams.

# Tools and Libraries
Image Preprocessing: OpenCV for image manipulation and preprocessing tasks.

Character Recognition: Utilized deep learning frameworks such as TensorFlow or PyTorch, commonly implementing Convolutional Neural Networks (CNNs) for character recognition.

Text Recognition and Grouping: Employed regular expressions or Tesseract OCR for text recognition and grouping purposes.

# Considerations
Building an effective ANPR system demands significant resources in terms of data, computational power, and expertise in computer vision and machine learning. For those less experienced, exploring pre-built solutions or collaborating with experts could be more practical. Ensure compliance with legal and ethical considerations when implementing an ANPR system.

