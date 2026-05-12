# opencv-image-processing
Image Handling and Pixel Transformations Using OpenCV
## AIM
To develop a Python program using OpenCV to perform basic image processing operations such as brightness adjustment, contrast modification, and color channel separation.

SOFTWARE REQUIREMENTS
Anaconda (Python 3.7)
Jupyter Notebook (for interactive development and execution)
## ALGORITHM
Step 1: Image Loading and Display
Load an image from the local directory using OpenCV and display it.

Step 2: Brightness Adjustment
Create a matrix of ones (data type float64) to control the brightness level of the image.

Step 3: Brightness Transformation
Generate:

A brighter image by adding the matrix to the original image
A darker image by subtracting the matrix from the original image
Display:

Original Image
Brighter Image
Darker Image
Step 4: Contrast Modification
Modify image contrast by applying scaling factors of 1.1 and 1.2 (without overflow correction) to generate higher contrast images.

Display:

Original Image
Lower Contrast Image
Higher Contrast Image
Step 5: Color Channel Separation
Split the image (boy.jpg) into Blue (B), Green (G), and Red (R) channels and display each channel separately.

## OUTPUT
Original image with enhanced visual transformations
Brightness-adjusted images
Contrast-adjusted images
Separate BGR channel images
## 🚀 LEARNING OUTCOMES
Understanding image representation in OpenCV
Performing pixel-level transformations
Working with brightness and contrast adjustments
Splitting and analyzing color channels
## NOTE
This project demonstrates fundamental image processing techniques using OpenCV for beginners in computer vision.
