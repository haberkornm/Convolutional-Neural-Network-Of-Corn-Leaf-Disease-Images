# Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images
Project developing a CNN for the classification of corn and maize leaf disease images.  Image dataset is composed of healthy, gray leaf spot, common rust, and blight leaf images.

## Summary
A Convolutional Neural Network (CNN) for four categories of corn leaf disease images was developed in this project.  Image categories of the corn leaf images were healthy, gray leaf spot, common rust, and blight.  These images were processed in Python to produce binary, grayscale, green filtered, brown filtered, Sobel edges, and Canny edges.  The brown and green filters were uniquely developed for this project.  Original RGB images, along with the six processed images were concatenated and utilized in the development of a CNN model.  Multiple models were produced, with the most basic CNN processing only RGB images and resulting in 85.3% accuracy.  Utilizing the concatenated processed images in a similar CNN model increased accuracy to 95.9%.  The best preforming model utilized the original RGB images concatenated with the six processed images.  This model used VGG16 transfer learning and resulted in 97.6% accuracy.  

## Table of Contents
  1. Original images can be found at [Kaggle: Corn or Maize Leaf Disease Dataset](https://www.kaggle.com/smaranjitghose/corn-or-maize-leaf-disease-dataset)
  2. 
