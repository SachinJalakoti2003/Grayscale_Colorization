# 🎨 Grayscale to Color Image Restoration – MIT-Based AI Model

Welcome to a deep learning project that brings old memories back to life! This tool colorizes grayscale images using a **pre-trained neural network** model developed by **MIT researchers** and powered by **OpenCV** + **Caffe**.

---

## 🧠 Project Description

This project uses a deep neural network to automatically colorize black-and-white photos. The model works by predicting the color information ('a' and 'b' channels) from the grayscale input ('L' channel) in the **LAB color space**. 

It's based on the paper **"Colorful Image Colorization"** by Zhang et al. (ECCV 2016) and provides a powerful example of how machine learning can be used for **image-to-image translation**.

Whether you're restoring vintage family photos or exploring computer vision techniques, this project offers a simple, effective, and high-quality solution.

---

## ✨ Features

- 🎯 **Automatic colorization** of grayscale images
- 🧪 **Deep learning model** trained on millions of natural images
- ⚙️ Built with **Python**, **OpenCV**, and **Caffe**
- 🖼️ Outputs realistic and vivid color images
- 💡 Based on research from **MIT & UC Berkeley**

---

## 📁 Folder Structure

Grayscale_Colorization_Project/
└── Old_Photos_colorization_Project_MIT-main/
├── app.py # Main application script
├── requirements.txt # Python dependencies
├── LICENSE # MIT License
├── models/ # Contains pre-trained models
│ ├── colorize.prototext
│ ├── release.caffemodel
│ └── pts_in_hull.npy
├── results/ # Colorized output images
└── sim/ # (Optional) Extra utilities/simulations
