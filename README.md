# Image-Processing-with-OpenCV
## Overview

This project demonstrates fundamental image processing techniques using OpenCV in Python. It covers operations such as image reading, transformation, enhancement, and annotation.

## Technologies Used
```
1.Python 
2.OpenCV 
3.NumPy 
4.Matplotlib
```
## Features Implemented
1. Image Reading & Display
Read image in grayscale
Display image using Matplotlib
Extract image height, width, and channels
2. Image Saving & Conversion
Save image in .png format
Convert image from BGR to RGB
3. Image Cropping
Extract specific region (Eagle) using slicing
4. Image Resizing
Resize image to 2x its original size
5. Image Flipping
Flip image horizontally
6. Image Annotation
Add text to image
Example: Apollo 11 Saturn V Launch, July 16, 1969
7. Drawing Shapes
Draw rectangle around object (rocket & tower)
8. Brightness Adjustment
Increase brightness manually using NumPy
Use OpenCV functions:
cv2.add() (Brighter)
cv2.subtract() (Darker)
9. Contrast Adjustment
Lower contrast (0.8 scaling)
Higher contrast (1.2 scaling)
10. Channel Splitting & Merging (RGB)
Split into Red, Green, Blue channels
Merge channels back to original image
11. HSV Color Space
Convert RGB → HSV
Split into:
Hue
Saturation
Value
## Sample Outputs
```
 *Grayscale Image
 *Cropped Eagle Image
 *Flipped Image
 *Annotated Rocket Image
 *Brightness & Contrast Adjustments
 *RGB & HSV Channel Visualizations
```
## How to Run
# Install dependencies
pip install opencv-python numpy matplotlib

# Run the script
python your_script_name.py
## Required Images

Make sure the following images are in your project folder:

Eagle_in_Flight.jpg
Apollo-11-launch.jpg
boy.jpg
## Learning Outcomes
Understanding image representation
Performing pixel-level operations
Working with different color spaces
Applying transformations and enhancements
## Conclusion

This experiment provides a strong foundation in computer vision basics and helps in understanding how images can be processed and manipulated using OpenCV.
