# Image Processing & Signal Analysis Project

## Overview
This project explores different image processing techniques using Python. The goal was to learn how to analyze images, segment objects, remove noise, and apply basic transformations using RGB, HSV, and grayscale images. I also experimented with filtering and pixel-level operations to see how images change.

## What I Did
1. **Color Channels & Masking**  
   - Separated RGB channels from `colors.png` and displayed them.  
   - Created a binary mask to highlight red regions and converted the image to grayscale.

2. **Object Segmentation**  
   - Used `apple.jpg` and `stop-sign.jpg` to segment objects in both RGB and HSV color spaces.  
   - Compared how well each color space helped isolate the object.

3. **Noise Removal with FFT**  
   - Applied 2D Fourier Transform to `bandnoise.png` to identify and remove band noise.  
   - Reconstructed a clean image using inverse FFT.

4. **Point Processing**  
   - Manipulated `dog.jpg` with brightness, contrast, inversion, and other pixel-level operations.  
   - Visualized the effects of each transformation.

5. **Filtering & Resizing**  
   - Applied average, Gaussian, and median filters to `cameraman.jpeg`.  
   - Resized images and analyzed the effect of filtering on image quality.

## Tools
Python, NumPy, OpenCV, Matplotlib, scikit-image  

## How to Run
1. Put all images in an `images/` folder.  
2. Open the Jupyter Notebook and run all cells to see results and plots.
