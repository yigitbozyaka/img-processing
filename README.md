# Image Processing Project

This repository contains Jupyter Notebook code for various image processing tasks.  The notebook demonstrates image manipulation techniques using OpenCV, NumPy, and Matplotlib.

**Author:** Yiğit Bozyaka
**Student ID:** B2280.060057

## Project Overview

This project explores several image processing techniques, including:

*   **Reading and displaying images:** Loading and visualizing images in color and grayscale using OpenCV.
*   **Finding image center:** Calculating and displaying the center coordinates of an image.
*   **Calculating intensity values:** Extracting and displaying the intensity value at the center of an image.
*   **Placing a colored patch:** Drawing a colored rectangle at the center of an image.
*   **Applying log transform:** Enhancing image visibility by compressing or expanding the dynamic range of pixel intensities.
*   **Applying inverse log transform:** Recovering original pixel intensities from a log-transformed image.
*   **Identifying and removing noise:** Detecting and mitigating noise in images using Gaussian and median filters.
*   **Histogram analysis:** Visualizing pixel intensity distributions to understand image characteristics.
*   **Histogram equalization:** Improving global contrast in an image.*   **Laplacian sharpening:** Enhancing edges and textures in an image.

## Requirements

To run the Jupyter Notebook, ensure you have the following libraries installed:

*   `opencv-python`
*   `numpy`
*   `matplotlib`
*   `skimage`

## Installation && Usage Instructions

1. Clone this repository
2. Ensure you have the required dependencies installed (The first two block is for the setup and install required dependencies. If you already have these packages skip this step.)
3. Make sure the data folder contains the following images:

tf2_engineer.jpg
einstein.tif
pout.tif
moon.tif
pcb.tif
pollen.tif


4. Run the Jupyter Notebook (image_processing.ipynb) cell by cell to see the results of each technique