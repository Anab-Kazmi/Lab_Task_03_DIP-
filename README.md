# **Task 03: Histogram Equalization and Contrast Enhancement**

**Roll Number:** 2023-SE-06

### **Prompt**

*"Write a Python program using OpenCV, NumPy, and Matplotlib in Google Colab to perform histogram and contrast enhancement on a colored image uploaded by the user. The program should do the following step by step:

* Allow the user to upload any image.
* Display the original image.
* Apply built-in histogram equalization on the image (use Y channel for color images) and display the result.
* Implement manual histogram equalization for grayscale images, display the result, and plot its histogram alongside the original histogram.
* Apply contrast stretching to the grayscale version and display the result.
* Apply logarithmic transformation and display the result.
* Apply gamma transformation (allow user to set gamma) and display the result.
* Display all transformations (Original Grayscale, Contrast Stretching, Log Transform, Gamma Transform) side by side in a single figure with proper titles and axes turned off.
* Ensure the code is well-structured, modular, and compatible with Google Colab, and each step is clearly labeled."*

---

## **Objective**

The objective of this task is to enhance image quality using **histogram equalization** (both built-in and manual) and **contrast enhancement techniques** such as contrast stretching, logarithmic, and gamma transformations. The task aims to compare the results of different enhancement methods to study their effect on image visibility and contrast.

---

## **Methodology / Approach**

1. Upload the image in Google Colab using `files.upload()`.
2. Display the **Original Image**.
3. Apply **built-in histogram equalization** on the Y channel (luminance) of the color image and display the enhanced color image.
4. Implement **manual histogram equalization** for the grayscale version, display the result, and compare its histogram with the original.
5. Apply **contrast stretching** on the grayscale image to improve intensity range.
6. Apply **logarithmic transformation** to enhance dark regions.
7. Apply **gamma transformation** with user-defined gamma to adjust brightness non-linearly.
8. Display all transformations (**Original Grayscale, Contrast Stretching, Log Transform, Gamma Transform**) side by side for visual comparison.

---

## **Results / Observations**

* **Built-in histogram equalization** enhances color contrast effectively by adjusting luminance.
* **Manual histogram equalization** produces similar improvement and provides insight into the underlying histogram computation.
* **Contrast stretching** improves the dynamic range of the grayscale image.
* **Logarithmic transform** brightens darker regions while maintaining overall intensity.
* **Gamma transformation** adjusts brightness non-linearly; lower gamma values brighten the image, higher values darken it.
* Comparing all techniques shows that different methods have varying effects on contrast and visibility, allowing selection based on application requirements.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **OpenCV (cv2):** Image reading, conversion, histogram equalization
* **NumPy (np):** Array operations and manual histogram calculation
* **Matplotlib (plt):** Visualization of original and enhanced images
* **Google Colab:** Image upload and execution environment

---
