# Optical Mark Recognition (OMR) System

This is a simple Flask web application for Optical Mark Recognition (OMR). The application takes an image of a marked answer sheet, processes it, and provides an evaluated result.

## Features

- Image processing using OpenCV and imutils for perspective transformation and contour detection.
- OMR evaluation based on a provided answer key in CSV format.
- Flask web interface for uploading images and CSV files.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- OpenCV
- imutils
- pandas

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/GUIVersionofOMRChecker/.git
   cd GUIVersionofOMRChecker

### Folder Structure
uploads: Folder to store uploaded images and CSV files.
static: Static files (CSS, images) for the Flask application.
templates: HTML templates for the web interface.
main.py: Main Flask application file


### Acknowledgments
Flask - Web framework for Python.
OpenCV - Open Source Computer Vision Library.
imutils - Convenience functions for OpenCV.
pandas - Data manipulation and analysis library.

### Author
Jakka Shiva Kumar Reddy

