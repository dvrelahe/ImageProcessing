# ImageProcessing
The notebook demonstrates how image content changes after processing and how histogram-based analysis can help compare

A beginner-friendly image processing notebook focused on loading, displaying, transforming, and analyzing images using OpenCV, NumPy, Matplotlib, and scikit-image.

## Overview

This project is a practical image processing exercise notebook created in Google Colab. It demonstrates the fundamentals of working with images in Python, including:

- loading images with OpenCV
- displaying images in Colab
- creating reusable image display functions
- inspecting image data types
- comparing original and noisy images
- analyzing image intensity distributions
- visualizing image histograms in 2D and 3D

The notebook is organized as a step-by-step lab with sections such as **PART A** and multiple exercises.

## Features

- **Image Loading and Display**  
  Reads image files and displays them using OpenCV and Colab utilities.

- **Reusable Display Function**  
  Defines a helper function for showing images with titles.

- **Image Data Type Inspection**  
  Examines image arrays and their formats such as `uint8` and `float64`.

- **Noise Analysis**  
  Compares original and noisy images.

- **Histogram Visualization**  
  Uses histograms to analyze pixel intensity distributions.

- **3D Histogram Plotting**  
  Builds and visualizes 2D histograms in 3D using `bar3d`.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- OpenCV (`cv2`)
- scikit-image
- Google Colab utilities

## Libraries Used
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import cv2
from google.colab.patches import cv2_imshow
from skimage.color import rgb2gray
import matplotlib.image as mpimg
from mpl_toolkits.mplot3d import Axes3D
