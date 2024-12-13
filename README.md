# **Image Visualization**

This project, **Image Visualization**, demonstrates various techniques to process, manipulate, and visualize images using Python libraries such as **NumPy**, **TensorFlow**, **Keras**, **Skimage**, and others. The project focuses on visualizing RGB channels, grayscale images, and performing data augmentation for machine learning tasks.

---

## **Key Features of the Project**

### **1. Image Processing**
- **Original Image Visualization**: Displaying the original image for reference.
- **RGB Channel Visualization**: Splitting the image into its Red, Green, and Blue channels and visualizing them individually.
- **Grayscale Conversion**: Converting an image to grayscale for simplified analysis.
- **Normalization**: Converting pixel values to a normalized range for consistent data scaling.

### **2. Image Augmentation**
- **Loading Images**: Used `keras.preprocessing.image.load_img` to load images and `img_to_array` to convert them into NumPy arrays.
- **Image Augmentation with Keras**:
  - Rotation
  - Brightness adjustment
  - Other transformations using `ImageDataGenerator`.

---

## **Technologies Used**
- **NumPy**: For numerical computations and pixel manipulations.
- **TensorFlow/Keras**: For loading and augmenting images.
- **Skimage**: For image manipulation and visualization.
- **Matplotlib**: For plotting and visualizing image transformations.
- **OS & Glob**: For handling file paths and loading datasets.
