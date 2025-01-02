# 🎨 Image Segmentation by Clustering Pixels

> **A practical implementation of image segmentation using K-means and DBScan clustering algorithms.**  
This project is a hands-on approach to clustering-based segmentation for processing and understanding images using Python.

---

## 📖 Table of Contents
1. [Overview](#overview)
2. [✨ Features](#features)
3. [🛠️ Installation](#installation)
4. [🚀 Usage](#usage)
5. [📂 Project Structure](#project-structure)
6. [🤝 Contributing](#contributing)
7. [📜 License](#license)

---

## 🔍 Overview
Image segmentation is essential in computer vision for dividing images into meaningful parts. This project implements:
- **K-means Clustering:** Groups pixels into clusters based on their color intensity.
- **DBScan Clustering:** A density-based algorithm that incorporates spatial information for segmenting pixels.

Both methods are implemented in Python and visualized using `Matplotlib`.

---

## ✨ Features
✔️ **K-means Clustering:**  
Cluster pixels into `k` distinct groups based on their RGB values.  
✔️ **DBScan Clustering:**  
Segment images by identifying dense regions in combined color and spatial data.  
✔️ **Interactive Visualizations:**  
View the original and segmented images side by side.

---

## 🛠️ Installation
To use this project, ensure the following dependencies are installed:

```
pip install opencv-python numpy matplotlib scikit-learn
```


## 🚀 Usage
Clone the repository and navigate to the notebook file:

```
git clone <repository_url>
cd <repository_directory>
```
Open the notebook in Jupyter Notebook or JupyterLab:

```
jupyter notebook Image_Segmentation_by_clustering_pixels.ipynb
```
Run the cells sequentially to:

Load an image 🖼️

Apply K-means clustering for segmentation 🎨

Apply DBScan clustering for segmentation 🧩

Visualize the results 📊

## 📁 Project Structure

```
Image_Segmentation_by_clustering_pixels.ipynb  # Main Jupyter Notebook
README.md                                      # Project documentation
```
## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make enhancements, and submit a pull request. Please ensure your contributions adhere to the existing code style and add relevant documentation.

Happy coding! 💻
