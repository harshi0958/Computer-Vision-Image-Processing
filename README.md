# Computer Vision Image Processing

This project demonstrates different image processing techniques using Python, OpenCV, NumPy, and Matplotlib.

The project uses a personal image and applies various spatial-domain, frequency-domain, filtering, edge detection, and morphological operations.

## Objective

The main objective of this assignment is to understand how different image processing techniques affect an image and to study the difference between spatial-domain and frequency-domain processing.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## Image Processing Operations

### 1. Original Image
The original input image is loaded using OpenCV and displayed for comparison with the processed images.

### 2. Gaussian Filter
Gaussian filtering smooths the image and reduces noise and small details using a Gaussian kernel.

### 3. Smoothing Filter
Smoothing reduces unwanted variations and noise in an image by applying a blur operation.

### 4. Mean Filter
The Mean Filter replaces each pixel with the average value of its neighboring pixels.

### 5. Median Filter
The Median Filter replaces a pixel with the median value of its neighborhood. It is useful for reducing salt-and-pepper noise.

### 6. Spatial Domain Filtering
Spatial domain processing directly operates on image pixel values. A Laplacian filter is used to highlight rapid intensity changes and edges.

### 7. Sharpening Filter
Sharpening enhances edges and fine details of an image by emphasizing high-frequency information.

### 8. Box Filter
The Box Filter performs smoothing by averaging pixels within a rectangular neighborhood.

### 9. Bilateral Filter
The Bilateral Filter smooths the image while preserving important edges.

### 10. Frequency Domain Filtering
The Fourier Transform converts the image from the spatial domain into the frequency domain. The magnitude spectrum represents the distribution of different frequencies.

### 11. Ideal Low Pass Filter
The Ideal Low Pass Filter allows low frequencies to pass and removes high frequencies. It is mainly used for image smoothing.

### 12. Butterworth Low Pass Filter
The Butterworth Low Pass Filter reduces high frequencies with a smooth transition between the passband and stopband.

### 13. Gaussian Low Pass Filter
The Gaussian Low Pass Filter gradually reduces high-frequency components and produces smooth image filtering.

### 14. Gaussian High Pass Filter
The Gaussian High Pass Filter removes low-frequency components and preserves high-frequency information such as edges and fine details.

### 15. Canny Edge Detection
Canny Edge Detection identifies significant intensity changes in an image and highlights object boundaries.

### 16. Erosion
Erosion shrinks the boundaries of foreground objects and can help remove small unwanted regions.

### 17. Dilation
Dilation expands the boundaries of foreground objects and can help connect nearby regions.

### 18. Opening
Opening consists of erosion followed by dilation. It is useful for removing small noise while preserving the main structure.

### 19. Closing
Closing consists of dilation followed by erosion. It is useful for filling small holes and gaps in objects.

### 20. Morphological Gradient
Morphological Gradient is calculated using dilation minus erosion and is useful for highlighting object boundaries.

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install opencv-python numpy matplotlib jupyter
