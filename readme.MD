# 🖼️ Image Editing App with OpenCV

An interactive web-based image editor built with **Streamlit** and **OpenCV** that allows you to apply various filters and adjustments to your images in real-time.

## Features

This application provides a comprehensive set of image editing tools:

- **Blur Filter** - Adjustable blur effect (kernel size: 1-51)
- **Sharpness Control** - Enhance image sharpness (0.0-3.0)
- **Brightness Adjustment** - Brighten or darken images (-100 to +100)
- **Contrast Control** - Adjust image contrast (0.5-3.0)
- **Edge Detection** - Apply Canny edge detection with customizable thresholds
- **Grayscale Conversion** - Convert images to black and white
- **Real-time Preview** - Side-by-side comparison of original and edited images
- **Download Edited Images** - Save your edited images as PNG files

## Tech Stack

- **Streamlit** - Web application framework
- **OpenCV (cv2)** - Image processing library
- **Pillow (PIL)** - Image handling
- **NumPy** - Numerical computations
- **Python 3.x**

## Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Madhukar-Palakaveeti/image_editor.git
   cd image_editor
