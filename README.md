# Cell Counting with OpenCV

This project performs automated cell counting on microscopy images using Python and OpenCV. It utilizes Gaussian smoothing, Otsu's thresholding, and morphological operations to detect and count cells.

## Features
* **Preprocessing:** Grayscale conversion and Gaussian blurring.
* **Segmentation:** Otsu’s thresholding for automatic binarization.
* **Noise Removal:** Morphological opening to remove artifacts.
* **Counting:** Connected component analysis to count cells.
* **Visualization:** Draws bounding boxes around detected cells.

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/yusufkorkmazyigit/cell_counting.git](https://github.com/yusufkorkmazyigit/cell_counting.git)