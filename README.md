# Image Processing with OpenCV

This project demonstrates various image processing techniques using OpenCV. The notebook provides practical implementations for analyzing image dimensions, applying filters, and performing augmentations.

## Features

### Dimensions
- Analyze image dimensions: height, width, and channels.

### Filters
- **Brightness Adjustment**: Modify image brightness.
- **Gaussian Blur**: Apply a Gaussian smoothing filter to reduce noise.
- **Median Blur**: Use a median filter to remove salt-and-pepper noise.
- **Bilateral Filter**: Smooth the image while preserving edges.
- **Sharpen Filter**: Enhance image details.
- **Emboss Filter**: Apply an emboss effect to create a 3D look.
- **Canny Edge Detection**: Detect edges using the Canny algorithm.
- **Motion Blur**: Simulate motion blur effects.

### Augmentations
- **Add Gaussian Noise**: Introduce random Gaussian noise to the image.
- **Grayscale Conversion**: Convert images to grayscale for preprocessing.

## Prerequisites

- Python 3.x
- OpenCV 4.x
- Jupyter Notebook

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/image-processing.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-processing
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

1. Open the notebook `imageprocessing-2.ipynb` in Jupyter.
2. Follow the cells sequentially to explore:
   - Analyzing dimensions of input images.
   - Applying various filters for enhancement or preprocessing.
   - Using augmentations for data preprocessing and augmentation tasks.
3. Replace the image path in relevant code cells with your desired file path.

## Troubleshooting

- **Error: Assertion Failed `_src.empty()`**  
  This error occurs when OpenCV fails to read the image file. Ensure the file path is correct and the file exists.

- **Dependencies not found:**  
  Ensure all required packages are installed using `pip install -r requirements.txt`.

Under guidance of:
[Dr Agughasi Victor Ikechukwu](https://github.com/Victor-Ikechukwu)
