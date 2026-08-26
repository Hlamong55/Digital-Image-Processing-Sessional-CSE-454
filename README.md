# Digital Image Processing Lab

This repository contains the laboratory exercises and Python implementations for the **Digital Image Processing (DIP)** course.

The programs are mainly implemented using **Python, OpenCV, NumPy, Matplotlib, and Google Colab**. The repository covers basic image processing operations and demonstrates how digital images can be loaded, analyzed, transformed, and manipulated programmatically.

---

## 🛠️ Technologies & Tools

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## 📚 Lab Exercises

### Lab 01 — Basic image processing operations

This lab introduces the basic concepts of digital images and demonstrates how to:

- Load an image using OpenCV
- Display images using Matplotlib
- Check image dimensions and properties
- Access individual pixel values
- Modify pixel values
- Draw basic shapes such as circles, rectangles, and lines
- Add text to an image
- Convert BGR images to RGB
- Convert RGB images to grayscale
- Save processed images

---

### Lab 02 — Image Resizing & Point Processing Operations

This lab focuses on basic geometric image operations.

#### Image Resizing

- Read an image using OpenCV
- Check the original image dimensions
- Resize an image to a specific width and height
- Compare the original and resized images

#### Image Cropping

- Determine image height and width
- Calculate cropping coordinates
- Perform center cropping
- Extract a specific region from an image
- Display and compare the original and cropped images

---

### Lab 03 — Implemented image enhancement techniques

This lab demonstrates the **Digital Image Negative** transformation.

The grayscale image is converted into its negative using:

```text
Negative = 255 - Pixel

---

### The program:

- Loads an input image
- Converts it to grayscale
- Applies the negative transformation
- Displays the original grayscale image and its negative
- Displays selected pixel values
- Saves the processed negative image


### 🔄 Basic Workflow:

Input Image
     ↓
Read Image using OpenCV
     ↓
Image Processing
     ↓
Display Result using Matplotlib
     ↓
Save Processed Image


### 🚀 How to Run:

- Using Google Colab
- Open the required .ipynb file in Google Colab.
- Run the cells sequentially.
- Upload an input image when requested.
- The program will process and display the result.
- Processed images can be saved/downloaded from the Colab environment.
- Using Local Python Environment

### Install the required libraries:

pip install opencv-python matplotlib numpy

Then run the Python scripts or open the notebooks using Jupyter Notebook.
 
---

### 🎯 Learning Objectives

Through these laboratory exercises, the following concepts are practiced:

- Digital image representation
- Image dimensions and channels
- Pixel-level operations
- Color space conversion
- Grayscale image processing
- Image resizing
- Image cropping
- Digital negative transformation
- Basic image visualization
- Image input/output using OpenCV
