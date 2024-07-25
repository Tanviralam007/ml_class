# Image Feature Extraction Project
## Group Members:
* 22-46534-1: **Tanvir Alam Tanim**
* 22-46698-1: **Shahriar Abir Hasan Khan**

## Introduction
This project explores various feature extraction techniques for images. The goal is to extract meaningful information from images that can be used for further analysis or machine learning tasks.

## Feature Extraction Techniques

### 1. Pixel Intensity Values

This technique extracts raw pixel values from the image. The image is first read and converted to RGB format, and then the pixel values are flattened into a single array, giving a direct representation of the image's pixel intensities.

### 2. Color Histograms

This technique calculates the color histograms for each of the RGB channels. The histograms represent the distribution of pixel intensities for the Red, Green, and Blue channels, providing information about the color composition of the image.

### 3. Edge Detection Algorithms

These techniques detect edges within the image, highlighting areas with significant intensity changes. The following algorithms are used:

* **Canny**: Detects edges by looking for local maxima in the gradient
* **Sobel**: Uses a pair of convolution filters (horizontal and vertical) to compute gradients
* **Laplacian**: Calculates the second derivative of the image, highlighting regions of rapid intensity change
* **Scharr**: Similar to Sobel but provides a better approximation of the gradient's magnitude

### 4. VGG16-based Feature (From Convolutional Neural Network)

This technique is not used for final analysis in this specific example but demonstrates a potential approach for more complex feature extraction. VGG16 is trained on a massive image dataset and can capture high-level features related to objects, textures, and colors in the image. For testing purposes, only one has been used.

## Conclusion

This project demonstrates various feature extraction techniques for images. These techniques can be used as a starting point for further analysis or machine learning tasks.
