# Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images
Project developing a CNN for the classification of corn and maize leaf disease images.  Image dataset is composed of healthy, gray leaf spot, common rust, and blight leaf images.

## Summary
A Convolutional Neural Network (CNN) for four categories of corn leaf disease images was developed in this project.  Image categories of the corn leaves were healthy, gray leaf spot, common rust, and blight.  These images were processed in Python to produce binary, grayscale, green filtered, brown filtered, Sobel edges, and Canny edges.  Brown and green filters were uniquely developed for this project.  Original RGB images, along with the six processed images were concatenated and utilized in the development of a CNN model.  Multiple models were produced, with the most basic CNN processing only RGB images and resulting in 85.3% accuracy.  Utilizing the concatenated processed images in a similar CNN model increased accuracy to 95.9%.  The best preforming model utilized the original RGB images concatenated with the six processed images.  This model used VGG16 transfer learning and resulted in 97.6% accuracy.  

## Table of Contents
  1. [Project Final Report](https://github.com/haberkornm/Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images/blob/main/Final_Report.pdf)
  2. [Project Presentation Slides](https://github.com/haberkornm/Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images/blob/main/Slide_presentation.pdf)
  3. Original images can be found at: [Kaggle: Corn or Maize Leaf Disease Dataset](https://www.kaggle.com/smaranjitghose/corn-or-maize-leaf-disease-dataset)
  4. [Data Wrangling and EDA](https://github.com/haberkornm/Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images/blob/main/Corn%20Disease%20Wrangling%20and%20EDA.ipynb)
      -Raw images viewed and explored 
      -Images processed to produce binary, grayscale, Sobel and Canny edge images
      -Green and brown filters produced
      -Processed images concatenated with original RGB images
   5. [Image Averaging and Statistics](https://github.com/haberkornm/Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images/blob/main/Image_Averages_and_Stats.ipynb)
      -Average images produced for the four categories of corn leaf disease images
      -Statistics produced for red, green, and blue image channels
      -KDE plots produced for RGB channels and image categories
      -Image statistics modeled with Random Forest
   6. [CNN Modeling](https://github.com/haberkornm/Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images/blob/main/CNN_Modeling.ipynb)
      -Models produced utilize either unprocessed original RGB images or RGB image concatenated with processed images
      -Image augmentation and VGG16 transfer learning utilized in different models
      -Best preforming model utilized processed images and VGG16 transfer learning
   7. [CNN VGG16 Filter Visualization](https://github.com/haberkornm/Convolutional-Neural-Network-Of-Corn-Leaf-Disease-Images/blob/main/CNN_Filter_visualization.ipynb)
      -Code used to visualize convolutional layer filters in model utilizing VGG16 transfer learning
