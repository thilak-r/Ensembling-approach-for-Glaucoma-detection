# 👁️‍🗨️ Glaucoma Detection with Deep Learning Ensembling 🚀

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/thilak-r/Glaucoma-Detection-ensembling/graphs/commit-activity)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.x-red.svg?logo=keras&logoColor=white)](https://keras.io/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-blueviolet.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.20+-green.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-purple.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="https://raw.githubusercontent.com/thilak-r/Glaucoma-Detection-ensembling/main/best%20grad_images/positive_gradcam_image_11.png" width="400" alt="Glaucoma Detection - Grad-CAM Example">
</p>

<h3 align="center">Detecting Glaucoma from Fundus Images using Deep Learning Ensemble Techniques </h3>

---

## 💡 Project Overview

This repository hosts a cutting-edge project focused on **glaucoma detection** using fundus (retinal) images. Leveraging the power of **deep learning** and **ensemble techniques**, this project aims to build robust and accurate models for early glaucoma screening. 👁️ Early detection is crucial in managing glaucoma and preventing irreversible vision loss. This project explores different Convolutional Neural Network (CNN) architectures and combines their strengths through ensembling to achieve superior diagnostic performance.

## ✨ Key Features

* **Ensemble Learning:** 🤖  Utilizes the power of model ensembling to enhance prediction accuracy and robustness by combining predictions from multiple diverse deep learning models.
* **Deep Learning Models:** 🧠 Explores various state-of-the-art CNN architectures known for image classification tasks, tailored and trained for glaucoma detection. (See the `/Models` directory)
* **Gradient Visualization:** 🌡️ Implements Grad-CAM and similar techniques to provide insights into the model's decision-making process, highlighting the regions in fundus images that contribute most to glaucoma diagnosis. (See the `/best grad_images` directory)
* **Training Notebooks:** 📚  Provides well-documented Jupyter notebooks for easy reproducibility of model training, evaluation, and experimentation. (See the `/Training notebook` directory)
* **Modular Design:** 🧱 Code is organized into logical modules for model definition, training, evaluation, and visualization, promoting readability and maintainability.
* **Ready-to-Use Models:** 📦 Includes pre-trained models (within `/Models`) for immediate inference and deployment. *(Instructions on usage coming soon)*

## 🛠️ Tech Stack

This project is built using the following powerful technologies:

* **Programming Language:**  🐍 **Python 3.7+**
* **Deep Learning Frameworks:**
    * <img src="https://img.shields.io/badge/TensorFlow-2.x-orange.svg?logo=tensorflow&logoColor=white" alt="TensorFlow"/> **TensorFlow 2.x**
    * <img src="https://img.shields.io/badge/Keras-2.x-red.svg?logo=keras&logoColor=white" alt="Keras"/> **Keras (integrated with TensorFlow)**
* **Data Science & Machine Learning Libraries:**
    * <img src="https://img.shields.io/badge/NumPy-1.20+-green.svg?logo=numpy&logoColor=white" alt="NumPy"/> **NumPy**
    * <img src="https://img.shields.io/badge/Pandas-1.3+-purple.svg?logo=pandas&logoColor=white" alt="Pandas"/> **Pandas**
    * <img src="https://img.shields.io/badge/scikit--learn-1.0+-blueviolet.svg?logo=scikit-learn&logoColor=white" alt="scikit-learn"/> **scikit-learn**
    * <img src="https://img.shields.io/badge/OpenCV-4.x-yellowgreen.svg?logo=opencv&logoColor=white" alt="OpenCV"/> **OpenCV (cv2)**
    * **Matplotlib & Seaborn** for visualization
* **Notebook Environment:**  Jupyter Notebook

## 🚀 Getting Started

Follow these steps to get started with the Glaucoma Detection project:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/thilak-r/Glaucoma-Detection-ensembling.git
   cd Glaucoma-Detection-ensembling
