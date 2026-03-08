# Computer Vision Assignment

This project implements basic image enhancement techniques manually on grayscale image matrices without using built-in image processing functions from libraries. Dummy images are represented as 2D matrices where each value corresponds to a pixel intensity between 0 (black) and 255 (white).
The goal is to demonstrate how common image enhancement techniques work at the pixel level by directly manipulating matrix values.

## Features Implemented

### Blur Techniques
1. **Box Blur (Mean Filter)** – Simple averaging of neighbors.  
2. **Gaussian Blur** – Weighted averaging with Gaussian kernel.  
3. **Median Blur** – Replaces pixel with neighborhood median, good for salt-and-pepper noise.  
4. **Bilateral Filter** – Smooths flat areas but keeps edges sharp.  
5. **Motion Blur** – Simulates directional movement blur.  

### Intensity Transformations
- **Brighten** – Increases pixel intensity to lighten the image.  
- **Darken** – Scales down intensities to make the image darker.  
- **Lower Contrast** – Compresses the intensity range to reduce contrast.  

## References
1. Image Blurring Example with OpenCV in Python - https://youtu.be/0Y9G-mYzffk?si=DivkdBzhjeHOFT6q
2. Python Intensity Transformation Operations on Images - https://www.geeksforgeeks.org/python/python-intensity-transformation-operations-on-images/
3. Histograms & Intensity Transformations OpenCV - https://www.kaggle.com/code/bhavinmoriya/histograms-intensity-transformations-opencv#Toy-Example
